---
layout: post
title: CDA Weekly Content Wrapup (Oct 21 2019)
subtitle: 
tags: [JavaScript, TypeScript, Node.js, CI/CD, Spring Boot, Azure Machine Learning, Python, Azure Container Instances, Azure Notebooks, Azure DevOps Services, Azure Pipelines, VS Code, Azure Cognitive Services Text API, Azure Cognitive Services, Azure Storage, Kafka, Azure Service Bus, Azure Logic Apps, APIs/API Development, Azure Functions, Azure Event Hubs, Go, GoLang, DevOps, Advice, Cloud Computing, AI/ML, Kubernetes, Azure App Service, UI/UX, UI Design, Azure Databricks, IoT, Azure IoT Hub, Azure IoT Central, HTML, Azure ARM Templates, Azure Automation, azure, Windows Server, Azure, PowerShell, Azure PowerShell, Azure Cloud Shell, Windows Admin Center, Azure Virtual Machines, Azure SignalR Service, Java, Azure Machine Learning Service, ASP.NET Core]
---

## [Real Talk JavaScript - Podcast Episode 51: Building Software without Frameworks - Niall Crosby](https://realtalkjavascript.simplecast.fm/99e4af34)

**by: John Papa**

In this episode, John, Ward and Dan talk with Niall Crosby about why he built Ag Grid, how he dealt with various issues when releasing open source software, and tips for anyone else thinking of writing their own frameworks or projects.

The podcast site also shares links to relevant people to follow on these topics, time-jumps to various parts of the discussion and provides relevant technology resources including OSS, AgGrid and JSPerf

Tags: JavaScript, TypeScript, Node.js

