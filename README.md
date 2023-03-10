# ChatGPT_QA_record

 Chat与AI问答的精彩总结记录，有关深度学习、Python、C、C++、Java等

#python相关

#论文阅读

#深度学习技术

##GAT

>1. GAT的本质和组成

GAT（Graph Attention Network）是一种基于图注意力机制的神经网络结构，用于处理图结构数据的机器学习任务。
GAT的本质是通过注意力机制对图中节点进行聚合，从而在节点级别上处理图结构数据。在传统的图卷积神经网络（GCN）中，所有节点的权重都是相同的，而在GAT中，每个节点都可以根据与其相邻的节点的特征动态地分配不同的权重，因此可以更好地处理图中节点之间的关系。
GAT的组成包括以下几个部分：
1.	输入层：将图结构数据转换为神经网络的输入格式。
2.	多头注意力层：通过多个注意力头，对每个节点进行局部特征聚合，并得到多个不同的节点表示。
3.	输出层：将多头注意力层得到的节点表示进行池化或合并，最终得到整个图的表示或执行任务的预测。
GAT的核心是多头注意力层，它包括多个注意力头，每个注意力头都有自己的权重参数，用于计算相邻节点之间的注意力分配。每个注意力头都可以探索节点之间的不同关系，从而提高模型的泛化能力。通过多头注意力的方式，GAT可以对图中节点进行不同尺度的特征聚合，从而更好地处理图结构数据。

##NER-命名实体识别

1. > 表格总结spacy的NER类型及含义

Spacy支持多种命名实体类型(NER)。以下是spacy v3.5.0版本的NER类型及其含义的列表：

*   PERSON: 人名
*   NORP: 民族、宗教或政治团体
*   FAC: 建筑物、机场、桥梁等
*   ORG: 公司、机构、政府等组织
*   GPE: 国家、城市、州等地理位置
*   LOC: 非GPE的地理位置，例如山脉或水体
*   PRODUCT: 产品名称，例如汽车或电视机
*   EVENT: 活动名称，例如音乐会或展览
*   WORK\_OF\_ART: 作品名称，例如书籍或电影
*   LAW: 法律文件或法律条款
*   LANGUAGE: 语言名称
*   DATE: 绝对或相对日期或时间
*   TIME: 时间
*   PERCENT: 百分数
*   MONEY: 货币金额
*   QUANTITY: 数量，例如长度或体积
*   ORDINAL: 序数，例如第一或第二
*   CARDINAL: 基数，例如1、2、3等

请注意，NER类型和定义可能随版本和模型而有所不同。如果您使用的是不同版本的spacy或不同的模型，请查看相应文档以获取最新的NER类型和定义。

