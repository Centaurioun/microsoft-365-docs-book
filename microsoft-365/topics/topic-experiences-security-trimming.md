---
ms.date: 01/01/2024
title: Security trimming in Topics
ms.author: daisyfeller
author: daisyfell
manager: elizapo
ms.reviewer: daisyfeller
audience: admin
ms.topic: article
ms.collection:
  - m365initiative-viva-topics
  - Tier1
ms.service: viva-topics 
search.appverid:
    - MET150  
ms.localizationpriority:  medium
description: Learn how security is used when viewing topics in Topics.
---

# Security trimming in Topics

Topics users can't view information in topics that their existing Office 365 permissions prevent them from seeing. Everything a user sees on a topic page (for example, SharePoint sites, documents, files) will be information they're already allowed to see. Topics doesn't make changes to any existing permissions.

## Why two users might have different views of the same topic

When a topic is created through AI or manual curation, it can contain a description of the topic, alternative names, people associated with the topic, and sites, pages, and files related to the topic. When this information is viewed on a topic page, it's possible that two users who are viewing the same topic might not see the same information.
  
For example, when User 1 views the Neptune topic page, they might see this view of the topic page.

![Neptune topic for user 1.](../media/knowledge-management/user2-topic-view.png)

However, when User 2 looks at the same Neptune topic page, their view differs from User 1.  User 2 is able to see the *DG-2000 Product Overview* file in the **Pinned files and pages** section of the topic page, which doesn't appear for User 1.

![Neptune topic for user 2.](../media/knowledge-management/user1-topic-view.png)

The difference in what users can see on the same topic is because users might not have the Office 365 permissions to view a related site or file. Topics respects the permissions that are set on items in a topic, and can't change access to them. In our example, User 1 isn't able to view the *DG-2000 Product Overview* file in their topic page for Neptune because User 1 doesn't have Office 365 permissions to view the file.

If a user isn't able to see enough information in a topic for it to be useful, the topic won't be available to the user. When this happens, the user won't see the highlighted topic. A different user who has permissions to more information in the topic for it to be useful, will be able to see the topic.

## Topic permissions for knowledge managers and topic contributors

Users that are assigned permissions to manage topics - knowledge managers - will only be able to view information they have permissions to see within topics.

Similarly, users who have create and edit topic permissions - topic contributors - will only be able to view information they have permissions to see within topics.

## AI versus manually curated topic information

Topics can contain information generated by AI and information added or edited by topic contributors or knowledge managers.

- Information in a topic that was added by AI is only visible to people who have access to the source content.
- Topic description and people information that has been manually added or edited by a topic contributor or knowledge manager is visible to everyone who can see the topic.
- Files, pages, and sites are only visible to users who have permissions to the source content, whether manually added or added by AI.

The following table describes what users - topic viewers, contributors, and knowledge managers - can see in a given topic based on their permissions.

|Topic item|What users can see|
|:---------|:------------------|
|Topic name|Users can see the topic name of topics in the topic center. Some topics might not be visible if users don't have permissions to the source content or have a low relevancy to the user.|
|Topic description|AI-generated descriptions are visible only to users who have permissions to the source content. Manually entered or edited descriptions are visible to all users.|
|People|Pinned people are visible to all users. Suggested people are only visible to users who have permissions to the source content.|
|Files|Files are only visible to users who have permissions to the source content.|
|Pages|Pages are only visible to users who have permissions to the source content.|
|Sites|Sites are only visible to users who have permissions to the source content.|