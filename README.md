#Elasticsearch目录


* [Elasticsearch目录](README.md)
* [1、基本概念](1、基本概念.md)
* [2、安装和启动](2、安装和启动.md)
* 3、快速入门
    * [3.1、快速入门案例实战](3、快速入门/3、快速入门案例实战.md)
    * [3.2、多种搜索方式](3、快速入门/3.2、多种搜索方式.md)
    * [3.3、嵌套聚合，下钻分析，聚合分析](3、快速入门/3.3、嵌套聚合，下钻分析，聚合分析.md)
    * [3.4、Elasticsearch的基础分布式架构](3、快速入门/3.4、Elasticsearch的基础分布式架构.md)
    * [3.5、shard&replica机制再次梳理以及单node环境中创建index图解](3、快速入门/3.5、shard&replica机制再次梳理以及单node环境中创建index图解.md)
* 4、document
    * [4.1_初步解析document的核心元数据以及图解剖析index创建反例](4、document/4.1_初步解析document的核心元数据以及图解剖析index创建反例.md)
    * [4.2_document id的手动指定与自动生成两种方式解析.md](4、document/4.2_document_id的手动指定与自动生成两种方式解析.md)
    * [4.3_document的_source元数据以及定制返回结果解析](4、document/4.3_document的_source元数据以及定制返回结果解析.md)
    * [4.4_document的全量替换、强制创建以及图解lazy delete机制](4、document/4.4_document的全量替换、强制创建以及图解lazy_delete机制.md)
* [5、深度图解剖析](5、深度图解剖析.md)
* 6、上机动手实战演练
    * [6.1_基于_version进行乐观锁并发控制](6、上机动手实战演练/6.1_基于_version进行乐观锁并发控制.md)
    * [6.2_基于external version进行乐观锁并发控制](6、上机动手实战演练/6.2_基于external_version进行乐观锁并发控制.md)
    * [6.3_图解partial update实现原理以及动手实战演练](6、上机动手实战演练/6.3_图解partial_update实现原理以及动手实战演练.md)
    * [6.4_基于groovy脚本进行partial update](6、上机动手实战演练/6.4_基于groovy脚本进行partial_update.md)
    * [6.5_图解partial update乐观锁并发控制原理以及相关操作讲解](6、上机动手实战演练/6.5_图解partial_update乐观锁并发控制原理以及相关操作讲解.md)
    * [6.6_mget批量查询api](6、上机动手实战演练/6.6_mget批量查询api.md)
* 7、分布式文档系统
    * [7.1_上机动手实战演练bulk批量增删改](7、分布式文档系统/7.1_上机动手实战演练bulk批量增删改.md)
    * [7.2_阶段性总结以及什么是distributed document store](7、分布式文档系统/7.2_阶段性总结以及什么是distributed document store.md)
    * [7.3_深度图解剖析document数据路由原理](7、分布式文档系统/7.3_深度图解剖析document数据路由原理.md)
    * [7.4_document增删改内部原理图解揭秘](7、分布式文档系统/7.4_document增删改内部原理图解揭秘.md)
    * [7.5_图解写一致性原理以及quorum机制深入剖析](7、分布式文档系统/7.5_图解写一致性原理以及quorum机制深入剖析.md)
    * [7.6_document查询内部原理图解揭秘](7、分布式文档系统/7.6_document查询内部原理图解揭秘.md)
    * [7.7_bulk api的奇特json格式与底层性能优化关系大揭秘](7、分布式文档系统/7.7_bulk api的奇特json格式与底层性能优化关系大揭秘.md)
