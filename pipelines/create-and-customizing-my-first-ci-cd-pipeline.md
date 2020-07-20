create-and-customizing-my-first-ci-cd-pipeline.md


[VSTS is now Azure DevOps. What has changed and why?](https://www.dotnetcurry.com/devops/1473/vsts-azure-devops-change)

Abtract: Microsoft recently launched Azure DevOps (formerly known as VSTS) that comprises of 5 different services that span the breadth of the value chain of product development. This article dives into what is the Azure DevOps offering and how is Microsoft uses Azure DevOps to build its own products. 


DevOps brings together people, processes and technology, automating software delivery to provide continuous value to your users. In other words, it enables any developer to ship customer value faster, more reliably, and with better quality.

Editorial Note: If you are interested in a story of how 84,000+ Microsoft engineers moved to Visual Studio Team Services (VSTS) to create unparalleled value for their customers using DevOps, read Microsoft’s Devops story.
Azure DevOps

Azure DevOps (formerly known as VSTS) is everything you need to build your software product from beginning to end. Azure DevOps is a one stop shop that helps every developer on this planet to plan projects using Agile tools, manage code using Git, test the application, and deploy code using the best CI/CD system.

Azure DevOps comprises of 5 services that span the breadth of the development cycle. Let me delve deep into some of these services and then get to the why aspect of this change.


![repos](https://github.com/ezahr/fail-fast-and-cheap/blob/master/pictures/repos-logo.png)
Azure Repos provides you with UNLIMITED Git repos. That means you can create a project in Azure DevOps and create as many repositories as you need and collaborate with your team members to build code with pull requests and advanced file management.

Microsoft enhanced git to scale to enterprise needs and invested in GVFS (Git Virtual File Systems) - https://gvfs.io/. GVFS helps in managing massive enterprise scale repositories. The Windows code base which is nearly 400GB in size is hosted on Azure Repos. A simple git clone command on the windows repo with git would take 12+ hours; but with GVFS it takes around 4-5 minutes.
How we use it? In Azure DevOps, we use git in Azure Repos to maintain our code and use a combination of small commits, branch policies, PR reviews, and test with each check-in to ensure our code in master is always shippable. We work out of a single master, that helps us to eliminate merge debt. Considering that Azure DevOps has nearly 800 engineers, merge debt can be a potentially big problem. Using the pull requests acts as forcing factor to test and review our code, helping us to detect errors in the pipeline.
We run a bunch of tests with every merge to master thereby helping us ensure that master is pristine


![pipelins](https://github.com/ezahr/fail-fast-and-cheap/blob/master/pictures/pipelines-logo.png)

Azure pipelines allow you to build, test, and deploy with CI/CD that works with any language, platform, and cloud. You can use Azure Pipelines to connect to GitHub or any other Git provider and deploy continuously.


