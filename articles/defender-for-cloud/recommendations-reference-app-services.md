---
title: Reference table for Azure App Service security recommendations 
description: This article lists the Microsoft Defender for Cloud security recommendations for Azure App Service.
author: dcurwin
ms.service: defender-for-cloud
ms.topic: reference
ms.date: 03/13/2024
ms.author: dacurwin
ms.custom: generated
ai-usage: ai-assisted
---

# Azure App Service security recommendations

This article lists all the security recommendations you might see issued by the Microsoft Defender for Cloud plan - Microsoft Defender for Cloud for Azure App Service.

The recommendations that appear in your environment are based on the resources that you're protecting and on your customized configuration.

To learn about actions that you can take in response to these recommendations, see [Remediate recommendations in Defender for Cloud](implement-security-recommendations.md).


> [!TIP]
> If a recommendation's description says *No related policy*, usually it's because that recommendation is dependent on a different recommendation and *its* policy.
>
> For example, the recommendation *Endpoint protection health failures should be remediated* relies on the recommendation that checks whether an endpoint protection solution is even installed (*Endpoint protection solution should be installed*). The underlying recommendation *does* have a policy. Limiting the policies to only the foundational recommendation simplifies policy management.

## App Services recommendations

### [API App should only be accessible over HTTPS](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/bf82a334-13b6-ca57-ea75-096fc2ffce50)

**Description**: Use of HTTPS ensures server/service authentication and protects data in transit from network layer eavesdropping attacks.
(Related policy: [API App should only be accessible over HTTPS](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2fb7ddfbdc-1260-477d-91fd-98bd9be789a6)).

**Severity**: Medium

### [CORS should not allow every resource to access API Apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/e40df93c-7a7c-1b0a-c787-9987ceb98e54)

**Description**: Cross-Origin Resource Sharing (CORS) should not allow all domains to access your API app. Allow only required domains to interact with your API app.
(Related policy: [CORS should not allow every resource to access your API App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fmicrosoft.authorization%2fpolicydefinitions%2f358c20a6-3f9e-4f0e-97ff-c6ce485e2aac)).

**Severity**: Low

### [CORS should not allow every resource to access Function Apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/7b3d4796-9400-2904-692b-4a5ede7f0a1e)

**Description**: Cross-Origin Resource Sharing (CORS) should not allow all domains to access your Function app. Allow only required domains to interact with your Function app.
(Related policy: [CORS should not allow every resource to access your Function Apps](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fmicrosoft.authorization%2fpolicydefinitions%2f0820b7b9-23aa-4725-a1ce-ae4558f718e5)).

**Severity**: Low

### [CORS should not allow every resource to access Web Applications](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/df4d1739-47f0-60c7-1706-3731fea6ab03)

**Description**: Cross-Origin Resource Sharing (CORS) should not allow all domains to access your web application. Allow only required domains to interact with your web app.
(Related policy: [CORS should not allow every resource to access your Web Applications](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fmicrosoft.authorization%2fpolicydefinitions%2f5744710e-cc2f-4ee8-8809-3b11e89f4bc9)).

**Severity**: Low

### [Diagnostic logs in App Service should be enabled](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/40394a2c-60fb-7cc5-1944-065772e94f05)

**Description**: Audit enabling of diagnostic logs on the app.
This enables you to recreate activity trails for investigation purposes if a security incident occurs or your network is compromised
(No related policy).

**Severity**: Medium

### [Ensure API app has Client Certificates Incoming client certificates set to On](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/ce2768c3-a7c7-1bbf-22cd-f9db675a9807)

**Description**: Client certificates allow for the app to request a certificate for incoming requests. Only clients that have a valid certificate will be able to reach the app.
(Related policy: [Ensure API app has 'Client Certificates (Incoming client certificates)' set to 'On'](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f0c192fe8-9cbb-4516-85b3-0ade8bd03886)).

**Severity**: Medium

### [FTPS should be required in API apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/67fc622b-4ce6-8c52-08ae-9f830036b757)

**Description**: Enable FTPS enforcement for enhanced security
(Related policy: [FTPS only should be required in your API App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f9a1b8c48-453a-4044-86c3-d8bfd823e4f5)).

**Severity**: High

### [FTPS should be required in function apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/972a6579-f38f-c0b9-1b4b-a5bbeba3ab5b)

**Description**: Enable FTPS enforcement for enhanced security
(Related policy: [FTPS only should be required in your Function App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f399b2637-a50f-4f95-96f8-3a145476eb15)).