* 8、初识搜索引擎
    * [8.1_search结果深入解析（search timeout机制揭秘）](8、初识搜索引擎/8.1_search结果深入解析（search timeout机制揭秘）.md)
    * [8.2_multi-index&multi-type搜索模式解析以及搜索原理初步图解](8、初识搜索引擎/8.2_multi-index&multi-type搜索模式解析以及搜索原理初步图解.md)
    * [8.3_分页搜索以及deep paging性能问题深度图解揭秘](8、初识搜索引擎/8.3_分页搜索以及deep paging性能问题深度图解揭秘.md)
    * [8.4_快速掌握query string search语法以及_all metadata原理揭秘](8、初识搜索引擎/8.4_快速掌握query string search语法以及_all metadata原理揭秘.md)
    * [8.5_用一个例子告诉你mapping到底是什么](8、初识搜索引擎/8.5_用一个例子告诉你mapping到底是什么.md)
    * [8.6_精确匹配与全文搜索的对比分析](8、初识搜索引擎/8.6_精确匹配与全文搜索的对比分析.md)
    * [8.7_倒排索引核心原理快速揭秘](8、初识搜索引擎/8.7_倒排索引核心原理快速揭秘.md)
    * [8.8_分词器的内部组成到底是什么，以及内置分词器的介绍](8、初识搜索引擎/8.8_分词器的内部组成到底是什么，以及内置分词器的介绍.md)
    * [8.9_query string的分词以及mapping引入案例遗留问题的大揭秘](8、初识搜索引擎/8.9_query string的分词以及mapping引入案例遗留问题的大揭秘.md)
    * [8.10_什么是mapping再次回炉透彻理解](8、初识搜索引擎/8.10_什么是mapping再次回炉透彻理解.md)
    * [8.11_mapping的核心数据类型以及dynamic mapping](8、初识搜索引擎/8.11_mapping的核心数据类型以及dynamic mapping.md)
    * [8.12_手动建立和修改mapping以及定制string类型数据是否分词](8、初识搜索引擎/8.12_手动建立和修改mapping以及定制string类型数据是否分词.md)
    * [8.13_mapping复杂数据类型以及object类型数据底层结构大揭秘](8、初识搜索引擎/8.13_mapping复杂数据类型以及object类型数据底层结构大揭秘.md)
    * [8.14_search api的基础语法介绍](8、初识搜索引擎/8.14_search_api的基础语法介绍.md)
    * [8.15_快速上机动手实战Query DSL搜索语法](8、初识搜索引擎/8.15_快速上机动手实战Query DSL搜索语法.md)
    * [8.16_filter与query深入对比解密：相关度，性能](8、初识搜索引擎/8.16_filter与query深入对比解密：相关度，性能.md)
    * [8.17_上机动手实战常用的各种query搜索语法](8、初识搜索引擎/8.17_上机动手实战常用的各种query搜索语法.md)
    * [8.18_上机动手实战多搜索条件组合查询](8、初识搜索引擎/8.18_上机动手实战多搜索条件组合查询.md)
    * [8.19_上机动手实战如何定位不合法的搜索以及其原因](8、初识搜索引擎/8.19_上机动手实战如何定位不合法的搜索以及其原因.md)
    * [8.21_上机动手实战如何定制搜索结果的排序规则](8、初识搜素引擎/8.21_上机动手实战如何定制搜索结果的排序规则.md)
    * [8.22_解密如何将一个field索引两次来解决字符串排序问题](8、初识搜索引擎/8.22_解密如何将一个field索引两次来解决字符串排序问题.md)
    * [8.23_相关度评分TF&IDF算法独家解密](8、初识搜索引擎/8.23_相关度评分TF&IDF算法独家解密.md)
    * [8.24_内核级知识点之doc value初步探秘](8、初识搜索引擎/8.24_内核级知识点之doc value初步探秘.md)
    * [8.25_分布式搜索引擎内核解密(query phase和fetch phase)](8、初识搜索引擎/8.25_分布式搜索引擎内核解密query phase和fetch phase.md)
    * [8.27_搜索相关参数梳理以及bouncing results问题解决方案](8、初识搜索引擎/8.27_搜索相关参数梳理以及bouncing results问题解决方案.md)
    * [8.28_上机动手实战基于scoll技术滚动搜索大量数据](8、初识搜索引擎/8.28_上机动手实战基于scoll技术滚动搜索大量数据.md)
* 9、索引管理
    * [9.1_快速上机动手实战创建、修改以及删除索引](9、索引管理/9.1_快速上机动手实战创建、修改以及删除索引.md)
    * [9.2_快速上机动手实战修改分词器以及定制自己的分词器](9、索引管理/9.2_快速上机动手实战修改分词器以及定制自己的分词器.md)
    * [9.3_内核级知识点：深入探秘type底层数据结构](9、索引管理/9.3_内核级知识点：深入探秘type底层数据结构.md)
    * [9.4_mapping root object深入剖析](9、索引管理/9.4_mapping root object深入剖析.md)
    * [9.5_定制化自己的dynamic mapping策略](9、索引管理/9.5_定制化自己的dynamic mapping策略.md)
    * [9.6_复杂上机实验：基于scoll+bulk+索引别名实现零停机重建索引](9、索引管理/9.6_复杂上机实验：基于scoll+bulk+索引别名实现零停机重建索引.md)
* 10、内核原理探秘
    * [10.1_倒排索引组成结构以及其索引可变原因揭秘](10、内核原理探秘/10.1_倒排索引组成结构以及其索引可变原因揭秘.md)
    * [10.2_深度图解剖析document写入原理（buffer，segment，commit）](10、内核原理探秘/10.2_深度图解剖析document写入原理（buffer，segment，commit）.md)
    * [10.3_优化写入流程实现NRT近实时（filesystem cache，refresh）](10、内核原理探秘/10.3_优化写入流程实现NRT近实时（filesystem cache，refresh）.md)
    * [10.4_继续优化写入流程实现durability可靠存储（translog，flush）](10、内核原理探秘/10.4_继续优化写入流程实现durability可靠存储（translog，flush）.md)
    * [10.5_最后优化写入流程实现海量磁盘文件合并（segment merge，optimize）](10、内核原理探秘/10.5_最后优化写入流程实现海量磁盘文件合并（segment merge，optimize）.md)
* 11、Java API初步使用_员工管理案例
    * [11.1_基于Java实现员工信息的增删改查](11、Java API初步使用_员工管理案例/11.1_基于Java实现员工信息的增删改查.md)
    * [11.2_基于Java对员工信息进行复杂的搜索操作](11、Java API初步使用_员工管理案例/11.2_基于Java对员工信息进行复杂的搜索操作.md)
    * [11.3_基于Java对员工信息进行聚合分析](11、Java API初步使用_员工管理案例/11.3_基于Java对员工信息进行聚合分析.md)
* [12、操作命令汇总.md](12、操作命令汇总.md)
* 参考：
>中文api： https://www.elastic.co/guide/cn/elasticsearch/guide/current/index.html

>mac安装：https://www.jianshu.com/p/18074e1e719f

>安装分词器：https://www.cnblogs.com/wangchuanfu/p/7239165.html