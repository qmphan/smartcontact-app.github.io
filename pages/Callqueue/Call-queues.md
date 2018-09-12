---
title: Call Queue Management
---

## What is call queue?

Call queue is to incoming calls manage from customers or to call away from the agent. A call queue consists agents of a group call handling a customer call in the queue.

This system allows forwarding some of the calls waiting for the next agent in the queue. Calls are redirected to the first agents available to reduce the customer's waiting.

The call queue interface will be displayed as follows:

#### Send SMS with wePhone SDK: 
Click here to see example of how to use wePhone PHP SDK to send SMS: [wePhone PHP SDK](/pages/wephone-php-sdk)

## Get the list of send and received SMS

Login to your wePhone account. Click on "SMS" menu on the left to have access to the list of SMS sent and received.

![SMS Sent](/images/sms-sent.png)


## Get notification by web callback when an SMS is delivered

You can define a web URL that get called everytime an SMS is delivered (or fails permanently to be delivered).
![SMS Sent](/images/sms-api-config.png)

Fill the text box "SMS Callback URL" with your own URL. That URL will receive a POST request with a JSON payload that give you information about the SMS delivery status. 

Example of POST payload:

```JSON
{
    "sms_id": "AD834FDSDDRF98DYDF80D0DF",
    "success": true,
    "delivery_time": "2018-02-01 16:06:57+01:00"
}
```