**Severity**: High

### [FTPS should be required in web apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/19beaa2a-a126-b4dd-6d35-617f6cc83fca)

**Description**: Enable FTPS enforcement for enhanced security
(Related policy: [FTPS should be required in your Web App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f4d24b6d4-5e53-4a4f-a7f4-618fa573ee4b)).

**Severity**: High

### [Function App should only be accessible over HTTPS](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/cb0acdc6-0846-fd48-debe-9905af151b6d)

**Description**: Use of HTTPS ensures server/service authentication and protects data in transit from network layer eavesdropping attacks.
(Related policy: [Function App should only be accessible over HTTPS](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f6d555dd1-86f2-4f1c-8ed7-5abae7c6cbab)).

**Severity**: Medium

### [Function apps should have Client Certificates (Incoming client certificates) enabled](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/c2ab4bea-c663-3259-a4cd-03a8feb02825)

**Description**: Client certificates allow for the app to request a certificate for incoming requests. Only clients with valid certificates will be able to reach the app.
(Related policy: [Function apps should have 'Client Certificates (Incoming client certificates)' enabled](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2feaebaea7-8013-4ceb-9d14-7eb32271373c)).

**Severity**: Medium

### [Java should be updated to the latest version for API apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/08a3b009-0178-ee60-e357-e7ee5aea59c7)

**Description**: Periodically, newer versions are released for Java either due to security flaws or to include additional functionality.
Using the latest Python version for API apps is recommended to benefit from security fixes, if any, and/or new functionalities of the latest version.
(Related policy: [Ensure that 'Java version' is the latest, if used as a part of the API app](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f88999f4c-376a-45c8-bcb3-4058f713cf39)).

**Severity**: Medium

### [Managed identity should be used in API apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/cc6d1865-7617-3cb2-cf7d-4cfc01ece1df)

**Description**: For enhanced authentication security, use a managed identity.
On Azure, managed identities eliminate the need for developers to have to manage credentials by providing an identity for the Azure resource in Azure AD and using it to obtain Azure Active Directory (Azure AD) tokens.
(Related policy: [Managed identity should be used in your API App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2fc4d441f8-f9d9-4a9e-9cef-e82117cb3eef)).

**Severity**: Medium

### [Managed identity should be used in function apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/23aa9cbe-c2fb-6a2f-6c97-885a6d48c4d1)

**Description**: For enhanced authentication security, use a managed identity.
On Azure, managed identities eliminate the need for developers to have to manage credentials by providing an identity for the Azure resource in Azure AD and using it to obtain Azure Active Directory (Azure AD) tokens.
(Related policy: [Managed identity should be used in your Function App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f0da106f2-4ca3-48e8-bc85-c638fe6aea8f)).

**Severity**: Medium

### [Managed identity should be used in web apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/4a3d7cd3-f17c-637a-1ffc-614a01dd03cf)

**Description**: For enhanced authentication security, use a managed identity.
On Azure, managed identities eliminate the need for developers to have to manage credentials by providing an identity for the Azure resource in Azure AD and using it to obtain Azure Active Directory (Azure AD) tokens.
(Related policy: [Managed identity should be used in your Web App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f2b9ad585-36bc-4615-b300-fd4435808332)).

**Severity**: Medium

### [Microsoft Defender for App Service should be enabled](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/0876ef51-fee7-449d-ba1e-f2662c7e43c6)

**Description**: Microsoft Defender for App Service leverages the scale of the cloud, and the visibility that Azure has as a cloud provider, to monitor for common web app attacks.
Microsoft Defender for App Service can discover attacks on your applications and identify emerging attacks.

Remediating this recommendation will result in charges for protecting your App Service plans. If you don't have any App Service plans in this subscription, no charges will be incurred.
If you create any App Service plans on this subscription in the future, they will automatically be protected and charges will begin at that time.
Learn more in [Protect your web apps and APIs](defender-for-app-service-introduction.md).
(Related policy: [Azure Defender for App Service should be enabled](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fmicrosoft.authorization%2fpolicyDefinitions%2f2913021d-f2fd-4f3d-b958-22354e2bdbcb)).

**Severity**: High

### [PHP should be updated to the latest version for API apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/6b86d069-b3c3-b4d7-47c7-e73ddf786a63)

