---
title: Other tools for debugging AEM SDK
description: A variety of other tools can aid in debugging the AEM SDK's local quickstart.
feature: Developer Tools
topics: development
version: Cloud Service
doc-type: tutorial
activity: develop
audience: developer
kt: 5251
topic: Development
role: Developer
level: Beginner, Intermediate
exl-id: 11fb83e9-dbaf-46e5-8102-ae8cc716c6ba
---
# Other tools for debugging AEM SDK

A variety of other tools can aid in debugging your application on the AEM SDK's local quickstart. 

## CRXDE Lite

![CRXDE Lite](./assets/other-tools/crxde-lite.png)

CRXDE Lite is a web-based interface for interacting with the JCR, AEM's data repository. CRXDE Lite provides completely visibility into the JCR, including nodes, properties, property values, and permissions.

CRXDE Lite is located at:

+ Tools > General > CRXDE Lite
+ or directly at [http://localhost:4502/crx/de/index.jsp](http://localhost:4502/crx/de/index.jsp)

## Explain Query

![Explain Query](./assets/other-tools/explain-query.png)

Explain Query web-based tool in AEM SDK's local quickstart, that provides key insights into how AEM interprets and executes queries, and an invaluable tool to ensure queries are being executed in a performant manner by AEM.

Explain Query is located at:

+ Tools > Diagnosis > Query Performance > Explain Query Tab
+ [http://localhost:4502/libs/granite/operations/content/diagnosistools/queryPerformance.html](http://localhost:4502/libs/granite/operations/content/diagnosistools/queryPerformance.html) > Explain Query tab

## QueryBuilder Debugger 

![QueryBuilder Debugger](./assets/other-tools/query-debugger.png)

QueryBuilder debugger is web-based tool that helps you debug and understand search queries using AEM's [QueryBuilder](https://experienceleague.adobe.com/docs/experience-manager-65/developing/platform/query-builder/querybuilder-api.html) syntax.

QueryBuilder Debugger is located at:

+ [http://localhost:4502/libs/cq/search/content/querydebug.html](http://localhost:4502/libs/cq/search/content/querydebug.html)
