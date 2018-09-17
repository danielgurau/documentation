---
title: How to create a new Cloud Storage user in the UKCloud Portal | UKCloud Ltd
description: Describes how to create a new Cloud Storage user in the UKCloud Portal
services: cloud-storage
author: Sue Highmoor

toc_rootlink: How To
toc_sub1:
toc_sub2:
toc_sub3:
toc_sub4:
toc_title: Create a new Cloud Storage user
toc_fullpath: How To/cs-how-create-user.md
toc_mdlink: cs-how-create-user.md
---

# How to create a new Cloud Storage user in the UKCloud Portal

## Overview

Cloud Storage is UKCloud's object storage solution based on Dell EMC Elastic Cloud Storage (ECS). Although you'll mostly interact with Cloud Storage through the API, you can create new Cloud Storage users in the UKCloud Portal.

### Intended audience

To complete the steps in this guide you must have been granted access to the relevant namespace.

## Creating a new Cloud Storage user

To create a new Cloud Storage user:

1. In the Portal navigation panel, expand the **Cloud Storage** option and select **ECS**.

2. On the *Storage* tab, click the **Users** button for the namespace in which you want to create the new user:

    ![Users button](images/cs-portal-btn-users.png)

3. The **Users** tab lists the different user IDs associated with the namespace.

    ![Users page](images/cs-portal-users.png)

4. Click the **Add new user** button.

5. In the *Create ECS User* dialog box, make a note of the **User ID** and **Secret Key** and then click **Close**.

    > [!NOTE]
    > After you close this dialog box, you will not be able to see the secret key again in the UKCloud Portal. If you do not make a note of the secret key or if you forget or lose it, you will need to reset it again. For information about how to do this, see [*How to reset your Cloud Storage secret key*](cs-how-reset-secret-key.md).

    ![Create ECS User dialog box](images/cs-portal-new-user.png)

## Next steps

This guide has shown you how to create a new Cloud Storage user. For more information about how to use the service, see the following articles:

- [*Getting Started Guide for Cloud Storage*](cs-gs.md)
- [*How to view Cloud Storage information in the UKCloud Portal*](cs-how-view-info-portal.md)
- [*How to reset your Cloud Storage secret key*](cs-how-reset-secret-key.md)
- [*Blueprint -- Using storage gateways with Cloud Storage*](https://ukcloud.com/wp-content/uploads/2016/04/UKC-GEN-574-Blueprint-Using-storage-gateways-with-Cloud-Storage-ECS-v1.pdf)
- [*Blueprint -- Using file browsers with Cloud Storage*](https://ukcloud.com/wp-content/uploads/2016/04/UKC-GEN-575-Blueprint-Using-file-browsers-with-Cloud-Storage-ECS-v1.pdf)

## Feedback

If you have any comments on this document or any other aspect of your UKCloud experience, send them to <products@ukcloud.com>.