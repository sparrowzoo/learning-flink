Discover the definitive guide to crafting lightning-fast data processing for distributed systems with Apach Flink(Apache Flink 的权威指南，一个面向分布式系统的快速数据处理框架。)

Preface (前言)
---
With the advent of massive computer systems, organizations in different domains generate large amounts of data at a real-time basis. The latest entrant to big data processing, Apache Flink, is designed to process continuous streams of data at a lighting fast pace.
(随着大规模计算机系统的出现，基本上在各个领域的组织都会生成大量的实时数据。而最后进入大数据处理领域的Apache Flink,旨在快速地处理连续数据流。）

This book will be your definitive guide to batch and stream data processing with Apache Flink. The book begins by introducing the Apache Flink ecosystem, setting it up and using the DataSet and DataStream API for processing batch and streaming datasets. Bringing the power of SQL to Flink, this book will then explore the Table API for querying and manipulating data. In the latter half of the book. readers will get to learn the remaining ecosvstem of Apache Flink to achieve complex tasks such as event processing, machine learning, and graph processing. The final part of the book would consist of topics such as scaling Flink solutions, performance optimization, and integrating Flink with other tools such as Hadoop, ElasticSearch, Cassandra, and Kafka.
（本书可以作为Aapache Flink的权威指南。本书开始部分将介绍Apache Flink的生态系统。安装和使用DataSet 和DataStream API 为处理处理批处理和流数据集。赋予Flink SQL能力，本书将为查询和操作数据探索 Table API 。后半部分，读者会学习Apache Flink生态系统的其余部分。最后会包括一些Apache Flink解决方案的扩展主题，性能优化及Flink与其他工具的集成，比如 hahddop,elastic search,cassandra 和kafka。）

Whether you want to dive deeper into Apache Flink, or investigate how to get more out of this powerful technology, you'll find everything inside. This book covers a lot of real-world use cases, which will help you connect the dots.
（无论是想深入了解Apache Flink的内部原理，还是想研究如何从这个强大的技术中获取更多知识，这本书可以满足.本书覆盖了很多现实世界中的很多应用场景，这些会帮助你把这些点连起来。）

What this book covers（本书包含哪些内容？）
---
`Chapter 1` Introduction to Apache Flink, introduces you to the history, architecture, features and installation of Apache Flink on single node and multinode clusters(第一章介绍Apache Flink，介绍它的历史，架构，功能及单机的和集群的安装)
`Chapte 2 `  Data Processing Usine the DataStream API ，provides you with the details of Flink's streaming first concept. You will learn details about data sources, transformation,and data sinks available with DataStream API(第二章 介绍使用`DataStream  API`的数据处理，介绍Flink 流处理的第一个概念。你将了解data source，transformation及sinks结合`DataStream API`使用细节)

`Chapter 3`, Data Processing Usine the Batch Processing APl, enlightens you with the batch processing API that is. DataSet API You will learn about data sources, transformations.and sinks. You will also leam about the connectors available with the API.(使用`Batch Processing API`进行数据处理。引导你使用批处理API,那就是DataSet API,你将学到data source,transformations  和sinks。你也会学到关于链接器结合这些API的使用)

`Chapter 4`, Data Processing Usine the Table API, helps you understand how to use SQL concepts with Flink data processing frameworks. You will also learn how to apply these concepts to the real-world use case.(使用Table API 的数据处理,有助于理解Flink数据处理框架的SQL概念。你还会学到怎样将这些概念用到现实世界的应用场景中。)

`Chapter 5`, Complex Event Processing, provides insights to you on how to solve complex event processing problems using Flink CEP library. You will learn details about the pattern definition, detection, and alert generation(复杂事件处理 CEP，提供给你用flink cep 包解决复杂事件处理问题见解。你也将学到关于 `pattern definition`,`detection`及`alert generation`的相关细节。)

`Chapter 6`. Machine Learning Using Flink ML. covers details on machine learning concepts and how to apply various algorithms to the real-life use cases.(第六章.机器学习 覆盖关于机器学习的详细概念和如何将各位机器学习算法应用到现实生活中。)


`Chapte 7`, Flink Graph API- Gelly, introduces you to the graph concepts and what Flink Gelly offers us to solve real-life use cases. It enlightens you on iterative graph processing.capabilities provided by Flink（第7章 Flink图API `Gelly`, 介绍图相关的概念和`Flink Gelly`为解决实际问题提供了什么功能。）
`Chapter 8`. Distributed Data Processing Usine Flink and Hadoop, covers details on how to use existing Hadoop-YARN clusters to submit Flink jobs. It talks about how Flink works on YARN in detail（使用Flink和hadoop进行分布式数据处理，覆盖如何用现有的`Hadoop-YARN`集群，提交`Flink jobs`。本章会讨论Flink如何工作在`Hadoop-YARN`上的细节。 ）
`Chapter 9`, Deploying Flink on Cloud, provides details on how to deploy Flink on Cloud, It talks in detail about how to use Flink on Google Cloud and AWS.(在云上部署Flink,向你提供怎样在云上部署flink 的细节，详细讨论Flink 如何如何工作在Google云和AWS云)

`Chapter 10`, Best Practices, covers various best practices developers should follow in order to use Flink in an efficient manner. It also talks about logging, monitoring best practices to control the Flink environment(最佳实践，覆盖多种开发者应该学习的最佳实践，以便可以更有效的使用Flink.也讨论关于日志，监控控制Flink环境的最佳实践。)
