---
title: Azure Stream Analytics preview features
description: This article lists the Azure Stream Analytics features that are currently in preview
author: enkrumah
ms.author: ebnkruma
ms.service: stream-analytics
ms.topic: conceptual
ms.date: 03/23/2022
---

# Azure Stream Analytics preview features

This article summarizes all the features currently in preview for Azure Stream Analytics. Using preview features in a production environment isn't recommended.

## Authenticate to SQL Database output with managed identities (preview)

Azure Stream Analytics supports [Managed Identity authentication](../active-directory/managed-identities-azure-resources/overview.md) for Azure SQL Database output sinks. Managed identities eliminate the limitations of user-based authentication methods, like the need to reauthenticate due to password changes. 

## C# custom de-serializers
Developers can leverage the power of Azure Stream Analytics to process data in Protobuf, XML, or any custom format. You can implement [custom de-serializers](custom-deserializer-examples.md) in C#, which can then be used to de-serialize events received by Azure Stream Analytics.

## Extensibility with C# custom code

Developers creating Stream Analytics modules in the cloud or on IoT Edge can write or reuse custom C# functions and invoke them directly in the query through [user-defined functions](stream-analytics-edge-csharp-udf-methods.md).

## Debug queries locally using job diagram in Visual Studio Code

You can use the job diagram while testing your query locally to examine the intermediate result set and metrics for each step.

## Explore jobs in Visual Studio Code

Stream Analytics Explorer in Visual Studio Code Extension gives developers a lightweight experience for managing their Stream Analytics jobs. In the Stream Analytics Explorer, you can easily manage your jobs, view job diagram, and debug in Job Monitor.

## Debug query steps in Visual Studio

You can easily preview the intermediate row set on a data diagram when doing local testing in Azure Stream Analytics tools for Visual Studio. 


## Live data testing in Visual Studio

Visual Studio tools for Azure Stream Analytics enhance the local testing feature that allows you to test you queries against live event streams from cloud sources such as Event Hub or IoT hub. Learn how to [Test live data locally using Azure Stream Analytics tools for Visual Studio](stream-analytics-live-data-local-testing.md).


