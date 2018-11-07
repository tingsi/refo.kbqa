# refo.kbqa
a kbqa system based on refo library. from http://openkg.cn/tool/eb483ee4-3be1-4d4b-974d-970d35307e8d

原文介绍：
 基于 REfO 的 KBQA 实现及示例

这是一个基于 Python 模块 REfO 实现的知识库问答初级系统. 该问答系统可以解析输入的自然语言问句生成 SPARQL 查询，进一步请求后台基于 TDB 知识库的 Apache Jena Fuseki 服务, 得到结果.

这是一个入门级的例子. 内含介绍此项目的 README.pdf. 方便用户快速把握这个项目的想法. 希望用户体会默认的 3 类 5 个问题. 不同的表述能够用统一的"对象正则表达式"匹配得到结果, 进而生成对应 SPARQL 查询语句.

运行样例时请注意观察结果, test.py和backend文件夹要在同一级目录上

