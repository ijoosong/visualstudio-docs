---
title: "How to: Create a BDC Model | Microsoft Docs"
description: Create a Business Data Connectivity (BDC) model using the Visual Studio template for that kind of item and then adding the model to any SharePoint project.
ms.custom: SEO-VS-2020
ms.date: "02/02/2017"
ms.topic: how-to
dev_langs:
  - "VB"
  - "CSharp"
helpviewer_keywords:
  - "BDC [SharePoint development in Visual Studio], creating a model"
  - "Business Data Connectivity service [SharePoint development in Visual Studio], creating a model"
author: John-Hart
ms.author: johnhart
manager: jmartens
ms.technology: sharepoint-development
ms.workload:
  - "office"
---
# How to: Create a BDC model

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]

  You can create a Business Data Connectivity (BDC) model by using the template for that kind of item and then adding the model to any SharePoint project. For more information, see [Create a business data connectivity model](../sharepoint/creating-a-business-data-connectivity-model.md). For more information about how to design the model, see [Design a business data connectivity model](../sharepoint/designing-a-business-data-connectivity-model.md).

## To create a BDC project

1. On the menu bar, choose **File** > **New** > **Project**.

::: moniker range=">=vs-2019"
2. On the **Create a New Project** dialog select the *SharePoint Empty Project** for the particular version of SharePoint you have installed. For example, if you have SharePoint 2019 install select the **SharePoint 2019 - Empty Project** template.
    [!INCLUDE[new-project-dialog-search](../sharepoint/includes/new-project-dialog-search-md.md)]

3. Change the name of the project if you would like to, and then choose the **Create** button.

::: moniker-end
4. On the **Specify the site and security level for debugging** page, specify the URL of a SharePoint site on the local computer, choose the **Deploy as farm solution** option button, and then choose the **Finish** button.

     You will test the model on the SharePoint site that you specified.

    > [!IMPORTANT]
    > You must deploy the project as a farm solution because BDC models support only farm solutions.

     An empty SharePoint project is created.

5. On the menu bar, choose **Project** > **Add New Item**.

6. In the **Add New Item** dialog box, choose the **Office/SharePoint** node.

7. In the list of SharePoint templates, choose **Business Data Connectivity Model (Farm Solution Only)**.

8. In the **Name** box, specify a name for the BDC model, and then choose the **Add** button.

     A **Business Data Connectivity Model** item is added to the project. By default, the model appears in the BDC designer. For more information, see [Create a business data connectivity model](../sharepoint/creating-a-business-data-connectivity-model.md).

## See also

- [Create a business data connectivity model](../sharepoint/creating-a-business-data-connectivity-model.md)
- [How to: Add an existing BDC model file to a SharePoint project](../sharepoint/how-to-add-an-existing-bdc-model-file-to-a-sharepoint-project.md)
- [How to: Use a resource file to specify localized names, properties, and permissions](../sharepoint/how-to-use-a-resource-file-to-specify-localized-names-properties-and-permissions.md)
- [How to: Include a custom assembly in a BDC feature](../sharepoint/how-to-include-a-custom-assembly-in-a-bdc-feature.md)
- [Integrating business data into SharePoint](../sharepoint/integrating-business-data-into-sharepoint.md)