**Description**: Periodically, newer versions are released for PHP software either due to security flaws or to include additional functionality.
Using the latest PHP version for API apps is recommended to benefit from security fixes, if any, and/or new functionalities of the latest version.
(Related policy: [Ensure that 'PHP version' is the latest, if used as a part of the API app](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f1bc1795e-d44a-4d48-9b3b-6fff0fd5f9ba)).

**Severity**: Medium

### [Python should be updated to the latest version for API apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/c2c90d64-38e2-e984-1457-7f4a98168c72)

**Description**: Periodically, newer versions are released for Python software either due to security flaws or to include additional functionality.
Using the latest Python version for API apps is recommended to benefit from security fixes, if any, and/or new functionalities of the latest version.
(Related policy: [Ensure that 'Python version' is the latest, if used as a part of the API app](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f74c3584d-afae-46f7-a20a-6f8adba71a16)).

**Severity**: Medium

### [Remote debugging should be turned off for API App](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/9172da4e-9571-6e33-2b5b-d742847f3be7)

**Description**: Remote debugging requires inbound ports to be opened on an API app. Remote debugging should be turned off.
(Related policy: [Remote debugging should be turned off for API Apps](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fmicrosoft.authorization%2fpolicydefinitions%2fe9c8d085-d9cc-4b17-9cdc-059f1f01f19e)).

**Severity**: Low

### [Remote debugging should be turned off for Function App](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/093c685b-56dd-13a3-8ed5-887a001837a2)

**Description**: Remote debugging requires inbound ports to be opened on an Azure Function app. Remote debugging should be turned off.
(Related policy: [Remote debugging should be turned off for Function Apps](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fmicrosoft.authorization%2fpolicydefinitions%2f0e60b895-3786-45da-8377-9c6b4b6ac5f9)).

**Severity**: Low

### [Remote debugging should be turned off for Web Applications](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/64b8637e-4e1d-76a9-0fc9-c1e487a97ed8)

**Description**: Remote debugging requires inbound ports to be opened on a web application. Remote debugging is currently enabled. If you no longer need to use remote debugging, it should be turned off.
(Related policy: [Remote debugging should be turned off for Web Applications](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fmicrosoft.authorization%2fpolicydefinitions%2fcb510bfd-1cba-4d9f-a230-cb0976f4bb71)).

**Severity**: Low

### [TLS should be updated to the latest version for API apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/5a659d57-117d-bb18-65f6-54e51da1bb9b)

**Description**: Upgrade to the latest TLS version.
(Related policy: [Latest TLS version should be used in your API App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f8cb6aa8b-9e41-4f4e-aa25-089a7ac2581e)).

**Severity**: High

### [TLS should be updated to the latest version for function apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/15be5f3c-e0a4-c0fa-fbff-8e50339b4b22)

**Description**: Upgrade to the latest TLS version.
(Related policy: [Latest TLS version should be used in your Function App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2ff9d614c5-c173-4d56-95a7-b4437057d193)).

**Severity**: High

### [TLS should be updated to the latest version for web apps](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/2a54c352-7ca4-4bae-ad46-47ecd9595bd2)

**Description**: Upgrade to the latest TLS version.
(Related policy: [Latest TLS version should be used in your Web App](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2ff0e6e85b-9b9f-4a4b-b67b-f730d42f1b0b)).

**Severity**: High

### [Web Application should only be accessible over HTTPS](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/1b351b29-41ca-6df5-946c-c190a56be5fe)

**Description**: Use of HTTPS ensures server/service authentication and protects data in transit from network layer eavesdropping attacks.
(Related policy: [Web Application should only be accessible over HTTPS](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2fa4af4a39-4135-47fb-b175-47fbdf85311d)).

**Severity**: Medium

### [Web apps should request an SSL certificate for all incoming requests](https://portal.azure.com/#blade/Microsoft_Azure_Security/RecommendationsBlade/assessmentKey/ca4e6a5a-3a9a-bad3-798a-d420a1d9bd6d)

**Description**: Client certificates allow for the app to request a certificate for incoming requests.
Only clients that have a valid certificate will be able to reach the app.
(Related policy: [Ensure WEB app has 'Client Certificates (Incoming client certificates)' set to 'On'](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2fproviders%2fMicrosoft.Authorization%2fpolicyDefinitions%2f5bb220d9-2698-4ee4-8404-b9c30c9df609)).

**Severity**: Medium



## Related content

- [Learn about security recommendations](security-policy-concept.md)
- [Review security recommendations](review-security-recommendations.md)