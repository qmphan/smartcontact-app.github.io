---
title: Send and Receive SMS with wePhone
---

## SMS API

You can use wePhone to send SMS to your client programmatically. All the SMS sent will be logged and can be seen from your wePhone account (see below).

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