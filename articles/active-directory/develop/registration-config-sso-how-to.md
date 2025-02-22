---
title: Configure application single sign-on
description: How to configure single sign-on for a custom application you are developing and registering with Azure AD.
services: active-directory
author: rwike77
manager: CelesteDG

ms.service: active-directory
ms.subservice: develop
ms.custom: aaddev, has-adal-ref
ms.workload: identity
ms.topic: conceptual
ms.date: 07/15/2019
ms.author: ryanwi
ROBOTS: NOINDEX
---

# How to configure single sign-on for an application

Enabling federated single sign-on (SSO) in your app is automatically enabled when federating through Azure AD for OpenID Connect, SAML 2.0, or WS-Fed. If your end users are having to sign in despite already having an existing session with Azure AD, it’s likely your app may be misconfigured.

* If you’re using Microsoft Authentication Library (MSAL), make sure you have **PromptBehavior** set to **Auto** rather than **Always**.

* If you’re building a mobile app, you may need additional configurations to enable brokered or non-brokered SSO.

For Android, see [Enabling Cross App SSO in Android](msal-android-single-sign-on.md).

For iOS, see [Enabling Cross App SSO in iOS](single-sign-on-macos-ios.md).

## Next steps

[Azure AD SSO](../manage-apps/what-is-single-sign-on.md)<br>

[Enabling Cross App SSO in Android](msal-android-single-sign-on.md)<br>

[Enabling Cross App SSO in iOS](single-sign-on-macos-ios.md)<br>

[Integrating Apps to AzureAD](./quickstart-register-app.md)<br>

[Permissions and consent in the Microsoft identity platform](./v2-permissions-and-consent.md)<br>

[AzureAD Microsoft Q&A](/answers/topics/azure-active-directory.html)
