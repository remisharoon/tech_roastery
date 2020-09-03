---
title: An Architects Guide to Serialization Formats
date: "2020-09-01T11:53:32.169Z"
template: "post"
draft: false
slug: "Deep-Dive-into-Serialization-Formats"
category: "Streaming"
tags:
  - "Streaming"
  - "Deploy"
  - "ZeroDownTime"
description: "An Architects Guide to Serialization Formats Illustrated using Python"
socialImage: "/media/test.jpg"
---

- [Types Of Serialization](#serialzation-types)
- [Comparison](#serialzation-comparison)
- [How to pick the one I need?](#serialzation-choose)


## Types Of Serialization

In todays microservices architecture different services are written in different languages. They need to communicate each other in a language independent format.

In the every modern services based application, serialization is an inevitable process. There are several types and formats of serializations avaialble infront of us.

They vary in terms of complexity, compatibility, extensibilty and several other fronts. Lets go through each one of them one by one.

1. Parquet
2. ORC
3. HDF5
4. Avro
5. JSON
6. CSV
7. Arrow
8. XML
9. ProtoBuf
10. Thrift
11. language specific format
12. msgpack - Schemaless binary format


## Comparison


## How to pick the one I need?

1. Complexity
2. Language Support
3. Schema Support [Metadata Support]
4. Performance
5. Security
6. Streaming