# 《Elasticsearch 7 Quick Start Guide》Learning Notes



## 1. Profiles

![Redis 4.x Cookbook](assets/cover.png)

|    **Title**    | **Elasticsearch 7 Quick Start Guide** [ISBN: 9781789803327] |
| :-------------: | :---------------------------------------------------------: |
|   **Author**    |            **Anurag Srivastava, Douglas Miller**            |
| **Publication** |                     **Packt, 2019.10**                      |
|    **Pages**    |                           **176**                           |

> **Introduction**
>
> Elasticsearch is one of the most popular tools for distributed search and analytics. This Elasticsearch book highlights the latest features of Elasticsearch 7 and helps you understand how you can use them to build your own search applications with ease.
>
> Starting with an introduction to the Elastic Stack, this book will help you quickly get up to speed with using Elasticsearch. You'll learn how to install, configure, manage, secure, and deploy Elasticsearch clusters, as well as how to use your deployment to develop powerful search and analytics solutions. As you progress, you'll also understand how to troubleshoot any issues that you may encounter along the way. Finally, the book will help you explore the inner workings of Elasticsearch and gain insights into queries, analyzers, mappings, and aggregations as you learn to work with search results.
>
> By the end of this book, you'll have a basic understanding of how to build and deploy effective search and analytics solutions using Elasticsearch.



## 2. Outlines

Status available：:heavy_check_mark: (Completed) | :hourglass_flowing_sand: (Working) | :no_entry: (Not Started) | :orange_book: (Finish reading)

| No.  |        Chapter Title        |          Status          |
| :--: | :-------------------------: | :----------------------: |
| Ch01 | [Introduction to Elastic Stack](./Ch01.md) |    :no_entry:    |
| Ch02 | [Installing Elasticsearch](./Ch02.md) | :no_entry: |
| Ch03 | [Many as One – the Distributed Model](./Ch03.md) |        :no_entry:        |
| Ch04 | [Prepping Your Data – Text Analysis and Mapping](./Ch04.md) |        :no_entry:        |
| Ch05 | [Let's Do a Search!](./Ch05.md) |        :no_entry:        |
| Ch06 | [Performance Tuning](./Ch06.md) |        :no_entry:        |
| Ch07 | [Aggregating Datasets](./Ch07.md) |        :no_entry:        |
| Ch08 | [Best Practices](./Ch08.md) |        :no_entry:        |



Powershell script for generating markdown files in batch:

```powershell
# Create 8 empty markdown files named Ch##.md:
for($i=1; $i -le 8; $i=$i+1){ New-Item -Name "Ch$('{0:d2}' -f $i).md"; }
```

 
