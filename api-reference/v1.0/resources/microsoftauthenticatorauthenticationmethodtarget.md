---
title: "microsoftAuthenticatorAuthenticationMethodTarget resource type"
description: "A collection of groups enabled to use Microsoft Authenticator authentication methods policy."
author: "mjsantani"
ms.localizationpriority: medium
ms.prod: "identity-and-sign-in"
doc_type: resourcePageType
---

# microsoftAuthenticatorAuthenticationMethodTarget resource type
Namespace: microsoft.graph

A collection of groups enabled to use [Microsoft Authenticator authentication methods policy](../resources/microsoftAuthenticatorAuthenticationMethodConfiguration.md) in Azure AD.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|authenticationMode|microsoftAuthenticatorAuthenticationMode|Determines which types of notifications can be used for sign-in. Possible values are: `any`, `deviceBasedPush` (passwordless only), `push`.|
|id|String|Object ID of an Azure AD user or group.|
|isRegistrationRequired|Boolean|Determines whether the user is enforced to register the authentication method. *Not supported*. |
|targetType|authenticationMethodTargetType| Possible values are: `user`, `group`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.microsoftAuthenticatorAuthenticationMethodTarget",
  "baseType": "microsoft.graph.authenticationMethodTarget",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.microsoftAuthenticatorAuthenticationMethodTarget",
  "targetType": "String",
  "id": "String (identifier)",
  "isRegistrationRequired": "Boolean",
  "authenticationMode": "String"
}
```
