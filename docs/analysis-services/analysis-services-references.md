---
title: "Analysis Services references | Microsoft Docs"
ms.date: 02/13/2020
ms.prod: sql
ms.technology: analysis-services
ms.custom:
ms.author: owend
ms.reviewer: owend
author: minewiskan
# monikerRange: "asallproducts-allversions || azure-analysis-services-current || power-bi-premium-current || >= sql-analysis-services-2016"
---
# Analysis Services references

## References

::: moniker range="asallproducts-allversions || azure-analysis-services-current || >= sql-analysis-services-2016"

### [Tabular Model Scripting Language (TMSL)](/analysis-services/tmsl/tabular-model-scripting-language-tmsl-reference)

A command and object model definition syntax for tabular models at compatibility level 1200 or higher. TMSL communicates through the XMLA protocol, where the XMLA.Execute method accepts both JSON-based and ASSL-based scripts.

::: moniker-end

::: moniker range="asallproducts-allversions || azure-analysis-services-current || >= sql-analysis-services-2016"

### [Tabular Object Model (TOM)](tom/introduction-to-the-tabular-object-model-tom-in-analysis-services-amo.md) 

TOM is an extension of the Analysis Management Object (AMO) client library, created to support programming scenarios for tabular models at compatibility level 1200 and higher.

::: moniker-end

::: moniker range="asallproducts-allversions || azure-analysis-services-current || >= sql-analysis-services-2016"

### [Analysis Management Objects](/analysis-services/amo/developing-with-analysis-management-objects-amo)

Analysis Management Objects (AMO) is a library of programmatically accessed objects that enables an application to manage an Analysis Services instance.

::: moniker-end


::: moniker range="asallproducts-allversions || azure-analysis-services-current || power-bi-premium-current || >= sql-analysis-services-2016"

### [Trace events](/analysis-services/trace-events/analysis-services-trace-events)

Capture and analyze trace events generated by server instance. Trace events are grouped so that you can more easily find related trace events. Each trace event contains a set of data relevant to the event. 

::: moniker-end

::: moniker range="asallproducts-allversions || azure-analysis-services-current || power-bi-premium-current || >= sql-analysis-services-2016"

### [Schema rowsets](/bi-reference/schema-rowsets/analysis-services-schema-rowsets)

Predefined tables that contain information about model database objects and server state, including schema, active sessions, connections, commands, and jobs executing on the server.

::: moniker-end

::: moniker range="asallproducts-allversions || >= sql-analysis-services-2016"

### [Conceptual schema definition language (CSDL)](/bi-reference/csdl/csdl-annotations-for-business-intelligence-csdlbi)

An XML-based language that describes entities, relationships, and functions in tabular models 1103 and lower compatibility levels and multidimensional models. Defined as part of the Entity Data Framework.

::: moniker-end

::: moniker range="asallproducts-allversions || >= sql-analysis-services-2016"

### [Analysis Services Scripting Language (ASSL for XMLA)](/bi-reference/assl/analysis-services-scripting-language-assl-for-xmla)

Client applications can communicate with Analysis Services using XML commands and object descriptions. ASSL represents the object definition language portion of this XML dialect.

::: moniker-end

::: moniker range="asallproducts-allversions || >= sql-analysis-services-2016"

### [ADOMD.NET](/bi-reference/adomd/developing-with-adomd-net)

.NET Framework data provider designed to communicate with Analysis Services. ADOMD.NET uses the XMLA protocol to communicate with analytical data sources by using either TCP/IP or HTTP.

::: moniker-end

::: moniker range="asallproducts-allversions || azure-analysis-services-current || power-bi-premium-current || >= sql-analysis-services-2016"

### [XML for Analysis (XMLA)](/bi-reference/xmla/xml-for-analysis-xmla-reference)

A SOAP-based XML protocol for tabular and multidimensional data sources. Fundamentally, all client libraries supported by Analysis Services formulate requests and responses in XMLA.

::: moniker-end

::: moniker range="asallproducts-allversions || azure-analysis-services-current || >= sql-analysis-services-2016"

### [Data Analysis Expressions (DAX)](https://docs.microsoft.com/dax/)

A library of functions and operators that can be combined to build formulas and expressions in Power BI Desktop, Azure Analysis Services, SQL Server Analysis Services, and Power Pivot in Excel.

::: moniker-end

::: moniker range="asallproducts-allversions || azure-analysis-services-current || >= sql-analysis-services-2016"

### [Power Query M formula language](https://docs.microsoft.com/powerquery-m/)

Used to query, filter and combine data from one or more supported data sources. 

::: moniker-end

::: moniker range="asallproducts-allversions || azure-analysis-services-current || >= sql-analysis-services-2016"

### [PowerShell for Analysis Services](powershell/analysis-services-powershell-reference.md)

PowerShell cmdlets used to configure and administer an Analysis Services model database.

::: moniker-end

::: moniker range="asallproducts-allversions || azure-analysis-services-current"

### [PowerShell for Azure Analysis Services](/azure/analysis-services/analysis-services-powershell)

PowerShell cmdlets used for resource management tasks like creating or deleting a server resource, suspending or resuming operations, or changing the service level (tier). Other tasks for managing databases like adding or removing role members, processing, or partitioning use cmdlets included in the SqlServer module.

::: moniker-end