[Read More](https://realtalkjavascript.simplecast.fm/99e4af34)



## [Real Talk JavaScript - Podcast Episode 52: Web Performance - Katie Hempenius](https://realtalkjavascript.simplecast.fm/fbdc36f9)

**by: John Papa**

In this episode, John and Ward talk with Katie Hempenius about web performance, lazy loading, code splitting, tti, and the difference between latency and bandwidth.

The podcast site also shares links to relevant people to follow on these topics, time-jumps to various parts of the discussion and provides relevant technology resources including Lighthouse tools, Web Performance, nginx compression and more.

Tags: JavaScript, TypeScript, Node.js

[Read More](https://realtalkjavascript.simplecast.fm/fbdc36f9)



## [Azure Spring Cloud training](https://github.com/microsoft/azure-spring-cloud-training)

**by: Julien Dubois**

Under this repository, find the full training for Azure Spring Cloud (12 chapters).

Tags: CI/CD, Spring Boot

[Read More](https://github.com/microsoft/azure-spring-cloud-training)

Related Links:
* [Install the Azure CLI : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli/?WT.mc_id=azurespringcloud-github-judubois)
* [Azure Cosmos DB : Microsoft Docs](https://docs.microsoft.com/en-us/azure/cosmos-db/?WT.mc_id=azurespringcloud-github-judubois)
* [Azure Database for MySQL documentation : Microsoft Docs](https://docs.microsoft.com/en-us/azure/mysql/?WT.mc_id=azurespringcloud-github-judubois)
* [Microsoft Azure](https://portal.azure.com/?WT.mc_id=azurespringcloud-github-judubois&microsoft_azure_marketplace_ItemHideKey=AppPlatformExtension#blade/Microsoft_Azure_Marketplace/MarketplaceOffersBlade/selectedMenuItemId/home/searchQuery/spring)
* [Microsoft Azure](https://portal.azure.com/?WT.mc_id=azurespringcloud-github-judubois)
* [Introduction to Azure Storage - Cloud storage on Azure : Microsoft Docs](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction/?WT.mc_id=azurespringcloud-github-judubois)
* [Azure Event Hubs documentation : Microsoft Docs](https://docs.microsoft.com/en-us/azure/event-hubs/?WT.mc_id=azurespringcloud-github-judubois)
* [Get started with Azure Monitor Log Analytics : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/get-started-portal/?WT.mc_id=azurespringcloud-github-judubois)
* [Azure Storage Explorer – cloud storage management : Microsoft Azure](https://azure.microsoft.com/en-us/features/storage-explorer/?WT.mc_id=azurespringcloud-github-judubois)


## [Automated Machine Learning:  Classification with Deployment using a Bank Marketing Dataset](https://github.com/Azure/MachineLearningNotebooks/blob/master/how-to-use-azureml/automated-machine-learning/classification-bank-marketing/auto-ml-classification-bank-marketing.ipynb)

**by: Francesca Lazzeri**

In this example we use the UCI Bank Marketing dataset to showcase how you can use AutoML for a classification problem and deploy it to an Azure Container Instance (ACI). The classification goal is to predict if the client will subscribe to a term deposit with the bank.
If you are using an Azure Machine Learning Notebook VM, you are all set. Otherwise, go through the configuration notebook first if you haven't already to establish your connection to the AzureML Workspace.
In this notebook you will learn how to:
Create an experiment using an existing workspace.
Configure AutoML using AutoMLConfig.
Train the model using local compute.
Explore the results.
Register the model.
Create a container image.
Create an Azure Container Instance (ACI) service.
Test the ACI service.

Tags: Azure Machine Learning, Python, Azure Container Instances, Azure Notebooks

[Read More](https://github.com/Azure/MachineLearningNotebooks/blob/master/how-to-use-azureml/automated-machine-learning/classification-bank-marketing/auto-ml-classification-bank-marketing.ipynb)

Related Links:
* [Create automated ML experiments - Azure Machine Learning : Microsoft Docs](https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-configure-auto-train#primary-metric)


## [Azure DevOps Multi-Stage Pipelines Approval Strategies  애저 데브옵스 다단계 파이프라인 승인 전략](https://devkimchi.com/2019/10/02/azure-devops-multi-stage-pipelines-approval-strategies/)

**by: Justin Yoo**

There are two ways using Azure DevOps Release Pipelines. We use UI so that we compose each task directly on the screen. On the other hand, we can use YAML pipelines so that all the pipeline stages, jobs and tasks are managed as code. We call the second option as “Multi-Stage Pipelines”. As the Multi-Stage Pipelines feature is still in public preview, it doesn’t fully offer the same functionalities that the UI pipelines do. The approval process for each release stage is one of the limited features, but it’s been available for a couple of months now.

In my previous post, I dealt with YAML pipeline refactoring technics. Throughout this post, I’m going to discuss how each release stage can configure the approval process.

Tags: Azure DevOps Services, Azure Pipelines, VS Code

[Read More](https://devkimchi.com/2019/10/02/azure-devops-multi-stage-pipelines-approval-strategies/)

Related Links:
* [Release pipelines - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/en-us/azure/devops/pipelines/release/?view=azure-devops&WT.mc_id=devkimchicom-blog-juyoo)
* [What’s new with Azure Pipelines : Azure DevOps Blog](https://devblogs.microsoft.com/devops/whats-new-with-azure-pipelines/?WT.mc_id=devkimchicom-blog-juyoo)
* [Pipeline deployment approvals - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/approvals?view=azure-devops&WT.mc_id=devkimchicom-blog-juyoo#approvals)
* [Microsoft account : Sign In or Create Your Account Today &#8211; Microsoft](https://account.microsoft.com/account?lang=en-us&WT.mc_id=devkimchicom-blog-juyoo)
* [Office 365 Login : Microsoft Office](https://www.office.com/?omkt=en-us)
* [Azure DevOps Services : Microsoft Azure](https://azure.microsoft.com/en-us/services/devops/?WT.mc_id=devkimchicom-blog-juyoo)
* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/?WT.mc_id=devkimchicom-blog-juyoo)
* [Control deployments by using approvals - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/en-us/azure/devops/pipelines/release/approvals/approvals?view=azure-devops&WT.mc_id=devkimchicom-blog-juyoo)
* [Control deployments by using gates - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/en-us/azure/devops/pipelines/release/approvals/gates?view=azure-devops&WT.mc_id=devkimchicom-blog-juyoo)
* [Deployment jobs - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/deployment-jobs?view=azure-devops&WT.mc_id=devkimchicom-blog-juyoo)
* [Environment - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/environments?view=azure-devops&WT.mc_id=devkimchicom-blog-juyoo)
* [Office 365 Login : Microsoft Office](https://www.office.com/?omkt=en-us&WT.mc_id=devkimchicom-blog-juyoo)
* [Release pipelines - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/ko-kr/azure/devops/pipelines/release/?view=azure-devops&WT.mc_id=aliencubeorg-blog-juyoo)
* [What’s new with Azure Pipelines : Azure DevOps Blog](https://devblogs.microsoft.com/devops/whats-new-with-azure-pipelines/?WT.mc_id=aliencubeorg-blog-juyoo)
* [애저 데브옵스 파이프라인 리팩토링 테크닉 &#8211; Aliencube Community](https://blog.aliencube.org/ko/2019/09/04/azure-devops-pipelines-refactoring-technics/)
* [Microsoft &#44228;&#51221; : &#47196;&#44536;&#51064; &#46608;&#45716; &#51648;&#44552; &#44228;&#51221; &#47564;&#46308;&#44592; - Microsoft](https://account.microsoft.com/account?lang=ko-kr&WT.mc_id=aliencubeorg-blog-juyoo)
* [Azure DevOps Services : Microsoft Azure](https://azure.microsoft.com/ko-kr/services/devops/?WT.mc_id=aliencubeorg-blog-juyoo)
* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/?WT.mc_id=aliencubeorg-blog-juyoo)
* [Control deployments by using approvals - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/ko-kr/azure/devops/pipelines/release/approvals/approvals?view=azure-devops&WT.mc_id=aliencubeorg-blog-juyoo)
* [Control deployments by using gates - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/ko-kr/azure/devops/pipelines/release/approvals/gates?view=azure-devops&WT.mc_id=aliencubeorg-blog-juyoo)
* [Deployment jobs - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/ko-kr/azure/devops/pipelines/process/deployment-jobs?view=azure-devops&WT.mc_id=aliencubeorg-blog-juyoo)
* [Environment - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/ko-kr/azure/devops/pipelines/process/environments?view=azure-devops&WT.mc_id=aliencubeorg-blog-juyoo)
* [Pipeline deployment approvals - Azure Pipelines : Microsoft Docs](https://docs.microsoft.com/ko-kr/azure/devops/pipelines/process/approvals?view=azure-devops&WT.mc_id=aliencubeorg-blog-juyoo#approvals)
* [Office 365 로그인 : Microsoft Office](https://www.office.com/?omkt=ko-KR&WT.mc_id=aliencubeorg-blog-juyoo)


## [Realizando traduções em tempo real com Translator Text & Node.js](https://dev.to/azure/realizando-traducoes-em-tempo-real-com-translator-text-node-js-1oeb)

**by: Glaucia Lemos**

In this article Glaucia teachs how to perform real-time translations with Translator Text & Node.js

Tags: JavaScript, TypeScript, Node.js, Azure Cognitive Services (Text API), Azure Cognitive Services, VS Code

[Read More](https://dev.to/azure/realizando-traducoes-em-tempo-real-com-translator-text-node-js-1oeb)

Related Links:
* [Servi&#231;os Cognitivos : Microsoft Azure](https://azure.microsoft.com/pt-br/services/cognitive-services/?WT.mc_id=devto-blog-gllemos)
* [API de Tradu&#231;&#227;o de Texto – Tradu&#231;&#227;o Autom&#225;tica : Microsoft Azure](https://azure.microsoft.com/pt-br/services/cognitive-services/translator-text-api/?WT.mc_id=devto-blog-gllemos)
* [Idiomas compatíveis – API de Tradução de Texto - Azure Cognitive Services : Microsoft Docs](https://docs.microsoft.com/pt-br/azure/cognitive-services/translator/language-support?WT.mc_id=devto-blog-gllemos#translation)
* [Idiomas compatíveis – API de Tradução de Texto - Azure Cognitive Services : Microsoft Docs](https://docs.microsoft.com/pt-br/azure/cognitive-services/translator/language-support?WT.mc_id=devto-blog-gllemos)
* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/?WT.mc_id=devto-blog-gllemos)
* [Crie sua conta gratuita do Azure hoje mesmo : Microsoft Azure](https://azure.microsoft.com/pt-br/free/?WT.mc_id=devto-blog-gllemos)
* [Azure for Students – Cr&#233;dito de Conta Gratuita : Microsoft Azure](https://azure.microsoft.com/pt-br/free/students/?WT.mc_id=devto-blog-gllemos)
* [Criar um recurso de serviços cognitivas no portal do Azure - Azure Cognitive Services : Microsoft Docs](https://docs.microsoft.com/pt-br/azure/cognitive-services/cognitive-services-apis-create-account?WT.mc_id=devto-blog-gllemos&tabs=multiservice%2Cwindows)
* [Plataforma e servi&#231;os de computa&#231;&#227;o em nuvem do Microsoft Azure](https://azure.microsoft.com/pt-br/?WT.mc_id=devto-blog-gllemos)


## [Live Coding on Twitch, Youtube & Facebook - Criando aplicação com Translator Text & Node.js](https://youtu.be/IzSVw1e2AxI)

**by: Glaucia Lemos**

During this live coding, Glaucia teaches you how to do real-time translations with Translator Text & Node.js and especially how to do translations in oriental languages such as Chinese!

Tags: JavaScript, TypeScript, Node.js, Azure Cognitive Services (Text API), Azure Cognitive Services, VS Code

[Read More](https://youtu.be/IzSVw1e2AxI)

Related Links:
* [Azure para desenvolvedores de JavaScript e Node.js – tutoriais, ferramentas e referências de SDK : Microsoft Docs](https://aka.ms/AA67u0c)
* [O que é a API de Tradução de Texto? - API de Tradução de Texto : Microsoft Docs](https://aka.ms/AA67u0d)
* [Processar e traduzir a fala com os Serviços de Fala Cognitiva do Azure - Learn : Microsoft Docs](https://aka.ms/AA67u0e)
* [Procurar tudo - Learn : Microsoft Docs](https://aka.ms/AA681u4)
* [Crie aplicativos inteligentes com a IA da Microsoft : Microsoft Azure](https://aka.ms/AA681u5)
* [Cognitive Services : Microsoft Azure](https://aka.ms/AA681u6)
* [Experimente os Servi&#231;os de IA com uma Conta Gratuita do Azure : Microsoft Azure](https://aka.ms/AA67u0g)


## [Many Meanings of Message Validation  메시지 유효성 검사에 대한 다양한 관점](https://devkimchi.com/2019/10/09/many-meanings-of-message-validation/)

**by: Justin Yoo**

Many information systems consist of a front-end user interface where users enter inputs and back-end that processes the input data. This concept can be extended to information systems that send and receive messages. Regardless the data come from user input or other systems, those messages MUST be validated before going forward. There are always chances that compromised messages are projected to a system, which is a real threat to the system. If the system can’t prevent those corrupted messages from being processed, the entire system will be down and result in the organisation’s business loss of opportunities.

How can we implement the message validation to the system, or how can we validate messages? More specifically, what does the “validation” even mean? Throughout this post, I’m going to discuss several viewpoints of the “message validation”.

Tags: Azure Storage, Kafka, Azure Service Bus, Azure Logic Apps, APIs/API Development, Azure Functions

[Read More](https://devkimchi.com/2019/10/09/many-meanings-of-message-validation/)

Related Links:
* [Azure Storage Documentation - Tutorials, API Reference : Microsoft Docs](https://docs.microsoft.com/en-us/azure/storage/?WT.mc_id=devkimchicom-blog-juyoo)
* [Azure Functions documentation : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/?WT.mc_id=devkimchicom-blog-juyoo)
* [Azure Logic Apps documentation : Microsoft Docs](https://docs.microsoft.com/en-us/azure/logic-apps/?WT.mc_id=devkimchicom-blog-juyoo)
* [Azure Service Bus Documentation - Tutorials, API Reference : Microsoft Docs](https://docs.microsoft.com/en-us/azure/service-bus/?WT.mc_id=devkimchicom-blog-juyoo)


## [Tutorial: Connect to Azure Event Hubs for Kafka using Go](https://dev.to/azure/tutorial-connect-to-azure-event-hubs-for-kafka-using-go-203i)

**by: Abhishek Gupta**

This blog will demonstrate how to interact with Event Hubs Kafka cluster using the Sarama Kafka client library which provides a pure Go client that supports Kafka v 0.8 and above.

Tags: Kafka, Azure Event Hubs, Go, GoLang

[Read More](https://dev.to/azure/tutorial-connect-to-azure-event-hubs-for-kafka-using-go-203i)

Related Links:
* [Use event hub from Apache Kafka app - Azure Event Hubs : Microsoft Docs](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-for-kafka-ecosystem-overview?WT.mc_id=devto-blog-abhishgu)
* [Create your Azure free account today : Microsoft Azure](https://azure.microsoft.com/en-us/free/?WT.mc_id=devto-blog-abhishgu)
* [Install the Azure CLI : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu)
* [Authentication and security model - Azure Event Hubs : Microsoft Docs](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-authentication-and-security-model-overview?WT.mc_id=devto-blog-abhishgu)
* [Use event hub from Apache Kafka app - Azure Event Hubs : Microsoft Docs](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-for-kafka-ecosystem-overview?WT.mc_id=devto-blog-abhishgu#features-that-are-not-yet-supported)


## [On-Call Nightmares Podcast - Episode 40: Ryan Kitchens (Netflix US)](https://www.podomatic.com/podcasts/oncallnightmares/episodes/2019-10-10T09_42_50-07_00)

**by: Jay Gordon**

Weekly podcast featuring interviews with DevOps experts and IT pros on their experiences dealing with "on-call" emergencies.

In this episode: A big milestone, episode 40! This week I speak with Netflix SRE Ryan Kitchen about birds, DR and movies!

Ryan Kitchens has been in a variety of positions in software over the past ten years allowing him to experience the good and the bad, the amazing and the bizarre. As an SRE with a film degree, he currently works at Netflix on the CORE team, focused on ensuring availability. The background of the team spans incident management and analysis, resilience engineering, and human factors & systems safety.

https://twitter.com/this_hits_home

Tags: DevOps, Advice, Cloud Computing

[Read More](https://www.podomatic.com/podcasts/oncallnightmares/episodes/2019-10-10T09_42_50-07_00)



## [Practical DevOps for the busy data scientist](https://speakerdeck.com/trallard/practical-devops-for-the-busy-data-scientist-b85e6447-6f6e-4caf-8441-acf1cb117a95)

**by: Tania Allard**

Slides for my talk "Practical DevOps for the busy data scientist" at PyCon DE
Focuses on ways to leverage DevOps for Machine learning or data science workflows

Tags: DevOps, AI/ML

[Read More](https://speakerdeck.com/trallard/practical-devops-for-the-busy-data-scientist-b85e6447-6f6e-4caf-8441-acf1cb117a95)



## [Tip: How to use the ‘storageClass' attribute in Kubernetes 🤔](https://dev.to/itnext/tip-how-to-use-the-storageclass-attribute-in-kubernetes-4pka)

**by: Abhishek Gupta**

This is a short blog post that covers an aspect of Kubernetes dynamic provisioning which often trips up folks when they are first exploring it

Tags: Kubernetes

[Read More](https://dev.to/itnext/tip-how-to-use-the-storageclass-attribute-in-kubernetes-4pka)

Related Links:
* [Select a disk type for Azure IaaS Windows VMs - managed disks : Microsoft Docs](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disks-types?WT.mc_id=devto-blog-abhishgu#standard-hdd)
* [Select a disk type for Azure IaaS Windows VMs - managed disks : Microsoft Docs](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disks-types?WT.mc_id=devto-blog-abhishgu#premium-ssd)
* [Disk Storage – HDD/SSD on Azure : Microsoft Azure](https://azure.microsoft.com/en-us/services/storage/disks/?WT.mc_id=devto-blog-abhishgu)


## [Tutorial: Use Azure Cognitive Services to build a translator app hosted on Azure App Service 👨‍💻👩‍💻](https://dev.to/azure/tutorial-use-azure-cognitive-services-to-build-a-translator-app-hosted-on-azure-app-service-4pp1)

**by: Abhishek Gupta**

This tutorial will demonstrate the usage of Azure Cognitive Services with the help of a text translation example implemented using a simple Golang app deployed to Azure App Service

Tags: Azure Cognitive Services, Go, GoLang, Azure App Service

[Read More](https://dev.to/azure/tutorial-use-azure-cognitive-services-to-build-a-translator-app-hosted-on-azure-app-service-4pp1)

Related Links:
* [Cognitive Services : Microsoft Azure](https://azure.microsoft.com/en-us/services/cognitive-services/?WT.mc_id=devto-blog-abhishgu)
* [Azure App Service – app hosting : Microsoft Azure](https://azure.microsoft.com/en-us/services/app-service/?WT.mc_id=devto-blog-abhishgu)
* [What is the Translator Text API? - Translator Text API : Microsoft Docs](https://docs.microsoft.com/en-us/azure/cognitive-services/translator/translator-info-overview?WT.mc_id=devto-blog-abhishgu)
* [Cognitive Services and Machine Learning - Azure Cognitive Services : Microsoft Docs](https://docs.microsoft.com/en-us/azure/cognitive-services/cognitive-services-and-machine-learning?WT.mc_id=devto-blog-abhishgu)
* [Cognitive Services Directory : Microsoft Azure](https://azure.microsoft.com/en-us/services/cognitive-services/directory/speech/?WT.mc_id=devto-blog-abhishgu)
* [Cognitive Services Directory : Microsoft Azure](https://azure.microsoft.com/en-us/services/cognitive-services/directory/lang/?WT.mc_id=devto-blog-abhishgu)
* [Cognitive Services Directory : Microsoft Azure](https://azure.microsoft.com/en-us/services/cognitive-services/directory/search/?WT.mc_id=devto-blog-abhishgu)
* [Cognitive Services Directory : Microsoft Azure](https://azure.microsoft.com/en-us/services/cognitive-services/directory/decision/?WT.mc_id=devto-blog-abhishgu)
* [Container support - Azure Cognitive Services : Microsoft Docs](https://docs.microsoft.com/en-us/azure/cognitive-services/cognitive-services-container-support?WT.mc_id=devto-blog-abhishgu)
* [Introduction to App Service on Linux - Azure : Microsoft Docs](https://docs.microsoft.com/en-us/azure/app-service/containers/app-service-linux-intro?WT.mc_id=devto-blog-abhishgu)
* [Microsoft Azure Documentation : Microsoft Docs](https://docs.microsoft.com/en-us/azure/?WT.mc_id=devto-blog-abhishgu)
* [Create your Azure free account today : Microsoft Azure](https://azure.microsoft.com/en-us/free/?WT.mc_id=devto-blog-abhishgu)
* [az cognitiveservices account : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/cognitiveservices/account?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-cognitiveservices-account-create)
* [Build a custom image and run in App Service from a private registry : Microsoft Docs](https://docs.microsoft.com/en-us/azure/app-service/containers/tutorial-custom-docker-image?WT.mc_id=devto-blog-abhishgu)
* [Azure Container Registry – Docker Registry : Microsoft Azure](https://azure.microsoft.com/en-us/services/container-registry/?WT.mc_id=devto-blog-abhishgu)
* [App Service plan overview - Azure : Microsoft Docs](https://docs.microsoft.com/en-us/azure/app-service/overview-hosting-plans?toc=%2fazure%2fapp-service%2fcontainers%2ftoc.json&WT.mc_id=devto-blog-abhishgu)
* [Azure Container Instances documentation - serverless containers, on demand : Microsoft Docs](https://docs.microsoft.com/en-us/azure/container-instances/?WT.mc_id=devto-blog-abhishgu)


## [Build Your Serverless Azure Function Apps With Bazel 1.0 🌿](https://dev.to/bazel/build-azure-function-apps-with-bazel-1-0-mci)

**by: Wassim Chegham**

Upon the annoncement of Bazel 1.0, Wassim share a guide taking you through the set up of an Azure Function application using Bazel, written in TypeScript.

Tags: Azure Functions

[Read More](https://dev.to/bazel/build-azure-function-apps-with-bazel-1-0-mci)



## [Vanilla JavaScript and HTML - No frameworks. No libraries. No problem.](https://dev.to/john_papa/vanilla-javascript-and-html-no-frameworks-no-libraries-no-problem-2n99)

**by: John Papa**

Have you ever heard the expression 'You don't know what you go, til it's gone'? Do you know what it takes to render HTML elements on a web page without Angular, React, Svelte, and Vue? Let's explore a controlled scenario of creating a simple web page and bring to the foreground what it takes to render a page with pure HTML, CSS, and JavaScript.

Tags: JavaScript, TypeScript, Node.js, VS Code

[Read More](https://dev.to/john_papa/vanilla-javascript-and-html-no-frameworks-no-libraries-no-problem-2n99)

Related Links:
* [Create your Azure free account today : Microsoft Azure](https://azure.microsoft.com/en-us/free/?wt.mc_id=devto-blog-jopapa)
* [TypeScript Programming with Visual Studio Code](https://code.visualstudio.com/docs/languages/typescript?wt.mc_id=devto-blog-jopapa)
* [Visual Studio Code - Code Editing. Redefined](https://code.visualstudio.com/?wt.mc_id=devto-blog-jopapa)


## [L’inclusive Design c’est l’affaire de tous !](https://www.youtube.com/watch?v=hrf1s2pbhFI)

**by: Christopher Maneu**

View the recording of the talk given at the MUG Montpellier + MAUG meetup in Montpellier during the Fall Roadshow. Accessibility is an important thing. Everyone agrees on that, right? So why aren't all our services are accessible? No "first-hand" experience with accessibility issues? Not bringing business value? Inclusive Design is a set of principles and design methodology that enables and draws on the full range of human diversity. During this session, we will see these principles in action, and how you can integrate these ideas into your product development. Because in an Inclusive Design world there is no such thing as ‘normal’, everybody can help a more inclusive society.

Tags: UI/UX, UI Design

<iframe width="560" height="315" src="https://www.youtube.com/embed/hrf1s2pbhFI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



## [Progressive Web Apps, Beyond the Buzzword](http://bit.ly/pwadeck)

**by: Yohan Lasorsa**

Slides from Yohan's talk about Progressive Web Apps given at several meetups during the Fall Roadshow. During this talk, see what Progressive Web Apps are and why developers should care.

3 takeways from this presentation:
- PWAs provide the same user experience as mobile apps, but using web technologies
- PWAs are cross-platform, cheap to make (vs multiple native apps), engaging and fast
- PWAs are easy to deploy and update, there's no store entry wall, validation and fee (but can still be pushed to app stores if needed!)

Tags: UI/UX, UI Design

[Read More](http://bit.ly/pwadeck)



## [How to use synchronization primitives in Go: Mutex, WaitGroup, Once](https://dev.to/itnext/how-to-use-synchronization-primitives-in-go-mutex-waitgroup-once-1aee)

**by: Abhishek Gupta**

This is the second post in a series of articles about the Go programming language. Covers some of the lower-level synchronization constructs which Go provides in the sync package

Tags: Go, GoLang

[Read More](https://dev.to/itnext/how-to-use-synchronization-primitives-in-go-mutex-waitgroup-once-1aee)



## [Automated ML on Azure Databricks](https://github.com/Azure/MachineLearningNotebooks/blob/master/how-to-use-azureml/azure-databricks/automl/automl-databricks-local-01.ipynb)

**by: Francesca Lazzeri**

In this example we use the scikit-learn's digit dataset to showcase how you can use AutoML for a simple classification problem.

In this notebook you will learn how to:

Create Azure Machine Learning Workspace object and initialize your notebook directory to easily reload this object from a configuration file.
Create an Experiment in an existing Workspace.
Configure Automated ML using AutoMLConfig.
Train the model using Azure Databricks.
Explore the results.
Viewing the engineered names for featurized data and featurization summary for all raw features.
Test the best fitted model.
Before running this notebook, please follow the readme for using Automated ML on Azure Databricks for installing necessary libraries to your cluster.

We support installing AML SDK with Automated ML as library from GUI. When attaching a library follow this link and add the below string as your PyPi package. You can select the option to attach the library to all clusters or just one cluster.

Tags: Azure Machine Learning, Python, Azure Databricks

[Read More](https://github.com/Azure/MachineLearningNotebooks/blob/master/how-to-use-azureml/azure-databricks/automl/automl-databricks-local-01.ipynb)



## [Azure IoT PnP Applications with Deepstream on Nvidia Jetson Devices](https://github.com/toolboc/azure-iot-nvidia-jetson-deepstream-pnp)

**by: Paul DeCarlo**

This GitHub repository contains a tutorial for using an Azure IoT PnP application to enable remote interaction and telemetry in IoT Central for DeepStream on Nvidia Jetson Devices.

Tags: IoT, Azure IoT Hub, Azure IoT Central

[Read More](https://github.com/toolboc/azure-iot-nvidia-jetson-deepstream-pnp)

Related Links:
* [Azure IoT Central Documentation - Tutorials, API Reference : Microsoft Docs](https://docs.microsoft.com/en-us/azure/iot-central/?WT.mc_id=github-deepstreampnp-pdecarlo)
* [Check device connectivity to Azure IoT Hub : Microsoft Docs](https://docs.microsoft.com/en-us/azure/iot-hub/tutorial-connectivity#create-an-iot-hub?WT.mc_id=github-deepstreampnp-pdecarlo)
* [Azure IoT Hub Device Provisioning Service Documentation - Tutorials, API Reference : Microsoft Docs](https://docs.microsoft.com/en-us/azure/iot-dps/?WT.mc_id=github-deepstreampnp-pdecarlo)
* [Create an Azure IoT Central application : Microsoft Docs](https://docs.microsoft.com/en-us/azure/iot-central/quick-deploy-iot-central-pnp?toc=/azure/iot-central-pnp/toc.json&bc=/azure/iot-central-pnp/breadcrumb/toc.json?WT.mc_id=github-deepstreampnp-pdecarlo)
* [Connect an IoT Plug and Play Preview device to Azure IoT Central : Microsoft Docs](https://docs.microsoft.com/en-us/azure/iot-central/quick-create-pnp-device-pnp?toc=/azure/iot-central-pnp/toc.json&bc=/azure/iot-central-pnp/breadcrumb/toc.json#generate-device-key?WT.mc_id=github-deepstreampnp-pdecarlo)


## [Too Hard, Too Soft, Just Right - Rendering HTML with lit-html](https://dev.to/azure/too-hard-too-soft-just-right-rendering-html-with-lit-html-1km8)

**by: John Papa**

Sometimes you need to render HTML elements on a web page. And like Goldilocks' search for "just right", you have to try a few techniques before you find the right one. Using a framework may be too hard. Using pure HTML and the DOM API may be too soft. What you need is something in the middle that is just right. Is lit-html "just right"? Let's find out.

First, I'll show how this all works. Then at the end of this article, I'll explain everything you need to get started with lit-html to try this for yourself.

Tags: JavaScript, TypeScript, Node.js, VS Code, HTML

[Read More](https://dev.to/azure/too-hard-too-soft-just-right-rendering-html-with-lit-html-1km8)

Related Links:
* [TypeScript Programming with Visual Studio Code](https://code.visualstudio.com/docs/languages/typescript?wt.mc_id=johnpapanet-blog-jopapa)
* [
        lit-html - Visual Studio Marketplace
    ](https://marketplace.visualstudio.com/items?itemName=bierner.lit-html&wt.mc_id=devto-blog-jopapa)
* [Create your Azure free account today : Microsoft Azure](https://azure.microsoft.com/en-us/free/?wt.mc_id=devto-blog-jopapa)


## [(VOD) Azure Subscription Cleaner Auto deployment](https://youtu.be/DIC6tYsfRW4)

**by: Frank Boucher**

In this session, join Frank Boucher in fixing the Azure Automation solution for the project Azure Subscription Cleaner (AzSubscriptionCleaner). Once the project is all working he will then work on extracting the Azure Resource Manager (#ARM) template.

Tags: Azure ARM Templates, Azure Automation, azure

[Read More](https://youtu.be/DIC6tYsfRW4)



## [Deploy and Install Windows Admin Center in an Azure VM](https://www.thomasmaurer.ch/2019/10/deploy-and-install-windows-admin-center-in-an-azure-vm/)

**by: Thomas Maurer**

The great thing about Windows Admin Center (WAC) you manage every Windows Server doesn’t matter where it is running. You can manage Windows Servers on-prem, in Azure or running at other cloud providers. Now if you want to use Windows Admin Center to manage your virtual machines running in Azure, you can use either an on-prem WAC installation and connecting it using a public IP address or a VPN connection, or you can deploy and install Windows Admin Center in Azure. This blog post will show you how you can deploy and install Windows Admin Center in an Azure virtual machine (VM).

In this article you learn how to deploy and install Windows Admin Center in Azure virtual machine.

Tags: Windows Server, Azure, PowerShell, Azure PowerShell, Azure Cloud Shell, Windows Admin Center, Azure Virtual Machines

[Read More](https://www.thomasmaurer.ch/2019/10/deploy-and-install-windows-admin-center-in-an-azure-vm/)

Related Links:
* [Deploy a Windows Admin Center gateway in Azure : Microsoft Docs](https://docs.microsoft.com/en-us/windows-server/manage/windows-admin-center/azure/deploy-wac-in-azure?WT.mc_id=thomasmaurer-blog-thmaure#deploy-manually-on-an-existing-azure-virtual-machine)
* [What is Azure Key Vault? : Microsoft Docs](https://docs.microsoft.com/en-us/azure/key-vault/basic-concepts?WT.mc_id=thomasmaurer-blog-thmaure)
* [Deploy a Windows Admin Center gateway in Azure : Microsoft Docs](https://docs.microsoft.com/en-us/windows-server/manage/windows-admin-center/azure/deploy-wac-in-azure?WT.mc_id=thomasmaurer-blog-thmaure)


## [Deploy and install Windows Admin Center in Azure](https://www.youtube.com/watch?v=cFQxRwnlaSY)

**by: Thomas Maurer**

(1) This Video will show you how you can deploy and install Windows Admin Center in an Azure virtual machine (VM).
(2) Video
(3) The great thing about Windows Admin Center (WAC) you manage every Windows Server doesn’t matter where it is running. You can manage Windows Servers on-prem, in Azure or running at other cloud providers. Now if you want to use Windows Admin Center to manage your virtual machines running in Azure, you can use either an on-prem WAC installation and connecting it using a public IP address or a VPN connection, or you can deploy and install Windows Admin Center in Azure. This video will show you how you can deploy and install Windows Admin Center in an Azure virtual machine (VM).

Tags: Windows Server, Azure, PowerShell, Azure PowerShell, Azure Cloud Shell, Windows Admin Center, Azure Virtual Machines

<iframe width="560" height="315" src="https://www.youtube.com/embed/cFQxRwnlaSY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Related Links:
* [Deploy a Windows Admin Center gateway in Azure : Microsoft Docs](https://docs.microsoft.com/en-us/windows-server/manage/windows-admin-center/azure/deploy-wac-in-azure?WT.mc_id=thomasmaurer-blog-thmaure)
* [Connecting Windows Server to Azure hybrid services : Microsoft Docs](https://docs.microsoft.com/en-us/windows-server/manage/windows-admin-center/azure/?WT.mc_id=thomasmaurer-blog-thmaure)
* [Configuring Azure Integration : Microsoft Docs](https://docs.microsoft.com/en-us/windows-server/manage/windows-admin-center/azure/azure-integration?WT.mc_id=thomasmaurer-blog-thmaure)
* [How to configure Azure Hybrid Services in Windows Admin Center](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/How-to-configure-Azure-Hybrid-Services-in-Windows-Admin-Center/ba-p/467431?WT.mc_id=thomasmaurer-blog-thmaure)


## [Add Real-time to your Java App with Azure SignalR Service](https://dev.to/azure/add-real-time-to-your-java-app-with-azure-signalr-service-3p8)

**by: Anthony Chu**

In this article, we look at the benefits of using Azure SignalR Service for real-time communication and how to integrate it with a Java Spring Boot chat application using the service's HTTP API.

Tags: APIs/API Development, Azure SignalR Service, Java

[Read More](https://dev.to/azure/add-real-time-to-your-java-app-with-azure-signalr-service-3p8)

Related Links:
* [Azure SignalR Service Documentation - Tutorials, API Reference : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-signalr/?WT.mc_id=devto-blog-antchu)
* [ASP.NET Core SignalR .NET Client : Microsoft Docs](https://docs.microsoft.com/en-us/aspnet/core/signalr/dotnet-client?WT.mc_id=devto-blog-antchu&view=aspnetcore-3.0&tabs=visual-studio)
* [ASP.NET Core SignalR JavaScript client : Microsoft Docs](https://docs.microsoft.com/en-us/aspnet/core/signalr/javascript-client?WT.mc_id=devto-blog-antchu&view=aspnetcore-3.0)
* [Quickstart - Azure SignalR Service REST API : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-signalr/signalr-quickstart-rest-api?WT.mc_id=devto-blog-antchu)


## [End-to-End Serverless Real-Time IoT with Python](https://dev.to/azure/end-to-end-serverless-real-time-iot-with-python-4i2b)

**by: Anthony Chu**

In this article, we look at how to build an end-to-end IoT solution using Python. We'll send telemetry from a device to Azure IoT Hub. Then we'll use Azure Functions and Azure SignalR Service to send messages from IoT Hub to a Python app in real-time.

Tags: Python, IoT

[Read More](https://dev.to/azure/end-to-end-serverless-real-time-iot-with-python-4i2b)

Related Links:
* [Introduction to Azure IoT Hub : Microsoft Docs](https://docs.microsoft.com/en-us/azure/iot-hub/about-iot-hub?WT.mc_id=devto-blog-antchu)
* [Azure Functions Overview : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview?WT.mc_id=devto-blog-antchu)
* [Azure SignalR Service Documentation - Tutorials, API Reference : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-signalr/?WT.mc_id=devto-blog-antchu)


## [Learning Python from Scratch - Building Python Projects](https://dev.to/azure/learning-python-from-scratch-projects-imports-and-more-26pe)

**by: Brian Clark**

In this session, Cecil, Brian and chat learn about creating and structuring Python projects. They also learn about different ways to run them, how imports work and little bit about the command line/terminal.

Tags: Python

[Read More](https://dev.to/azure/learning-python-from-scratch-projects-imports-and-more-26pe)

Related Links:
* [Subscribe to the Microsoft.Source newsletter : Microsoft Azure](https://azure.microsoft.com/en-us/resources/join-the-azure-developer-community/?WT.mc_id=pythonfromscratch-devto-cxa)


## [How to Tackle the Challenges in Deploying Machine Learning Models](https://dzone.com/trendreports/machine-learning-deploying-models-at-scale)

**by: Francesca Lazzeri**

Artificial intelligence offers companies the potential to transform their
operations: from applications that predict and schedule equipment
maintenance, to intelligent R&D systems that estimate the cost of new
drug development, to AI-powered tools for HR that enhance the hiring
process and employee retention strategy. However, in order to be able
to leverage this opportunity, companies must learn how to successfully build, train, test, and push hundreds of machine learning models to
production. They also need to move models from development to their
production environment in ways that are robust, fast, and repeatable.
Today's data scientists and developers have a much easier experience
when building AI-based solutions through the availability and accessibility of data and open source machine learning frameworks. This process
becomes a lot more complex, however, when they need to think about
model deployment and pick the best strategy to scale up to a production-grade system.
In this article, we will introduce some common challenges of machine learning model deployment. We will also discuss the following points that may enable you to tackle some of those challenges:
1. Why successful model deployment is fundamental for AI-driven companies.
2. Why companies struggle with model deployment.
3. How to select the right tools to succeed with model deployment.

Tags: Azure Machine Learning Service

[Read More](https://dzone.com/trendreports/machine-learning-deploying-models-at-scale)

Related Links:
* [Machine Learning documentation - Azure : Microsoft Docs](https://docs.microsoft.com/en-us/azure/machine-learning/?WT.mc_id=dzone-article-lazzeri)


## [Cloud Native Show : Configuration and Setting in ASP.NET Core](https://www.youtube.com/watch?v=LvA3YpGKX1c)

**by: Shayne  Boyer**

One of the "Factors" in cloud native applications states you should store your configuration and settings outside of your core application code. In this episode, Shayne talks with Andrew to get a run down on how the configuration options in .NET Core allows for layers of configurability and abstractions for your app.

Tags: ASP.NET Core, Azure App Service

<iframe width="560" height="315" src="https://www.youtube.com/embed/LvA3YpGKX1c" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Related Links:
* [Configuration in ASP.NET Core : Microsoft Docs](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-3.0&WT.mc_id=cloudnative-ch9-shboyer)
* [Use multiple environments in ASP.NET Core : Microsoft Docs](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments?view=aspnetcore-3.0&WT.mc_id=cloudnative-ch9-shboyer)
* [What is Azure App Configuration? : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-app-configuration/overview?WT.mc_id=cloudnative-ch9-shboyer)
* [Azure Key Vault Configuration Provider in ASP.NET Core : Microsoft Docs](https://docs.microsoft.com/en-us/aspnet/core/security/key-vault-configuration?view=aspnetcore-3.0&WT.mc_id=cloudnative-ch9-shboyer)
* [Managed identities overview - Azure App Service : Microsoft Docs](https://docs.microsoft.com/en-us/azure/app-service/overview-managed-identity?WT.mc_id=cloudnative-ch9-shboyer)
* [Safe storage of app secrets in development in ASP.NET Core : Microsoft Docs](https://docs.microsoft.com/en-us/aspnet/core/security/app-secrets?view=aspnetcore-3.0&tabs=windows&WT.mc_id=cloudnative-ch9-shboyer)

