---
title: API
layout: rancher-api-v1-default-v1.1
version: v1.1
lang: en
apiVersion: v1
redirect_from:
  - /rancher/v1.1/zh/api/v1/api-resources/externalServiceEvent/
---

## externalServiceEvent



### Resource Fields


#### Read Only Fields

Field | Type   | Notes
---|---|---
accountId | [account]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/{{page.apiVersion}}/api-resources/account/)  | The unique identifier for the associated account
created | date  | The date of when the externalServiceEvent was created.
environment | json  | 
eventType | string  | 
externalId | string  | 
id | int  | The unique identifier for the externalServiceEvent
kind | string  | 
reportedAccountId | [account]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/{{page.apiVersion}}/api-resources/account/)  | 
service | json  | 
state | enum  | The current state of the externalServiceEvent. The options are `created`, `creating`, `removed`, `removing`, `requested`.
transitioning | enum  | Whether or not the externalServiceEvent is in a transitioning state
transitioningMessage | string  | The message to show while in a transitioning state
transitioningProgress | int  | The percentage remaining in the transitioning process of the externalServiceEvent
uuid | string  | The universally unique identifier for the externalServiceEvent. This will always be unique across Rancher installations.


<br>
