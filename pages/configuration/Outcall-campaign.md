---
title: Outbound Campaign management
---

## Introduction

Using Outbound campaign, you can upload a csv file containing the contacts to be called. The system will take care of calling contacts in the file when one or some agents become available. You can also set the period of time to make outbound call (i.e beenween 10am and 15pm) and the list of agents who will handle these calls.

## Format of the csv file

In order to make an outbound call, you need a csv file containing all the contact to be called. CSV stands for Comma Separated Values -  a delimited text file that uses a comma to separate values. You can use Microsoft Excel to generate a CSV file from an excel sheet. The first line of the file must contain the names of each column and the following line contain contact data. Here is an example of the csv file

```
firstname, lastname, enterprise, phone, address
Big, Ben, The Tower, 0101010101, Westminster, London SW1A 0AA, UK
Jean, Pierre, The Startup, 0102020202, Avenue Des Champs-Elysées, Paris 08, FR
```

## Create an outbound campaign

From campaign management page, click on the button "Create" from the campaign management page.

![Group](/images/campaign-create.png)

Fill all the fields in this General tab with the required information.

### Schedule Start Date and Schedule End Date

The day the campaign should begin and the day it should stop. If these values are not defined, the campaign will run as long as there are contacts to be called. You can check the checkbox "Set start time and end time" if you only want the campaign to be active during some period of the day.

### Campaign Type:

Campaign type can take 2 values:
1. Call agent first: The system will try to call agent first. Only when agent has anwsered, the system will call the client. This mode should be preferred if you want to make sure the client will have an agent available when he/she picks up the call.
2. Call client first: In this mode, the system will call the client first, then play an IVR while searching for an available agent. Do not use this mode unless you are sure that the called contacts would accept to wait to talk to an agent.

## Upload contact to be called to the newly created campaign

From campaign edit page, click on the tab "Contact to be called", then click on "Import from csv". The upload csv dialog will shown as bellow.

![Group](/images/campaign-import-csv.png)

(You can click on the link "Download an example" to get an example of the csv file, as describe above).

Click on the rectangle or drop a file into it to open. Then click on Next.

## Map the fields from the csv file to the campaign

![Group](/images/campaign-detail-csv2.png)

From the left hand of the dialog, use the dropdown selector to match a field from the csv file with a campaign field. The right hand side of the dialog show the list of fields not yet mapped. The only required field to be mapped is phone number. The other fields are optional.

## Choose agents who will handle the campaign

In order for the campaign to run, you need to add agents to it. You can do so from the "Agent" tab of the campaign editing page.

![Group](/images/campaign_agents.png)

Click on the Add button to add agent to the campaign.

## Start the campaign

One the contacts are uploaded and agent are added, verify that the information about the start date and end date of the campaign are correct, then you can run the campaign.
To run the campaign, click on the button "Run now" on the top left corner of the campaign editing page.

One the campaign is running, you can follow it by going to the live page (Dashboard => Active Outbound Campaign)

![Group](/images/campaign-active-outbound.png)

