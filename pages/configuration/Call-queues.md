---
title: Call Queue Management
---

## Create Call queue

Call queue is to incoming calls manage from customers or to call away from the agent. A call queue consists of agents of a group call handling a customer call in the queue.

This system allows forwarding some of the calls waiting for the next agent in the queue. Calls are redirected to the first agents available to reduce the customer's waiting.

The call queue interface will be displayed as follows:
![Call queue](/images/callqueue-list.png)

Users create a new queue, select "Create" to display the window:
![Call queue](/images/callqueue-create.png)

## General interface

![Call queue](/images/callqueue-general.png)

Input information as follows:
- Logo: The logo of the queue, easy to identify for the user.
- Name: Input the name of the queue.
- Group: Select a group of attendants to join the queue.
- Work calendar: Select the opening hours of the queue so customers can call. In addition to these hours, customer calls will be transferred to voicemail. Agents can customize their working hours by clicking the "Create New" button. A window "Create a new hour" opens and prompts the operator to fill in the necessary information for the new opening hours.
- Limit in queue waiting time: Set the queue maximum timeout
- Record all call in this queue: Select to activate or deactivate call recording, which allows callers to hear back calls from customers in a dispute or customer complaint.
- Caller can leave message in case of unavailability:The caller can leave a message in the absence of an answering agent.
- Send notification by mail when a voicemail is received: User set up email addresses to receive voice messages.
- Priority: Very high, high, medium, low, very low for queue priority. High priority is processed first

### Queue sounds interface

![Call queue](/images/callqueue-sounds.png)

Input information as follows:
- When a call arrive: There are three options: "Answer the call and play sounds", "Do not answer until an agent in found (otherwise hang up in silent)", or "Do not answer until an agent in found (otherwise tell the caller why before hanging up)".
- Languages: Allows multi-language support for messages in the queue. Select the language the user wants to activate the queue.
- Welcome message: Select the greeting message the customer hear when making a call.
- Waiting music: Select the music waiting for customers while waiting to connect to the agent.
- Music on hold: Select the music waiting for customers while waiting in between calls.
- Out of hours message: Select the out-of-queue notification message.
- No agent available message: Select the message to the customer when the agent is busy.

### At the end of a call interface

![Call queue](/images/callqueue-end-call.png)

Actions are executed after the end of the call:
- Send client call to this IVR: The user selects the available menus to perform after the end of the call.
- Pause agent after each call: The caller will have a pause to perform the specialization for the call.
- Agent becomes available after: After each call, the user sets the mode after how long the operator can receive the other call.

### Call classification interface

![Call queue](/images/callqueue-classification.png)

It is an assessment to classify customers, for use in statistics later:
- Active qualification: After each call will show evaluation featurewill show evaluation feature.
- Inbound call: Classify incoming calls.
- Outgoing call: Sort outcalls.
- Agent must qualify call before taking next call

### Backoffice action interface

![Call queue](/images/callqueue-backoffice.png)

This option allows the display of the interface each time an incoming call is based on the incoming phone number. There are 3 options:
- Do nothing: This option will not display anything on the back-office page.
- Open the following url: The user enters the URL text
  
### Transfer numbers interface

![Call queue](/images/callqueue-transfer-numbers.png)

These numbers are intended for call forwarding. These numbers will be an option when the operator wants to take a call.

### History interface

![Call queue](/images/callqueue-history.png)

Record the change history in the queue.

## Add users to the queue

Users can view the list of available phones in the queue. Only agents on this list will receive calls to or from this queue.
![Call queue](/images/callqueue-agents.png)

## Route some DIDs to the Queue

This DID dedicated routing number is used for incoming and outgoing calls. Customers will call the enterprise through this DID. Agents can select this DID to call the customer.
![Call queue](/images/callqueue-numbers.png)

