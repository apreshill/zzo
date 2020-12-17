---
categories:
- diagram
date: "2019-11-18T12:00:06+09:00"
description: Generates UML sequence diagrams from simple text
draft: false
enableToc: false
enableTocContent: false
image: images/feature2/transfer.png
libraries:
- msc
series:
- null
tags:
- null
title: JS Sequence Diagram support
---

```msc
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

```msc
Title: Here is a title
A->B: Normal line
B-->C: Dashed line
C->>D: Open arrow
D-->>A: Dashed open arrow
```