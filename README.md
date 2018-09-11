Apache CarbonData源码阅读
=========================

源码：<https://github.com/apache/incubator-carbondata>
版本： 1.5.0

**目录**

1. [源码目录](1-module-outline.md)

2. [format模块](2-format.md)

   2.1 文件目录结构

   2.2 文件内容详解
   
      2.2.1 Schema文件格式

      2.2.2 carbondata文件格式

      2.2.3 carbonindex文件格式

      2.2.4 dictionary 文件格式

      2.2.5 tablestatus 文件格式

3. [integration模块](3-integration.md)

   3.1 spark集成

   3.2 spark2集成

4. [core模块](4-core.md)

   4.1 Scan（查询）

   4.2 Filter Expression

   4.3 LRU Cache

   4.4 BTree Index

5. [processing模块](5-processing.md)

   5.1 Global Dictionary

   5.2 DataLoading（数据加载）

   5.3 Compression Encoding
