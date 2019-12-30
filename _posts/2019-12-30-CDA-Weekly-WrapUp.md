---
layout: post
title: CDA Weekly Content Wrapup (Dec 30 2019)
subtitle: 
tags: [Python, Azure Notebooks, Azure Cognitive Services, Azure Cognitive Services Face API, Microsoft Face API, Azure Arc, Azure Lighthouse, Microservices, DevOps, Spring Boot, Red Hat OpenShift on Azure, Azure Functions, Java, Azure CosmosDB, Azure Analytics, Azure IoT Hub, Azure IoT Central, Mixed Reality, Azure Spatial Anchors, Serverless, Xamarin, Xamarin.Essentials, Programming General, APIs/API Development, Xamarin.Forms, azure, Kubernetes, Azure Kubernetes Service, Microsoft Blazor, .NET, .NET Core, C#, Github Actions, Azure Static Sites, Virtual Machine Platform, Azure Virtual Machines]
---

## [People Blending: Some Experiments with Face API and Generative Art](https://soshnikov.com/scienceart/peopleblending/)

**by: Dmitry Soshnikov**

(1) This is a code example that shows usage of Face API for a fun project of generating Science Art portraits using a technique I called "People Blending". This is a first sample in a series dedicated to using AI in Science Art.
This piece is in English, but I am planning to produce a version in Russian as well
(2) Azure / Jupyter Notebook. This code sample will be accompanied by a blog post, and will be followed by a series of blogs posts on similar topics (a column)
(3) This sample can be useful for different audiences: for people interested in science art it gives gentle introduction to cognitive services and Face API, and shows a technique they can explore and rely upon in their work. For general developers it shows that cognitive services can be used in unexpected ways, producing some fun result.

Tags: Python, Azure Notebooks, Azure Cognitive Services, Azure Cognitive Services (Face API), Microsoft Face API

[Read More](https://soshnikov.com/scienceart/peopleblending/)



## [Managing security with Azure Lighthouse and Azure Arc](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Managing-security-with-Azure-Lighthouse-and-Azure-Arc/ba-p/1032864)

**by: Sonia Cuff**

ITOpsTalk blog article for IT Operations on a scenario of how the Azure Lighthouse and Azure Arc products can monitor the security (Azure Policy compliance, Azure Security Centre and Secure Score) of multiple tenants and how adding Azure Arc to the mix then includes on-prem and other-Cloud resources in those management blades.  No video demo but lots of screenshots.

Tags: Azure Arc, Azure Lighthouse

[Read More](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Managing-security-with-Azure-Lighthouse-and-Azure-Arc/ba-p/1032864)



## [How to move to modernize the system](https://www.slideshare.net/tyoshio2002/sapporo-developer-festa-2019)

**by: Yoshio Terada**

Overview: In order to proceed to Microservices, Engineers need to understand the basic concept of when introduction of Microservices actually makes sense. I focused on  what kind of mind change is required to survive in current technology intense world and how kubernetes can help

Context: In Japan, not many companies and engineers can proceed to Microservices/Kubernetes. I explained what kind of improvements they need to proceed to Microservices/Kubernetes.

Tags: Microservices, DevOps

[Read More](https://www.slideshare.net/tyoshio2002/sapporo-developer-festa-2019)



## [Introduction and demonstration of Azure Spring Cloud](https://www.slideshare.net/tyoshio2002/jjug-ccc-2019-fall-azure-spring-cloud)

**by: Yoshio Terada**

1: Microsoft and Pivotal announce the new services as "Azure Spring Cloud" on Oct 2019.
   In my session, I explained about "Azure Spring Cloud"
2: Presentation and Demonstration Video
   https://www.youtube.com/watch?v=lxvTPMkqeo4 ,  https://github.com/yoshioterada/Azure-Spring-Cloud-with-MySQL-Sample

3. Azure Spring Cloud is the PaaS for Spring Cloud. And it is very useful tool for Spring Developers.
This is new feature and Japanese developers didn't know the tool. So I explained about the technology.

Tags: Spring Boot, Red Hat OpenShift on Azure, Azure Functions, Java

[Read More](https://www.slideshare.net/tyoshio2002/jjug-ccc-2019-fall-azure-spring-cloud)



## [Introduction of Azure RedHat OpenShift](https://www.slideshare.net/tyoshio2002/azure-redhat-openshift-red-hat-forum-2019)

**by: Yoshio Terada**

1: Microsoft and Red Hat announce the new services as "Azure RedHat OpenShift".
   In my session, I explained about "ARO"
2: Presentation and Demonstration Video
   https://www.youtube.com/watch?v=oz7I_BQuttU
3. ARO is the managed OpenShift on Azure. I explained about the good point of the ARO to Red Hat Customers.

Tags: Red Hat OpenShift on Azure

[Read More](https://www.slideshare.net/tyoshio2002/azure-redhat-openshift-red-hat-forum-2019)



## [Storing IoT data in a database](https://dev.to/azure/storing-iot-data-in-a-database-4257)

**by: Jim Bennett**

In this blog post Jim Bennett covers how to use stream analytics to store IoT data in cosmos db. This is a service that can be connected to any event stream, such as an IoT Hub, and take the live stream of data and do something with it, such as filter, manipulate and output to other systems.

Tags: Azure CosmosDB, Azure Analytics, Azure IoT Hub

[Read More](https://dev.to/azure/storing-iot-data-in-a-database-4257)



## [IoT Ugly Sweater](https://github.com/jimbobbennett/IoTUglySweater)

**by: Jim Bennett**

It's holiday season, and that time of year where Ugly Sweaters become the top fashion item. And the only thing better than an ugly sweater, is an IoT ugly sweater. 
This repo has all the instructions on how to build and power your own IoT ugly sweater using low priced hardware and the power of the cloud. The sweater will light up, with the lights controlled via the cloud - either from an online dashboard or by sending a tweet!

Tags: Azure IoT Central

[Read More](https://github.com/jimbobbennett/IoTUglySweater)



## [Developing Multi-Platform Mixed Reality Solutions](https://github.com/Yonet/MixedRealityUnitySamples)

**by: Aysegul Yonet**

This GitHub repo includes sample code and repository and workshop around  Developing Multi-Platform Mixed Reality Solutions. Along with presentation slides.

Tags: Azure Cognitive Services, Mixed Reality

[Read More](https://github.com/Yonet/MixedRealityUnitySamples)



## [Spotlight XR: Developing Multi Platform Mixed Reality Solutions](https://slides.com/aysegulyonet/spotlightxr2019)

**by: Aysegul Yonet**

Slides for FITC SpotlightXR 2019 conference.

Tags: Azure Spatial Anchors, Azure Cognitive Services, Mixed Reality

[Read More](https://slides.com/aysegulyonet/spotlightxr2019)



## [Announcing #25DaysOfServerless](https://dev.to/azure/introducing-25daysofserverless-an-azure-functions-challenge-6b5)

**by: Brandon Minnick**

Introduces #25DaysOfServerless to the .NET community on Dev.to

Tags: Serverless, Azure Functions

[Read More](https://dev.to/azure/introducing-25daysofserverless-an-azure-functions-challenge-6b5)



## [Xamarin: Efficiently using  a SQLIte Database](https://codetraveler.io/2019/11/26/efficiently-initializing-sqlite-database/)

**by: Brandon Minnick**

The most popular SQLite ORM for Xamarin is SQLite-net. This blog post shares recommendations for Xamarin developers to best use SQLite in their mobile apps.

Tags: Xamarin, Xamarin.Essentials

[Read More](https://codetraveler.io/2019/11/26/efficiently-initializing-sqlite-database/)



## [No Dogma Podcast #133 Brandon Minnick, Async Await – Common Mistakes, Part 1](https://nodogmapodcast.bryanhogan.net/133-brandon-minnick-async-await-common-mistakes-part-1/)

**by: Brandon Minnick**

A deep dive into async/await in .NET:
- How to make a synchronous method asynchronous
- Freeing the calling thread
- What the compiler does with async code
- Calling async from sync
- Don't use .Result() it's a blocking call
- .Result() throws an aggregate exception; use .GetAwaiter().GetResult().

Tags: Programming (General)

[Read More](https://nodogmapodcast.bryanhogan.net/133-brandon-minnick-async-await-common-mistakes-part-1/)



## [No Dogma Podcast #134 Brandon Minnick, Async Await – Common Mistakes, Part 2](https://nodogmapodcast.bryanhogan.net/134-brandon-minnick-async-await-common-mistakes-part-2/)

**by: Brandon Minnick**

Summary
Brandon Minnick of Microsoft continues with his list of common mistakes in async/await programming and suggested solutions.

Details
Don't return awaits (sometimes), ConfigureAwait(false), synchronization context, what about API applications with no UI, and .NET Core is different too. Do I need async if I my threadpool never runs out of threads, consider scaling in the future. New in .NET Core 3, ValueTask (if method has an await but might not use it), heaps and stacks, how to find Brandon.

Tags: Programming (General)

[Read More](https://nodogmapodcast.bryanhogan.net/134-brandon-minnick-async-await-common-mistakes-part-2/)



## [AsyncAwaitBestPractices v4.0.0-pre3](https://github.com/brminnick/AsyncAwaitBestPractices/releases/tag/v4.0.0-pre3)

**by: Brandon Minnick**

New In This Release:

Added Support for ValueTask in SafeFireAndForget
Added Support for ValueTask
Added IAsyncValueCommand : ICommand
Added AsyncValueCommand : IAsyncValueCommand
Added IAsyncValueCommand<T>; : ICommand
Added AsyncValueCommand<T>; : IAsyncValueCommand<T>
Added RaiseCanExecuteChanged to IAsyncCommand and IAsyncValueCommand

Tags: APIs/API Development

[Read More](https://github.com/brminnick/AsyncAwaitBestPractices/releases/tag/v4.0.0-pre3)



## [InvestmentDataSampleApp](https://github.com/brminnick/InvestmentDataSampleApp)

**by: Brandon Minnick**

This sample app demonstrates the following new features in Xamarin.Forms:

Xamarin.Forms.SwipeView
Xamarin.Forms.RefreshView
Xamarin.Forms.CollectionView
Xamarin.Forms.PlatformConfiguration.iOSSpecific.UIModalPresentationStyle.FormSheet

Tags: Xamarin.Forms, Xamarin

[Read More](https://github.com/brminnick/InvestmentDataSampleApp)



## [Deploying Java EE apps to Azure: Part 3](https://medium.com/microsoftazure/deploying-java-ee-apps-to-azure-part-3-772e717bc4d1)

**by: Abhishek Gupta**

This is the final blog in a series of posts that explore different options for running Java EE workloads on Azure. In this part, we will run the Java EE app on a Kubernetes cluster in Azure.

Tags: Java, azure

[Read More](https://medium.com/microsoftazure/deploying-java-ee-apps-to-azure-part-3-772e717bc4d1)



## [How to access your Kubernetes applications using Services](https://dev.to/azure/how-to-access-your-kubernetes-applications-using-services-5626)

**by: Abhishek Gupta**

Another part of the "Kubernetes in a Nutshell" blog series which dives into Kubernetes Services

Tags: Kubernetes, Azure Kubernetes Service

[Read More](https://dev.to/azure/how-to-access-your-kubernetes-applications-using-services-5626)



## [Can You Use Blazor for Only Part of an App?](https://www.aaron-powell.com/posts/2019-12-10-can-you-use-blazor-for-only-part-of-an-app/)

**by: Aaron Powell**

This blog post takes a look at how to host Blazor WASM applications within a larger application.

Tags: Microsoft Blazor

[Read More](https://www.aaron-powell.com/posts/2019-12-10-can-you-use-blazor-for-only-part-of-an-app/)



## [Optimising Our Blazor Search App](https://dev.to/dotnet/optimising-our-blazor-search-app-2m05)

**by: Aaron Powell**

Building on the last post about Blazor + Lucene.NET, this one looks at how to improve the index performance by pre-building it.

Tags: .NET, .NET Core, C#, Microsoft Blazor

[Read More](https://dev.to/dotnet/optimising-our-blazor-search-app-2m05)



## [Implementing GitHub Actions for an Azure Static Website](https://dev.to/azure/implementing-github-actions-for-an-azure-static-website-488h)

**by: Aaron Powell**

This blog is a walk through of using GitHub Actions to build a Hugo website and deploy it to Azure static websites, including updating Azure CDN.

Tags: Github Actions, Azure Static Sites

[Read More](https://dev.to/azure/implementing-github-actions-for-an-azure-static-website-488h)



## [Hyper-V for Developers on Windows 10](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Hyper-V-for-Developers-on-Windows-10/ba-p/1062570?WT.mc_id=twitter-social-thmaure)

**by: Thomas Maurer**

(1) Hyper-V is more known as a server virtualization technology; however, since Windows 8, it is also available in the client operating system. In Windows 10, Microsoft improved the experience drastically to make Hyper-V an excellent solution for developers and IT Pros.
(2) Blog
(3) Developers learn how they can use Hyper-V on Windows 10 for virtualization, app testing, Android development, and Containers.

Tags: Virtual Machine Platform, Azure Virtual Machines

[Read More](https://techcommunity.microsoft.com/t5/ITOps-Talk-Blog/Hyper-V-for-Developers-on-Windows-10/ba-p/1062570?WT.mc_id=twitter-social-thmaure)



## [Reflecting on 12 Months Submitting to Conferences](https://dev.to/aaronpowell/reflecting-on-12-months-submitting-to-conferences-2ddf)

**by: Aaron Powell**

This blog is based on some twitter discussions where I shared optics around the hit and miss of my year on submitting to conferences.

[Read More](https://dev.to/aaronpowell/reflecting-on-12-months-submitting-to-conferences-2ddf)


