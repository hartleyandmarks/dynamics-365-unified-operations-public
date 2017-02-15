---
# required metadata

title: Data entities report
description: This topic points you to a report that lists the data entities available in Microsoft Dynamics AX.
author: annbe
manager: AnnBe
ms.date: 2016-10-10 13 - 32 - 44
ms.topic: article
ms.prod: 
ms.service: Dynamics365Operations
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Developer, IT Pro
# ms.devlang: 
# ms.reviewer: 71
ms.search.scope: Operations, Platform, AX Platform
# ms.tgt_pltfrm: 
ms.custom: 202654
ms.assetid: 7b26a922-7347-4768-80ba-3ce0f11b601f
ms.search.region: Global
# ms.search.industry: 
ms.author: annbe
ms.dyn365.intro: May-16
ms.dyn365.version: Platform update 1

---

# Data entities report

This topic points you to a report that lists the data entities available in Microsoft Dynamics AX.

A *data entity* is an abstraction from the physical implementation of database tables. For example, in normalized tables, a lot of the data for each customer might be stored in a customer table, and then the rest might be spread across a small set of related tables. In this case, the data entity for the customer concept appears as one de-normalized view, in which each row contains all the data from the customer table and its related tables. A data entity encapsulates a business concept into a format that makes development and integration easier. The abstracted nature of a data entity can simplify application development and customization. Later, the abstraction also insulates application code from the inevitable churn of the physical tables from version to version of Microsoft Dynamics AX. For more information about data entities, see [Data entities home page](data-entities-home-page.md).

## View the report
The [Data entities report](https://mbs.microsoft.com/customersource/northamerica/AX/downloads/reports/axtechrefrep)lists each data entity that is available. The report indicates the data source of the entity and the fields included in the entity. The report also indicates whether the data entity is public.

## How the report is grouped
The report is a Microsoft Excel file. For large reports, the rows are grouped alphabetically on tab 1. All rows are displayed when you click tab 2. [![GeneratedReports](./media/generatedreports.png)](./media/generatedreports.png)
