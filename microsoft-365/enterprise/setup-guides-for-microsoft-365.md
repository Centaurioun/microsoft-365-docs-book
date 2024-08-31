---
title: "Advanced deployment guides for Microsoft 365 and Office 365 products"
ms.author: kvice
author: kelleyvice-msft
manager: scotv
ms.date: 12/19/2023
audience: ITPro
ms.topic: conceptual
ms.service: microsoft-365-enterprise
ms.subservice: administration
ms.localizationpriority: medium
ms.collection:
- scotvorg
- Ent_O365
- M365-subscription-management
- SPO_Content
- m365initiative-coredeploy
- must-keep
f1.keywords:
- CSH
ms.custom: Adm_O365_Setup
search.appverid:
- MET150
- MET150
- BCS160
ms.assetid: 165f46e8-3533-4d76-be57-97f81ebd40f2
description: "Microsoft 365 and Office 365 advanced deployment guides help admins install, update, and configure Microsoft products. Find resources for your Microsoft 365 apps."
---

# Advanced deployment guides for Microsoft 365 and Office 365 products

Microsoft 365 and Office 365 advanced deployment guides give you tailored guidance and resources for planning and deploying your tenant, apps, and services. These guides are created using the same best practices that [Microsoft 365 FastTrack](https://www.microsoft.com/fasttrack/microsoft-365) onboarding specialists share in individual interactions. They provide information on product setup, enabling security features, deploying collaboration tools, and provide scripts to speed up advanced deployments.

All advanced deployment guides are available in the Microsoft 365 admin center as described in the section below, and most guides can also be found in the [Microsoft 365 Setup portal](https://go.microsoft.com/fwlink/?linkid=2220880).

Access to advanced deployment guides in the admin center requires authentication to a Microsoft 365 tenant as an administrator or other role with access to the admin center. Advanced deployment guides in the Microsoft 365 Setup portal can be accessed by anyone. We have provided links to both locations for each guide, where available, in the tables below.

Note that guides are still being added to the setup portal, but there are a few guides that will only be available in the admin center because they require authentication to a tenant to function.

In this article:

- [How to access advanced deployment guides in the Microsoft 365 admin center](#how-to-access-advanced-deployment-guides-in-the-microsoft-365-admin-center)
- [Guides for initial setup](#guides-for-initial-setup)
- [Guides for authentication and access](#guides-for-authentication-and-access)
- [Guides for security and compliance](#guides-for-security-and-compliance)
- [Guides for collaboration](#guides-for-collaboration)
- [Advanced guides](#advanced-guides)

## How to access advanced deployment guides in the Microsoft 365 admin center

Advanced deployment guides are accessible from the [Advanced deployment guides & assistance](https://go.microsoft.com/fwlink/?linkid=2224913) page in the Microsoft 365 admin center. When you access advanced deployment guides from the admin center, you can keep track of the status of your progress and return at any time to complete a guide. This functionality is not available when you access guides from the [Microsoft 365 Setup portal](https://go.microsoft.com/fwlink/?linkid=2220880).

> [!NOTE]
> You must be assigned an admin role such as _Global Reader_ to access advanced deployment guides in the Microsoft 365 admin center. Only admins with the _Global Administrator_ role can use the guides to change settings in the tenant.

> [!IMPORTANT]
> Any selections, task assignments, and progress status saved **before January 10, 2023** within each advanced deployment guide in the admin center were reset due to EU data regulations.

To reach the **Advanced deployment guides & assistance** page:

1. In the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2224913), go to the **Home** page.

2. Find the _Training, guides & assistance_ card and select **Advanced deployment guides & assistance**.

3. If you don’t see that card, access the page directly at (https://aka.ms/advanceddeploymentguides).
   
   :::image type="content" alt-text="This screenshot shows the training & guides card in the Microsoft 365 admin center." source="../media/setup-guides-for-microsoft-365/thumbnail_ADG-TrainingCard.png":::

## Guides for initial setup

Advanced deployment guides in the admin center require authentication to a Microsoft 365 tenant as an administrator or other role with access to the admin center, but guides in the Microsoft 365 Setup portal can be accessed by anyone.

|**Guide - [Setup Portal](https://go.microsoft.com/fwlink/?linkid=2220880)** |**Guide - [Admin Center](https://go.microsoft.com/fwlink/?linkid=2224913)** |**Description** |
|---------|---------|---------|
|[‎Microsoft 365 Copilot‎ setup guide](https://go.microsoft.com/fwlink/?linkid=2249661)|[Microsoft 365 Copilot setup guide](https://go.microsoft.com/fwlink/?linkid=2249662)|The **Microsoft 365 Copilot setup guide** gets you up to speed on Copilot, which revolutionizes collaboration and takes advantage of AI to automate tasks such as writing, editing, and data visualization across Word, Excel, PowerPoint, Outlook, and Teams. Copilot also simplifies the creation of meeting summaries. Our setup guide facilitates smooth integration, allowing your organization to automate work processes and enhance collaboration seamlessly.|
|[Prepare your environment guide](https://go.microsoft.com/fwlink/?linkid=2223234)|[Prepare your environment guide](https://go.microsoft.com/fwlink/?linkid=2224195)|The **Prepare your environment guide** helps you prepare your organization's environment for Microsoft 365 and Office 365 services. Whatever your goals are, there are tasks you'll need to complete to ensure a successful deployment. To avoid any errors while preparing your environment, you're provided with step-by-step instructions to connect your domain, add users, assign licenses, set up email with Exchange Online, and install or deploy Office apps.|
|[Email setup guide](https://go.microsoft.com/fwlink/?linkid=2223145)|[Email setup guide](https://go.microsoft.com/fwlink/?linkid=2224461)|The **Email setup guide** provides you with the step-by-step guidance needed for configuring Exchange Online for your organization. This guidance includes setting up new email accounts, migrating email, and configuring email protection. For a successful email setup, use this advisor and you'll receive the recommended migration method based on your organization's current mail system, the number of mailboxes being migrated, and how you want to manage users and their access.|
|[Gmail contacts and calendar advisor](https://go.microsoft.com/fwlink/?linkid=2222987)|[Gmail contacts and calendar advisor](https://go.microsoft.com/fwlink/?linkid=2224296)|When you migrate a Gmail user's mailbox to Microsoft 365, email messages are migrated, but contacts and calendar items are not. The **Gmail contacts and calendar advisor** provides steps for importing Google contacts and Google calendar items to Microsoft 365 using import and export methods with Outlook.com, the Outlook client, or PowerShell.|
||[Microsoft 365 setup guide](https://go.microsoft.com/fwlink/?linkid=2224293)|The **Microsoft 365 setup guide** provides you with guidance when setting up productivity tools, security policies, and device management capabilities. With a Microsoft 365 Business Premium or Microsoft 365 for enterprise subscription, you can use this guide to set up and configure your organization's devices.<br>You'll receive guidance and access to resources to enable your cloud services, update devices to the latest supported version of Windows 10, and join devices to Microsoft Entra ID, all in one central location.|
||[Remote work setup guide](https://go.microsoft.com/fwlink/?linkid=2224692)|The **Remote work setup guide** provides organizations with the tips and resources needed to ensure your users can successfully work remotely, your data is secure, and users' credentials are safeguarded.<br>You'll receive guidance to optimize remote workers' device traffic to both Microsoft 365 resources in the cloud and your organization's network, which will reduce the strain on your remote access VPN infrastructure.|
|[Windows 11 and Surface setup guide](https://go.microsoft.com/fwlink/?linkid=2223054)|[Windows 11 and Surface setup guide](https://go.microsoft.com/fwlink/?linkid=2224778)|The **Windows 11 and Surface setup guide** provides information on deployment capabilities, tools, and strategies for deploying Windows 11 for new devices, existing devices, and Surface devices. You’ll gain knowledge on setting up co-management with Intune, using autopilot for customizing the out-of-box experience, and reviewing endpoint security features. This information will provide a starting point for planning your Windows 11 deployment.|
|[Microsoft Edge setup guide](https://go.microsoft.com/fwlink/?linkid=2223317)|[Microsoft Edge setup guide](https://go.microsoft.com/fwlink/?linkid=2224189)|Microsoft Edge has been rebuilt from the ground up to bring you world-class compatibility and performance, the security and privacy you deserve, and new features designed to bring you the best of the web.<br>The **Microsoft Edge setup guide** will help you configure Enterprise Site Discovery to see which sites accessed in your org might need to use IE mode, review and configure important security features, configure privacy policies and compliance policies to meet your org's requirements, and manage web access on your devices. You can download Microsoft Edge to individual devices, or we'll show you how to deploy to multiple users in your org with Group Policy, Configuration Manager, or Microsoft Intune.|
|[Configure IE mode for Microsoft Edge guide](https://go.microsoft.com/fwlink/?linkid=2223137)|[Configure IE mode for Microsoft Edge guide](https://go.microsoft.com/fwlink/?linkid=2224688)|If you've already deployed Microsoft Edge and only want to configure IE mode, the **Configure IE mode for Microsoft Edge guide** will give you scripts to automate the configuration of Enterprise Site Discovery. You'll also get IE mode recommendations from a cloud-based tool that will help you create an Enterprise Mode Site List to deploy to your users.|
||[Microsoft Search setup guide](https://go.microsoft.com/fwlink/?linkid=2224295)|Microsoft Search helps your organization find what they need to complete what they're working on. Whether it's searching for people, files, org charts, sites, or answers to common questions, your org can use Microsoft Search throughout their workday to get answers.<br>The **Microsoft Search setup guide** helps you configure Microsoft Search whether you want to pilot it to a group of users or roll it out to everyone in your org. You'll assign Search admins and Search editors and then customize the search experience for your users with answers and more options, like adding the Bing extension to Chrome or setting Bing as your default search engine.|
||[Block use of Internet Explorer in your organization guide](https://go.microsoft.com/fwlink/?linkid=2225100)|Microsoft support for Internet Explorer 11 is ending soon for most versions of Windows 10. The **Block use of Internet Explorer in your organization guide** ensures that your users can still run legacy web apps that rely on Internet Explorer. This guide also helps you move those users to Microsoft Edge with IE mode.|

## Guides for authentication and access

|Guide - [Setup Portal](https://go.microsoft.com/fwlink/?linkid=2220880) |Guide - [Admin Center](https://go.microsoft.com/fwlink/?linkid=2224913) |Description |
|---------|---------|---------|
| | [Configure multi-factor authentication (MFA) guide](https://go.microsoft.com/fwlink/?linkid=2224780) |The Configure multifactor authentication (MFA) guide provides customers who have the Microsoft Entra ID P1 or Microsoft Entra ID P2 license with customizable Conditional Access templates that include the most common and least intrusive security standards. Customers with the P2 license can also use risk-based Conditional Access policies. Customers without a P1 or P2 license can use a one-click solution to enable security defaults, a baseline protection policy for all users. They can also enable legacy (per-user) MFA.|
||[Identity security for Teams guide](https://go.microsoft.com/fwlink/?linkid=2224786)|The **Identity security for Teams guide** helps you with some basic security steps you can take to ensure your users are safe and have the most productive time using Teams.|
|[Microsoft Entra setup guide](https://go.microsoft.com/fwlink/?linkid=2223229)|[Microsoft Entra setup guide](https://go.microsoft.com/fwlink/?linkid=2224193)|The **Microsoft Entra setup guide** provides information to ensure your organization has a strong security foundation. In this guide you'll set up initial features, like Azure Role-based access control (Azure RBAC) for admins, Microsoft Entra Connect for your on-premises directory, and Microsoft Entra Connect Health, so you can monitor your hybrid identity's health during automated syncs.<br>It also includes essential information on enabling self-service password resets, conditional access, and integrated third party sign-on including optional advanced identity protection and user provisioning automation.|
|[Add or sync users to Microsoft Entra ID guide](https://go.microsoft.com/fwlink/?linkid=2223230)|[Add or sync users to Microsoft Entra ID guide](https://go.microsoft.com/fwlink/?linkid=2224811)|The **Add or sync users to Microsoft Entra ID guide** will help streamline the process of getting your user accounts set up in Microsoft 365. Based on your environment and needs, you can choose to add users individually, migrate your on-premises directory with Microsoft Entra Cloud Sync or Microsoft Entra Connect, or troubleshoot existing sync problems when necessary.|
| | [Plan your passwordless deployment guide](https://go.microsoft.com/fwlink/?linkid=2224194) | Use the **Plan your passwordless deployment guide** to discover the best passwordless authentication methods to use and receive guidance on how to upgrade to an alternative sign-in approach that allows users to access their devices securely with one of the following passwordless authentication methods:<ul><li>Windows Hello for Business</li><li>The Microsoft Authenticator app</li><li>Security keys</li><li>Temporary Access Pass</li></ul>|
||[Secure your cloud apps with Single Sign on (SSO) guide](https://go.microsoft.com/fwlink/?linkid=2224689)|This guide is designed to help you add cloud apps to Microsoft 365. In our guide, you can add an application to your tenant, add users to the app, assign roles, and more. If the app supports single sign-on (SSO), we’ll walk you through that configuration. |
|[Plan your self-service password reset (SSPR) deployment guide](https://go.microsoft.com/fwlink/?linkid=2223231)|[Plan your self-service password reset (SSPR) deployment guide](https://go.microsoft.com/fwlink/?linkid=2224781)|Give users the ability to change or reset their password independently, if their account is locked, or they forget their password without the need to contact a helpdesk engineer.<br>Use the **Plan your self-service password reset (SSPR) deployment guide** to receive relevant articles and instructions for configuring the appropriate Azure portal options to help you deploy SSPR in your environment.|
|[Migrate from AD FS to Microsoft Entra ID](https://go.microsoft.com/fwlink/?linkid=2229256)|[Migrate from AD FS to Microsoft Entra ID](https://go.microsoft.com/fwlink/?linkid=2225005)|In **Migrate from AD FS to Microsoft Entra ID** we offer custom guidance for migrating from Active Directory Federation Services (AD FS) to Microsoft Entra ID. You'll first answer a few questions about your AD FS infrastructure. Then implement either pass-through authentication (PTA) or password hash sync (PHS) to give users a streamlined experience while accessing your organization's apps.|

## Guides for security and compliance

|**Guide - [Setup Portal](https://go.microsoft.com/fwlink/?linkid=2220880)** |**Guide - [Admin Center](https://go.microsoft.com/fwlink/?linkid=2224913)** |**Description** |
|---------|---------|---------|
|[Security analyzer](https://go.microsoft.com/fwlink/?linkid=2223325)|[Security analyzer](https://go.microsoft.com/fwlink/?linkid=2224900)|The **Security analyzer** will analyze your security approach and introduce you to Microsoft integrated security and compliance solutions that can improve your security posture. You'll learn about advanced features, such as managing identities and helping to protect against modern attacks. You can then sign up for a trial subscription and be pointed to the corresponding setup guidance for each solution.|
|[Set up your Microsoft Zero Trust security model](https://go.microsoft.com/fwlink/?linkid=2222968)|[Set up your Microsoft Zero Trust security model](https://go.microsoft.com/fwlink/?linkid=2224820)|Use the **Set up your Zero Trust security model guide** to configure security that effectively adapts to the complexity of the modern environment, embraces the hybrid workplace, and helps protect people, devices, apps, and data wherever they're located. Key recommendations include: always authenticate, limit user access, minimize the blast radius, segment access, verify end-to-end encryption, and use analytics to get visibility, drive threat detection, and improve defenses.|
|[Deploy and set up Microsoft Intune](https://go.microsoft.com/fwlink/?linkid=2223058)|[Deploy and set up Microsoft Intune](https://go.microsoft.com/fwlink/?linkid=2224812)|Set up Microsoft Intune to manage devices in your organization. For full control of corporate devices, you'll use Intune's mobile device management (MDM) features. To manage your organization's data on shared and personal devices, you can use Intune's mobile application management (MAM) features.<br>With the **Deploy and set up Microsoft Intune guide**, you'll set up device and app compliance policies, assign app protection policies, and monitor the device and app protection status.|
|[Microsoft Defender for Endpoint setup guide](https://go.microsoft.com/fwlink/?linkid=2223155)|[Microsoft Defender for Endpoint setup guide](https://go.microsoft.com/fwlink/?linkid=2224785)|The **Microsoft Defender for Endpoint setup guide** provides instructions that will help your enterprise network prevent, detect, investigate, and respond to advanced threats. Make an informed assessment of your organization's vulnerability and decide which deployment package and configuration methods are best.<br>**NOTE:** A Microsoft Volume License is required for Microsoft Defender for Endpoint.|
||[Exchange Online Protection setup guide](https://go.microsoft.com/fwlink/?linkid=2224191)|Microsoft Exchange Online Protection (EOP) is a cloud-based email filtering service for protection against spam and malware, with features to safeguard your organization from messaging policy violations.<br>Use the **Exchange Online Protection setup guide** to set up EOP by selecting which of the three deployment scenarios&mdash;on-premises mailboxes, hybrid (mix of on-premises and cloud) mailboxes, or all cloud mailboxes&mdash;fits your organization. The guide provides information and resources to set up and review your user's licensing, assign permissions in the Microsoft 365 admin center, and configure your organization's anti-malware and spam policies in the Security & Compliance Center.|
|[Microsoft Defender for Office 365 setup guide](https://go.microsoft.com/fwlink/?linkid=2222971)|[Microsoft Defender for Office 365 setup guide](https://go.microsoft.com/fwlink/?linkid=2224784)|The **Microsoft Defender for Office 365 setup guide** safeguards your organization against malicious threats that your environment might come across through email messages, links, and third party collaboration tools. This guide provides you with the resources and information to help you prepare and identify the Defender for Office 365 plan to fit your organization's needs.|
|[Microsoft Defender for Identity setup guide](https://go.microsoft.com/fwlink/?linkid=2222970)|[Microsoft Defender for Identity setup guide](https://go.microsoft.com/fwlink/?linkid=2224783)|The **Microsoft Defender for Identity setup guide** provides security solution set-up guidance to identify, detect, and investigate advanced threats that might compromise user identities. These include detecting suspicious user activities and malicious insider actions directed at your organization. You'll create a Defender for Identity instance, connect to your organization's Active Directory, and then set up sensors, alerts, notifications, and configure your unique portal preferences.|
|[Microsoft Purview Communication Compliance and Insider Risk Management setup guide](https://go.microsoft.com/fwlink/?linkid=2223415)|[Microsoft Purview Communication Compliance and Insider Risk Management setup guide](https://go.microsoft.com/fwlink/?linkid=2224188)|The **Microsoft Purview Communication Compliance and Insider Risk Management setup guide** helps you protect your organization against insider risks that can be challenging to identify and difficult to mitigate. Insider risks occur in a variety of areas and can cause major problems for organizations, ranging from the loss of intellectual property to workplace harassment, and more.<br>The solutions in this guide will help you gain visibility into user activities, actions, and communications with native signals and enrichments from across your organization:<ul><li>With the communication compliance solution, you can identify and act on communication risks for items like workplace violence, insider trading, harassment, code of conduct, and regulatory compliance violations.</li><li>The insider risk management solution helps you identify, investigate, and take action on risks for intellectual property theft, sensitive data leaks, security violations, data spillage, and confidentiality violations.</li></ul>|
|[Microsoft Purview Information Protection setup guide](https://go.microsoft.com/fwlink/?linkid=2222967)|[Microsoft Purview Information Protection setup guide](https://go.microsoft.com/fwlink/?linkid=2224687)|Get an overview of the capabilities you can apply to your information protection strategy so you can be confident your sensitive information is protected. Use a four-stage lifecycle approach in which you discover, classify, protect, and monitor sensitive information. The **Microsoft Purview Information Protection setup guide** provides guidance for completing each of these stages.|
|[Microsoft Purview Data Lifecycle Management setup guide](https://go.microsoft.com/fwlink/?linkid=2223154)|[Microsoft Purview Data Lifecycle Management setup guide](https://go.microsoft.com/fwlink/?linkid=2224686)|The **Microsoft Purview Data Lifecycle Management setup guide** provides you with the information you'll need to set up and manage your organization's governance strategy, to ensure that your data is classified and managed according to the specific lifecycle guidelines you set. With this guide, you'll learn how to create, auto-apply, or publish retention labels, retention label policies, and retention policies that are applied to your organization's content and compliance records. You'll also get information on importing CSV files with a file plan for bulk scenarios or for applying them manually to individual documents.|
|[Microsoft Defender for Cloud Apps setup guide](https://go.microsoft.com/fwlink/?linkid=2222969)|[Microsoft Defender for Cloud Apps setup guide](https://go.microsoft.com/fwlink/?linkid=2224814)|The **Microsoft Defender for Cloud Apps setup guide** provides easy to follow deployment and management guidance to set up your Cloud Discovery solution. With Cloud Discovery, you'll integrate your supported security apps, and then you'll use traffic logs to dynamically discover and analyze the cloud apps that your organization uses. You'll also set up features available through the Defender for Cloud Apps solution, including threat detection policies to identify high-risk use, information protection policies to define access, and real-time session controls to monitor activity. With these features, your environment gets enhanced visibility, control over data movement, and analytics to identify and combat cyberthreats across all your Microsoft and third party cloud services.|
|[Microsoft Purview Auditing solutions in Microsoft 365 guide](https://go.microsoft.com/fwlink/?linkid=2223153)|[Microsoft 365 Auditing solutions in Microsoft 365 guide](https://go.microsoft.com/fwlink/?linkid=2224816)|The **Microsoft Purview Auditing solutions in Microsoft 365 guide** provides an integrated solution to help organizations effectively respond to security events, forensic investigations, and compliance obligations. When you use the auditing solutions in Microsoft 365, you can search the audit log for activities performed in different Microsoft 365 services.|
|[Microsoft Purview eDiscovery solutions setup guide](https://go.microsoft.com/fwlink/?linkid=2223416)|[Microsoft Purview eDiscovery solutions setup guide](https://go.microsoft.com/fwlink/?linkid=2224465)|eDiscovery is the process of identifying and delivering electronic information that can be used as evidence in legal cases. The **Microsoft Purview eDiscovery solutions setup guide** assists in the use of eDiscovery tools in Microsoft Purview that allow you to search for content in Exchange Online, OneDrive for Business, SharePoint Online, Microsoft Teams, Microsoft 365 Groups, and Viva Engage communities.|

## Guides for collaboration

|**Guide - [Setup Portal](https://go.microsoft.com/fwlink/?linkid=2220880)** |**Guide - [Admin Center](https://go.microsoft.com/fwlink/?linkid=2224913)** |**Description** |
|---------|---------|---------|
|[Deploy employee experience with Microsoft Viva](https://go.microsoft.com/fwlink/?linkid=2241022)|[Deploy employee experience with Microsoft Viva](https://go.microsoft.com/fwlink/?linkid=2224787)|Viva is an integrated, employee experience platform (EXP) that brings together communications, knowledge, learning, resources, and insights into the flow of work and fosters a culture where people and teams thrive and are empowered to be their best from anywhere. You can use the steps and guidance in the guides linked here to deploy one or more Viva apps and achieve better employee engagement throughout your organization.|
|[Enable Microsoft Viva Connections](https://go.microsoft.com/fwlink/?linkid=2222984)     |[Enable Microsoft Viva Connections](https://go.microsoft.com/fwlink/?linkid=2224697)         | Encourage meaningful connections while fostering a culture of inclusion and aligning the entire organization around your vision, mission, and strategic priorities.      |
|[Enable Microsoft Viva Engage](https://go.microsoft.com/fwlink/?linkid=2223067)   |  [Enable Microsoft Viva Engage](https://go.microsoft.com/fwlink/?linkid=2224797)       | Bring people together across the organization to connect with leaders, coworkers, and communities; crowdsource answers and ideas; share their work and experience; and find belonging at work.        |
|[Enable Microsoft Viva Goals](https://go.microsoft.com/fwlink/?linkid=2222980)    | [Enable Microsoft Viva Goals](https://go.microsoft.com/fwlink/?linkid=2224796)        | Align teams with your organization's strategic priorities, driving results and a thriving business.        |
|[Enable ‎Microsoft Viva Insights](https://go.microsoft.com/fwlink/?linkid=2240668)    | [Enable ‎Microsoft Viva Insights](https://go.microsoft.com/fwlink/?linkid=2224795)       | Viva Insights‎ helps improve productivity and wellbeing through data-driven, privacy-protected insights and recommendations.        |
|[Enable Microsoft Viva Learning](https://go.microsoft.com/fwlink/?linkid=2223163)     |[Enable Microsoft Viva Learning](https://go.microsoft.com/fwlink/?linkid=2225000)         | Bring enterprise learning into the flow of work by connecting content from your organization, learning management systems, non-‎Microsoft‎ providers, and ‎Microsoft‎.     |
|[Enable Microsoft Viva Topics](https://go.microsoft.com/fwlink/?linkid=2222986)    |[Enable Microsoft Viva Topics](https://go.microsoft.com/fwlink/?linkid=2224826)         |  Use AI to automatically organize content and expertise across your systems and teams into related topics, like projects, products, processes, and customers.      |
|[Enable Microsoft Viva Amplify ](https://go.microsoft.com/fwlink/?linkid=2263448)    |[Enable Microsoft Viva Amplify](https://go.microsoft.com/fwlink/?linkid=2263282)         |  Centralize campaign management, publishing, and reporting to reach and engage employees.      |
|[Enable Microsoft Viva Glint ](https://go.microsoft.com/fwlink/?linkid=2264113)    |[Enable Microsoft Viva Glint](https://go.microsoft.com/fwlink/?linkid=2263279)         |  Improve engagement and performance with recommended actions and data-driven insights across employee lifecycle and organization-wide surveys.      |
|[Enable Microsoft Viva Pulse](https://go.microsoft.com/fwlink/?linkid=2263280)    |[Enable Microsoft Viva Pulse](https://go.microsoft.com/fwlink/?linkid=2263281)         |  Empower managers to seek out and act on confidential feedback using smart templates, research-backed questions and analytics.      |
|[Microsoft 365 Apps setup guide](https://go.microsoft.com/fwlink/?linkid=2234169)|[Microsoft 365 Apps setup guide](https://go.microsoft.com/fwlink/?linkid=2233871)|The **Microsoft 365 Apps setup guide** provides comprehensive guidance for setting up and deploying the latest versions of Office products like Word, Excel, PowerPoint, and OneNote on your users' devices. You'll be walked through the activation process for your Microsoft 365 product key, as well as various deployment methods including easy self-install options and enterprise deployments with management tools. Additionally, the guide offers instructions on assessing your environment, determining your specific deployment requirements, and implementing the necessary support tools to ensure a successful installation.|
||[Mobile apps setup guide](https://go.microsoft.com/fwlink/?linkid=2224813)|The **Mobile apps setup guide** provides instructions for the download and installation of Office apps on your Windows, iOS, and Android mobile devices. This guide provides you with step-by-step information to download and install Microsoft 365 and Office 365 apps on your phone and tablet devices.|
|[Microsoft Teams setup guide]( https://go.microsoft.com/fwlink/?linkid=2222975)|[Microsoft Teams setup guide](https://go.microsoft.com/fwlink/?linkid=2224815)|The **Microsoft Teams setup guide** provides your organization with guidance to set up team workspaces that host real-time conversations through messaging, calls, and audio or video meetings for both team and private communication. Use the tools in this guide to configure Guest access, set who can create teams, and add team members from a .csv file, all without the need to open a PowerShell session. You'll also get best practices for determining your organization's network requirements and ensuring a successful Teams deployment.|
|[Plan and implement your Microsoft Teams Phone deployment](https://go.microsoft.com/fwlink/?linkid=2223356)|[Plan and implement your Microsoft Teams Phone deployment](https://go.microsoft.com/fwlink/?linkid=2224790)|This guide will help you transition from your existing voice solution to Microsoft Teams Phone. You'll be guided through discovery and planning phases, or you can go straight to deployment. You'll be able to configure a calling plan, Operator Connect, Teams Phone Mobile, Direct Routing, caller ID, and other features.|
|[Plan and deploy ‎Teams Premium‎ features](https://go.microsoft.com/fwlink/?linkid=2263689)|[Plan and deploy ‎Teams Premium‎ features](https://go.microsoft.com/fwlink/?linkid=2264353)|Microsoft Teams Premium helps make every meeting more intelligent, engaging, and protected. This guide will help you to plan for and deploy one or more Teams Premium features and take advantage of your Teams Premium licenses.|
|[SharePoint setup guide](https://go.microsoft.com/fwlink/?linkid=2223320)|[SharePoint setup guide](https://go.microsoft.com/fwlink/?linkid=2224196)|The **SharePoint setup guide** helps you set up your SharePoint document storage and content management, create sites, configure external sharing, migrate data and configure advanced settings, and drive user engagement and communication within your organization. You'll follow steps for configuring your content-sharing permission policies, choose your migration sync tools, and enable the security settings for your SharePoint environment.|
|[Surface Hub and Microsoft Teams Rooms setup guide](https://go.microsoft.com/fwlink/?linkid=2222974)|[Surface Hub and Microsoft Teams Rooms setup guide](https://go.microsoft.com/fwlink/?linkid=2224463)|The **Surface Hub and Microsoft Teams Rooms setup guide** will customize your experience based on your environment. If you're hosted in Exchange Online and using Microsoft Teams, the guide will automatically create your device account with the correct settings.|
|[OneDrive setup guide](https://go.microsoft.com/fwlink/?linkid=2223143)|[OneDrive setup guide](https://go.microsoft.com/fwlink/?linkid=2224690)|Use the **OneDrive setup guide** to get started with OneDrive file storage, sharing, collaboration, and syncing capabilities. OneDrive provides a central location where users can sync their Microsoft 365 Apps files, configure external sharing, migrate user data, and configure advanced security and device access settings. The OneDrive setup guide can be deployed using a OneDrive subscription or a standalone OneDrive plan.|
|[Viva Engage deployment advisor](https://go.microsoft.com/fwlink/?linkid=2223165)|[Viva Engage deployment advisor](https://go.microsoft.com/fwlink/?linkid=2224694)|Connect and engage across your organization with Viva Engage. The **Viva Engage deployment advisor** prepares your Viva Engage network by adding domains, defining admins, and combining Viva Engage networks. You'll get guidance to deploy Viva Engage and then customize the look, configure security and compliance, and refine the settings.|

## Advanced guides

|**Guide - [Setup Portal](https://go.microsoft.com/fwlink/?linkid=2220880)** |**Guide - [Admin Center](https://go.microsoft.com/fwlink/?linkid=2224913)** |**Description** |
|---------|---------|---------|
||[In-place upgrade with Configuration Manager guide](https://go.microsoft.com/fwlink/?linkid=2224789)|Use the **In-place upgrade with Configuration Manager guide** when upgrading Windows 7 and Windows 8.1 devices to the latest version of Windows 10. You'll use the script provided to check the prerequisites and automatically configure an in-place upgrade.|
||[Deploy Office to your users guide](https://go.microsoft.com/fwlink/?linkid=2224458)|Deploy Office apps from the cloud with the ability to customize your installation by using the Office Deployment Tool. The **Deploy Office to your users guide** helps you create a customized Office configuration with advanced settings, or you can use a pre-built recommended configuration. Whether your users are conducting a self-install or you're deploying to your users individually or in bulk, this advanced guide provides you with step-by-step instructions to give users an Office installation tailored to your organization.|
||[Deploy Office to remote users guide](https://go.microsoft.com/fwlink/?linkid=2224292)|Now that working remotely is the norm, users need to receive your organization's Office settings when they're not connected to your internal network or when using their own devices.<br>Use the **Deploy Office to remote users guide** to create a customized Office installation and then send users a generated PowerShell script that will seamlessly install Office with your configuration.|
||[Deploy and update Microsoft 365 Apps with Configuration Manager advisor](https://go.microsoft.com/fwlink/?linkid=2224459)|For organizations using Configuration Manager, you can use the **Deploy and update Microsoft 365 Apps with Configuration Manager advisor** to generate a script that will automatically configure your Microsoft 365 Apps deployment using best practices recommended by FastTrack engineers. Use this guide to build your deployment groups, customize your Office apps and features, configure dynamic or lean installations, and then run the script to create the applications, automatic deployment rules, and device collections you need to target your deployment.|
||[Intune Configuration Manager co-management setup guide](https://go.microsoft.com/fwlink/?linkid=2224782)|Use the **Intune Configuration Manager co-management setup guide** to set up existing Configuration Manager client devices and new internet-based devices that your org wants to co-manage with both Microsoft Intune and Configuration Manager. Co-management allows you to manage Windows 10 devices and adds new functionality to your org's devices, while receiving the benefits of both solutions.|
||[SDS Rollover setup guide](https://go.microsoft.com/fwlink/?linkid=2224792)|The **SDS Rollover setup guide** provides the steps to help your organization sync student information data to Microsoft Entra ID and Office 365. This guide streamlines the term lifecycle management process by creating Office 365 Groups for Exchange Online and SharePoint Online, class teams for Microsoft Teams and OneNote, as well as Intune for Education, and rostering and single sign-on integration for third-party apps. You'll perform end-of-year closeout, tenant cleanup and archive, new school year preparation, and new school year launch. Then you can create new profiles using the sync deployment method that suits your organization.|
|[Windows 365 Enterprise checklist](https://go.microsoft.com/fwlink/?linkid=2240015)|[Windows 365 Enterprise deployment checklist](https://go.microsoft.com/fwlink/?linkid=2239740)|The **Windows 365 Enterprise deployment checklist** provides customers with information for provisioning and hosting Cloud PCs.  With the deployment checklist, you can determine if Microsoft Entra join, Azure virtual network, or Microsoft-hosted networks path fits your organization. You can review resources that will assist with the required configuration for deployment features, health checks, updates, and maintenance for image configuration.|