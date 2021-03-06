---
title: "Create events | MicrosoftDocs"
description: "Learn how to create events that can be used to show notifications in Omni-channel Engagement Hub."
keywords: ""
author: kabala123
ms.author: kabala
manager: shujoshi
applies_to: 
ms.date: 2/8/2019
ms.service: dynamics-365-customerservice
ms.topic: article
ms.assetid: 09f35941-3c5b-4076-99a2-66032b0c6d4f
ms.custom: 
---
# Step 3: Create events

Applies to Dynamics 365 for Customer Engagement apps version 9.1.0

[!include[cc-beta-prerelease-disclaimer](../../includes/cc-beta-prerelease-disclaimer.md)]

Create the following events:

 - CreateCustomerSession

 - IncomingRequestRejected

 - TimedOut

 - Omni-channel Context Fetch

Follow these steps to create the events.

1. Sign in to Microsoft Dynamics 365 for Customer Engagement instance.

2. Go to **Settings** > **Unified Service Desk**.

3. Select **Events** and select **+ New**.

4. In the new event page, specify the following details.

 | **Field**          | **Value**                       |
 |--------------------|---------------------------------|
 | Name               | CreateCustomerSession           |
 | Hosted Application | Omni-channel Popup Notification |

 > [!div class=mx-imgBorder]
 > ![create customer session event](../media/oc-usd-crm-create-customer-session-event.png "Create customer session action call")

5. Save the event.

 Repeat the steps from 3 - 5 through create **IncomingRequestRejected**, **TimedOut**, and **Omni-channel Context Fetch** events.

 For the **Omni-channel Context Fetch** event, specify the following details.

 | **Field**          | **Value**                  |
 |--------------------|----------------------------|
 | Name               | Omni-channel Context Fetch |
 | Hosted Application | OmniChannelHostedControl   |

 > [!div class=mx-imgBorder]
 > ![omni-channel context fetch event](../media/oc-usd-crm-context-fetch-event.png "Omni-channel context fetch action call")  

> [!div class="nextstepaction"]
> [Next topic: Step 4: Create an action call to display the notification](alertnotification-step4-create-action-call-display-notification.md)

## See also

- [Configure notification (Screen pop) for agents](configure-notification-screen-pop-agents.md)
- [Step 1: Create forms to define layout and behavior of the notification](alertnotification-step1-create-forms-define-layout-behavior-notification.md)
- [Step 2: Create hosted controls](alertnotification-step2-create-hosted-controls.md)
- [Step 5: Add the action calls to the events](alertnotification-step5-add-action-calls-events.md)
- [Step 6: Add the hosted controls, events, and action calls to the agent and supervisor configurations](alertnotification-step6-add-hosted-controls-events-action-callsagent-supervisor-configurations.md)
- [Configure toast notification in Unified Service Desk](configure-toast-notification-unified-service-desk.md)
