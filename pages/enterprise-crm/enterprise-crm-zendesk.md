---
title: wePhone PHP SDK
---

# How to use Zendesk with wePhone

See how to add a CRM into wePhone [here](enterprise-crm)

To add Zendesk integration to wePhone, you first need to get your API authentication token from Zendesk.

1. Get api authentication token from Zendesk
    Login to your Zendesk with an administrator account then follow the 6 steps in the image bellow in order to get your API authentication token

    ![alt text](/images/zendesk-get-api-token.png)


2. Enter your Zendesk API authentication information to wePhone

    ![alt text](/images/enterprise-crm-zendesk-setup.png)

    - Name: Name your CRM to identify it easily.
    - URL: url to your Zendesk. Often, its have the format https://<enteprise-name>.zendesk.com
    - Default user name: The email of the Zendesk user that will be used to log call to your CRM. If the option "Every agent has a CRM account with the same email" bellow is checked, this default user name is used to log only calls that are not handled by any agent (missed calls)
    - Password/Token: The API authentication token you get from Zendesk (see step 5 above).
    - "Every agent has a CRM account with the same email": Check this option if every wePhone users in your enterprise has one Zendesk account with the same email addresse (as the one used in wePhone). When this option is check, call handled by an agent will be logged with his Zendesk account