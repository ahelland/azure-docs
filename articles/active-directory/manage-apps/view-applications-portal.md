---
title: 'Quickstart: View enterprise applications'
description: View the enterprise applications that are registered to use your Azure Active Directory tenant.
titleSuffix: Azure AD
services: active-directory
author: davidmu1
manager: CelesteDG
ms.service: active-directory
ms.subservice: app-mgmt
ms.workload: identity
ms.topic: quickstart
ms.date: 09/07/2021
ms.author: davidmu
ms.reviewer: arvinh
ms.custom: mode-other
#Customer intent: As an administrator of an Azure AD tenant, I want to search for and view the enterprise applications in the tenant.
---

# Quickstart: View enterprise applications

In this quickstart, you learn how to use the Azure Active Directory Admin Center to search for and view the enterprise applications that are already configured in your Azure Active Directory (Azure AD) tenant.

It is recommended that you use a non-production environment to test the steps in this quickstart.

## Prerequisites

To view applications that have been registered in your Azure AD tenant, you need:

- An Azure account. [Create an account for free](https://azure.microsoft.com/free/?WT.mc_id=A261C142F).
- One of the following roles: Global Administrator, Cloud Application Administrator, Application Administrator, or owner of the service principal.
- Completion of the steps in [Quickstart: Add an enterprise application](add-application-portal.md).

## View a list of applications

To view the enterprise applications registered in your tenant:

1. Go to the [Azure Active Directory Admin Center](https://aad.portal.azure.com) and sign in using one of the roles listed in the prerequisites.
1. In the left menu, select **Enterprise applications**. The **All applications** pane opens and displays a list of the applications in your Azure AD tenant.

    :::image type="content" source="media/view-applications-portal/view-enterprise-applications.png" alt-text="View the registered applications in your Azure AD tenant.":::

1. To view more applications, select **Load more** at the bottom of the list. If there are many applications in your tenant, it might be easier to search for a particular application instead of scrolling through the list.

## Search for an application

To search for a particular application:

1. In the **Application Type** menu, select **All applications**, and choose **Apply**.
1. Enter the name of the application you want to find. If the application has been added to your Azure AD tenant, it appears in the search results. For example, you can search for the **Azure AD SAML Toolkit 1** application that is used in the previous quickstarts. 
1. Try entering the first few letters of an application name.

## Select viewing options

Select options according to what you're looking for:

1. You can view the applications by **Application Type**, **Application Status**, and **Application visibility**.
1. Under **Application Type**, choose one of these options:
    - **Enterprise Applications** shows non-Microsoft applications.
    - **Microsoft Applications** shows Microsoft applications.
    - **Managed Identities** shows applications that are used to authenticate to services that support Azure AD authentication.
    - **All Applications** shows both non-Microsoft and Microsoft applications.
1. Under **Application Status**, choose **Any**, **Disabled**, or **Enabled**. The **Any** option includes both disabled and enabled applications.
1. Under **Application Visibility**, choose **Any**, or **Hidden**. The **Hidden** option shows applications that are in the tenant, but aren't visible to users.
1. After choosing the options you want, select **Apply**.

## Clean up resources

If you created a test application named **Azure AD SAML Toolkit 1** that was used throughout the quickstarts, you can consider deleting it now to clean up your tenant. For more information, see [Delete an application](delete-application-portal.md).

## Next steps

Learn how to delete an enterprise application.
> [!div class="nextstepaction"]
> [Delete an application](add-application-portal.md)
