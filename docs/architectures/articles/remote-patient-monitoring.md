---
title: Remote Patient Monitoring Solutions 
description: Provide a high level of preventative medical care with remote patient monitoring from Azure. Analyze large amounts of medical data in a secure environment.
author: adamboeglin
ms.date: 10/18/2018
---
# Remote Patient Monitoring Solutions 
Predict and prevent future incidents by combining IoT and intelligence to optimize treatments, using Azure to remotely monitor patients and analyze the massive amounts of data generated by medical devices.

## Architecture
<img src="media/remote-patient-monitoring.svg" alt='architecture diagram' />

## Data Flow
1. Securely ingest medical sensor and device data using Azure IoT Hub.
1. Securely store sensor and device data in Cosmos DB.
1. Analyze sensor and device data using a pre-trained Cognitive Services API or a custom developed Machine Learning model.
1. Store Artificial Intelligence (AI) and Machine Learning results in Cosmos DB.
1. Interact AI and Machine Learning results using PowerBI, while preserving Role-Based Access Control (RBAC).
1. Integrate data insights with backend systems and processes using Logic Apps.

## Components
* [IoT Hub](href="http://azure.microsoft.com/services/iot-hub/): Connect, monitor and manage billions of IoT assets
* [Security Center](href="http://azure.microsoft.com/services/security-center/): Unify security management and enable advanced threat protection across hybrid cloud workloads
* [Cognitive Services](href="http://azure.microsoft.com/services/cognitive-services/): Get started with quickstarts, samples, and tutorials
* [Key Vault](href="http://azure.microsoft.com/services/key-vault/): Safeguard and maintain control of keys and other secrets
* [Logic Apps](href="http://azure.microsoft.com/services/logic-apps/): Automate the access and use of data across clouds without writing code
* [Power BI Embedded](href="http://azure.microsoft.com/services/power-bi-embedded/): Embed fully interactive, stunning data visualizations in your applications
* [Azure Cosmos DB](href="http://azure.microsoft.com/services/cosmos-db/): Globally distributed, multi-model database for any scale
* Application Insights
* [Machine Learning Studio](href="http://azure.microsoft.com/services/machine-learning-studio/): Easily build, deploy, and manage predictive analytics solutions
* [Azure Monitor](href="http://azure.microsoft.com/services/monitor/): Highly granular and real-time monitoring data for any Azure resource

## Next Steps
* [IoT Hub Documentation](https://docs.microsoft.com/azure/iot-hub)
* [Azure Security Center Documentation](https://docs.microsoft.com/azure/security-center)
* [Get Started with Azure](https://docs.microsoft.com/azure/#pivot=get-started)
* [What is Azure Key Vault?](https://docs.microsoft.com/azure/key-vault/key-vault-overview)
* [Azure Logic Apps Documentation](https://docs.microsoft.com/azure/logic-apps)
* [Power BI Embedded Documentation](https://docs.microsoft.com/azure/power-bi-embedded)
* [Azure Cosmos DB Documentation](https://docs.microsoft.com/azure/cosmos-db)
* [Application Insights Documentation](https://docs.microsoft.com/azure/application-insights)
* [Azure Machine Learning Documentation](https://docs.microsoft.com/azure/machine-learning)
* [Azure Monitor Documentation](https://docs.microsoft.com/azure/monitoring-and-diagnostics)