---
title: User Management
---

## User Management

In wePhone, users are all employees of your company to whom an account is assigned. Users may have the status of administrator, supervisor or advisor depending on their function.

## Format of the csv file

To add more users to the list, you need a CSV file that contains all user lists. CSV stands for Comma Separated Values - a delimited text file that uses a comma to separate values. You can use Microsoft Excel to generate a CSV file from an excel sheet. The first line of the file must contain the names of each column and the following line contain contact data. Here is an example of the csv file:

```
email, first_name, last_name, password, user_type, record_call, alias, skills
trystan_thomps@gmail.com, Vonnie, M Hill, 123456789, admin, 0, Hill M, skill1 name:1;skill2 name:2
camille.skil@gmail.com, John, E Truitt, 123456789, agent, 1, , skill1 name:1;skill2 name:2
brandy_bergstr@hotmail.com, Pedro, M Ramirez, 123456789, user, 0, , ,
```
## Create user
To create a new user, click on "Users" in the "Main Menu" block.
Then click on the "Create" button at the top left of the "Work Window".
A "Create a new user" window appears. Fill in the required fields to create your new user.
![User](/images/user-create.png)

## Edit user
Once your new user is created, you can find it and set the user information in "User" in the "Main Menu" block.
To configure the user's settings, click the user in question. The right side of the "Work Window" displays the user information.
![User](/images/user-edit.png)

## Telephony settings (VoIP)
By default, the Voice over IP feature is disabled. Click on the button "Enable sip phone connection" to activate it.
Once the function is activated, a window appears:

![User](/images/user-voip.png)

- wePhone extension number: Used to install on the Softphone and make outgoing calls to the WePhone system.
- Outbound display number: Allows you to choose the number assigned to this user.
- Allow destination: Allows you to set the user profile according to the restrictions you wish to impose. 
        - Default profile
        - National fix & mobile
        - National and special
        - International
- Connection information: This is the information allowing the user to connect his SIP phone to the wePhone interface.

## Upload information user to the new user list
From user edit page, click on "Import user from file csv". The upload csv dialog will shown as bellow.

![User](/images/user-file-csv.png)

(You can click on the link "Download an example" to get an example of the csv file, as describe above).

Click on the rectangle or drop a file into it to open. Then click on Next.

## Choose agents who will handle the call queues
On the tab "Call center", the agent handles calls in the queue. The user can be added to one or more queues.

![User](/images/user-queue.png)

Click on the "Add queue for agent" button to add agent to the call queue.

The user can also select a working calendar to process calls in the call center.