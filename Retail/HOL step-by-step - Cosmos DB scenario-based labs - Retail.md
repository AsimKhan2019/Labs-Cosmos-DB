<div class="MCWHeader1">
Cosmos DB scenario-based labs - Retail
</div>

<div class="MCWHeader2">
Hands-on lab step-by-step
</div>

<div class="MCWHeader3">
September 2019
</div>


Information in this document, including URL and other Internet Web site references, is subject to change without notice. Unless otherwise noted, the example companies, organizations, products, domain names, e-mail addresses, logos, people, places, and events depicted herein are fictitious, and no association with any real company, organization, product, domain name, e-mail address, logo, person, place or event is intended or should be inferred. Complying with all applicable copyright laws is the responsibility of the user. Without limiting the rights under copyright, no part of this document may be reproduced, stored in or introduced into a retrieval system, or transmitted in any form or by any means (electronic, mechanical, photocopying, recording, or otherwise), or for any purpose, without the express written permission of Microsoft Corporation.

Microsoft may have patents, patent applications, trademarks, copyrights, or other intellectual property rights covering subject matter in this document. Except as expressly provided in any written license agreement from Microsoft, the furnishing of this document does not give you any license to these patents, trademarks, copyrights, or other intellectual property.

The names of manufacturers, products, or URLs are provided for informational purposes only and Microsoft makes no representations and warranties, either expressed, implied, or statutory, regarding these manufacturers or the use of the products with any Microsoft technologies. The inclusion of a manufacturer or product does not imply endorsement of Microsoft of the manufacturer or product. Links may be provided to third party sites. Such sites are not under the control of Microsoft and Microsoft is not responsible for the contents of any linked site or any link contained in a linked site, or any changes or updates to such sites. Microsoft is not responsible for webcasting or any other form of transmission received from any linked site. Microsoft is providing these links to you only as a convenience, and the inclusion of any link does not imply endorsement of Microsoft of the site or the products contained therein.

© 2019 Microsoft Corporation. All rights reserved.

Microsoft and the trademarks listed at <https://www.microsoft.com/en-us/legal/intellectualproperty/Trademarks/Usage/General.aspx> are trademarks of the Microsoft group of companies. All other trademarks are property of their respective owners.

**Contents** 

<!-- TOC -->

- [Cosmos DB scenario-based labs - IoT hands-on lab step-by-step](#cosmos-db-scenario-based-labs---iot-hands-on-lab-step-by-step)
  - [Abstract and learning objectives](#abstract-and-learning-objectives)
  - [Overview](#overview)
  - [Solution architecture (High-level)](#solution-architecture-high-level)
  - [Requirements](#requirements)
  - [Before the hands-on lab](#before-the-hands-on-lab)
  - [Exercise 1: Deployment and Setup](#exercise-1-deployment-and-setup)
    - [Task 1: Blah](#task-1-blah)
  - [Exercise 2: Creating and deploying rule calculations](#exercise-2-creating-and-deploying-rule-calculations)
    - [Task 1: Blah](#task-1-blah-1)
  - [Exercise 3: Simulate data and events](#exercise-3-simulate-data-and-events)
    - [Task 1: Blah](#task-1-blah-2)
  - [Exercise 4: Reporting with Stream Analytics and Power BI](#exercise-4-reporting-with-stream-analytics-and-power-bi)
    - [Task 1: Blah](#task-1-blah-3)
  - [Exercise 5: Email alerts using Logic Apps](#exercise-5-email-alerts-using-logic-apps)
    - [Task 1: Blah](#task-1-blah-4)
  - [After the hands-on lab](#after-the-hands-on-lab)
    - [Task 1: Delete resource group](#task-1-delete-resource-group)

<!-- /TOC -->

# Cosmos DB scenario-based labs - IoT hands-on lab step-by-step

## Abstract and learning objectives

In this hands-on-lab, TODO

At the end of this lab you will TODO

## Overview

Contoso Movies, Ltd. has TODO

## Solution architecture (High-level)

![The proposed solution utilizing Azure Security Center for IoT and its agents to monitor and secure the IoT Devcies.  Log data is forwarded to Log Analytics where alerts and logic apps will execute to start investigation and remediation.](../Media/solution-diagram-1.png "Solution Architecture")

## Requirements

1. Microsoft Azure subscription must be pay-as-you-go or MSDN.

    - Trial subscriptions will not work.
    
## Before the hands-on lab

Refer to the Before the hands-on lab setup guide manual before continuing to the lab exercises.

## Exercise 1: Deployment and Setup

Duration: 30 minutes

Synopsis:  In this exercise you will TODO

### Task 1: Deploy the Azure Resources

1.  Run the Deploy.ps1 script to deploy the ARM template and do some time saving  setup and configuration.

## Exercise 2: Complete and deploy Web App and Function Apps

Duration: 30 minutes

Synopsis: We have pregenerated a set of events that include **buy** events.  Based on this information, a **Top Items** recommendation will be made to users that are new to the site.  You will implement this code in the web application and function applications, then deploy the applications to test the functionality.

### Task 1: Implement the Top Items recommendation

1.  Blah

### Task 2: Add the Function App code

1.  Blah

### Task 3: Deploy the applications

1.  Blah

## Exercise 3: Perform and deploy association rules calculation for offline algorithms

Duration: 30 minutes

Synopsis: Based on the pre-calculated events in the Cosmos DB for our pre-defined personality types (Comedy fan, Drama fan, etc), you will implement and deploy an algorithm that will generate these associations and put them in Cosmos DB for offline processing by the web and function applications.

### Task 1: Blah

1.  Blah

### Task 2: Blah

1.  Blah

## Exercise 4: Perform and deploy collaborative filtering rules calculation

Duration: 30 minutes

In this exercise you will TODO

### Task 1: Blah

1.  Blah

## Exercise 5: Explore Cosmos DB data

Duration: 30 minutes

In this exercise you will TODO

### Task 1: Explore Cosmos DB Collections

1.  Open your Cosmos DB resource in the Azure Portal

2.  Click **

## Exercise 6: Reporting with Stream Analytics and Power BI

Duration: 30 minutes

In this exercise you will TODO

### Task 1: Setup Stream Analytics 

1.  Blah

### Task 1: Setup Power BI Dashabord 

1.  Blah

## Exercise 7: Email alerts using Logic Apps

Duration: 30 minutes

In this exercise you will TODO

### Task 1: Blah

1.  Blah

## After the hands-on lab 

Duration: 10 minutes

In this exercise, attendees will deprovision any Azure resources that were created in support of the lab.

### Task 1: Delete resource group

1.  Using the Azure portal, navigate to the Resource group you used throughout this hands-on lab by selecting **Resource groups** in the menu.

2.  Search for the name of your research group, and select it from the list.

3.  Select **Delete** in the command bar, and confirm the deletion by re-typing the Resource group name and selecting **Delete**.

You should follow all steps provided *after* attending the Hands-on lab.

