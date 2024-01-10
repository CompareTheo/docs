---
layout: default
title: GOBI ISBN Retrieval
parent: Alma Documentation
nav_order: 5
---
### Creating the Analysis

ISBN Formula: EVALUATE('regexp_substr(%1,%2,%3,%4)', "Bibliographic Details"."ISBN", '(^978)[^\; ]+', 1, 1)