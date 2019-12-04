---
layout: post
title: CDA Weekly Content Wrapup (Sep 30 2019)
subtitle: 
tags: [Azure Machine Learning, Python, TensorFlow, Azure Functions, azure, Serverless, Azure, Kubernetes, Security, Monitoring, Cloud Computing, Kafka, Azure Event Hubs, Azure Storage, Azure Front Door, Azure DevOps Services, DevOps, .NET, .NET Core, C#, Cloud-Native, Testing, VS Code, Azure Logic Apps, SQL, SQL Server, .NET Core, Azure Cognitive Services, Azure Data Explorer, Windows 10, WSL 2, Windows, Windows Terminal, WSL, Azure Pipelines, R, Azure Kubernetes Service, Agnostic, Rust, Infrastructure, Azure Virtual Network, Azure CLI, Windows Server, Azure PowerShell, Azure Virtual Machines, Azure Bastion, Internet Control Message Protocol ICMP, Azure Portal, Azure Resource Graph, PowerShell, Azure AD, Azure Key Vault, Active Directory, JavaScript, Node.js, Web Development, Enterprise Databases SQL and NoSQL, Azure Table Storage]
---

## [Tutorial: Apply machine learning models in Azure Functions with Python and TensorFlow](https://docs.microsoft.com/en-us/azure/azure-functions/functions-machine-learning-tensorflow)

**by: Anthony Chu**

This article demonstrates how Azure Functions allows you to use Python and TensorFlow with a machine learning model to classify an image based on its contents.
In this tutorial, you learn to initialize a local environment for developing Azure Functions in Python, import a custom TensorFlow machine learning model into a function app, build a serverless HTTP API for predicting whether a photo contains a dog or a cat and consume the API from a web application.

Tags: Azure Machine Learning, Python, TensorFlow, Azure Functions

[Read More](https://docs.microsoft.com/en-us/azure/azure-functions/functions-machine-learning-tensorflow)



## [6 Figure Dev Podcast with Anthony Chu](https://6figuredev.com/podcast/episode-107-azure-functions-with-anthony-chu/)

**by: Anthony Chu**

Anthony joins the 6 Figure Dev podcast to talk about how he got started in software development as well as some cool tricks and tips on Azure Functions.

Tags: Azure Functions, azure

[Read More](https://6figuredev.com/podcast/episode-107-azure-functions-with-anthony-chu/)



## [Large-Scale Serverless Machine Learning Inference with Azure Functions](https://dev.to/azure/machine-learning-inferencing-at-scale-with-azure-functions-1m3j-temp-slug-8530185?preview=a4b2165e42795a421d875c82ef47dd1ca06d1c064f6eaeadc55656b9c309717f96e4c2e3fc64b976b0f4d078cd5f09352269db8f097532fab66d9c8e)

**by: Anthony Chu**

Azure Functions recently announced the general availability of their Python language support. We can use Python 3.6 and Python's large ecosystem of packages, such as TensorFlow, to build serverless functions.

This blog post walks through how to use TensorFlow for ML inference in Azure Functions with Python and take advantage of Azure Function's on-demand scaling to perform on image classification at large scale.

Tags: Azure Machine Learning, Python, Serverless, Azure Functions

[Read More](https://dev.to/azure/machine-learning-inferencing-at-scale-with-azure-functions-1m3j-temp-slug-8530185?preview=a4b2165e42795a421d875c82ef47dd1ca06d1c064f6eaeadc55656b9c309717f96e4c2e3fc64b976b0f4d078cd5f09352269db8f097532fab66d9c8e)

Related Links:
* [Introduction to Azure Queues - Azure Storage : Microsoft Docs](https://docs.microsoft.com/en-us/azure/storage/queues/storage-queues-introduction?WT.mc_id=devto-blog-antchu)
* [Azure Functions Overview : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview?WT.mc_id=devto-blog-antchu)
* [Azure SignalR Service Documentation - Tutorials, API Reference : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-signalr/?WT.mc_id=devto-blog-antchu)
* [Tutorial: Use Python and TensorFlow in Azure Functions to make machine learning inferences : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/functions-machine-learning-tensorflow?WT.mc_id=devto-blog-antchu)
* [Develop and configure Azure Functions SignalR Service applications : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-signalr/signalr-concept-serverless-development-config?WT.mc_id=devto-blog-antchu)


## [How to get your Kubernetes cluster service principal and use it to access other Azure services?](https://dev.to/azure/azure-tip-how-to-get-your-kubernetes-cluster-service-principal-and-use-it-to-access-other-azure-services-2735)

**by: Abhishek Gupta**

This is a quick "Azure tip" which summarizes how to get the AKS cluster service principal and use it to access other Azure services

Tags: Azure, Kubernetes

[Read More](https://dev.to/azure/azure-tip-how-to-get-your-kubernetes-cluster-service-principal-and-use-it-to-access-other-azure-services-2735)

Related Links:
* [Azure Kubernetes Service (AKS) Documentation - Tutorials, API Reference : Microsoft Docs](https://docs.microsoft.com/en-us/azure/aks/?WT.mc_id=devto-blog-abhishgu)
* [Azure Container Registry – Docker Registry : Microsoft Azure](https://azure.microsoft.com/en-us/services/container-registry/?WT.mc_id=devto-blog-abhishgu)
* [az role assignment : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/role/assignment?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu)
* [Quickstart - Create an Azure Kubernetes Service (AKS) cluster in the portal : Microsoft Docs](https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough-portal?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu)
* [az aks : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/aks?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-aks-create)
* [Install the Azure CLI : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu)
* [az ad sp : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/ad/sp?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-ad-sp-create-for-rbac)
* [az aks : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/aks?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-aks-show)


## [Deploying Kubernetes in an Enterprise Environment](https://dzone.com/storage/assets/12453878-dzone-trendreport-kubernetesintheenterprise.pdf)

**by: Adi Polak**

Kubernetes is a great container orchestrator, with out-of-the-box capabilities like resource management, deployment management, automatic updates, self-healing and many more. However, Kubernetes itself is just the first step towards having a full-blown, enterprise-grade production environment.

In this article, we will cover implementing security controls, meeting compliance regulations, monitoring both the infrastructure and the applications on top of it, safely and gradually deploy applications to multiple, world-wide clusters, and much more.

Tags: Security, Monitoring, Kubernetes, Cloud Computing

[Read More](https://dzone.com/storage/assets/12453878-dzone-trendreport-kubernetesintheenterprise.pdf)



## [Learning Python from Scratch 010 - Control Statements: “if” “else” “elif”](https://www.twitch.tv/videos/479976049?t=00h03m51s)

**by: Brian Clark**

In this session, Cecil and Brian learned about control statements "if" "else" and "elif" in Python. They spent most of the time writing a coin flip program and improving it with things they learned on past episodes. The next session they will start learning about continuous loops and how to stop them in Python.

Tags: Python

[Read More](https://www.twitch.tv/videos/479976049?t=00h03m51s)



## [How to quickly test connectivity to your Azure Event Hubs for Kafka cluster, without writing any code](https://dev.to/azure/how-to-quickly-test-connectivity-to-your-azure-event-hubs-for-kafka-cluster-without-writing-any-code-4la1)

**by: Abhishek Gupta**

Quickly test connectivity to your Azure Event Hubs Kafka instance using only the Kafka CLI, without writing client code

Tags: Kafka, Azure Event Hubs

[Read More](https://dev.to/azure/how-to-quickly-test-connectivity-to-your-azure-event-hubs-for-kafka-cluster-without-writing-any-code-4la1)

Related Links:
* [Use event hub from Apache Kafka app - Azure Event Hubs : Microsoft Docs](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-for-kafka-ecosystem-overview?WT.mc_id=devto-blog-abhishgu)
* [Install the Azure CLI : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu)
* [Azure Cloud Shell – Browser-Based Command Line : Microsoft Azure](https://azure.microsoft.com/en-us/features/cloud-shell/?WT.mc_id=devto-blog-abhishgu)
* [Overview of features - Azure Event Hubs : Microsoft Docs](https://docs.microsoft.com/en-us/azure/event-hubs/event-hubs-features?WT.mc_id=devto-blog-abhishgu#namespace)
* [Authorize access with a shared access signature in Azure Event Hubs : Microsoft Docs](https://docs.microsoft.com/en-us/azure/event-hubs/authorize-access-shared-access-signature?WT.mc_id=devto-blog-abhishgu)
* [Authorize access with a shared access signature in Azure Event Hubs : Microsoft Docs](https://docs.microsoft.com/en-us/azure/event-hubs/authorize-access-shared-access-signature?WT.mc_id=devto-blog-abhishgu#best-practices-when-using-sas)
* [az eventhubs namespace : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/eventhubs/namespace?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-eventhubs-namespace-create)
* [az eventhubs eventhub : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/eventhubs/eventhub?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-eventhubs-eventhub-create)
* [az eventhubs namespace authorization-rule : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/eventhubs/namespace/authorization-rule?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-eventhubs-namespace-authorization-rule-list)
* [az eventhubs namespace authorization-rule keys : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/eventhubs/namespace/authorization-rule/keys?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-eventhubs-namespace-authorization-rule-keys-list)


## [Cloud Native Show - DevOps for .NET Core & Cloud Native Apps](https://youtu.be/Ztl3OB_DjCY)

**by: Shayne  Boyer**

Abel and Shayne sit down to discuss the relationship between DevOps and cloud native applications to understand how they fit together. They demonstrate an application, the pipeline that builds it and talk about how it improves the overall experience and efficiency of the overall process.

Tags: Azure Storage, Azure Front Door, Azure DevOps Services, DevOps, .NET, .NET Core, C#, Azure Functions, Cloud-Native

[Read More](https://youtu.be/Ztl3OB_DjCY)



## [Testing in .NET Core](https://dev.to/dotnet/testing-in-net-core-ojh)

**by: Chris Noring**

In this primer, Chris shows readers the ins-and-outs of testing in .NET Core, including how to create and run test projects, what the differences are between different testing types, and how to name and arrange tests.

Tags: .NET, .NET Core, C#, Testing, Serverless, VS Code

[Read More](https://dev.to/dotnet/testing-in-net-core-ojh)

Related Links:
* [Get started with C# and Visual Studio Code - .NET Core : Microsoft Docs](https://docs.microsoft.com/en-us/dotnet/core/tutorials/with-visual-studio-code?wt.mc_id=devto-blog-chnoring)
* [dotnet test command - .NET Core CLI : Microsoft Docs](https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-test?tabs=netcore21)
* [Unit testing C# with NUnit and .NET Core - .NET Core : Microsoft Docs](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-nunit?wt.mc_id=devto-blog-chnoring)
* [Unit testing C# code in .NET Core using dotnet test and xUnit - .NET Core : Microsoft Docs](https://docs.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-dotnet-test?wt.mc_id=devto-blog-chnoring)


## [How YOU can build your first Serverless Logic app, part I](https://dev.to/azure/how-you-can-build-your-first-logic-app-18he)

**by: Chris Noring**

This article describes Logic Apps and explains when it's a good candidate and what parts it consists of. The reader will also learn how to build a project using logic apps.

Tags: Serverless, Azure Logic Apps

[Read More](https://dev.to/azure/how-you-can-build-your-first-logic-app-18he)

Related Links:
* [Azure Functions documentation : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/?WT.mc_id=servsept_devto-blog-cxa)
* [Create your Azure free account today : Microsoft Azure](https://azure.microsoft.com/en-us/free/?wt.mc_id=servsept_devto-blog-chnoring)
* [Azure Logic Apps documentation : Microsoft Docs](https://docs.microsoft.com/en-us/azure/logic-apps/?wt.mc_id=servsept_devto-blog-chnoring)
* [Introduction to Azure Logic Apps - Learn : Microsoft Docs](https://docs.microsoft.com/en-us/learn/modules/intro-to-logic-apps/?wt.mc_id=servsept_devto-blog-chnoring)
* [Route and process data automatically using Logic Apps - Learn : Microsoft Docs](https://docs.microsoft.com/en-us/learn/modules/route-and-process-data-logic-apps/?wt.mc_id=servsept_devto-blog-chnoring)
* [Browse all - Learn : Microsoft Docs](https://docs.microsoft.com/en-us/learn/browse/?products=azure&resource_type=module&term=logic%20app&wt.mc_id=servsept_devto-blog-chnoring)
* [Connectors for Azure Logic Apps : Microsoft Docs](https://docs.microsoft.com/en-us/azure/connectors/apis-list?wt.mc_id=servsept_devto-blog-chnoring)
* [Create a custom connector in Azure Logic Apps : Microsoft Docs](https://docs.microsoft.com/en-us/connectors/custom-connectors/create-logic-apps-connector?wt.mc_id=servsept_devto-blog-chnoring)
* [Create your first function in Azure using Visual Studio Code : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-first-function-vs-code?wt.mc_id=servsept_devto-blog-chnoring)


## [How YOU can build your first Serverless Logic app, part II](https://dev.to/azure/how-you-can-build-your-first-logic-app-2o85)

**by: Chris Noring**

In this second part of a series on how to build a Logic app with an accompanying Serverless API, we delve deeper into the serverless function that will help us connect to the SQL Database we set up in part I.

Tags: SQL, Serverless, Azure Logic Apps, SQL Server

[Read More](https://dev.to/azure/how-you-can-build-your-first-logic-app-2o85)

Related Links:
* [Create your Azure free account today : Microsoft Azure](https://azure.microsoft.com/en-us/free/?wt.mc_id=servsept_devto-blog-chnoring)
* [Azure Logic Apps documentation : Microsoft Docs](https://docs.microsoft.com/en-us/azure/logic-apps/?wt.mc_id=servsept_devto-blog-chnoring)
* [Introduction to Azure Logic Apps - Learn : Microsoft Docs](https://docs.microsoft.com/en-us/learn/modules/intro-to-logic-apps/?wt.mc_id=servsept_devto-blog-chnoring)
* [Route and process data automatically using Logic Apps - Learn : Microsoft Docs](https://docs.microsoft.com/en-us/learn/modules/route-and-process-data-logic-apps/?wt.mc_id=servsept_devto-blog-chnoring)
* [Browse all - Learn : Microsoft Docs](https://docs.microsoft.com/en-us/learn/browse/?products=azure&resource_type=module&term=logic%20app&wt.mc_id=servsept_devto-blog-chnoring)
* [Connectors for Azure Logic Apps : Microsoft Docs](https://docs.microsoft.com/en-us/azure/connectors/apis-list?wt.mc_id=servsept_devto-blog-chnoring)
* [Create a custom connector in Azure Logic Apps : Microsoft Docs](https://docs.microsoft.com/en-us/connectors/custom-connectors/create-logic-apps-connector?wt.mc_id=servsept_devto-blog-chnoring)
* [Create your first function in Azure using Visual Studio Code : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-first-function-vs-code?wt.mc_id=servsept_devto-blog-chnoring)


## [How YOU can build a Serverless .Net Core API in no time, with bindings and CosmosDB](https://dev.to/azure/how-you-can-build-a-serverless-net-core-api-in-no-time-with-bindings-and-cosmosdb-2eg8)

**by: Chris Noring**

As part of #ServerlessSeptember, learn how you can build an Azure Function that connects to a CosmosDB database using C#. 

We'll cover what Serverless in, look at bindings and triggers and then build a project together to demostrate what you've learned.

Tags: .NET, .NET Core, C#, Serverless, .NET Core

[Read More](https://dev.to/azure/how-you-can-build-a-serverless-net-core-api-in-no-time-with-bindings-and-cosmosdb-2eg8)

Related Links:
* [Create your Azure free account today : Microsoft Azure](https://azure.microsoft.com/en-us/free/?wt.mc_id=servsept_devto-blog-chnoring)
* [Triggers and bindings in Azure Functions : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/functions-triggers-bindings?wt.mc_id=devto-blog-chnoring)
* [Azure Cosmos DB bindings for Functions 2.x : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-cosmosdb-v2#input---c-examples?wt.mc_id=devto-blog-chnoring)
* [Chain Azure Functions together by using input and output bindings - Learn : Microsoft Docs](https://docs.microsoft.com/en-us/learn/modules/chain-azure-functions-data-using-bindings/?wt.mc_id=devto-blog-chnoring)


## [9 Advanced Tips for Production Machine Learning](https://medium.com/microsoftazure/9-advanced-tips-for-production-machine-learning-6bbdebf49a6f)

**by: Ari  Bornstein**

Incorporating a new state of the art machine learning model into a production application is a rewarding yet often frustrating experience. The following post provides tips for production Machine Learning, with examples using the Azure Machine Learning Service.

Tags: Azure Machine Learning, Azure Storage, Azure Cognitive Services, Azure Event Hubs, Azure Data Explorer

[Read More](https://medium.com/microsoftazure/9-advanced-tips-for-production-machine-learning-6bbdebf49a6f)



## [Reproducible science: the good, the bad, the ugly and the untold](https://speakerdeck.com/trallard/reproducible-science-the-good-the-bad-the-ugly-and-the-untold)

**by: Tania Allard**

These are the slides from Tania's keynote at PyCon UK 2019. 
They focus on the importance of open source and scientific computing on research. They also highlights the main barriers to reproducibility and finish with a call for action to change the current culture in academic research.

Tags: Python

[Read More](https://speakerdeck.com/trallard/reproducible-science-the-good-the-bad-the-ugly-and-the-untold)



## [Kubernetes, are you ready for production?](https://dev.to/adipolak/kubernetes-are-you-ready-for-production-ba4)

**by: Adi Polak**

Adi's blog introduces her work for mthe DZone Kubernetes trend report, and opens a conversation on the use of Kubernetes in production.

Tags: Kubernetes

[Read More](https://dev.to/adipolak/kubernetes-are-you-ready-for-production-ba4)

Related Links:
* [Concepts - Kubernetes basics for Azure Kubernetes Services (AKS) : Microsoft Docs](https://docs.microsoft.com/en-us/azure/aks/concepts-clusters-workloads?WT.mc_id=devto-article-adpolak)


## [How to Change the Windows Terminal Background Image](https://www.thomasmaurer.ch/2019/09/how-to-change-the-windows-terminal-background-image/)

**by: Thomas Maurer**

Microsoft released a new Windows Terminal which is currently in preview. In this article, you learn how you can configure and customize the Windows Terminal background image.

Tags: Windows 10, WSL 2, Windows, Windows Terminal, WSL

[Read More](https://www.thomasmaurer.ch/2019/09/how-to-change-the-windows-terminal-background-image/)

Related Links:
* [Introducing Windows Terminal : Windows Command Line](https://devblogs.microsoft.com/commandline/introducing-windows-terminal?WT.mc_id=thomasmaurer-blog-thmaure)


## [Serverless September Weekly Content Wrap-Up - Week 2](https://dev.to/azure/serverless-september-weekly-content-wrap-up-week-2-20e3)

**by: Jan Schenk**

This is the weekly content wrap-up of  week two of #ServerlessSeptember. Here you'll find all the curated articles that were published by community and Cloud Advocates during the second week of Serverless September.

Tags: DevOps, Azure Functions

[Read More](https://dev.to/azure/serverless-september-weekly-content-wrap-up-week-2-20e3)



## [Serverless September Content Collection](https://dev.to/azure/serverless-september-content-collection-2fhb)

**by: Jan Schenk**

This is the full daily updated content collection of #ServerlessSeptember. Come back here to never miss a piece of content from the Cloud Advocacy curated articles during the month of September 2019. Awesome content contributions come from the serverless community and Cloud Advocates, daily.

Tags: Azure Functions

[Read More](https://dev.to/azure/serverless-september-content-collection-2fhb)



## [A DevOps Process for Deploying R to Production](https://blog.revolutionanalytics.com/2019/09/devops-and-r.html)

**by: David Smith**

In this talk, David shares his experience deploying R-based applications using Azure Pipelines and Azure Machine Learning Service.

Tags: Azure Machine Learning, Azure Pipelines, R

[Read More](https://blog.revolutionanalytics.com/2019/09/devops-and-r.html)



## [La révolution numérique](https://speakerdeck.com/cmaneu/diginova-2019-keynote)

**by: Christopher Maneu**

This presentation was delivered as the opening keynote of the Diginova conference. It presents the digital revolution through the tools currently available and the possibilities they generate and tackles topics such as the tech adoption, the tech capability a trust regarding AI and network security.

[Read More](https://speakerdeck.com/cmaneu/diginova-2019-keynote)



## [L'agilité : Du code aux organisations](https://speakerdeck.com/cmaneu/diginova-2019-agilite-organisations)

**by: Christopher Maneu**

This presentation shows how to apply agile principles in companies, in other domains than product developement, such as HR and Management.

[Read More](https://speakerdeck.com/cmaneu/diginova-2019-agilite-organisations)



## [How to develop a Kafka Streams application for data processing and deploy it to Kubernetes](https://dev.to/azure/learn-how-to-develop-a-kafka-streams-application-for-data-processing-and-deploy-it-to-kubernetes-25li)

**by: Abhishek Gupta**

This tutorial will guide you through how to build a stateless stream processing application using the Kafka Streams library and run it in a Kubernetes cluster on Azure (AKS)

Tags: Kafka, Kubernetes, Azure Kubernetes Service

[Read More](https://dev.to/azure/learn-how-to-develop-a-kafka-streams-application-for-data-processing-and-deploy-it-to-kubernetes-25li)

Related Links:
* [Azure Kubernetes Service (AKS) Documentation - Tutorials, API Reference : Microsoft Docs](https://docs.microsoft.com/en-us/azure/aks/?WT.mc_id=devto-blog-abhishgu)
* [Azure Container Registry Documentation - Tutorials : Microsoft Docs](https://docs.microsoft.com/en-us/azure/container-registry/?WT.mc_id=devto-blog-abhishgu)
* [Install the Azure CLI : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu)
* [Azure Kubernetes Service (AKS) : Microsoft Azure](https://azure.microsoft.com/en-us/services/kubernetes-service/?WT.mc_id=devto-blog-abhishgu)
* [Kubernetes Learning Path](https://azure.microsoft.com/en-us/resources/kubernetes-learning-path/?WT.mc_id=devto-blog-abhishgu)
* [Best practices for Azure Kubernetes Service (AKS) : Microsoft Docs](https://docs.microsoft.com/en-us/azure/aks/best-practices?WT.mc_id=devto-blog-abhishgu)
* [Azure Container Registry – Docker Registry : Microsoft Azure](https://azure.microsoft.com/en-us/services/container-registry/?WT.mc_id=devto-blog-abhishgu)
* [az acr : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/acr?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-acr-create)
* [az aks : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/aks?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-aks-get-credentials)
* [az aks : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/aks?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-aks-show)
* [az acr : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/acr?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-acr-login)
* [az acr repository : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/acr/repository?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-acr-repository-list)
* [az account : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/account?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-account-set)
* [az role assignment : Microsoft Docs](https://docs.microsoft.com/en-us/cli/azure/role/assignment?view=azure-cli-latest&WT.mc_id=devto-blog-abhishgu#az-role-assignment-create)


## [Adopting a Programming Language](https://gist.github.com/rylev/baa3942b12c1e371df49809d5df6a212)

**by: Ryan Levick**

Ryan Levick authored this article on github Gist to dicuss how programming languages are adopted. He takes a closer look into how Rust is being adopted at Microsoft.

Tags: Agnostic, Rust

[Read More](https://gist.github.com/rylev/baa3942b12c1e371df49809d5df6a212)



## [Step-By-Step: Connect your AWS and Azure environments with a VPN tunnel - Updated](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Step-By-Step-Connect-your-AWS-and-Azure-environments-with-a-VPN/ba-p/339211)

**by: Pierre Roman**

In this article, Pierre Roman outlines a workaround to interconnect Azure and AWS virtual network over VPN to ensure secure communication in a multi-cloud environment. At present, there is no supported way of doing this. So check out this article that provides a simple way of achieving secured connectivity.

Tags: Infrastructure, Azure Virtual Network, azure

[Read More](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Step-By-Step-Connect-your-AWS-and-Azure-environments-with-a-VPN/ba-p/339211)

Related Links:
* [About VPN devices for cross-premises Azure connections : Microsoft Docs](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpn-devices?WT.mc_ID=ITOpstalk-Blog-pierrer)
* [VPN Gateway documentation : Microsoft Docs](https://docs.microsoft.com/en-us/azure/vpn-gateway/?WT.mc_ID=ITOpstalk-Blog-pierrer)


## [Connecting Azure Shell in the new Windows Terminal (Preview)](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Connecting-Azure-Shell-in-the-new-Windows-Terminal-Preview/ba-p/787623)

**by: Pierre Roman**

In this article, Pierre shares how one can enable the use of Azure Shell within the New Windows Terminal (preview).

Tags: Azure CLI

[Read More](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Connecting-Azure-Shell-in-the-new-Windows-Terminal-Preview/ba-p/787623)



## [DevOps Lab: Taking Advantage of the Azure DevOps Wiki as a Developer](https://channel9.msdn.com/Shows/DevOps-Lab/Taking-Advantage-of-the-Azure-DevOps-Wiki-as-a-Developer)

**by: Damian Brady**

Description
In this episode, Abel sits down with Dipendra Namdeo to talk more about the Azure DevOps Wiki.

As developers, we have special needs when it comes to wiki's and documentation. Specifically, we often have our documentation sit next to our source code in our repos, allowing us to version our documentation along with our source code. This developer-specific workflow is totally supported by Azure DevOps Wiki. Dipendra walks us through this developer focused workflow on this episode of DevOps Lab.

Tags: Azure DevOps Services

[Read More](https://channel9.msdn.com/Shows/DevOps-Lab/Taking-Advantage-of-the-Azure-DevOps-Wiki-as-a-Developer)

Related Links:
* [Wiki : Azure DevOps](https://azure.microsoft.com/en-us/services/devops/wiki/?WT.mc_id=devopslab-c9-dabrady)
* [Share information using READMEs or Wikis in Azure DevOps - Azure DevOps : Microsoft Docs](https://docs.microsoft.com/en-us/azure/devops/project/wiki/?toc=%2Fazure%2Fdevops%2Fproject%2Fwiki%2Ftoc.json&bc=%2Fazure%2Fdevops%2Fproject%2Fwiki%2Fbreadcrumb%2Ftoc.json&WT.mc_id=devopslab-c9-dabrady&view=azure-devops)
* [Create your Azure free account today : Microsoft Azure](https://azure.microsoft.com/en-us/free/?utm_source=channel9&utm_medium=descriptionlinks&utm_campaign=freeaccount)


## [How to enable Ping (ICMP echo) on an Azure VM](https://www.thomasmaurer.ch/2019/09/how-to-enable-ping-icmp-echo-on-an-azure-vm/)

**by: Thomas Maurer**

Microsoft Azure by default denies and blocks all public inbound traffic to an Azure virtual machine, and also includes ICMP traffic. This is a good thing since it improves security by reducing the attack surface. In certain cases you need to enable ping ICMP. 

In this blog post you learn how to enable ping (ICMP) on a public IP address of an Azure virtual machine (VM).

Tags: Windows Server, Azure PowerShell, Azure Virtual Machines, Azure Bastion, Internet Control Message Protocol (ICMP)

[Read More](https://www.thomasmaurer.ch/2019/09/how-to-enable-ping-icmp-echo-on-an-azure-vm/)

Related Links:
* [Windows Virtual Machines Overview - Azure : Microsoft Docs](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/overview?WT.mc_id=thomasmaurer-blog-thmaure)
* [Azure security groups overview : Microsoft Docs](https://docs.microsoft.com/en-us/azure/virtual-network/security-overview?WT.mc_id=thomasmaurer-blog-thmaure)


## [Inventory Dashboards Using the Power of Azure Resource Graph](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Inventory-Dashboards-Using-the-Power-of-Azure-Resource-Graph/ba-p/858729)

**by: Phoummala Schmitt **

In this blog post, Phoummala shows readers how to use Azure Resource graph explorer queries to create an inventory dashboard in Azure portal.

Tags: Azure Portal, Azure Resource Graph

[Read More](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Inventory-Dashboards-Using-the-Power-of-Azure-Resource-Graph/ba-p/858729)

Related Links:
* [Starter query samples - Azure Resource Graph : Microsoft Docs](https://docs.microsoft.com/en-us/azure/governance/resource-graph/samples/starter?WT.mc_id=itopstalk-blog-phschmit)
* [Advanced query samples - Azure Resource Graph : Microsoft Docs](https://docs.microsoft.com/en-us/azure/governance/resource-graph/samples/advanced?WT.mc_id=itopstalk-blog-phschmit)
* [Create and share Azure portal dashboards : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-portal/azure-portal-dashboards?WT.mc_id=itopstalk-blog-phschmit)
* [Overview of Azure Resource Graph - Azure Resource Graph : Microsoft Docs](https://docs.microsoft.com/en-us/azure/governance/resource-graph/overview?WT.mc_id=itopstalk-blog-phschmit)


## [Diving into Durable Entities with Azure Functions](https://dev.to/azure/diving-into-durable-entities-with-azure-functions-173e)

**by: Cecil Phillip**

On .NET, Chris Gillum and Sebastian Burckhardt sit down with Jeremy Likness to give us the rundown on Durable Entities, talking about the differences compared to the actor model,  invoking entities via HTTP, and more.

Dev.to article for serverless September that features our On .NET episode on Durable Entities for Azure Functions.

Tags: Azure Functions

[Read More](https://dev.to/azure/diving-into-durable-entities-with-azure-functions-173e)

Related Links:
* [Durable Functions 预览版功能 - Azure Functions : Microsoft Docs](https://docs.microsoft.com/zh-cn/azure/azure-functions/durable/durable-functions-preview)
* [Durable Functions Overview - Azure : Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-overview)


## [PowerShell Basics: How to Create an Azure AD App Registration](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/PowerShell-Basics-How-to-Create-an-Azure-AD-App-Registration/ba-p/811570)

**by: Anthony Bartolo**

Azure Active Directory (Azure AD) is Microsoft's fully managed multi-tenant identity and access capabilities for app service. More organizations are now harnessing the security capabilities of Azure AD into the apps they create for an additional layer of authentication. This post will cover how to register an app to Azure AD via PowerShell to take advantage of this.

Tags: PowerShell, Azure AD, Azure Key Vault

[Read More](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/PowerShell-Basics-How-to-Create-an-Azure-AD-App-Registration/ba-p/811570)

Related Links:
* [Create identity for Azure app in portal : Microsoft Docs](https://docs.microsoft.com/en-us/azure/active-directory/develop/howto-create-service-principal-portal?WT.mc_id=ITOPSTALK-blog-abartolo)
* [What is Azure Key Vault? : Microsoft Docs](https://docs.microsoft.com/en-us/azure/key-vault/basic-concepts?WT.mc_id=ITOPSTALK-blog-abartolo)
* [Azure Active Directory PowerShell for Graph: Version release history : Microsoft Docs](https://docs.microsoft.com/en-us/powershell/azure/active-directory/ad-pshell-v2-version-history?https://docs.microsoft.com/en-us/powershell/azure/active-directory/overview?WT.mc_id=ITOPSTALK-blog-abartolo&view=azureadps-2.0)


## [Step-By-Step: Managing Windows 10 with Administrative ADMX templates](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Step-By-Step-Managing-Windows-10-with-Administrative-ADMX/ba-p/842926)

**by: Anthony Bartolo**

Windows 10 Administrative templates, released back in August 2015, are offered as language-neutral .admx files and language-specific .adml files used by Group Policy administrators to configure the same set of policies by using two languages. There are over 190 different administration templates included with Windows 10 and additional .admx files that can be downloaded here: Windows 10 Administrative Templates Download.

Tags: Windows Server, Windows 10, Active Directory

[Read More](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Step-By-Step-Managing-Windows-10-with-Administrative-ADMX/ba-p/842926)



## [A Robot Poet Goes for a Walk in the Park](https://www.youtube.com/watch?v=swQ338aOGm0)

**by: Em Lazer-Walker**

Designing complex, dynamic systems that can produce interesting and aesthetically pleasing art is a very hard problem to solve, even when you're just talking about something as focused as a Twitter bot. What happens when you try to make procgen art that doesn't just exist on the Internet, but actually lives in and interacts with the real world?

Computational Flâneur is a generative site-specific poetry walk that came out of my research at the MIT Media Lab. As you wander through the Fort Mason Park in San Francisco, a poetry robot makes up and reads you poems based on where you walk. Walk by the bay, and you'll hear poems of the sea; walk by the cannons and you'll hear poems of war.

This talk will explore the design and development of Computational Flâneur. On a technical level, we'll discuss the neural network model that powers the piece's poetry generator, including a brief overview of common text generation tools and how this exact structure was chosen to create a specific "bot-like" aesthetic. We'll also discuss how it's seeded by various forms of smartphone sensor data like location and weather, what sorts of prototyping processes were needed to fine-tune it, and how to conceptually approach this sort of real-world procgen differently from normal procedural generation problems.

<iframe width="560" height="315" src="https://www.youtube.com/embed/swQ338aOGm0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



## [Introducing NoSQL Azure Table Storage for NestJS](https://trilon.io/blog/nestjs-nosql-azure-table-storage)

**by: Wassim Chegham**

This guest post explains how to add Azure Table Storage to NestJS applications in only a few minutes with the new @nestjs/azure-database library!

Tags: JavaScript, Node.js, Web Development, Enterprise Databases (SQL and NoSQL), Azure Table Storage

[Read More](https://trilon.io/blog/nestjs-nosql-azure-table-storage)

Related Links:
* [Introduction to Azure Storage - Cloud storage on Azure : Microsoft Docs](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction?WT.mc_id=trilon-blog-wachegha)
* [Create a storage account - Azure Storage : Microsoft Docs](https://docs.microsoft.com/en-us/azure/storage/common/storage-quickstart-create-account?tabs=azure-portal&WT.mc_id=trilon-blog-wachegha)
* [Table storage : Microsoft Azure](https://azure.microsoft.com/en-us/services/storage/tables/?WT.mc_id=trilon-blog-wachegha)


## [Learning Python from Scratch 009 - Loops and Control Statements](https://dev.to/azure/learning-python-from-scratch-loops-26mj)

**by: Brian Clark**

In this session, Cecil and Brian learned about Loops in Python. They compared for loops in JavaScript and Python to talk through the differences as well as write some example loops in Python. The next session they will start learning about Control Statements like "if", "else" and "elif" in Python.

Tags: Python

[Read More](https://dev.to/azure/learning-python-from-scratch-loops-26mj)

Related Links:
* [
        Python - Visual Studio Marketplace
    ](https://marketplace.visualstudio.com/items?itemName=ms-python.python&WT.mc_id=clarkio-blog-cxa)


## [Learning Python from Scratch 010 - Control Statements: "if" "else" "elif"](https://dev.to/azure/learning-python-from-scratch-if-else-elif-30nl)

**by: Brian Clark**

In this session, Cecil and Brian learned about control statements "if" "else" and "elif" in Python. They spent most of the time writing a coin flip program and improving it with things they learned on past episodes. The next session they will start learning about continuous loops and how to stop them in Python.

Tags: Python

[Read More](https://dev.to/azure/learning-python-from-scratch-if-else-elif-30nl)

Related Links:
* [
        Python - Visual Studio Marketplace
    ](https://marketplace.visualstudio.com/items?itemName=ms-python.python&WT.mc_id=pythonfromscratch-clarkio-cxa)

