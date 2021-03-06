---
title: 云数据库 
header: develop
nav: cloud
sidebar: cloud_essentials
---
 

云开发提供了一个 NoSQL 文档数据库，可供开发者存储、查询数据。开发者可以在智能小程序端和云函数端通过 SDK 对数据库进行操作。按照云数据库的 NoSQL 数据模型，一个云数据库可以拥有多个集合（相当于关系型数据库中表的概念），每一个集合都可以包含若干条记录，每一条记录都是一则类似 JSON 格式的文档，包含一系列字段和对应的值。开发者可以通过指定各类检索条件、排序和数量限制来查询云数据库中的记录。

下面是一条记录的简单示例。

```json
{
    "_id": "358a732d-bd8d-45a5-bd9c-9874e1a654c4",
    "title": "一个标题",
    "content": "内容",
    "author": "作者用户ID",
    "comments": [
        {
            "message": "评论内容",
            "user": "评论用户ID"
        },
        {
            "message": "另一个评论内容",
            "user": "另一个评论用户ID"
        }
    ]
}
```
