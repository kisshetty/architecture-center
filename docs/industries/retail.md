---
title: Solutions for the retail industry
titleSuffix: Azure Architecture Center
description: Architectures and ideas to use Azure services for building efficient, scalable, and reliable retail solutions.
author: martinekuan
ms.author: robbag
ms.date: 06/14/2023
ms.topic: conceptual
ms.service: azure-architecture-center
ms.subservice: architecture-guide
keywords:
  - Azure
products:
  - azure
  - dynamics-365
  - microsoft-365
categories:
  - ai-machine-learning
  - analytics
  - databases
  - iot
  - storage
  - web
---

# Solutions for the retail industry

Retail is one of the fastest growing industries worldwide, generating some of the biggest revenues and accounting to almost a third of American jobs. The core of retail industry is selling products and services to consumers, through channels such as, storefront, catalog, television, and online. Retailers can enhance or reimagine their customer's journey using Microsoft Azure services by:

- keeping their supply chains agile and efficient,
- unlocking new opportunities with data and analytics,
- creating innovative customer experiences using mixed reality, AI, and IoT, and
- building a personalized and secure multi-channel retail experience for customers.

<br>

<!-- markdownlint-disable MD034 -->

> [!VIDEO https://www.youtube.com/embed/Vn5x7VM7UwQ]

<!-- markdownlint-enable MD034 -->

<br>

> [!NOTE]
> Learn more about a retail company's journey to cloud adoption, in [Cloud adoption for the retail industry](/azure/cloud-adoption-framework/industry/retail).

Using Azure services, retailers can easily achieve these goals. For use cases and customer stories, visit [Azure for retail](https://azure.microsoft.com/industries/retailers/). Microsoft is also revolutionizing the retail industry, by providing a comprehensive retail package, [Microsoft Cloud for Retail](https://www.microsoft.com/industry/retail/microsoft-cloud-for-retail).

## Architecture guides for retail

The following articles provide more details about retail architectural topics. Although they are mostly conceptual, they can also include implementation details.

| Guide | Summary | Technology focus |
| ------- | ------- | ------- |
| [Overview of Retail data solutions in Microsoft Fabric](/industry/retail/retail-data-solutions/overview-retail-data-solutions) | Primer for how to ingest, prepare, store, analyze, and take action on data, for the retail industry. | Databases |
| [Migrate your e-commerce solution to Azure](/previous-versions/azure/industry-marketing/retail/migrating-ecommerce-solution-to-azure?toc=/azure/architecture/toc.json&bc=/azure/architecture/_bread/toc.json) | Learn how to move an existing e-commerce solution to the cloud. The three stages are to rehost, refactor, and rebuild your solution. | Migration |
| [Visual search in retail with Azure Cosmos DB](/previous-versions/azure/industry-marketing/retail/visual-search-use-case-overview?toc=/azure/architecture/toc.json&bc=/azure/architecture/_bread/toc.json) | This document focuses on the AI concept of visual search and offers a few key considerations on its implementation. It provides a workflow example and maps its stages to the relevant Azure technologies. | Databases |
| [SKU optimization for consumer brands](/previous-versions/azure/industry-marketing/retail/sku-optimization-solution-guide?toc=/azure/architecture/toc.json&bc=/azure/architecture/_bread/toc.json) | Topics include automating decision making, SKU assortment optimization, descriptive analytics, predictive analytics, parametric models, non-parametric models, implementation details, data output and reporting, and security considerations. | Analytics |

## Architectures for retail

The following articles provide detailed analysis of architectures developed and recommended for the retail industry.

| Architecture | Summary | Technology focus |
| ------- | ------- | ------- |
| [Data warehousing and analytics](../example-scenario/data/data-warehouse.yml) | Build an insightful sales and marketing solution with a data pipeline that integrates large amounts of data from multiple sources into a unified analytics platform in Azure. | Analytics |
| [IBM z/OS online transaction processing on Azure](../example-scenario/mainframe/ibm-zos-online-transaction-processing-azure.yml) | With a dynamically adaptable infrastructure, businesses can realize and launch their products quickly to delight their users. Learn how to migrate a z/OS mainframe OLTP application to a secure, scalable, and highly available system in the cloud. | Mainframe |
| [Intelligent product search engine for e-commerce](../example-scenario/apps/ecommerce-search.yml) | Use Azure Cognitive Search, a dedicated search service, to dramatically increase the relevance of search results for your e-commerce customers. | Web |
| [Magento e-commerce platform in Azure Kubernetes Service](../example-scenario/magento/magento-azure.yml) | Learn how to deploy and host Magento, an open-source e-commerce platform, on Azure. | Web |
| [Stream processing with Azure Databricks](../reference-architectures/data/stream-processing-databricks.yml) | Use Azure Databricks to build an end-to-end stream processing pipeline for a taxi company, to collect, and analyze trip and fare data from multiple devices. | Analytics |
| [Stream processing with Azure Stream Analytics](../reference-architectures/data/stream-processing-stream-analytics.yml) | Use Azure Stream Analytics to build an end-to-end stream processing pipeline for a taxi company, to collect, and analyze trip and fare data from multiple devices. | Analytics |

## Solution ideas for retail

The following are other ideas that you can use as a starting point for your retail solution.

**AI**:

- [Personalized Offers](../solution-ideas/articles/personalized-offers.yml)

**Analytics**:

- [Big data analytics with Azure Data Explorer](../solution-ideas/articles/big-data-azure-data-explorer.yml)
- [Interactive price analytics](../solution-ideas/articles/interactive-price-analytics.yml)
- [Modern analytics architecture with Azure Databricks](../solution-ideas/articles/azure-databricks-modern-analytics-architecture.yml)

**Mixed Reality**:

- [Facilities management powered by mixed reality and IoT](../solution-ideas/articles/facilities-management-powered-by-mixed-reality-and-iot.yml)

**Networking**:

- [Video capture and analytics for retail](../networking/idea/video-analytics.yml)

**Web**:

- [E-commerce website running in secured App Service Environment](../web-apps/idea/ecommerce-website-running-in-secured-ase.yml)
- [Architect a scalable e-commerce web app](../web-apps/idea/scalable-ecommerce-web-app.yml)
