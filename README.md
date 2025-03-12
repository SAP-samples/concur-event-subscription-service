# SAP-samples/repository-template
This default template for SAP Samples repositories includes files for README, LICENSE, and REUSE.toml. All repositories on github.com/SAP-samples will be created based on this template.

# Containing Files

1. The LICENSE file:
In most cases, the license for SAP sample projects is `Apache 2.0`.

2. The REUSE.toml file: 
The [Reuse Tool](https://reuse.software/) must be used for your samples project. You can find the REUSE.toml in the project initial. Please replace the parts inside the single angle quotation marks < > by the specific information for your repository.

3. The README.md file (this file):
Please edit this file as it is the primary description file for your project. You can find some placeholder titles for sections below.

# SAP Concur Client Web Services - Event Subscription Service

<!--- Register repository https://api.reuse.software/register, then add REUSE badge:
[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/REPO-NAME)](https://api.reuse.software/info/github.com/SAP-samples/REPO-NAME)
-->

## Description
This repository provides an example of how to register an external endpoint to for the Concur Event Subscription Service, in order to receive events for a specific topic. It includes the following steps:
1.	Obtain application-level Bearer token 
2.	Get available event topics
3.	Check existing subscriptions
4.	Create/update a subscription
5.	Verify subscription
6.	Delete subscription
7.	Activate subscription

## Requirements
In order to use this repository you will need
1) The Web Service Administration role within SAP Concur (to be able to create SAP Concur applications)
2) Postman (to be able to use the files included in this repository)
3) Have downloaded / installed the Authentication Postman collection [found here](https://github.com/SAP-samples/concur-web-services-authentication).

## Download and Installation

## Known Issues
No knowns issues.

## How to obtain support
This project is provided "as-is", with no expected changes or support.
The complete documentation for the APIs used can be found [here](https://developer.concur.com/api-reference/ess/v4.event-subscription.html).
 
For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## Contributing
This repository is provided "as-is".

## License
Copyright (c) 2024 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.
