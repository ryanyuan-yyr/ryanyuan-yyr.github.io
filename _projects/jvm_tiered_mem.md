---
layout: page
title: JVM-Managed Tiered Memory
description: Leverages semantic information in Java runtimes to place objects in tiered memory
img: assets/img/jvm-heap.png
importance: 1
category: Research projects
---

In this project, we aim to leverage managed runtimes to automatically decide the placement of objects over the tiered memory. To take advantage of both the low latency of fast memory and the large capacity of slow memory, the managed runtimes are required to identify and predict the access frequency of objects and place the frequently accessed ones in fast memory and infrequently accessed ones in slow memory. 

We leveraged the reachability of objects to design the object placement policy. With the sematic information obtained from JVM, we can manage the tiered memory in a finer granularity and predict the hot areas more accurately compared to OS management. 