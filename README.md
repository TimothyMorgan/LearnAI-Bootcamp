<<<<<<< HEAD
## LearnAI
# Bot in a Day
Building Intelligent Apps and Agents with LUIS, Azure Search and Azure Bot Service
=======
# Apps & Agents
>>>>>>> pr/1

![Header](./assets/header.png)

<<<<<<< HEAD
Welcome to Bot in a Day. We will focus on hands-on activities that develop proficiency in Azure Cognitive Services including LUIS and Bing Search. You will also learn to leverage other AI-oriented services such as Azure Search and Azure Bot Services. These labs assume an introductory to intermediate knowledge of these services, and, if this is not the case, then you should spend the time working through the prerequisites.

=======
## Cognitive Services Bootcamp - Build an Intelligent Search Solution for Images using Microsoft AI Platform

## About this course

In this course, you will focus on hands-on activities that develop proficiency in Azure Cognitive Services including Computer Vision, Custom Vision, LUIS, and Bing Search. You will also learn to leverage other AI-oriented services such as Azure Search and Azure Bot Services. These labs assume an introductory to intermediate knowledge of these services, and, if this is not the case, then you should spend the time working through the prerequisites.

> **!!Important note 09/28/2018!!**: The Microsoft Bot Builder SDK V4 went GA at Ignite this week. The bot labs have been updated to SDK V4, but the SDK V3 labs are located in the resources folder for the bot labs (not being maintained). Additionally, we have moved the logging and testing labs to supplementary exercises (not being maintained at the moment), and the bootcamp will focus on the addition of the Bing Search APIs to bots and other applications.  
> If you are an instructor redelivering this course and have questions, please email learnAI@microsoft.com.  
>>>>>>> pr/1

## Goals

Most challenges observed by customers in these realms are in stitching multiple services together. As such, where possible, we have tried to place key concepts in the context of a broader example.

At the end of this workshop, you should be able to:

- Understand how to configure your apps to call Cognitive Services
- Build an application that calls various Cognitive Services APIs (specifically LUIS)
- Understand how to implement Azure Search features to provide a positive search experience inside applications
- Configure an Azure Search service to extend your data to enable full-text, language-aware search
- Build, train, and publish a LUIS model to help your bot communicate effectively
- Build and publish an intelligent bot using Microsoft Bot Framework that leverages LUIS and Azure Search

## Prerequisites

This workshop is meant for an AI Developer on Azure. Since this is only a short workshop, there are certain things you need before you arrive.

Firstly, you should have some previous exposure to Visual Studio. We will be using it for everything we are building in the workshop, so you should be familiar with [how to use it](https://docs.microsoft.com/en-us/visualstudio/ide/visual-studio-ide) to create applications. Additionally, this is not a class where we teach you how to code or develop applications. We assume you have some familiarity with C# (intermediate level - you can learn [here](https://mva.microsoft.com/en-us/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Lvld4EQIC_2706218949) and [here](https://docs.microsoft.com/en-us/dotnet/csharp/quick-starts/)), but you do not know how to implement solutions with Cognitive Services.

Second, you should have some experience developing bots with Microsoft's Bot Framework. We won't spend a lot of time discussing how to design them or how dialogs work. If you are not familiar with the Bot Framework, you should complete [this tutorial](https://docs.microsoft.com/en-us/azure/bot-service/dotnet/bot-builder-dotnet-sdk-quickstart?view=azure-bot-service-4.0) prior to attending the workshop.

Third, you should have experience with the portal and be able to create resources (and spend money) on Azure. We will not be providing Azure passes for this workshop.

Finally, before arriving at the workshop, we expect you to have completed [1_Setup](./lab01.1-computer_vision/1_Setup.md) along with configuring the following for Custom Vision:

1. Training API Key: The training API key allows you to create, manage and train Custom Vision project programmatically

1. You can obtain a key by creating a new project at <https://customvision.ai> and then clicking on the “setting” gear in the top right

## Agenda

Please note: This is a rough agenda, and the schedule is subject to change pending class activities, breaks, and interactions.

- 8-9 (optional): Setup assistance
- 9-10: Introduction and Context for the Course
- 10-11: [Lab 1.5: Developing Intelligent Applications with LUIS][lab-cogsrvc-341]
- 11-12: [Lab 2.1: Developing Intelligent Applications with Azure Search][lab-azsearch-301]
- 12-1: Lunch
- 1-2:30: [Lab 2.2: Building Intelligent Bots][lab-intelbot-301]
- 2:30-4: [Lab 2.3: Enhancing Applications with Bing Search](https://github.com/InsightDI/LearnAI-Bootcamp/blob/master/lab02.3-bing_search/0_README.md)
- 4:30-5: Q&A and Feedback for Bot In A Day
 
## PowerPoint Slides

Download the [Powerpoint slides here](./presentations/). 

## Supplementary materials
Please refer to the main [README](../README.md) that has all of the materials for the two-day bootcamp.

The LearnAI team has provided some extra labs you may be interested in:

- [Lab 2.5: Log Chat Conversations in your Bot](./lab02.5-logging_chat_conversations/0_README.md)
- [Lab 2.6: Testing your Bot](./lab02.6-testing_bots/0_README.md)

## Related courses

Here are some related courses from the LearnAI team:

- [LearnAI: Intelligent Agents: Design and Architecture](https://aka.ms/daaia)
- [LearnAI: Building Enterprise Cognitive Search Solutions](https://aka.ms/kmb)  

## Contact

Contact us: learnAI@microsoft.com and <http://aka.ms/LearnAI-GitHub>

## Certifications

The LearnAI team had intense participation in the creation of the following new Microsoft certifications:

- Azure Data Engineer​
  - DP-200: Implementing an Azure Data Solution ​
  - 80% off discount code thru Mar 12, 2019: DP200BigTrips​
  - DP-201: Designing an Azure Data Solutions​
  - 80% off discount code thru Mar 12, 2019: DP201Walks​

- Azure AI Engineer​
  - AI-100: Designing and Implementing an Azure AI Solution ​
  - 80% off discount code thru Mar 5, 2019: AI100Goals​

- Azure Data Scientist ​
  - DP-100: Designing and Implementing a Data Science Solution on Azure​
  - 80% off discount code thru Mar 7, 2010: DP100KLS​

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit <https://cla.microsoft.com.>

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
