- [Course Intro](#course-intro)
      - [Reading: Workbook](#reading-workbook)
      - [Cloud Architect Workbook](#cloud-architect-workbook)
  - [Intro: Defining a Case Study](#intro-defining-a-case-study)
    - [Defining Your Case Study](#defining-your-case-study)
    - [Module Overview](#module-overview)
    - [Requirements, Analysis & Design](#requirements-analysis--design)
    - [Activity Intro: Analyzing Your Case Study](#activity-intro-analyzing-your-case-study)
    - [Activity Review: Analyzing Your Case Study](#activity-review-analyzing-your-case-study)
    - [KPIs & SLIs](#kpis--slis)
    - [SLOs & SLAs](#slos--slas)
    - [Activity Intro: Defining SLIs & SLOs](#activity-intro-defining-slis--slos)
    - [Activity Review: Defining SLIs & SLOs](#activity-review-defining-slis--slos)
    - [Review](#review)
  - [Module Overview - Application Architecture & Microservice Design](#module-overview---application-architecture--microservice-design)
    - [Microservices](#microservices)
    - [Microservices Best Practices](#microservices-best-practices)
    - [Activity Intro - Designing Microservices for Your Application:](#activity-intro---designing-microservices-for-your-application)
    - [Activity Review - Designing Microservices for Your Application:](#activity-review---designing-microservices-for-your-application)
    - [REST](#rest)
    - [HTTP](#http)
    - [APIs](#apis)
    - [Activity Intro - Designing REST APIs](#activity-intro---designing-rest-apis)
    - [Activity Review - Designing REST APIs](#activity-review---designing-rest-apis)
    - [Review](#review-1)
  - [Module Overview: DevOps Automation](#module-overview-devops-automation)
    - [Continuous Integration Pipelines](#continuous-integration-pipelines)
    - [Infrastructure as Code](#infrastructure-as-code)
      - [Lab Intro - Building a DevOps Pipeline](#lab-intro---building-a-devops-pipeline)
      - [Lab Review - Building a DevOps Pipeline](#lab-review---building-a-devops-pipeline)
    - [Module Review](#module-review)
  - [Module Overview - Google Cloud Storage and Data Solutions](#module-overview---google-cloud-storage-and-data-solutions)
    - [Key Storage Characteristics](#key-storage-characteristics)
    - [Activity Intro: Defining Storage Characteristics](#activity-intro-defining-storage-characteristics)
    - [Activity Review: Defining Storage Characteristics](#activity-review-defining-storage-characteristics)
    - [Choosing Google Cloud Storage & Data Solutions](#choosing-google-cloud-storage--data-solutions)
    - [Activity Intro: Choosing Google Cloud Storage & Data Solutions](#activity-intro-choosing-google-cloud-storage--data-solutions)
    - [Activity Review: Choosing Google Cloud Storage & Data Solutions](#activity-review-choosing-google-cloud-storage--data-solutions)
    - [Review](#review-2)
  - [Module Intro: Designing Google Cloud Networks](#module-intro-designing-google-cloud-networks)
    - [Designing Google Cloud Networks](#designing-google-cloud-networks)
    - [Designing Google Cloud Load Balancers](#designing-google-cloud-load-balancers)
    - [Activity Intro: Defining Network Characteristics](#activity-intro-defining-network-characteristics)
    - [Activity Review: Defining Network Characteristics](#activity-review-defining-network-characteristics)
    - [Connecting Networks](#connecting-networks)
    - [Activity Intro: Diagramming Your Network](#activity-intro-diagramming-your-network)
    - [Activity Review: Diagramming Your Network](#activity-review-diagramming-your-network)
    - [Review](#review-3)
  - [Overview - Deploying Applications to Google Cloud](#overview---deploying-applications-to-google-cloud)
    - [Google Cloud Infrastructure as a Service](#google-cloud-infrastructure-as-a-service)
    - [Google Cloud Deployment Platforms](#google-cloud-deployment-platforms)
      - [Lab Intro: Deploying Apps to Google Cloud](#lab-intro-deploying-apps-to-google-cloud)
      - [Lab Review: Deploying Apps to Google Cloud](#lab-review-deploying-apps-to-google-cloud)
    - [Review](#review-4)
  - [Module Overview: Designing for Reliability](#module-overview-designing-for-reliability)
    - [Key Performance Metrics](#key-performance-metrics)
    - [Designing for Reliability](#designing-for-reliability)
    - [Activity Intro: Designing Reliable Scalable Applications](#activity-intro-designing-reliable-scalable-applications)
    - [Activity Review: Designing Reliable Scalable Applications](#activity-review-designing-reliable-scalable-applications)
    - [Disaster Planning](#disaster-planning)
    - [Activity Intro: Disaster Planning](#activity-intro-disaster-planning)
    - [Activity Review: Disaster Planning](#activity-review-disaster-planning)
    - [Review](#review-5)
  - [Module Overview: Security Concepts](#module-overview-security-concepts)
    - [Security Concepts](#security-concepts)
    - [Securing People](#securing-people)
    - [Securing Machine Access](#securing-machine-access)
    - [Network Security](#network-security)
    - [Encryption](#encryption)
    - [Activity Intro: Modeling Secure Google Cloud Services](#activity-intro-modeling-secure-google-cloud-services)
    - [Activity Review: Modeling Secure Google Cloud Services](#activity-review-modeling-secure-google-cloud-services)
    - [Review](#review-6)
  - [Module Overview: Managing Versions & Cost Control](#module-overview-managing-versions--cost-control)
    - [Managing Versions](#managing-versions)
    - [Cost Planning](#cost-planning)
    - [Monitoring Dashboards](#monitoring-dashboards)
    - [Activity Intro: Cost Estimating & Planning](#activity-intro-cost-estimating--planning)
    - [Activity Review: Cost Estimating & Planning](#activity-review-cost-estimating--planning)
      - [Lab Intro: Monitoring Applications in Google Cloud](#lab-intro-monitoring-applications-in-google-cloud)
      - [Lab Review: Monitoring Applications in Google Cloud](#lab-review-monitoring-applications-in-google-cloud)
    - [Module Review](#module-review-1)
    - [Reading: What's Next? Get Certified](#reading-whats-next-get-certified)
    - [Reading: Workbook Example Solution](#reading-workbook-example-solution)

# Course Intro

his course is about architecting, design, and process. A cloud architect's job is to determine which cloud services to use in order to most effectively implement the applications and services they are building.

This is not an easy job. That's right, many services seem interchangeable. In many cases, multiple different services would work for the same use case.

The intent of this course is to simulate the process you can use to design a system that will run on Google Cloud.

This course is not about implementing specific cloud features. It's about architecture, design, and process. We like to joke that the job of an architect is to draw rectangles and point arrows at them. Which to a certain extent is true, that is an important step in designing complex systems.

In this course, you will focus on that design and planning, specifically, you will work on architecting and designing a case study in this course. The starting point for any software development is to figure out what the software is supposed to do, who your users are, and why this is important. You will begin with this requirements gathering phase.

Once you understand your software's requirements and your users, you can start laying out the overall design. In software, this is a process of decomposition, breaking the big thing, your program, into smaller manageable units that you can start programming. In a modern cloud-based system, it is considered a best practice to break your application into microservices.

Microservices refers to an architectural style for developing applications. Microservices allow a large application to be decomposed into independent constituent parts, with each part having its own area of responsibility. To serve a single user or API request, a microservices based application can call many internal microservices to compose its response.

 The architecture and the course will be microservice based. This has a significant effect on the agility of the application in aspects such as development speed, deployment, and monitoring. We will consider the advantages and disadvantages of this architectural style.

 We'll also help you choose the best storage and deployment services using objective criteria. Choosing the right ones can be complicated. Do you want a relational database, a NoSQL database, or a data warehouse? You also need to consider your compute platform. Do you want to deploy your apps to virtual machines, a Kubernetes cluster or an automated platform like app engine?

 You will learn what the factors are and how to choose the right services for your various microservices. Google provides many services that you can use to make your applications reliable. Availability, durability, cost, and disaster recovery are all important considerations when designing systems. If you understand your requirements, you can choose the right Google Cloud services to meet your applications goals for reliability while optimizing costs.

 Now, there's a saying security is not icing on the cake, it is baked into the cake. Before implementing a system on Google Cloud, you should carefully consider its security requirements and use the appropriate security services.

 Security and computer systems is implemented in layers, Google Cloud handle some things for you. For example, Google secures the physical hardware that Google Cloud is running on. Google also provides many controls to help secure your applications and data.

 Security is a shared responsibility though. The way you configure your network, storage services, and machines will determine how your application is secured. When you design your case study, you will consider its security requirements and bake them into the design.

 At the end you will monitor your app to see whether you're meeting your service objectives. In Google Cloud, there are many services for monitoring your application.

 <br>

 <img src="../../assets/../google_devops_cert/assets/monitor_app.png" alt="app monitor" width="50%" height="50%">

 <br>

 These include dashboards, logs, error reporting and tracing. You start by defining your application requirements, as you develop your solution, you can use the monitoring tools to determine how successful you are at meeting your application goals.

 The Reliable Cloud Infrastructure Design and Process course is a part of the Cloud Infrastructure learning path. This path is designed for IT professionals who are responsible for implementing, deploying, migrating, and maintaining applications in the cloud. The prerequisite for this course is either the Architecting with Google Compute or Engine or the Architecting with Google Kubernetes Engine Course. In other words, this course is not intended to be your first exposure to Google Cloud.

 <br>

 <img src="../../assets/../google_devops_cert/assets/learning_path.png" alt="cloud learning path" width="50%" height="50%">

 <br>

 Now, the course consists of lectures, design activities, and hands-on labs. You should spend a significant amount of time on the design and architecture assignments we will give you. As with many situations, there will be no one right answer and typically different people come up with different solutions. Architecting systems is a matter of weighing the pros and cons of various solutions and trying to find the best solution given your requirements and constraints.

 Now, the more effort you put into these design activities, the more you will learn from this course. Besides this introduction module, there are nine modules in this course.

 First, you will analyze and design a case study application using a microservice architecture.

 Then, we will cover Google Cloud tools for DevOps and Automation and you will choose the appropriate storage services for your case study. After that, you will learn about network design for cloud and hybrid applications and learn how to choose the appropriate deployment service. We will finish by designing for reliability and security and by monitoring your application.

<br>

#### Reading: Workbook

Throughout this course you will work on design activities in the course???s workbook.You have three options for accessing the workbook:

1. [Google Slides](https://docs.google.com/presentation/d/13ZXquIwCqp9sp2I7eqbQecENH49vx1xvi-E2k1pHTCE/copy)
2. [Powerpoint](https://storage.cloud.google.com/cloud-training/archdp/v2.0/OnDemand/Workbook%20%7C%20Design%20%26%20Process.pptx)
3. [PDF](https://storage.googleapis.com/cloud-training/archdp/v2.0/OnDemand/Workbook%20%7C%20Design%20%26%20Process.pdf)

All of these formats have the exact same content but we recommend picking one for the entire course.

<br>

#### [Cloud Architect Workbook](../assets/CloudArchitectWorkbook_Design_Process.pdf)

<br>

## Intro: Defining a Case Study

Slides are great for explaining concepts. But let's start working on the design activity workbook of this course. You can find the full workbook in the resources section of this course.

In the first activity, you need to come up with a case study idea. Whatever your idea is, you don't want it to be too trivial. It should be complex enough idea that designing the solution will be challenging.

For example, you might want to design an online banking portal, a ride sharing application, or an online shopping site. These are all complex applications with many interesting design possibilities.

Now all of these examples have been designed before. Feel free to use your imagination to come up with something that hasn't been done before. You can use something that you might want to develop as part of your work. It's up to you.

As this course is recorded, we won't be able to provide you with specific feedback on your design.

Instead we will provide you with a sample solution for an online travel portal application for each design activity.

Now part A of this activity is to come up with an interesting case study. For part B, write a short description and list the main features and roles of some typical users of your application.

<br>

### Defining Your Case Study

In this first activity, you were asked to come up with a case study, write a short description, list some of its main features, and list some of the roles users would play while using the application.

To give you an idea of what to come up with, we'll go over our sample solution for an online travel portal application.

Let's call it Click Travel. Click Travel is a global travel agency that wants to build scalable e-commerce platform to serve a global customer base. Let's go over the main features.

Travelers can search and book travel like hotels, flights, trains, and cars. Pricing will be individualized based on the customer's preferences and demand.

There should be a strong social media integration with reviews, post, and analytics.

Suppliers like airlines and hotels can upload their inventory.

As for roles of typical users, we envision a customer, a traveler, an inventory supplier, and a manager.

I'm sure we could come up with more features and roles, but this gives us a good feel for the application we would like to build. Now we can get started working on more detailed requirements and a design.

<br>

### Module Overview

In this module, we focus on defining services. A new development begins with the planning and design phases.

These require information gathering, starting with business requirements. Once the requirements are defined, it is important to measure that they're providing business value. In this module, we will look at gathering requirements and then techniques from measuring the impact of these solutions.

Let's take a closer look at what we will cover.

In this module, you will learn to describe users of a system in terms of the roles and personas they take. These users will then help define and refine the qualitative requirements which will be captured in the a form of user stories.

These provide a context for the architectural design and subsequent technical decisions you will make as a cloud architect.

Example of business requirements include: accelerating the pace of software development, reducing capital expenditure, and reducing time to recover incidents.

The technical requirements of a systems are both the functional and non-functional features required.

To help identify the most important requirements and measure our impact, you will learn how to measure success using key performance indicators or KPIs.

We will also discuss the importance of using SMART criteria when defining KPIs. We'll finish by considering the most suitable service level objectives or SLOs, and service level indicators or SLIs, and from these service level agreements or SLAs.

<br>

### Requirements, Analysis & Design

Let's start talking about requirements, analysis, and design.

Useful questions to ask a Cloud architect to help build the requirements are who, what, why, when, and how.

The who is about determining not only the user of the system, but also the developers and stake holders. The aim is to build a full picture of who the system will affect both directly and indirectly.

The what is both simple and difficult, we need to establish the main areas of functionality required, but in a clear, unambiguous manner.

Why the system is needed, is a really important question. What is a problem the proposed system aims to address or solve? Without a clear understanding of the need, it is likely that extra requirements will be added.

The why will also potentially help in defining KPIs, and SLOs, and SLAs. When, helps determine a realistic timeline and can help contain the scope.

How, helps to determine a lot of the non-functional requirements. These could be, for instance, how many users the system needs to support concurrently? What does the average payload size of service requests? Are there latency requirements, etc?

They could be that the users will be located across the world or in a particular region only. All of these requirements are vital to capture, because they impact the potential solution you as a Cloud architect will provide.

In the previous design activity, you defined user roles for your application. Roles represent the goal of a user at some point and they enable the analysis of a requirement in a particular context. It is important to note that a role is not necessarily a person, it is an actor on the system and it could be another system such as a microservice client that is accessing another microservice.

The role should describe the user's objective when using the system. For example, the role of a shopper on an eCommerce application clearly defines what the user wants to do. There are many ways to determine the roles for the requirement you working on.

One process that works particularly well is, first brainstorm an initial set of roles. Write as many roles as you can think of, with each role being a single user. Now, organize this initial set. Here, you can identify overlapping roles and related roles, and group these together.

With the set of roles now grouped, consolidate the roles, the aim here is to consolidate and condense the roles to remove duplication.

Finally, refine the roles including internal and external roles, and the different usage patterns. Here, extra information can be provided, such as the user's level of expertise in the domain or the frequency of use of the proposed software. Following a simple process like this, provide structure and brings focus to the task.

<br>

<img src="../../assets/../google_devops_cert/assets/roles.png" alt="user roles" width="50%" height="50%">

<br>

Identifying user roles is a useful technique that's part of the requirements getting process. An additional technique, in particular for more important roles can be to create a persona for the role. A persona is an imaginary representations of a user role.

The aim of the persona is to help the architect and developers think about the characteristics of users by personalizing them. Often, a role has multiple personas.

Consider the example of requirements for a banking application. We can think in terms of users of the system and many requirements can be gathered this way. Using personas can provide further insights.

For example, Jocelyn is a person who's a busy working mom. Jocelyn wants to save time and money as well as perform these standard banking operations online and receive benefits such as cashback.

Using a persona helps build a fuller picture of the requirements.

For instance, Jocelyn's wanting to save time indicates that the task to be performed should possibly be automated, which affects latency hence service design. In this example, when a question rises from the architect or maybe a developer, they can often better answer that question by thinking, what would Jocelyn want here? Now, user stories describe one thing a user wants the system to do, they are written in a structured way typically using the form as a, type of user, I want to - do something so that I can get some benefit. Another commonly used form is given some context, when I do something, then this should happen.

So when writing stories, give each story a title that describes its purpose as a starting point, follow this with a concise, one-sentence description of the story that follows one of the forms just described. This form describes the user role, what they want to do and why they want to do it.

As an example, consider a banking system and a story to determine the available balance of a bank account. The title of the story could be `balance inquiry`. Then following the template we described the story as an account holder, I want to check my available balance at any time of day, so I am sure not to overdraw my account.

This explains the role, what they want to do and why they want to do it. User stories provide a clear and simple way of agreeing to requirements with a customer/end-user. The INVEST criteria can be used to evaluate good user stories. Let me go through each letter of these criteria.

- Independent, a story should be independent to prevent problems with prioritization and planning.
- Negotiable, they are not written contracts, but are used to stimulate discussion between customer and developers until there is a clear agreement, they add collaboration.
- Valuable, story should provide value to users. Think about outcomes and impact, not outputs and deliverables.
- Estimatable, the story must be estimatable. If it is not, it often indicates missing details or the story is too large.
- Small, good stories should be small, this helps keep scope small and therefore less ambiguous and supports fast feedback from users.
- Testable, stories must be testable so that developers can verify that the story has been implemented correctly and validate when requirement has been met slash/is done.

<br>

### Activity Intro: Analyzing Your Case Study

In this design activity, you're going to work on activities two A and two B of the design workbook. In the first activity, you defined roles. For an online store, examples of roles might be account holder, shopper, customer, administrator and seller. Roles are played by people and different people playing the same role might be significantly different. In activity two A, you will write some user personas. Personas are stories that describe typical people playing some role while using your system. It's important to understand your users when designing a system. So it's important to write some personas. Now, in a real project, you should find some users and interview them. For this course, feel free to use your imagination. In activity two B, you will write some user stories. User stories are short one sentence descriptions of your applications features.

In the first activity, you listed some features. Now, turn those features into user stories, write your user stories in the form as A and then you fill in the role. I want to and then tell me your goal, so that and you say why this is important to you. For example, an online store might have a feature to search for products. The user story might be, as a shopper, I want to be able to quickly search for products by name keyword or category so I can quickly find information about products I want to purchase.

Here's an example persona.

Jocelyn is a busy working mom who wants to access MegaCorp Bank to check her account balances and make sure that there are enough funds to pay for her kids' music and sports lessons.

She also uses the website to automate payments of bills and see her credit account balances.

Jocelyn wants to save time and money. She wants a credit card that gives her cash back.

Here's an example user story for a feature, balance inquiry.

As a checking account holder, I want to check my available balance at any time of day so that I'm sure not to overdraw my account.

<br>

### Activity Review: Analyzing Your Case Study

In this second activity, you are asked to write personas and user stories for your case study. Here are a couple of examples of personas for our online travel portal.

Karen is a busy businesswoman who likes to take luxury weekend breaks, often booked at the last minute. A typical booking comprises of a hotel and flight. Recommendations play a major role in the choice Karen makes, as does customer feedback. Karen likes to perform all operations from her phone.

Andrew is a student who likes to travel home to visit parents and also takes vacations twice yearly. His primary concern is cost, and he will always book the lowest price travel regardless of convenience. Andrew has no loyalty, and will use whichever retailer can provide the best deal.

Here are a couple of examples of user stories for our online travel portal.

For the Search for Flight and Hotel feature, I could write:
> as a traveler, I want to search for a flight-hotel combination to a destination on dates of my choice so that I can find the best price.

For the Supply Hotel Inventory feature, I could write:
> as a hotel operator, I want to bulk supply hotel inventory so that ClickTravel can sell it on my behalf.

For the Analyze Sales Performance feature, I could write:
> as a ClickTravel manager, I want to analyze the sales performance data of all of our suppliers so that I can identify poor performers and help them improve.

<br>

### KPIs & SLIs

With a set of requirements in place, we will now move on to consider how to measure whether the technical and business requirements have been met.

<br>

<img src="../../assets/../google_devops_cert/assets/quantitative_requirements.png" alt="quantitative requirements" width="50%" height="50%">

<br>

To manage a service well it is important to understand which behaviors matter and how to measure and evaluate these behaviors. These must always be considered in the context of the constraints which are usually time, funding, and people. Then we consider what can be achieved. The type of system being evaluated determines the data that can be measured, for example, for user-facing systems was a request responded to which refers to availability. How long did it take to respond, which refers to latency. How many requests can be handled, which refers to throughput. For data storage systems, how long does it take to read and write data? That's latency. Is the data there when we need it, that's availability. If there is a failure to we lose any data, that's durability.

The key to all of these items is it the questions can be answered with data gathered from the services.

Business decision makers want to measure the value of projects. This enables them to better support the most valuable projects and not waste resources on those that are not beneficial. A common way to measure success is to use KPIs, KPIs can be categorized as Business KPIs and Technical KPIs.

<br>

<img src="../../assets/../google_devops_cert/assets/kpis.png" alt="KPIs" width="50%" height="50%">

<br>

Business KPIs are a formal way of measuring what the business values such as ROI in relation to a project or service. Others include, earnings before interest and taxes or impact on users, such as customer churn or maybe employer turnover.

Technical or software KPIs can consider aspects such as how effective the software is through page views, user registration, and number of checkouts. These KPIs should also be closely aligned with business objectives. As an architect, it is important that you understand how the business measures success of the systems that you design. Now, a KPI is not the same thing as a goal or objective. The goal is the outcome or result you want to achieve, the KPI is a metric that indicates whether you are on track to achieve the goal.

To be the most effective, KPIs need an accompanying goal. This should be the starting point in defining KPIs, then for each goal define the KPIs that will allow you to monitor and measure progress. For each KPI, define targets for what success looks like. Monitoring KPIs against goals is important to achieving success and allows readjustment based on feedback.

As an example, a goal may be to increase turnover for an online store and an associated KPI maybe the percentage of conversions on the website.

<br>

<img src="../../assets/../google_devops_cert/assets/effective_kpi.png" alt="effective KPIS" width="50%" height="50%">

<br>

For KPIs to be effective, they must be specific rather than general.

For example, user friendly is not specific, it's very subjective. Section 508 Accessible is much more specific.

Measurable is vital because monitoring the KPIs indicates whether you're moving toward or away from your goal.

Being achievable is also important, for example, expecting 100% conversions on a website is not achievable.

Relevant is absolutely vital, without a relevant KPI the goal probably will not be met. In our example of increasing turnover, we're improving the conversion rate as subsequent increase in turnover should be achievable assuming a similar number of users.

Time-bound helps with measuring the KPI. Some KPIs are more sensitive to time, for example, is availability per day, per month or per year.

So to summarize, KPIs are used to measure success or progress toward a goal.

Let's introduce service level terminology. To provide a given level of service to customers, it is important to define service level indicators or SLIs, objectives or SLOs and agreements or SLAs. These are measurements that describe basic properties of the metrics to measure. The values those metrics should read and how to react if the metrics cannot be met.

Service level indicator is a quantitative measure of some aspect of the level of service being provided. Examples include throughput, latency, and error rate.

Service level objective is an agreed upon target or range of values for a service level that is measured by an SLI.

<br>

<img src="../../assets/../google_devops_cert/assets/kpi_slo_sla.png" alt="" width="50%" height="50%">

<br>

It is normally stated in the form of SLI is smaller than equal to target or lower bound, which is smaller than, equal to SLI, smaller than, equal to upper bound. An example of an SLO is that an average latency of HTTP requests for our service should be less than 100 milliseconds.

Service level agreement is an agreement between a service provider and a consumer. They define responsibilities for delivering a service and consequences when these responsibilities are not met. The SLA is a more restrictive version of the SLO. We want to architect a solution and maintain an agreed SLO, so that we provide ourselves spare capacity against the SLA.

<br>

<img src="../../assets/../google_devops_cert/assets/sli.png" alt="SLI" width="50%" height="50%">

<br>

Understanding what users want from a service will help inform the selection of indicators. The indicators must be measurable, for example, fast response time is not measurable. Whereas HTTP GET requests that respond within 400 milliseconds aggregated per minute is clearly measurable. Similarly, highly available is not measurable but percentage of successful requests over all request aggregated per minute is measurable. Not only must indicators be measurable but the way they are aggregated needs careful consideration.

For example, consider requests per second to a service, how is the value calculated? By measurements obtained once per second or by averaging request over a minute? The once per second measurement may hide high requests rates that occur in bursts of a few seconds.

For example, consider a service that receives 1,000 requests per second on even-numbered seconds and 0 requests on odd-numbered seconds. The average requests per second could be reported over a minute as 500. However, the reality is that the load at times is twice as large as the average. Similar averages can mask user experience when used for metrics like latency. It can mask the request the take a lot longer to respond than the average.

It is better to use percentiles for such metrics, where a high order percentile, such as 99% shows worst-case values. While the 50th percentile would indicate a typical case.

<br>

### SLOs & SLAs

The relevancy of SLOs is vital. You want objectives that help or improve the user experience.

<br>

<img src="../../assets/../google_devops_cert/assets/slo.png" alt="SLO" width="50%" height="50%">

<br>

It is easy to define a SLOs based around what is easy to measure rather than what is useful. For clarity, SLOs should specify how they are measured and the conditions when they are valid.

Consider availability as measured with an uptime check over ten seconds aggregated per minute. It is unrealistic as well as undesirable to have SLOs with a 100% target. Such a target results in expensive, overly conservative solutions, that are still unlikely to reach the SLO. It is better to track the rate at which SLOs are missed and work to improve this. In many cases 99% may be good enough availability and be far easier to achieve as well as engineer. It is also highly likely to be much more cost-effective to run.

The use case needs to be considered also.

For example, if a HTTP service for photo uploads requires 99% of uploads to be complete within 100 milliseconds aggregated per minute, this may be unrealistic or overkill if the majority of users are using mobile phones. In such a case, an SLO of 80% is much more achievable and good enough.

It is often okay to specify multiple SLOs.

Consider the following, 99% of HTTP get calls will complete in less than 100 milliseconds. This is a valid SLO, but it may be the case that the shape of the performance curve is important. In this case, the SLO could be written as follows. 90% of HTTP get calls will complete in less than 50 milliseconds, 99% of HTTP get calls will complete in less than 100 milliseconds. And 99.9% of HTTP get calls will complete and less than 500 milliseconds.

Selecting SLOs has both product and business implications. Often trade-offs need to be made based on constraints such as staff, time to market and funding. As the slide states, the aim is to keep users happy, not to have an SLO that requires heroic efforts to maintain.

<br>

<img src="../../assets/../google_devops_cert/assets/slo_tips.png" alt="tips for SLOs" width="50%" height="50%">

<br>

Let me give you some tips on selecting SLOs.

Do not make them too high. It is better to have lower SLOs to begin with and tighten them over time as you learn about the system, instead of defining those that are unattainable and require a significant effort and cost try and achieve. Keep them simple. More complex SLOs can obscure important changes in performance.

Avoid absolute values. To have a SLO that states 100% availability is unrealistic. Such an SLO increases the time to build, complexity, and cost to operate. And in most cases is highly unlikely to be required.

Minimize SLOs. A common mistake is to have too many SLOs. The recommendation is to have just enough SLOs to give coverage of the key system attributes. In summary, good SLOs should reflect what the users care about. They work as a forcing function for development teams. A poor SLO will result in a significant amount of wasted work if it is too ambitious or a poor product if it is to relaxed.

An SLA is a business contract between the service provider and the customer.

<br>

<img src="../../assets/../google_devops_cert/assets/sla.png" alt="SLA" width="50%" height="50%">

<br>

A penalty will apply if the service provider does not maintain the levels agreed on. Not every service has an SLA, but all services should have a SLOs. As with SLO, it is better to be conservative with SLAs because it is too difficult to change or remove SLAs that offer little value or cause a large amount of work.

In addition, because they can have a financial implication through compensation to the customer, setting them too high can result in unnecessary compensation being paid. To provide protection and some level of safety, an SLA should have a threshold that is lower than the SLO. This should always be the case.

<br>

<img src="../../assets/../google_devops_cert/assets/slo_sli_sla_example.png" alt="Example: SLO, SLI, SLA" width="50%" height="50%">

<br>

Let's consider an example of a service, An SLI, SLO and SLAs for the service. The service is an HTTP endpoint accessed using HTTP get.

The SLI is the end-to-end latency of successful HTTP responses. That is HTTP-200. These are averaged over one minute.

The SLO has been agreed that the latency of 99% of the responses must be less than or equal to 200 milliseconds.

The SLA is set that the user is compensated if the 99th percentile latency exceeds 300 milliseconds. The SLA has clearly built a buffer over the SLO, which means that even if the SLO is exceeded there is some capacity before the SLA is broken.

**This is the wanted position in the relationship between SLO and SLA.**

<br>

### Activity Intro: Defining SLIs & SLOs

In this design activity, you will define SLIs and SLOs for your case study. Let's say you wanted to write an SLI and SLO for an online shopping application related to availability.

The SLO is what you want to measure. For example, you might want to measure the fraction of successful versus unsuccessful HTTP responses from an API endpoint aggregated per day. The SLO is the target you're trying to achieve.

For your online stores, search for product service that might be 99.95 percent.

Here are a couple of more examples for an imaginary online bank.

The SLI defines what you want to measure, like the fraction of 200 versus 500 HTTP responses from an API endpoint, or the time to last byte GET request measured every 10 seconds aggregated per minute.

The SLO defines the target you want to achieve, like 99.95 percent availability, or that 95 percent of request will complete in under 300 milliseconds.

<br>

### Activity Review: Defining SLIs & SLOs

In this third activity, you are asked to write SLIs and SLOs for your case study. Here's some example SLOs and SLIs for our travel portal application. Notice that the SLI describes what we're going to measure and how. For example, fraction of 200 vs 500 HTTP responses from API endpoint measured per month.

<br>

<img src="../../assets/../google_devops_cert/assets/example_slo_sli.png" alt="Example: SLOs & SLIs" width="50%" height="50%">

<br>

This example is a way of measuring availability.

The SLO represents the goal we're trying to achieve for a given SLI. For example, available 99.95% of the time. Feel free to pause the video to read through the other SLOs and SLIs for each user story.

<br>

### Review

In this module, we learned about qualitative and quantitative requirements.

Qualitative requirements are things that user care about like features. We can express qualitative requirements in the form of user stories. In order to understand our users better, we should write personas.

Quantitative requirements are things we can measure. We can express them as key performance indicators, or KPIs. KPIs and software are things like user sign-ups, clicks, processions, completed purchases, or customer retention. We can also express quantitative requirements as SLOs and SLIs.

These are lower level metrics, things like latency, availability, or response time.

<br>

## Module Overview - Application Architecture & Microservice Design

In this module, we introduce Application Architecture and Microservice design.

Specifically, you will learn about microservice architectures and how to decompose monolithic applications into microservices. The benefits of a microservice architecture for Cloud-native applications is discussed and contrasted with a monolith.

The challenges of decomposing applications into microservices with clear boundaries to support independently deployable units are investigated.

You will learn how to architect for some of the major technical challenges of microservices architecture, such as state management, reliability, and scalability.

Once a Cloud-native microservice architecture has been chosen, the best practices for development and deployment are introduced based around the widely recognized 12-factor best practices.

At the end of the module, we will go over a core component of the microservices architecture, which is the design of consistent, loosely coupled service interfaces.

<br>

### Microservices

<br>

<img src="../../assets/../google_devops_cert/assets/microservices.png" alt="microservices" width="50%" height="50%">

<br>

Let's begin by looking at microservices in more details. Microservices divide a large program into a number of smaller independent services, as shown on the right. Unlike a monolithic application which implements all features in a single codebase with a database for all data, as shown on the left. Microservices are the current industry trends. However, it's important to ensure that there is a good reason to select this architecture.

The primary reason is to enable teams to work independently and delivered through to production at their own cadence, this supports scaling the organization, adding more teams increases speed. There's also the additional benefit of being able to scale the microservices independently based on their requirements.

Architecturally, an application designed as a monolith or around microservices should be composed of modular components with clearly defined boundaries. With the monolith all the components are packaged at deployment time and deployed together. With microservices, the individual components are deployable.

Google Cloud provides several compute services that facilitate deploying microservices. These include App Engine, Cloud Run, GKE, and Cloud Functions.

Each offers different level of granularity and control and will be discussed later in the course.

To achieve independence on services, each service should have its own datastore. This lets the best datastore solution for that service to be selected and also keeps the services independent. We do not want to introduce coupling between services through a datastore.

A properly designed microservice architecture can help achieve the following goals:

- Define strong contracts between the various microservices.
- Allow for independent deployment cycles, including rollback.
- Facilitate concurrent AB release testing on subsystems.
- Minimize test automation and quality assurance overhead.
- Improve clarity of logging and monitoring.
- Provide fine grained cost accounting.
- Increase overall application scalability and reliability through scaling smaller units.

However, the advantages must be balanced with the challenges this architectural style introduces.

<br>

<img src="../../assets/../google_devops_cert/assets/pros_cons_microservices.png" alt="Microservice pros and cons" width="50%" height="50%">

<br>

Some of these challenges include:

It can be difficult to define clear boundaries between services to support independent development and deployment.

Increased complexity of infrastructure with distributed services having more points of failure.

The increased latency introduced by network services and the need to build in resilience to handle possible failures and delays.

Due to the networking involved, there is a need to provide security for service to service communication, which increases complexity of infrastructure.

Strong requirement to manage in version service interfaces with independent deployable services, the need to maintain backward compatibility increases.

<br>

<img src="../../assets/../google_devops_cert/assets/decompose_apps.png" alt="decomposing apps" width="50%" height="50%">

<br>

Decomposing applications into microservices is one of the biggest technical challenges of application design. Here are techniques like domains driven design are extremely useful in identifying logical functional groupings. The first step is to decompose the application by feature or functional groupings to minimize dependencies.

Consider, for example, an online retail application. Logical functional groupings could be product management, reviews, accounts, and orders. These groupings then for many applications which exposes an API, each of these mini applications will be implemented by potentially multiple microservices internally.

Internally, these microservices are then organized by architectural layer and each should be independently deployable and scalable. Any analysis will also identify shared services such as authentication, which are then isolated and deployed separately from the mini applications.

When you are designing microservices, services that do not maintain state but obtain their state from the environment or stateless services are easier to manage.

<br>

<img src="../../assets/../google_devops_cert/assets/stateful_services.png" alt="stateful services" width="50%" height="50%">

<br>

That is, they are easy to scale, to administer and to migrate to new versions because of their lack of state. However, it is generally not possible to avoid using stateful services at some point in a microservice based application. It is therefore important to understand the implications of having stateful services on the architecture of the system. These include introducing significant challenges in the ability to scale and upgrade the services.

Being aware of how state will be managed is important in the very early stages of microservice application design. Let me introduce some suggestions and best practices on how this can be achieved.

<br>

<img src="../../assets/../google_devops_cert/assets/shared_state.png" alt="" width="50%" height="50%">

<br>

In memory, shared state has implications that impact and negate many of the benefits of a microservice architecture. The autoscaling potential of individual microservices is hindered because subsequent client requests have to be sent to the same server that the initial request was made to.

In addition, this requires configuration of the load balancers to use sticky sessions, which in Google Cloud is referred to as session affinity. A recognized best practice for designing stateful services is to use backend storage service that are shared by frontend stateless services.

For example, for persistent state, the Google Cloud managed to data services such as Firestore or Cloud SQL maybe suitable then to improve the speed of data access, the data can be cached. The memory store which is a highly available Redis based service, is ideal for this.

<br>

<img src="../../assets/../google_devops_cert/assets/store_state.png" alt="stored state" width="50%" height="50%">

<br>

This diagram displays a general solution that shows the separation of the frontend and backend processing stages. A load balancer distributes the load between the backend and frontend services. This allows the backend to scale if it needs to keep up with the demand from the frontend.

In addition, the stateful services or servers are also isolated. The stateful services can make use of the persistent storage services and caching, as previously discussed. This layout allows a large part of the application to make use of the scalability and fault tolerance of Google Cloud Services as stateless services. By isolation of the stateful servers and services, the challenges of Scaling and upgrading are limited to a subset of the overall set of services.

<br>

### Microservices Best Practices

Let's discuss microservice best practices. The 12-factor app is a set of best practices for building web or software as a service applications. The 12-factor design helps you decouple components of the application so that each component can be deployed to the cloud using continuous deployment and scaled up or down seamlessly.

<br>

<img src="../assets/12_factor_app.png" alt="12 factor app design" width="50%" height="50%">

<br>

The design principles also help maximize portability to different environments. Because the factors are independent of any programming language or software stack, 12-factor design can be applied to a wide variety of applications.

Let's take a look at these best practices.

<br>

<img src="../assets/12_factor_1.png" alt="12 factors" width="50%" height="50%">

<br>

The first factor is codebase. The codebase should be tracked in a version control such as Git. Cloud Source repositories provide fully featured private repositories.

The second factor is dependencies. There are two main considerations when it comes to dependencies for 12-factor apps, dependency declaration and dependency isolation. Dependencies should be declared explicitly and stored in version control. Dependency tracking is performed by language specific tools such as Maven for Java and Pip for Python. An application and its dependencies can be isolated by packaging them into a container. Container registry can be used to store the images and provide fine-grained access control.

The third factor is configuration. Every application has a configuration for different environments like test, production and development. This configuration should be external to the code and usually kept in environment variables for deployment flexibility.

Fourth factor is backing services. Every backing service such as database, cache or message service should be accessed via URLs and set by configuration. The backing services act as abstractions for the underlying resource. The aim is to be able to swap one backing service for a different implementation easily.

<br>

<img src="../assets/12_factors_2.png" alt="12 factors cont." width="50%" height="50%">

<br>

The fifth factor is build, release, run. The software deployment process should be broken into three distinct stages, built, release and run. Each state should result in an artifact that's uniquely identifiable. Build will create a deployment package from the source code. Every deployment package should be linked to a specific release that's a result of combining a runtime environment configuration with the build. This allows easy road maps and a visible audit trail of the history of every production deployment. The run stage then simply executes the application.

The sixth factor is processes. Applications run as one or more stateless processes. If state is required, the technique discussed earlier in this module for State Management should be used. For instance, each service should have its own data store and cache using for example Memorystore to cache and share common data between services used.

The seventh factor is port binding. Services should be exposed using a port number. The applications bundle the web server as part of the application and do not require a separate server like Apache. In Google Cloud, such apps can be deployed on platform services such as Compute Engine, GKE, App Engine or Cloud Run.

The eighth factor is concurrency. The application should be able to scale out by starting new processes and scale back in as needed to meet demand or load.

<br>

<img src="../assets/12_factor_3.png" alt="12 factors cont." width="50%" height="50%">

<br>

The ninth factor is disposability, applications should be written to be more reliable than the underlying infrastructure they run on. This means they should be able to handle temporary failures in the underlying infrastructure and gracefully shut down and restart quickly. Applications should also be able to scale up and down quickly, acquiring and releasing resources as needed.

The tenth factor is development production parity. The aim should be to have the same environments used in development and test or staging as are used in production. The infrastructure as code and Docker containers make this easier. Environments can be rapidly and consistently provisioned and configured via environment variables. Google Cloud provides several tools that can be used to build workflows that keep the environments consistent. These tools include Cloud Source repositories, Cloud Storage, Container Registry and Cloud Deployment Manager. Deployment Manager allows the writing of templates to create deployments using Google Cloud services.

The 11th factor is logs, logs provide an of the health of your applications. It's important to decouple the collection processing and analysis of logs from the core logic of your apps. Logging should be to standard output and aggregating into a single source. This is particularly useful when your apps require dynamic scaling and are running on public clouds because it eliminates the overhead of managing the storage location for logs. And the aggregation from distributed and often ephemeral VMs or containers. Google Cloud offers a suite of tools that helps with the collection, processing and structured analysis of logs.

The 12th factor is admin processes. These are usually one-off processes and should be decoupled from the application. These should be automated and repeatable, not manual processes. Depending on your deployment on Google Cloud, there are many options for this including cron jobs in GKE, Cloud tasks on App Engine and Cloud Scheduler.

<br>

### Activity Intro - Designing Microservices for Your Application:

In this design activity, you're going to work on Activity Four of the Design Workbook. You will design microservices for your application. The primary aim is to diagram the microservices required by your case study application. Some of the things to consider are the microservice boundaries and state management, as well as common services. Use the principle we have discussed in this module so far. Here's an example diagram for microservices for the website and the mobile phone application of an online banking service.

Draw a diagram similar to the one shown here for your case study.

<br>

### Activity Review - Designing Microservices for Your Application:

In this activity, you were asked to diagram your case study application using microservice style architecture.

The number of microservices appropriate for application and recognizing the microservice boundaries is not obvious.

Two programs might look similar, but their architecture might be considerably different based on the number of users, size of data, security and many other factors.

Fewer services might make deployment and communication between services easier, but also make development and adding new features harder. Having more smaller services makes each individual service easier to understand and implement, but may make the overall architecture of your program more complicated.

Like many things in life, you are looking for the right balance trading off one type of complexity for a different type, hoping to make the system overall as simple and as maintainable as possible. Here is a sample diagram depicting the microservices of our online travel portal.

I suppose we could lay this out in many different ways, there really isn't one and only right way to design an application.

Notice, we have separate services for a web and mobile UIs. There's a shared authentication service and we have microservices for search, orders, inventory, analytics, and reporting. Remember, each of these services will be deployed as a separate application.

Where possible, we want the stateless services, but the orders and inventory services will need databases, and the analytics service will provide a data warehouse. This might make a good starting point and we could adjust as needed when we start implementing the application.

<br>

### REST

Let's talk about the design of microservices based on rest and HTTP to achieve loosely coupled independent services.

<br>

<img src="../assets/loose_coupling.png" alt="loosely coupled" width="50%" height="50%">

<br>

One of the most important aspects of microservices based applications is the ability to deploy microservices completely independent of one another. To achieve this independence, each microservice must provide a versioned, well-defined contract to its clients, which are other microservices or applications.

Each service must not break these versioned contracts until it's known that no other microservice relies on a particular versioned contract. Remember that other microservices may need to roll back to a previous code version that requires a previous contract. So it's important to account for this fact in your deprecation and turn down policies.

**A culture around strong versioned contracts is probably the most challenging organizational aspect of a stable microservices based application.**

At the lower level of detail, services communicate using HTTPS with text-based payloads, for example, JSON or XML and use the HTTP verbs such as, `get` and `post`, to provide meaning for the actions requested. Clients should just need to know the minimal details to use the service. The URI, the request and the response message formats.

<br>

<img src="../assets/REST.png" alt="REST" width="50%" height="50%">

<br>

REST architecture supports loose coupling. REST stands for `Representational State Transfer`. And is protocol independent. The HTTP is the most common protocol but gRPC is also widely used. REST supports loose coupling, but still requires strong engineering practices to maintain that loose coupling. A starting point is to have a strong contract. HTTP-based implementations can use a standard like open API and gRPC provides protocol buffers.

To help maintain loose coupling, it is vital to maintain backward compatibility of the contract and to design an API around a domain and not particular use cases or clients.

If the latter is the case, each new use case or application will require another special purpose REST API regardless of the protocol. Why request-response processing is the typical use case, streaming may also be required and can influence the choice of protocol. gRPC supports streaming, for example.

<br>

<img src="../assets/RESTful_services.png" alt="RESTful services" width="50%" height="50%">

<br>

Resources are identified by URIs or endpoints and responses to requests return an immutable representation of the resource information. REST applications should provide consistent uniform interfaces and can link to additional resources. Hypermedia as the engine of application state is a component of REST that allows the client to require little prior knowledge of a service because links to additional resources are provided as part of the responses.

It is important that API design is part of the development process. Ideally, a set of API design rules is in place that helps the REST APIs provide a uniform interface. For example, each service reports errors consistently, the structure of the URLs is consistent, and the use of paging is consistent. Also consider caching for performance and resource optimization for immutable resources.

In REST, a client and server exchange representations of resource. A resource is an abstract notion of information. The representation of a resource is a copy of the resource information.

For example, a resource could represent a dog. The representation of a resource is the actual data for a particular dog. For example, Noir who is a Schnoodle or Bree who is Mutt. Two different representations of resource.

The URI provides access to a resource. Making a request for that resource returns a representation of that resource, usually in JSON format. The resource requested can be single items or a collection of items. For performance reasons returning collection of items, instead of individual items can be beneficial. These types of operations are often referred to as batch APIs.

<br>

<img src="../assets/resource_representation.png" alt="Representation of resources" width="50%" height="50%">

<br>

Representation of a resource between client and services are usually achieved using text-based standard formats. JSON is the norm for text-based formats, although XML can be used as well. For public facing or external facing APIs, JSON is the standard. For internal services, gRPC may be used, in particular, if performance is key.

<br>

### HTTP

<br>

<img src="../assets/http_requests.png" alt="http requests" width="50%" height="50%">

<br>

A client accessing HTTP service forms an HTTP request. HTTP requests are built in three parts.

The request line, header variables and request body.

The request line has the HTTP verb, `GET`, `POST`, `PUT`, etc, the requested URI and the protocol version.

The header variables contain key value pairs. Some of these are standards such as user-agent, which helps the receiver identify the requesting software agent. Metadata about the message format or preferred message formats is also included here for HTTPS based REST services. You can add custom headers here.

The request body contains data to be sent to the server and is only relevant for HTTP commands that send data such as POST and PUT.

Here we see two examples of HTTP client text-based messages.

<br>

<img src="../assets/http_examples.png" alt="http examples" width="50%" height="50%">

<br>

The first example shows an HTTP get request to the URL using HTTP version 1.1. There's one request header variable named `host` with the value `pets.drehnstron.com`.

The second example shows an HTTP POST request to the URL/add using HTTP version 1.1. There are three request header variables, `host`, `content-type` set to JSON, `content-length` set to 35 bytes. There is a request body which has the JSON document name Noir, breed, schnoodle. This is the representation of the pet being added.

<br>

<img src="../assets/http_verbs.png" alt="http verbs" width="50%" height="50%">

<br>

As part of a request, the HTTP verb tells the server the action to be performed on a resource. HTTP as a protocol provides nine verbs, but usually only the four listed here are used in REST.

`GET` is used to retrieve resources.
`POST` is used to request the creation of a new resource. The service then creates the resource and usually returns the unique ID generated for the new resource to the client.
`PUT` is used to create a new resource or make a change to an existing resource. `PUT` request should be idempotent, which means that no matter how many times the request is made by the client to a service, the effects on the resource are always exactly the same.
Finally, a `DELETE` request is used to remove a resource.

<br>

<img src="../assets/http_responses.png" alt="http responses" width="50%" height="50%">

<br>

HTTP services return responses in a standard format defined by HTTP. These HTTP responses are built in three parts.

The response line, header variables, and response body.

The response line has the HTTP version and a response code. The response codes are broken on boundaries around the hundreds. The 200 range means okay. For example, 200 is okay. 201 means a resource has been created. The 400 range means the client request is an error. For example, 403 means forbidden due to request or not having permission. 404 means requested resource not found. The 500 range means the server encountered an error and cannot process the request. For example, 500 is internal server error. 503 is not available usually because the server is overloaded.

The response header is a set of key value pairs, such as `content-type`, which indicates to the receiver the type of the content the response body contains.

The response body has the resource representation requested in the format specified in the `content-type` header and can be JSON, XML, HTML, etc.

<br>

<img src="../assets/uri.png" alt="uri" width="50%" height="50%">

<br>

The guidelines listed here focus on achieving consistency on the API. Singular nouns should be used for individual resources and plural nouns for collections or sets. For an example, consider the following URI `/pet`. Then a GET request for URI `/pet/1` should fetch a pet with ID one, whereas GET `/pets` should fetch all the pets. Do not use URIs such as GET `/GET pets`. The URI should refer to the resource, not the action on the resource. That is the rule of the verb. Remember that URIs are case insensitive and that they include version information.

<br>

<img src="../assets/diagramming_services.png" alt="diagramming services" width="50%" height="50%">

<br>

It is a good practice to diagram services. This diagram shows that there is a service that provides access to the resource known as pets. The representation of the resource is the pet. When a request is made for the resource via the service, one or more representations of a pet are returned.

<br>

### APIs

Let's move on to the API design.

<br>

<img src="../assets/api_design.png" alt="API design" width="50%" height="50%">

<br>

It is important to design consistent APIs for Services, Google provides an API design guide with recommendations on items such as names, error handling documentation, versioning, and compatibility. This guide and the API style book are linked in the slides.

For examples of best practices, it is useful to examine the Google Cloud APIs. Each Google Cloud Service exposes a rest API.

Functions are defined in the form `service.collection.verb`. The service represents the service endpoint example for the Compute Engine API, the service endpoint is `compute.googleapis.com`.

Collections include instances, instance groups, and instance tablets. The verbs then include `list`, `get` and `insert`, for example, to see all your Compute Engine instances make a get request to the link shown on the slide.

Parameters are passed either in the URL or on the request body in JSON format.

<br>

<img src="../assets/openAPI.png" alt="OpenAPI" width="50%" height="50%">

<br>

Open API is an industry standard for exposing APIs to clients.

Version 2.0 of the specification was known as Swagger.

Swagger is now a set of open source tools built around open API that with associated tooling supports designing, building, consuming, and documenting APIs.

Open API supports an API first approach.

Designing the API through open API can provide a single source of truth from which source code for client Libraries and server stubs can be generated automatically, as well as API user documentation. Open API is supported by Cloud Endpoints and Apigee.

The example document shows a sample of an open API specification of a pet store service.

The URI is `petstore.swagger.io/v1`. Note the version in the URI here. The example then shows an endpoint slash pets which is accessed using the HTTP `GET` and will provide a list of all pets.

<br>

<img src="../assets/gRPC.png" alt="gRPC" width="50%" height="50%">

<br>

Developed at Google gRPC is a binary protocol that is extremely useful for internal microservices communication.

It provides support for many programming languages, has strong support for loose coupling via contracts defined using protocol buffers and is high-performing because it's a binary protocol.

It is based on HTTP2 and supports both client and server streaming. The protocol is supported by many Google Cloud services, such as the global load balancer and Cloud Endpoints for microservices, as well as on GKE by using an envoy Proxy.

<br>

<img src="../assets/gcp_endpoint_management.png" alt="GCP endpoint management" width="50%" height="50%">

<br>

Google Cloud provides two tools for managing APIs.

Cloud Endpoints and Apigee.

Cloud Endpoints is an API management gateway which helps you develop, deploy, and manage APIs on any Google Cloud Backend. It runs on Google Cloud and leverages a lot of Google's underlying infrastructure.

Apigee is an API management platform built for enterprises with deployment options on Cloud, on-premises or hybrid. The feature set includes an API Gateway, customizable portal for onboarding partners and developers, monetization and deep analytics around APIs. You can use Apigee for any HTTP/HTTPS back ends, no matter where they are running on-premises, any public cloud, et cetera.

Boot solutions provide tools for services such as user authentication, monitoring and securing, and also for OpenAPI and gRPC.

<br>

### Activity Intro - Designing REST APIs

You will now design the APIs for the microservices identified for your application.

The aim of this activity is to gain experience designing the APIs and considering aspects such as the API URL structure, the message request response formats and versioning.

Let's say we were defining an API for an online store. The API might look similar to what's shown here. Whether a service provides a user interface or some back-end functionality, it requires a programmatic interface that is callable via HTTPS.

The only difference between a website and a web service is the format of the data that is returned. For a UI service, we might return HTML but a back-end service might return JSON or XML.

Use the principles we have discussed in this module so far and refer to Activity five in the design workbook.

<br>

### Activity Review - Designing REST APIs

In this activity, you were asked to design a RESTful API for the microservices used in your case study.

Here's an example for our online travel portal.

Obviously, our API would be larger than this, but in a way, the APIs are all more of the same. Each service manages and makes available some collection of data. For any collection of data, there are a handful of typical operations we do with that data.

This is similar to Google Cloud APIs. For example, in Google Cloud, we have a service called Compute Engine, which is used to create and manage virtual machines, networks, and the like. The Compute Engine API has collections like instances, instance groups, networks, sub-networks, and many more. For each collection, various methods are used to manage the data.

<br>

<img src="../assets/compute_api_example.png" alt="Cloud Compute API Example" width="50%" height="50%">

<br>

For example, here are the methods for adding, managing, and deleting firewalls. When you're designing your APIs, you should strive to be as consistent as possible. This will make development easier and will also make it easier for clients to learn to use your APIs.

<br>

### Review

In this module, we focused on microservice design and architecture.

We started out defining what a microservice architecture is and the advantages and disadvantages of using microservices. We also enumerated some microservice best practices.

Then we covered how to design service APIs and implement a rest style architecture.

<br>

## Module Overview: DevOps Automation

This module introduces DevOps automation, a key factor in achieving consistency, reliability, and speed of deployment.

Specifically, we will talk about services that support continuous integration and continuous delivery practices; part of DevOps way of working.

With DevOps and microservices, automated pipelines for integrating, delivering, and potentially deploying code are required. These pipelines ideally run on on-demand provisioned resources.

This module introduces the Google Cloud tools for developing code and creating automated delivery pipelines that are provisioned on-demand.

We will talk about using Cloud Source Repositories for source and version control.

Cloud Build, including build triggers for automating builds and managing containers with Container Registry.

We will finish by reviewing infrastructure as code tools like Deployment Manager and Terraform.

<br>

### Continuous Integration Pipelines

Let's begin by talking about continuous integration pipelines.

<br>

<img src="../assets/ci_pipeline.png" alt="CI Pipeline" width="50%" height="50%">

<br>

Continuous integration pipelines, automate building applications. This graphic shows a very simplistic view of a pipeline which would be customized to meet your requirements.

The process starts with checking code into a repository where all the unit tests are run. On successful passing of the tests, a deployment package is built as a docker image. This image is then saved in a container registry from where it can be deployed.

Each micro service should have its own repository. Typical extra steps include linting of code, quality analysis by tools such as sonarqube, integration tests, generating test reports and image scanning. Google Cloud provides the components required to build a continuous integration pipeline.

Let's go through each of these.

<br>

<img src="../assets/ci_services.png" alt="GCP CI services" width="50%" height="50%">

<br>

The Cloud Source Repository Service provides private Git repositories hosted on Google Cloud. These repositories let you develop and deploy an app or service in a space that provides collaboration and working control for your code. Cloud source repositories is integrated with Google Cloud so it provides a seamless developer experience.

Cloud Build executes your builds on Google cloud infrastructure. It can import source code from cloud storage, cloud source repositories, GitHub or Bitbucket, execute a build to your specification and produce artifacts such as docker containers or Java archives. Cloud Build executes your build as a series of build steps where each build step is run in a docker container. A build step can do anything that can be done from a container irrespective of the environment. There are standard steps or you can define your own steps.

A Cloud Build trigger automatically starts a build whenever you make any changes to your source code. You can configure the trigger to build your code on any changes to the source repository or only changes that match the certain criteria.

Container registry is a single place for your team to manage docker images or deployment packages, perform vulnerability analysis and decide who can access what with fine grained access controls.

Let's go through each of these services in more detail.

<br>

<img src="../assets/cloud_source_repo.png" alt="Cloud Source Repositories" width="50%" height="50%">

<br>

Clouds source repositories provide managed Git repositories. You can use Cloud IAM to add team members to your project and to grant them permissions to create, view and update repositories. Repositories can be configured to publish messages to a specific Pub/Sub topic. Messages can be published when a user creates or deletes a repository or pushes a comment. Some other features of cloud source repositories include the ability to debug in production using cloud debugger, audit logging to provide insights into what actions were performed where and when? And direct deployment to app engine. It is also possible to connect an existing Git hub orbit bucket repository to cloud source repositories. Connected repositories are synchronized with clouds source repositories automatically.

<br>

<img src="../assets/cloud_build.png" alt="Cloud Build" width="50%" height="50%">

<br>

Cloud build, lets you build software quickly across all languages. It is a google hosted Docker build service and is an alternative to using the Docker build. The CLI can be used to submit a build using G cloud. An example is shown on this slide. Gcloud build submits, submits the build and will run as a remote built. The `--tag` is the tag to use when the image is created. The tag must use the `gcr.io` or `star.gcr.io.star` name space. Your source must contain a Docker file if you use the tag. Finally, the dot represents the location of the source to build.

<br>

<img src="../assets/build_trigger.png" alt="Build Triggers" width="50%" height="50%">

<br>

Build triggers, watch a repository and build a container whenever code is pushed. Google's build triggers support Maven, cloud builds and Docker. A cloud build trigger automatically starts a build whenever a change is made to source code. It can be set to start a build on commits to a particular branch or on commits that contain a particular tag. You can specify a regular expression with the branch or tag value to match. The build configuration can be specified either in a Docker file or a cloud build file. The configuration required is shown on this slide. First, a source is selected. This can be cloud source repositories, GitHub or Bitbucket. In the next stage, a source repositories selected followed by the trigger settings. The trigger settings include information like the branch or tag to use for trigger. And the build configuration, for example, the Docker file or cloud build file.

<br>

<img src="../assets/container_registry.png" alt="Container Registry" width="50%" height="50%">

<br>

Container registry is a Google Cloud hosted Docker repository. Images built using cloud build are automatically saved in container registry. Images are tagged with a prefix as shown on this slide. It is also possible to push and pull images using the standard Docker commands. So to push an image, use `docker push gcr.io/your-project-id/image-name`. To pull an image, use `docker pull gcr.io/your-project-id/image-name`.

<br>

<img src="../assets/binary_auth.png" alt="Binary Authorization" width="50%" height="50%">

<br>

Now, binary authorization allows you to enforce deployment of only trusted containers into GKE. Binary authorization is a Google Cloud service and is based on the KRITIS specification. For this to work, you must enable binary authorization on your GKE cluster where your deployment will be made. A policy is required to sign the images. When an image is built by Cloud Build and an a tester verifies that it was from a trusted repository, for example, source repositories,container registry includes a vulnerability scanner that scans containers.

A typical workflow is shown in the diagram. Check in of code triggers a Cloud Build. As part of the build, container registry will perform a vulnerability scan when a new image is uploaded. The scanner publishes messages to Pub/Sub. The KRITIS signer listens to pops up notifications from a container registry vulnerability scanner, and makes an attestation if the image scanning past the vulnerability scan. Google Cloud binary authorization service then enforces the policy requiring attestations by the KRITIS signer before a container image can be deployed. This flow prevents deployment of images with vulnerabilities below a certain threshold.

<br>

### Infrastructure as Code

Let's now move on to consider Infrastructure as Code.

<br>

<img src="../assets/moving_to_cloud.png" alt="Moving to the Cloud" width="50%" height="50%">

<br>

Moving to the Cloud requires a mindset change. The on-demand pay-per-use model of Cloud computing is a different model to traditional on-premise infrastructure provisioning. A typical on-premise model would be to buy machines and keep them running continuously. The Compute Infrastructure is typically built from fewer larger machines. From an accounting view, the machines are capital expenditure that deprecates over time. When using the Cloud, resources are rented instead of purchased, and as a result, we want to turn the machines off as soon as they are not required to save on cost.

The approach is to typically have lots of smaller machines scale out instead of scale up, and to expect an engineer for failure.

From an accounting view, the machines are a monthly operating expenditure.

In other words, in the Cloud, all infrastructure needs to be disposable.

<br>

<img src="../assets/disposable_infra.png" alt="Disposable Infrastructure" width="50%" height="50%">

<br>

The key to this is Infrastructure as Code, IaC, which allows for provisioning, configuration, and deployment activities to be automated. Having the process automated minimizes risks, eliminates manual mistakes, and supports repeatable deployments, scale, and speed. Deploying one or 100 machines is the same effort. The automation can be achieved using scripts or declarative tools such as Terraform, which we will discuss later.

It is really important that no time is spent trying to fix broken machines, or installing patches, or upgrades. These will lead to problems recreating the environment at a later date. If a machine requires maintenance, remove it and create a new one instead. Costs can be reduced by provisioning ephemeral environments such as test environments that replicate the production environment.

<br>

<img src="../assets/iac.png" alt="IaC" width="50%" height="50%">

<br>

In essence, Infrastructure as Code allows for the quick provisioning and removing of infrastructure. The on-demand provisioning of a deployment is extremely powerful. This can be integrated into a continuous integration pipeline, smooths the path to continuous deployment.

Automated infrastructure provisioning means that it can be provisioned on demand and the deployment complexity is managed in code. This provides the flexibility to change infrastructure as requirements change, and all the changes are in one place.

Infrastructure for environments such as deployment and test can now easily replicate production and can be deleted immediately when not in use, all because of Infrastructure as Code.

Several tools can be used for IaC.

Google Cloud provides deployment manager where deployments are described in a YAML file known as Configuration. This details all the resources that should be provisioned. Configurations can be modularized using templates, which allows the abstraction of resources into reusable components across deployments.

In addition to deployment manager, Google Cloud also provides support for other IaC tools including
- Terraform
- CHEF
- Puppet
- Ansible
- Packer.

Let's take a closer look at deployment manager and Terraform.

<br>

<img src="../assets/cloud_deployment_manager.png" alt="Cloud Deployment Manager" width="50%" height="50%">

<br>

Cloud Deployment Manager defines infrastructure using YAML files. Templates allow the separation of configuration into different pieces that can be used and reused across different deployments. These templates can be specific or more generalized. They can make use of template properties, environment variables, and modules to create dynamic configuration and template files. The template files can be written in Python or Jinja, the Python templating language. Deployments can be created using the Google Cloud Console, APIs, or GCloud. The example YAML snippet to the right shows a section from a deployment manager configuration. The configuration must list resources, which in this example is a virtual machine, including the type of VM, zone, disk, and network interface.

<br>

<img src="../assets/terraform.png" alt="Terraform" width="50%" height="50%">

<br>

Terraform is similar to deployment manager, but can be used on multiple public and private Clouds. Terraform is already installed in Cloud Shell. The example configuration files shown on the right begins by indicating that the provider is Google Cloud. What follows is the configuration of a compute engine instance and its disk. The output section allows for the IP address of the provisioned instance to be obtained from the deployment.

<br>

#### Lab Intro - Building a DevOps Pipeline

In this first lab, you will build a DevOps Pipeline using Cloud Source repositories, Cloud Build and Container Registry.

Specifically, you will first create a git repository.

You will then write a simple Python application and add it to your repository.

After that, you will test your web application in Cloud Shell and then define a Docker build.

Once you define the build, you will use Cloud Build to create a Docker image and store the image in container registry.

Then you will see how to automate builds using triggers.

Once you have the trigger, you will test it by making a change to your program and pushing that change to a git repo.

<br>

#### Lab Review - Building a DevOps Pipeline

In this lab, you learned how to use Google Cloud tools to create a simple and automated continuous integration pipeline. You used Cloud Source repositories to create a Git repository, and then use Cloud Build and triggers to automate the creation of your Docker images when code was checked into that repo. When Cloud Build created your Docker images, it stored them in Container Registry. You saw how to access those images and test them in a Compute Engine VM. You can stay for a lab walk through, but remember that Google Cloud's user interface can change. So your environment might look slightly different. So here I am in the GCP console. The first thing I'm going to do is I'm going to go create a new repository. For that, in the navigation menu, I'm going to scroll down to Source Repositories.

That opens in a new tab.

In here, I'm going to click Add repository.

We're going to create a new one, click Continue, and then we're just going to give it a name, which is the one we have in the lab instructions, which is `devops-repo`.

Now, I want to select the project that I'm working with. So for that, you want to just make sure that you're selecting the actual Qwiklabs project that is displayed in your Qwiklabs UI.

So I'm going to select that, and I'm going to click Create. So this is going to create now. What I'm going to do is I'm going to return to the Cloud Console.

So I'm just switching tabs here.

Within here I'm going to click Activate Cloud Shell.

When prompted, I'm going to click Continue.

So I'm actually also going to move this to a new tab, a specific new window. I can do that right here, and then I can see a little bit more here.

So within here now I'm just going to create a new directory. So let me copy the directory name from the lab instructions, and then I'm just going to navigate to that directory. S

o now we're going to clone the empty repository that we just created, and we should get a warning here. That is because we're actually using an empty directory.

So you can see that right here, you appear to have cloned an empty directory, and that's okay. So this directory now created the folder devops-repo. So we can also navigate to that and right now, right now.

That completes really your first task.

Now, in the next task, we're now going to use the code editor and actually create a file in here. So up here, I'm going to click on Launch editor, and what we're going to do is we're going to go to the File menu and create a new file, but we want to make sure that we do that in the devops-repo.

So let me navigate to the devops-repo here, then click File, New File, we're going to call that main.py. We can see that as now within that directory, and I'm just going to paste the Python code that we have from the lab instructions in there, and then I can save that.

Now, I'm going to now create a new folder in here called templates.

So in the devops-folder, I'm going to right-click and I can click on New Folder and I'm giving it a name templates. In that folder we're going to create the file `layout.html`, which is also from the lab instructions. So these first couple of steps are really just a lot of setting up the code here that we're going to use, and rather than just cloning this from somewhere, we're giving you all of the files and showing you what this code is so that you can understand what this code does.

Again, this is just a simple Python application. So it's just really a little bit better than Hello World, but we're going to use it for the pipeline. We actually are going to use something similar throughout the other labs that we have in this course as well. Now, we also need to create an `index.html`. So I'm going to in the templates folder, also add another file, call it `index.html`, and we're also going to copy code in there, and then we're going to save that as well.

Now, we also need a requirements file. This is typical for Python applications, so it's a prerequisite, and so I'm going to, in the DevOps folder, not the templates folder now, I'm going to add a new file, and call it `requirements.txt` and specify Flask in there.

So now we have some files, we can save them. So what we're going to nano first we need to add all the files that we just created to the local git repo.

So in Cloud Shell, we're going to make sure that we navigate to this folder. So if you copy the lab instructions that just asks you to cd to that folder, and let me make this a little bit bigger here and clear this so we can see more. Navigate, we're still there, and then we're going to run the command `git add --all`.

Now, we're going to commit those changes to the repository. Now, the lab instructions say that you want to enter an email, and then what you want to enter a name, you could use your gmail or anything else here is really up to you. So I'm going to add these first command, and what I can actually do is I can just grab the email that I have in Qwiklabs as an example. So let me get to that.

So in there, for example, from my current session, I have this, so I can run that for the configuration, and then I can also go back to the lab instructions. Now, specify the username, and here I can put my name, and I could just use this part of the email for that.

This is just for illustration purposes, usually you'd want to put your own email and your own name here. This is just a demo.

So we've configured git, so now we can go ahead and actually commit and we give it a name. Let's just call it initial commit.

So here we can see the commits, these are all the files that we just did, again the requirements is directly within a devops-repo folder as well as `main.py`, and then the two HTML files are within the templates. So now we can push this to the master, and we can see that this is done.

Now I can go back and switch to the Source Repositories page, and I can go refresh this, and we should see the code here. So here we go. So this worked successfully and that completes task 2.

So that's all great, but we want to also test this application and actually create the Docker build and all of that. So let's get on that, I am going to go back to Cloud Shell, and first we're going to install the Flask framework using pip. So I want again, just make sure I'm in the right folder by running first the cd command, and then we're going to run `sudo pip3 install`, and that is going to go through, and then we're going to run the program with the Python command.

So we can see that this is configured to run on port 8080, and we can actually preview this, what this looks like. So up here, we have a Web preview button. So if I click on this, and then preview on port 8080, it'll open a new tab for me, and that worked.

So it says Hello DevOps Fans in here.

So this is working, I can stop that if I go back to Cloud Shell and just `ctrl + c` out of this, and what I'm going to do now is I'm going to go into the `main.py` and I'm actually going to change the name. So if I go into `main.py` here, we see this is where that text Hello DevOp Fans was coming from. So we can change that to something else. Let's say for example, Hello Google Cloud Fans, and we're going to save that.

Now we're going to take these changes we just made, and we're going to commit them. So let me just do that and give it a name, second commit, and then we'll also push to the master.

Great, and now if I go back to Cloud Store Repositories, I can go in here into `main.py`, and I can see that this change actually took effect. That's the end of task three.

So now we're actually going to get creative here, and we're going to define a Docker build and actually work on our DevOps pipeline.

The first step to that is to create a file called `Dockerfile`, and that file just defines how I Docker containers constructed. So let me go back to Cloud Shell, and within the DevOps repo folder, I'm going to want to create a new file. I'm just going to give it the name `Dockerfile`, no extension or anything, and the `Dockerfile`.

So here at the top of the file, I'm just going to say from Python 3.7. So this is just the base image, and you can actually choose many base images. In this case, you're using one with Python already installed on it, and then we're going to enter the following.

Workdir app and then copy, and these lines just copy the source code from the current folder into the app folder in the container image.

Then we're also going to add commands, and this uses pip to install the requirements of the Python application into the container, and `gunicorn` is a Python Web server that we use to run the Web app. Then we're also going to enter the environment variables, and this just sets the port of the application running, in this case, port 80, and the last line in here runs a Web app using `gunicorn` Web server.

So you can see that here, and then you are also given, let me just make this a little bigger so we can see this whole file. You also given what the whole file looks like again. So I could also just copy that, and just make sure one more time that I have done everything correctly, and that seems to be the case.

So that's it for task four.

We've defined a Docker build and now we need to actually manage the Docker images with Cloud built and Container Registry. So within Cloud Shell, first I want to make sure we're still in the right folder, and we keep doing that in the lab instructions just in case you do something else or you close Cloud Shell, and reopen it and you are not in the same folder anymore.

So just want to confirm I'm in the right folder. Now we're going to create an environment variable that's specifically for the project, but that's actually already stored in devshell project ID. So let's actually verify that. If I go `echo $DEVSHELL_PROJECT_ID`, we can see right here that I have my project ID, and it can also verify if I go back to my console, that is the current project I'm working on. So you can see that ends with 625c, and the same is true here. So now we're going to go ahead and use that environment variable to now start the belt. So let's do that, and this might ask us now to enable Cloud build, it's downloading.

We're just going to wait for that.

Now in Container Registry, the image name will always begin with `gcr.io/` and then followed by the project ID of the project you're working with, followed by the image, name, and the version, and then the period at the end of the command represents the path to `Dockerfile`.

In this case, it'll be the current directory. So we're just going to wait for this to complete, and then we're going to return to the console, and look at the Container Registry.

All right, it's actually done. So here you can see what I just talked about, the `gcr.io`. Then we have the name of the project. Here we have the project itself, and then the version, so the image name and the version. So I'm going to go back now to Container Registry.

So let me go to Cloud Console, click on Container Registry and we're going to minimize that here, and here we can see that DevOps image. So now what we're going to do is we're going to go to Cloud Build and we should see this already. We're going to go to Compute Engine and create a VM that is going to directly use that container image. So let's go to the navigation menu and then we're going to go to Cloud Build.

It's a long list in here, but here we go, and here we can see the history of that build that just happened. So we can see 50 seconds ago, and we could get some more information.

We can see where this is stored.

We can click into it and I can get all information, and if something were to go wrong, we can see that information here as well.

But for the time being, let's go to Compute Engine and create a new VM, and in the instance creation page, we're going to use the container image that we just created. So I can just leave the name, it's instance one, and I'm going to scroll down, and the key here is now we're going to check this box that says deploy a container image to this VM instance, and then the image. Now, here we need to copy from Cloud Shell.

So let me go back to Cloud Shell. Let me grab this whole path here, copy it once you select it, and then let me paste that in here, and obviously that's going to be different for your projects. So keep in mind, don't just copy the one I have here because you will have different project ideas. Now I also want to enable HTTP traffic. So this is just going to add a network tag, and then create a firewall rule with that tag to allow traffic there, and we're doing that because again, we enabled traffic on port 80, and then we're going to click Create.

We're going to wait for this VM to start, and then we're going to make a request to the external IP address. I can close this over here. This is anytime you're using a new project, you get this Learn page, and with all of Qwiklabs, you're always have new projects for all of your different labs. So here we have the external IP. I can click on here.

Directly, and this might take a while for this to startup, so you might have to wait a minute or so. So let's actually do that and let's get back to here. So here we go.

Took about a minute to two minutes just for that container to start. But here we can see now, the new text that we have in here We can see that this is running. So again, all I did is make a request to the external IP address, and this is the IP address in my case, you can just click on that directly or you could navigate to that by just entering that IP address.

Great, so now what we're going to do is we want to save these changes to our Git Repository. So we're going to go back to Cloud Shell, and let me just clear this to get a bit more space. In here now we're going to make sure we're on the right folder which we already are, and then we're going to `git add --all`.

Then we're going to first commit the changes locally with just a message that we added to Docker Support, and then we're going to push that to the master.

So that worked. So now we can go back to Cloud Source Repository.

So let me switch tabs to that and I'm just going to refresh this page, and there we can now also see our `Dockerfile`. So we can see that's in there too now. So that's all great. But now we want to actually move into the automation piece. So we're going to now automate builds with triggers.

So for that we're going to go to Container Registry, and I have that in a different tab, I believe. Let me close a couple of these. Let's actually go back just to Cloud Console, Navigation menu safety, and then scroll down to Container Registry.

So we have this DevOps image folder here. If I go in there, here we can see the container that we created earlier. So now we're going to go to Cloud Build. Let me go back to navigation menu.

Cloud Build, and we're going to create a trigger. So let's go through the Trigger section. We're going to create a trigger, we're going to do that for our DevOps repository, we're going to give this a name. The lab instructions just has `devops-trigger`.

Now there are a lot of defaults in here. We're going to accept those. It's just going trigger on the branch and you can say what files to include, exclude, the image name, and so on.

In our case, we're just going to go ahead and create this, and then once it's created, we're going to run this trigger. So let's click Run trigger.

So it says that build has started, and then we're going to go to the History link. We're going to ensure that this is actually running. So let me go back here to History, and here we can see that this has triggered. So we're going to wait for this to finish, and then we're going to click on this actual trigger here and scroll down to look at the logs, and the output of the build here is what you would have seen if you're running it on your machine. S

o let's just wait for this to complete and then we're going to explore that. So we can see that this is complete, I'm just going to go click on the link for that, and this is what I mentioned, if you had run this from Cloud Shell like we did earlier, this is the output that you would see.

So you might see this is very familiar to what we saw earlier. So now we're going to go back to the Container Registry service and we should see the new image in there. So if I go to the navigation menu and scroll down, and go to the Container Registry, we now see the devops-image here, we have a devops-repo folder here, and here we have that new image.

Here, sorry, I navigated into the wrong place. So here we see the new image, you can see that this was just created a minute ago. So we're going to go back now, we're going to make changes to our file, and we're going to try to see how these builds are done automated.

Then we want to also test these build changes. So I'm going to navigate back to Cloud Shell, we're going to go to the main function, and just like we did earlier, we're going to change this title, and let's just call it what is in the lab instructions, which is `Hello Build Trigger`.

We're going to save that, and we're going to commit that, first make sure we are in the right folder, and then we're going to push our changes to clutters repositories.

So all I've done now is made the change, and they should now cause a trigger. So if we go back to the Cloud Build service now in the console, we can see here that this is automatically triggered, and that's the end of task 6.

That's all great, but now we want to actually test this. So we're going to wait for this build to complete, we can then click on it to see the detail, and then under the build information, we're going to find the image link, and then we're going to create a new Virtual Machine to test this because this is a new image that we have and we're going to allow HTTP traffic on that, wait for that to start up, and then we should see a text that is different from this.

It shouldn't say Hello Google Cloud Fans, it should say Hello Build Triggers. So here we can see that the build is completed and I can now click on it, and I'm now looking for the image so I can go through the Build Log or it can also go to the Build Artifacts, and here I see the image.

So let me just make some more space here and let's copy that, and then we're going to go to the navigation menu and we're going to head over to Compute Engine and create a new instance on this. So I'll go to Compute Engine, click on Create Instance. I'm going to leave the name and regions on the default.

Now importantly, need to click Deploy a Container. I'm going to paste in the image, allow HTTP traffic, and then we're going to go create that. We're going to wait for this VM to startup, and once it's started, we're going to click in the external IP address, and just like before, that won't be automatically ready because we have to wait for the container to start. So let's just do that.

So here we can see that this is now finished, the container is running, and it now it says, Hello Build Trigger.

That's the end of the lab.

<br>

### Module Review

In this module you learned about sources you can use to help automate the deployment of your cloud resources and services. You use cloud source repositories, cloud build, triggers, and container registry to create continuous integration pipelines.

A CI pipeline automates the creation of deployment packages like Docker images in response to changes in your source code. You also saw how to automate the creation of infrastructure using infrastructure as code tools like deployment manager and terraform.

<br>

## Module Overview - Google Cloud Storage and Data Solutions

In this module, we discuss Google Cloud Storage and Data Solutions and how to select the most suitable one to meet your business and technical requirements.

Google Cloud provides a rich set of different storage options that cater to different types of data, sizes of data, lifecycle and also data access patterns.

We will discuss storing binary data with Cloud Storage, relational data with Cloud SQL or Spanner and NoSQL or unstructured data using Firestore and Bigtable. In addition, we will consider caching for fast data access using Memorystore and finally aggregating data for queries and reports using BigQuery as a data warehouse.

<br>

### Key Storage Characteristics

Let's get started by considering key storage characteristics.

<br>

<img src="../assets/gcp_managed_storage.png" alt="GCP Managed Storage" width="50%" height="50%">

<br>

Google Cloud has a wide range of managed storage and database options in its portfolio. Knowing the characteristics of each and being able to select a suitable solution is vital as an architect during the design process.

From a high-level the services range from relational, NoSQL, object storage, data warehouse, to In-memory. These services are fully managed to scalable and backed by industry leading SLAs. Making a decision on which storage solution is right for your requirements is a balance of a number of characteristics including the type of data, scale, durability, availability, and location requirements.

We will discuss ways in which you can make the decision based on your requirements in this module.

<br>

<img src="../assets/data_storage_sla.png" alt="Data Storage SLAs" width="50%" height="50%">

<br>

Different data storage services have different availability SLAs. For a service, the availability SLA is often dependent on the configuration of the service.

For example, for Cloud storage as the slide shows the availability varies depending on whether multi-regional, regional or coldline buckets are created. The same can be seen for Cloud Spanner and Firestore with multi-region offering higher availability than single region configurations.

This is where requirements are extremely important as they will help inform the storage choices.

The availability SLAs are typically defined per month. Monthly uptime percentage means the total number of minutes in a month, minus the number of minutes of downtime suffered from all downtime periods in a month, divided by the total number of minutes in a month.

**For up-to-date SLA numbers refer to the documentation.**

Now durability of data represents the odds of losing the data.

<br>

<img src="../assets/durability.png" alt="Durability of Data" width="50%" height="50%">

<br>

Depending on the storage solution, the durability is a shared responsibility. Google Cloud's responsibility is to ensure that data is durable in the event of a hardware failure. Your responsibility is performing backups of your data, for example Cloud storage provides you with 11 9's durability and versioning is a feature.

However, it's your responsibility to determine when to use versioning.

I recommend turning versioning on and having older versions archived as part of an object lifetime management policy.

For other storage services to achieve durability, it usually means taking backups of data. For disks this means snapshots. So snapshot jobs should be scheduled.

For Cloud SQL, Google Cloud provides automated machine backups, point-in-time recovery, and optionally a failover server. To improve durability SQL database backup should also be run. Spanner and Firestore provide automatic replication and you should run export jobs with the data being exported to Cloud storage.

<br>

<img src="../assets/amount_data.png" alt="Data Amounts" width="50%" height="50%">

<br>

The amount of data and the number of reads and writes are important to know when selecting a data storage service.

Some services scale horizontally by adding nodes, for example, Bigtable and Spanner, which is in contrast to Cloud SQL and Memorystore which scale machines vertically.

Other services scale automatically with no limits for example, Cloud storage, BigQuery, and Firestore.

Strong consistency is another important characteristic to consider when designing data solutions. A strongly consistent database will update all copies of data within a transaction and ensure that everybody gets the latest copy of committed data on reads.

<br>

<img src="../assets/data_consistency.png" alt="Consistency of Data" width="50%" height="50%">

<br>

Google Cloud Services providing strong consistency include Cloud storage, Cloud SQL, Spanner, and Firestore.

Eventual consistent data bases typically have multiple copies of the same data for performance and scalability. They support handling large volumes of writes. They operate by updating one copy of the data synchronously and all copies asynchronously. Which means that not all readers are guaranteed to read the same value at a given point in time. The data will eventually become consistent but not immediately.

Bigtable and Memorystore are examples of Google Cloud data services that have eventual consistency.

<br>

<img src="../assets/storage_costs.png" alt="Cost of Data Storage" width="50%" height="50%">

<br>

When designing a data storage solution, calculating the total cost per GB is important to help determine the financial implications of a choice.

Bigtable and Spanner are designed for massive data sets and are not as cost effective for small data sets.

Firestore is less expensive per GB stored, but the cost for reads and writes must be considered.

Cloud storage is not as expensive, but is only suitable for certain data types.

BigQuery storage Is relatively cheap but does not provide fast access to records and a cost is incurred for each query.

So as you see the choice of the right storage solution is not simple. It has to be based on the type of data, size of data, and read/write patterns.

<br>

### Activity Intro: Defining Storage Characteristics

You will now define storage characteristics for each of your case study services.

In a microservice architecture, there is not one big database to store everything for the entire application. Each service should maintain its own data, storage characteristics include whether the data is structured or unstructured, and relational or no SQL.

Ask yourself if you require strong consistency, or if eventual consistency is good enough.

Also think about how much data you have, and if you need read/write or read only.

Here's an example table for an account service that specifies all the business and technical requirements that I just mentioned.

Refer to activities six in your design workbook to fill out a similar table for your service

<br>

### Activity Review: Defining Storage Characteristics

In this activity, you were asked to define these storage characteristics for the case study you are designing.

These characteristics will help you choose Google Cloud Storage Services the most appropriate for your application.

Here's an example for our online travel portal, Click Travel. We focused on the inventory, inventory uploads, ordering, and analytic services.

As you can see, each of these services has different requirements that might result in choosing different Google Cloud Services.

<br>

### Choosing Google Cloud Storage & Data Solutions

Now that you've documented the data characteristics of your services let's talk about how to select Google cloud storage and data solutions. The Google cloud storage and database portfolio covers relational, no SQL, object, data warehouse and in memory stores, as shown in this table.

<br>

<img src="../assets/storage_portfolio.png" alt="Storage & Database portfolio" width="50%" height="50%">

<br>

Let's discuss each service from left to right.

Cloud SQL is a fixed schema data store with a storage limit of 30 terabytes. It is offered using MySQL, PostgreSQL and SQL Server. These services are good for web applications such as CMS, or e-commerce.

Cloud Spanner is also rational and fixed schema, but it scales infinitely I can be regional or multi regional. Example use cases include scalable relational databases greater than 30 gigabytes with high availability and also global accessibility, like supply chain management and manufacturing.

Google clouds NoSQL data stores are schemas Firestore is a completely managed document data store with a maximum document size of 1 megabyte. It is useful for hierarchical data for example, a game stage or user profiles.

Cloud Big Table is also a no SQL data store that scales infinitely. It is good for heavy read write events and use cases including financial services, internet of things and digital advert streams.

For object storage, Google Cloud offers Cloud Storage. Cloud storage is schemaless and it is completely managed with infinite scale. It stores binary object data and so it's good for storing images, media serving, and back-ups.

Data warehousing is provided by BigQuery. The storage uses a fixed schema and supports completely managed SQL analysis of the data stored. It is excellent for performing analytics and business intelligence dashboards.

For in memory storage, MemoryStore provides a schemaless managed Redis database. It is excellent for caching for Web and mobile applications and for providing fast access to state in microservice architectures.

Let's surmise the services in this module with this decision chart.

<br>

<img src="../assets/storage_decision_chart.png" alt="Storage & Database Decision Chart" width="50%" height="50%">

<br>

First, ask yourself, is your data structured and will it need to be accessed using a structured data format? If the answer is no, then ask yourself, do you need a shared file system?

If you do then choose FileStore. If you don't, then choose Cloud Storage. If your data is structured and needs to be accessed in this way, ask yourself does your workload focus on analytics? If it does, then you'll want to choose Cloud Big Table or BigQuery, depending on your latency and update needs. Otherwise, check whether your data is relational If it's not, then choose firestore. If it is relational, you'll want to choose Cloud SQL or Cloud Spanner, depending on your need for horizontal scalability.

Depending on your application, you might want to use one or several of these services to get the job done. For more information on how to choose between these services, please refer to the links on storage options and databases in the course resources.

You might also want to consider how to transfer data in Google Cloud.

A number of factors must be considered including cost, time, offline versus online transfer options and security. All transfer into Cloud Storage is free. There will be costs with the storage of data, and maybe even appliance costs if a transfer appliance is used or egress costs if transferring from another cloud provider.

If you have huge data sets, the time required for transfer across a network may be unrealistic. Even if it is realistic, the effects on your organization's infrastructure may be damaging while the transfer is taking place.

This table shows the challenge of moving large data sets.

<br>

<img src="../assets/transfer_data.png" alt="Data Transfer" width="50%" height="50%">

<br>

For example, if you have one terabyte of data to transfer over 100 megabits per second connection It will take about 12 days to transfer the data. The color coded cells highlight unrealistic timelines that require alternative solutions. Let's go over online and offline data transfer options.

<br>

<img src="../assets/uploads.png" alt="Data uploads" width="50%" height="50%">

<br>

For smaller or scheduled data uploads Use cloud storage transfer service, which enables you to move or backup data to a Cloud Storage bucket from another cloud storage provider, such as Amazon S3, from on premise storage, or from any HTTP or HTTPS location. It allows you to move data from one storage bucket to another so that it's available to different groups of users or applications. It also allows for periodic movement of data as part of a data processing pipeline or analytical workflow.

Storage transfer service provides options that can make data transfers and synchronization easier. For example, you can schedule one time transfer operations or recurring transfer operations.

You can delete existing objects in the destination bucket if they don't have a corresponding object in the source. You can delete data source objects after transferring them. You can schedule periodic synchronization from a data source to a data sync with advanced filters based on file creation dates, file name filters, and the time of day you prefer to import data.

<br>

<img src="../assets/storage_transfer.png" alt="Storage transfer" width="50%" height="50%">

<br>

Use the storage transfer service for on premises data for large scale uploads from your data center. The storage transfer service for on premises data allows large scale online data transfers, from on premises storage to Cloud Storage.

With this service, data validation, encryption, error retries and fault tolerance are built in. On-premises software is installed on your servers. The agent comes as a Docker container and a connection to Google Cloud is set up. Directories to be transferred to cloud storage are selected in the Cloud Console.

Once the data transfer begins, the service will paralyze the transfer across many agents supporting a scale to billions of files and hundreds of terabytes. Via the cloud console, a user can view a detailed transfer log and also the creation, management and monitoring of transfer jobs.

To use the storage transfer service for on premises a POSIX compliance source is required and a network connection of at least 300 megabits per second.

Also, a Docker supported Linux server that can access the data to be transferred is required with Port 80 and 443 open for outbound connections.

The use case is for on premises transfer of data whose size is greater than one terabyte.

<br>

<img src="../assets/transfer_appliance.png" alt="Transfer Appliance" width="50%" height="50%">

<br>

For large amounts of on premises data that would take too long to upload, use transfer appliance. Transfer appliance is a secure rackable high capacity storage server that you set up in your data center.

You fill it with data and ship it to an ingest location where the data is uploaded to Google. The data is secure and you control the encryption key and Google erases the appliance after the transfer is complete. The process for using a transfer appliance is that you request an appliance, and it is shipped in a tamper evident case. Data is transferred to the appliance. The appliance is shipped back to Google. Data is loaded into Cloud storage and you are notified that it is available.

Google uses tamper evidence seals on shipping cases to and from the data ingest safe. Data is encrypted to AES-256 standard the moment to capture. Once the transfer is complete, the appliance is a raised per NST-888 standards, you decrypted data when you want to use it.

<br>

<img src="../assets/bigquery_data_transfer.png" alt="BigQuery Data Transfer" width="50%" height="50%">

<br>

There is also a transfer service for BigQuery. The BigQuery data transfer service automates data movement from SAS applications to BigQuery on a scheduled and managed basis. The data transfer service initially supports Google applications sources, like Google ads, campaign manager, Google ad manager and YouTube.

There are also data connectors that allow easy data transfer from Teradata, Amazon Redshift and Amazon S3 to BigQuery. The screenshot on slide shows that the source type is selected for a transfer, a schedule is configured on a data destination is selected.

For the transfer the data formats are also configured.

<br>

### Activity Intro: Choosing Google Cloud Storage & Data Solutions

You will now select storage products for each of your case study services.

Use these storage characteristics and your understanding of Google Cloud's various services that we covered in this module to help you choose which storage services would be most appropriate for each of your microservices.

Here's an example table for an account service that should leverage Cloud SQL because we require a relational database that's strongly consistent with gigabytes of data and read/write capabilities.

Refer to Activity 7 in your design workbook to fill out a similar table for your applications services.

<br>

### Activity Review: Choosing Google Cloud Storage & Data Solutions

In this activity, you are asked to select the appropriate Google Cloud Storage services for your case study.

Here's an example for our online travel portal, ClickTravel.

For the inventory service, we will use Cloud Storage for the raw inventory uploads. Suppliers will upload the inventory as JSON data stored in text files. That inventory will then be imported into a Firestore database. The orders service will store its data in a relational database running in Cloud SQL. The analytics service will aggregate data from various sources into a data warehouse for which we'll use BigQuery.

<br>

### Review

In this module, we covered the various storage services available in Google Cloud.

These include cloud storage for binary data, Cloud SQL, and Spanner for relational databases, Cloud Bigtable, and Firestore for NoSQL databases, and BigQuery for data warehouses.

We also talked about different storage characteristics and how they can be used to help you choose where to store your data.

<br>

## Module Intro: Designing Google Cloud Networks

In this module, we discuss Google Cloud network architectures including hybrid architectures.

We will start by talking about how to design VPC networks to optimize for cost, security, and performance.

Then, we'll cover the configuration of global and regional load balancers to provide access to services. As part of the load balancer configuration, you can enable Cloud CDN to provide a lower latency and decrease network egress, which ultimately decreases your networking costs.

We will also introduce the Network Intelligence Center to evaluate your networks architecture, and go over the network connection options including peering, VPN and Cloud Interconnect.

<br>

### Designing Google Cloud Networks

Let's get started by designing Google Cloud Networks and load balancers.

<br>

<img src="../assets/google_network.png" alt="Google Global Network" width="50%" height="50%">

<br>

Google runs a worldwide network that connects regions all over the world. You can use this high bandwidth infrastructure to design your cloud networks to meet your requirements, such as location, number of users, scalability, fault tolerance, and latency.

Let's take a closer look at Google Cloud's network.

<br>

<img src="../assets/google_cloud_network.png" alt="Cloud Network Reach" width="50%" height="50%">

<br>

This map represents Google Cloud's reach. On a high level, Google Cloud consists of regions which are the icons in blue, points of presence or `pops`, which are the dots in gray.

A global private network which is represented by the blue lines and services.

A region is a specific geographical location where you can run your resources. This map shows several regions that are currently operating, as well as future regions and zones. As of this recording, there are 21 regions and 64 zones. The pops are where Google's network is connected to the rest of the Internet.

Google Cloud can bring its traffic closer to its peers because it operates an extensive global network of interconnection points. This reduces costs and provides users with a better experience. The network connects regions and pops and is composed of a global network of fiber optic cables with several submarine cable investments.

<br>

<img src="../assets/vpc_networks.png" alt="VPC networks" width="50%" height="50%">

<br>

In Google Cloud, VPC networks are global. You can either create auto mode networks and have one subnet per region, or create your own custom mode network, where you get to specify which region to create a subnet in. Resources across regions can communicate using their internal IP addresses without any added Interconnect.

For example, the diagram on the right shows two subnets in different regions with a server on each subnet. They can communicate with each other using their internal IP addresses because they are connected to the same VPC Network. Selecting which regions to create subnets in depends on your requirements.

For example, if you are a global company, you will most likely create subnetworks in regions across the world. If users are within a particular region, it may be suitable to select just one subnet in a region closest to these users and maybe a backup region close by. Also, you can have multiple networks per project.

These networks are just a collection of regional subnetworks or subnets.

<br>

<img src="../assets/custom_subnets.png" alt="Custom Subnets" width="50%" height="50%">

<br>

To create custom subnets, you specify the region and the internal IP address range, as illustrated in the screenshots on the right. The IP ranges of the subnets don't need to be derived from a single site or block, but they cannot overlap with other subnets of the same VPC network. This applies to primary and secondary ranges. Secondary ranges allow you to define an alias IP addresses. Also, you can expand the primary IP address space of any subnets without any workload, shutdown or downtime.

Once you defined your subnets machines in the same VPC network can communicate with each other through the internal IP address, regardless of the subnet they're connected to.

<br>

<img src="../assets/vm_network_interfaces.png" alt="VM Network Interfaces" width="50%" height="50%">

<br>

Now, a single VM can have multiple network interfaces connecting to different VPC networks. This graphic illustrates an example of a Compute Engine instance connected to four different networks. Convering Production, Test, Infra, and Outbound Network.

A VM must have at least one network interface, that can have up to eight depending on the instance type and the number of vCPUs.

A general rule is that with more vCPUs, more network interfaces are possible.

All of the network interfaces must be created when the instance is created. Each interface must be attached to a different network.

<br>

<img src="../assets/shared_vpc.png" alt="Shared VPC Network" width="50%" height="50%">

<br>

Shared VPC allows an organization to connect resources from multiple projects of a single organization to a common VPC network. This allows the resources to communicate with each other securely and efficiently using internal IPs from that network.

This graphic shows a scenario where a shared VPC is used with three other projects, namely service projects A, B, and C. Each of these projects has a VM instance that is attached to the shared VPC.

Shared VPC is a centralized approach to multi-project networking because security and network policy occurs in a single designated VPC network. This allows for network administrators rights to be removed from developers so that they can focus on what they do best. Meanwhile, organization network administrators maintain control of resources such as subnets, firewall rules and routes, while delegating the control of creating resources such as instances to service project administrators or developers.

<br>

### Designing Google Cloud Load Balancers

Let's talk about load balancers.

<br>

<img src="../assets/global_load_balancers.png" alt="Global Load Balancers" width="50%" height="50%">

<br>

Global load balancers provide access to services deployed in multiple regions.

For example, the load balancer shown on this slide has a backend with two instance groups deployed in different regions. Cloud load balancing is used to distribute the load among these instance groups. Global load balancing is supported by HTTP load balancers and TCP and SSL proxies in Google Cloud.

For an HTTP load balancer, a global anycast IP address can be used simplifying DNS lookup. By default, requests are routed to the region closest to the requester.

For services deployed in a single region, use a regional load balancer.

<br>

<img src="../assets/regional_load_balancers.png" alt="Regional Load Balancers" width="50%" height="50%">

<br>

This graphic illustrates resources deployed with a single region and Cloud load balancing routing requests to these resources. Regional load balancers support HTTP and any TCP or UDP port. If your load balancers have public IP addresses, traffic will likely be traversing the Internet.

<br>

<img src="../assets/ssl_load_balancer.png" alt="Load Balancer SSL" width="50%" height="50%">

<br>

I recommend securing this traffic with SSL which is available for HTTP and TCP load balancers as shown in the screenshot on the right. You can use either self-managed SSL certificates or Google managed SSL certificates when using SSL.

Now, if you are using HTTPS load balancing, you should leverage Cloud CDN to achieve lower latency and decrease egress costs.

<br>

<img src="../assets/cloud_cdn.png" alt="Google CLoud CDN" width="50%" height="50%">

<br>

You can enable Cloud CDN by simply checking the box when configuring an HTTP global load balancer. Cloud CDN caches content across the world using Google Cloud's edge-caching locations. This means that content is cached closest to the user making the requests. The data that is cached can be from a variety of sources, including Compute Engine instances, GKE pods, or Cloud Storage buckets.

Let me recap this discussion on Google Cloud load balancers and summarize the types and their capabilities.

<br>

<img src="../assets/load_balancer_types.png" alt="Load Balancer Types Overview" width="50%" height="50%">

<br>

At a high level, load balances can work with internal or external IP addresses. We refer to external IP addresses as Internet-facing. The load balancers can be regional or multi-regional. And finally, they support different traffic types, HTTP, TCP, and UDP. Let's review these starting with the traffic type.

HTTPS Load Balancing is a Layer 7 load balancer. Support is provided for HTTP and HTTPS including HTTP/2. The load balancing supports both Internet-facing, and internal load balancing, as well as regional or global.

TCP Load Balancing provides Layer 4 balancing or proxy for applications that require TCP/SSL protocol. You can configure a TCP Load Balancer, or a TCP, or SSL proxy. TCP Load Balancing supports both Internet-facing, and internal load balancing, as well as regional and global.

UDP Load Balancing is for those applications that rely on UDP as a protocol. The UDP Load Balancer supports both Internet-facing, and internal load balancing, but only regional traffic.

As part of our discussion of designing VPC networks, I also want to mention the Network Intelligence Center.

<br>

<img src="../assets/network_intel_center.png" alt="Network Intelligence Center" width="50%" height="50%">

<br>

The Network Intelligence Center is a Google Cloud service that can be used to visualize your VPC network topology and test network connectivity.

The left-hand graphic shows a simple network topology visualization with external clients in three different regions, and traffic routed through an external load balancer to resources in US Central one. This facility is extremely valuable for confirming the network topology when configuring a network or when performing diagnostics. The right-hand graphic shows the configuration of a connectivity test between a source and destination along with a protocol and port.

The following tests can be performed.

- Between source and destination and points in your VPC network
- From your VPC Network to and from the Internet
- From your VPC network to and from your on-premises network

<br>

### Activity Intro: Defining Network Characteristics

In this design activity, you specify the network characteristics for your case study and select the type of load balancer required for each service.

In the first part of this activity, describe the network characteristics of each of your services by filling out this table.

The example shown here is for the account service. Because this is a backend service, you will only be access internally using TCP, and we don't plan to deploy the service in multiple regions.

Then based on the network characteristics for each of your services, select the right load balancer using this table. Based on the parameters from the last slide, we will use the regional TCP load balancer.

Refer to activities 8A and B in your design workbook to fill out similar tables for your services.

Feel free to explore Cloud CDN to decrease latency and network egress costs.

<br>

### Activity Review: Defining Network Characteristics

In this activity, you are asked to specify the network characteristics of each of your services, and choose the appropriate load balances for each one.

Here's a completed example for our online Travel Portal, Click Travel.

The Inventory and Order Service are internal and regional using TCP. The other services need to be facing the Internet using HTTP.

We decided to deploy these to multiple regions for lower latency, higher performance, and high availability to our users who are in multiple countries around the world.

Based on those network characteristics, we chose the global HTTP load balancer for our public facing services, and the internal TCP load balancer for our internal facing services

<br>


### Connecting Networks

Let's focus our attention on Google Cloud's network connectivity products, which are peering, Cloud VPN, and Cloud Interconnect.

If you're trying to connect two VPC networks, you might want to consider VPC peering.

<br>

<img src="../assets/vpc_peering.png" alt="VPC Peering" width="50%" height="50%">

<br>

VPC peering allows private RFC 1918 connectivity across two VPC networks regardless of whether they belong to the same project or the same organization.

Now remember, each VPC network will have firewall rules that define traffic that is allowed or denied between the networks. This diagram shows a VPC peering connection between two networks belonging in different projects and different organizations. You might notice that the subnet ranges do not overlap. This is a requirement for a connection to be established.

Speaking of the connection, network administrators for each VPC network must configure a VPC peering request for a connection to be established.

<br>

<img src="../assets/cloud_vpn.png" alt="Cloud VPN" width="50%" height="50%">

<br>

Cloud VPN securely connects your on-premises network to your Google Cloud VPC network through an IPsec VPN tunnel. Traffic traveling between the two networks is encrypted by one VPN gateway and then decrypted by another VPN gateway. This protects your data as it travels over the public Internet.

That's why Cloud VPN is useful for low volume data connections.

As a managed service, Cloud VPN provides an SLA of 99.9 percent monthly uptime for the classic VPN Configuration and 99.99 percent monthly uptime for the high availability VPN configuration.

The classic VPN gateways have a single interface and a single external IP address. Whereas the high availability VPN gateways have two interfaces with two external IP addresses, one for each gateway.

The choice of VPN gateways comes down to your SLA requirements and routing options. Cloud VPN supports, site-to-site VPN, static routes and dynamic routes using Cloud Router, and IKEv1 and IKEv2 ciphers. However, static routes are only supported by classic VPN.

Also, Cloud VPN doesn't support use cases where clients computers need to dial in to a VPN using Client VPN software.

For more information on the SLA and these features refer to the documentation.

<br>

<img src="../assets/vpn_topology.png" alt="VPN Topology" width="50%" height="50%">

<br>

Let's walk through an example of Cloud VPN. This diagram shows a classic VPN connection between your VPC and on-premises network.

Your VPC network has subnets in us-east1 and us-west, with the Google Cloud resources in each of those regions. These resources are able to communicate using their internal IP addresses because routing within a network is automatically configured, assuming that firewall rules allow the communication.

Now, in order to connect your on-premises network and it's resources, you need to configure your Cloud VPN gateway, your on-premises VPN gateway, and two VPN tunnels.

The Cloud VPN gateway is a regional resource that uses a regional external IP address. Your on-premises VPN gateway can be a physical device in your data center, or a physical or software based VPN offering in another Cloud providers network.

This VPN gateway also has an external IP address.

A VPN tunnel then connects your VPN gateways and serves as a virtual medium to which encrypted traffic is passed. In order to create a connection between two VPN gateways, you must establish two VPN tunnels. Each tunnel defines a connection from the perspective of it's gateway and traffic can only pass when a pair of tunnels is established.

Now, one thing to remember when using Cloud VPN is the maximum transmission unit or MTU for your on-premises VPN gateway cannot be greater than 1,460 bytes. This is because of the encryption and the capsulation of packets.

For more information on this MTU consideration, refer to the documentation.

In addition to classic VPN, Google Cloud also offers a second type of Cloud VPN gateway, HA VPN.

<br>

<img src="../assets/ha_vpn.png" alt="HA VPN" width="50%" height="50%">

<br>

HA VPN is a high availability Cloud VPN solution that lets your securely connect to your on-premises network, to your Virtual Private Cloud through IPSec VPN connection in a single region. HA VPN provides an SLA of 99.99 percent service availability. To guarantee a 99.99 percent availability SLA for HA VPN connections, you must properly configure two or four tunnels from your HA VPN gateway to your peer VPN gateway, or to another HA VPN gateway.

When you create a HA VPN gateway, Google Cloud automatically chooses two external IP addresses. One for each of it's fixed number of two interfaces. Each IP address is automatically chosen from a unique address pool to support high availability. Each of the HA VPN gateway interfaces support multiple tunnels. You can also create multiple HA VPN gateways. When you delete the HA VPN gateway, Google Cloud releases the IP addresses for reuse.

You can configure HA VPN gateway with only one active interface and one external IP address. However, this configuration does not provide a 99.99 percent service availability SLA.

VPN tunnels connected to HA VPN gateways must use dynamic routing, BGP. Depending on the way that you configure root priorities for HA VPN tunnels, you can create an active active, or active passive routing configuration. HA VPN supports site-to-site VPN in one of the following recommended topologies or configuration scenarios.

- A HA VPN gateway to peer VPN devices
- A HA VPN gateway to an Amazon Web Services virtual private gateway
- or two HA VPN gateways connected to each other

Let's explore these configurations in a bit more detail.

<br>

<img src="../assets/gateway_topology.png" alt="HA VPN to Peer VPN Gateway Topology" width="50%" height="50%">

<br>

There are three typical peer gateway configurations for HA VPN.

A HA VPN gateway to two separate peer VPN devices, each with its own IP address.

A HA VPN gateway to one peer VPN device that uses two separate IP addresses.

And a HA VPN gateway to one peer VPN device that uses one IP address.

Let's walk through an example. In this topology, one HA VPN gateway connects to two peer devices. Each peer device has one interface and one external IP address. The HA VPN gateway uses two tunnels, one tunnel to each peer device. If your peer side gateway is hardware-based, having a second peer side gateway provides redundancy and fail-over on that side of the connection.

A second physical gateway lets you take one of the gateways offline for software upgrades or for other scheduled maintenance. It also protects you if there is a failure in one of your devices.

In Google Cloud, the redundancy type for this configuration takes the value two IPs redundancy.

The example shown here provides 99.99 percent availability.

<br>

<img src="../assets/ha_vpn_to_aws.png" alt="HA VPN to AWS Gateway Topology" width="50%" height="50%">

<br>

When configuring a HA VPN external VPN gateway to Amazon Web Services, you can use either a transit gateway or a virtual private gateway. Only the transit gateway supports equal cost multipath or ECMP route. When enabled, ECMP equally distributes traffic across active tunnels.

Let's walk through that example.

In this topology, there are three major gateway components to set up for this configuration. A HA VPN gateway in Google Cloud with two interfaces, two AWS virtual private gateways, which connect to your HA VPN gateway, and an external VPN gateway resource in Google Cloud that represents your AWS virtual private gateway.

This resource provides information to Google Cloud about your AWS gateway.

The supported AWS configuration uses a total of four tunnels, two tunnels from one AWS virtual private gateway to one interface of the HA VPN gateway, and two tunnels from the other AWS virtual private gateway to the other interface of the HA VPN gateway.

<br>

<img src="../assets/ha_vpn_to_peer.png" alt="HA VPN to Peer VPN gateway" width="50%" height="50%">

<br>

You can connect two Google Cloud VPC networks together using a HA VPN gateway in each network.

The configuration shown provides 99.99 percent availability.

From the perspective of each HA VPN gateway, you create two tunnels. You connect interface zero on one HA VPN gateway to interface zero on the other HA VPN gateway, and interface one on one HA VPN gateway to interface one on the other HA VPN gateway.

**For more information on HA VPN, refer to the documentation.**

**For information on moving to HA VPN, also refer to the documentation.**

I mentioned earlier that Cloud VPN supports both static and dynamic routes.

<br>

<img src="../assets/cloud_router.png" alt="Cloud Router" width="50%" height="50%">

<br>

In order to use dynamic routes, you need to configure Cloud Routers. A Cloud Router can manage routes for a Cloud VPN tunnel using Border Gateway Protocol or `BGP`.

This routing method allows for routes to be updated and exchanged without changing the tunnel configuration. This allows for new subnets like staging in the VPC network and rack 30 in the peer network to be seamlessly advertised between networks.

If you need a dedicated high-speed connection between networks, consider using Cloud Interconnect.

<br>

<img src="../assets/cloud_interconnect.png" alt="Cloud Interconnect" width="50%" height="50%">

<br>

Cloud Interconnect has two options for extending on-premises networks.

Dedicated Interconnect and Partner Interconnect.

Dedicated Interconnect provides a direct connection to a co-location facility. The co-location facility must support either 10 gigabits per second or 100 gigabits per seconds circuits. A dedicated connection can bundle up to eight 10 gigabits per second connection or two 100 gigabits per second connection for a maximum of 200 gigabits per second.

Partner Interconnect provides a connection through a service provider. This can be useful for lower bandwidth requirements, starting from 50 megabits per second. In both cases, Cloud Interconnect allows access to VPC resources using an internal IP address space.

You can even configure Private Google Access for on-premises hosts to allow them to access Google services using private IP addresses.

<br>

<img src="../assets/dedicated_interconnect.png" alt="Dedicated Interconnect" width="50%" height="50%">

<br>

In order to use Dedicated Interconnect, you need to provision a cross connect between the Google network and your own router in a common co-location facility, as shown on this diagram. To exchange routes between the networks, you configure a BGP session over the interconnect between the Cloud Router and your on-premises router.

This will allow for user traffic from the on-premises network to reach Google Cloud resources on the VPC network and vice-versa.

<br>

<img src="../assets/partner_interconnect.png" alt="Partner Interconnect" width="50%" height="50%">

<br>

Partner Interconnect provides connectivity between your on-premises network and your VPC network through a supported service provider. This is useful if your data center isn't a physical location that cannot reach a Dedicated Interconnect co-location facility or if your data needs don't warrant a Dedicated Interconnect.

<br>

### Activity Intro: Diagramming Your Network

In this design activity, you draw a diagram that depicts the network requirements of your case study.

Let me show you a simple example.

<br>

<img src="../assets/network_example.png" alt="Network Example" width="50%" height="50%">

<br>

This network diagram shows where the network boundaries are and how traffic is served from our users through a load balancer to our backend.

We could also include the use of Cloud CDN, Cloud VPN, or any Cloud Interconnect services that are relevant to our network design.

Refer to Activity 9 in your workbook to create a similar network diagram for your services.

<br>

### Activity Review: Diagramming Your Network

In this activity, you are asked to create a diagram that depicts the network requirements of your application.

Here's an example for our online travel portal, Click Travel.

<br>

<img src="../assets/network_example2.png" alt="Network Example #2" width="50%" height="50%">

<br>

User traffic from mobile and web will first be authenticated using a third party service. Then a global HTTP load balancer directs traffic to our public facing search and web UI services.

From there, regional TCP load balances direct traffic to the internal inventory and order services.

The Analytics service could leverage BigQuery as the data warehouse with an on-premise reporting service that accesses the Analytics service over a VPN.

This might be good enough to start and we could refine this once we start implementing it.

<br>

### Review

In this module, you learned about Google Cloud networking and how to design networks that meet your application security, performance, reliability, and scalability requirements.

We also covered the different options to connect networks using Peering, VPN, and Cloud Interconnect.

<br>

## Overview - Deploying Applications to Google Cloud

In this module, we discuss the different options of deploying applications to Google Cloud.

Google Cloud offers many possible deployment platforms, and the choice is not always immediately obvious.

<br>

<img src="../assets/choosing_deployment.png" alt="Choosing GCP Deployment" width="50%" height="50%">

<br>

Let me give you a high-level overview of how you could decide on the most suitable platform for your application.

First, ask yourself whether you have specific machine and OS requirements. If you do, then Compute Engine is a platform of choice.

If you have no specific machine or operating system requirements, then the next question to ask is whether you are using containers.

If you are, then you should consider Google Kubernetes Engine or Cloud Run. Depending on whether you want to configure your own Kubernetes cluster.

If you are not using containers, then you want to consider Cloud Functions if your service is event-driven, and App Engine if it's not.

We'll talk through each of these services in this module, and you will get to explore them in a lab. Let's get started.

<br>

### Google Cloud Infrastructure as a Service

Let's begin by talking about Compute Engine, which is Google cloud's infrastructure as a service or IaaS offering.

<br>

<img src="../assets/compute_engine.png" alt="Compute Engine" width="50%" height="50%">

<br>

Compute Engine is a great solution when you need complete control over your operating systems, or if you have an application that is not containerized, an application built on a micro service architecture or an application that is a database. Instance groups and auto-scaling as shown on this slide allow you to meet variations in demand on your application.

Let's take a closer look at instance groups.

<br>

<img src="../assets/instance_groups.png" alt="Managed Instance Groups" width="50%" height="50%">

<br>

Managed instance groups create VMs based on instance templates. Instance templates are just a resource used to define VMs and manage instance groups. The templates define the boot disk image or container image to be used, the machine type, labels and other instance properties like a startup script to install software from a GIT repository.

The virtual machines in a managed instance group are created by an instance group manager. Using a managed instance group offers many advantages such as auto healing to recreate instances that don't respond and creating instances in multiple zones for high availability.

<br>

<img src="../assets/instance_groups_backend.png" alt="instance groups for backend" width="50%" height="50%">

<br>

I recommend using one or more instance groups as the backend for load balancers. If you need instance groups in multiple regions, use a global load balancer. And if you have static content, simply enable Cloud CDN as shown on the right.

<br>

### Google Cloud Deployment Platforms

Let's go through the other deployment platforms.

GKE, Cloud Run, App Engine and Cloud Functions.

<br>

<img src="../assets/gke" alt="GKE environment" width="50%" height="50%">

<br>

Google Kubernetes Engine, or GKE provides a managed environment for deploying, managing and scaling containerized applications using google infrastructure. The GKE environment consists of multiple compute engine virtual machines grouped together to form a cluster.

GKE clusters are powered by the kubernetes open source cluster management system. Kubernetes provides the mechanisms with which to interact with the cluster. Kubernetes commands and resources are used to deploy and manage applications, perform administration tasks and set policies and monitor the health of deployed workloads. This diagram on the right shows the layout of a kubernetes cluster. A cluster consists of at least one cluster control plane and multiple working machines that are called nodes. These control plane and node machines run the kubernetes cluster orchestration system.

Pods are the smallest, most basic deployable objects in kubernetes. A pod represents a single instance of a running process in a cluster. Pods contain one or more containers, such as docker containers that run the services being deployed. You can optimize resource use by deploying multiple services to the same cluster.

<br>

<img src="../assets/cloud_run.png" alt="Cloud Run" width="50%" height="50%">

<br>

Cloud Run, on the other hand, allows you to deploy containers to a Google managed kubernetes cluster. A big advantage is that you don't need to manage or configure the cluster. The services that you deploy must be stateless and the images you use must be in Container Registry.

Cloud Run can be used to automate deployment to Anthos GKE clusters. You should do this if you need more control over your services, because it will allow you to access your VPC network, tune the size of compute instances and run your services in all GKE regions. The screen shot on the right shows a Cloud Run configuration where the Container image url is specified along with the deployment platform, which can be fully managed Cloud Run or Cloud Run for Anthos.

<br>

<img src="../assets/app_engine.png" alt="App Engine" width="50%" height="50%">

<br>

App Engine is a fully managed serverless application platform supporting the building and deploying of applications.

Applications can be scaled seamlessly from zero upward without having to worry about managing the underlying infrastructure. App Engine was designed for microservices. For configuration each google cloud project can contain one app engine application, and an application has one or more services. Each service can have one or more versions and each version has one or more instances.

App engine supports traffic splitting so it makes switching between versions and strategies such as canary testing or A/B testing simple.

The diagram on the right shows the high level organization of a google cloud project with two services and each service has two versions. These services are independently deployable and versioned.

Let me show you a typical app engine micro service architecture.

<br>

<img src="../assets/app_engine_microservices.png" alt="App Engine Microservices Architecture" width="50%" height="50%">

<br>

This could be an example of a retailer that sells online. Here, App Engine serves as the front end for both web and mobile clients. The back end of this application is a variety of google cloud storage solutions with static content such as images stored in cloud storage, Cloud SQL, used for structured relational data such as customer data and sales data, and Firestore, used for NoSQL storage such as product data. Firestore has the benefit of being able to synchronize with client applications. Memcached is used to reduce the load on the data stores by caching inquiries, and cloud tasks are used to perform work a synchronously outside a user request or service to service request. There's also a batch application that generates data reports for management.

<br>

<img src="../assets/cloud_functions.png" alt="Cloud Functions" width="50%" height="50%">

<br>

Cloud functions are a great way to deploy loosely coupled event driven microservices. They have been designed for processing events that occur in Google Cloud. The functions can be triggered by changes in a cloud storage bucket, a Pub/Sub message or http requests.

The platform is completely managed, scalable and inexpensive. You do not pay if there are no requests and processing is paid for by execution time in 100 millisecond increments.

This graphic illustrates an image translation service, implemented with Cloud Functions.

When an image is uploaded to a cloud storage bucket, it triggers an OCR Cloud Function that identifies the text in the image using Google Cloud Vision API. Once the text has been identified, this service then published as a message to a Pub/Sub topic for translation, which triggers another Cloud Function that will translate the identified text and the image using the Cloud Translation API.

After that, the translator cloud function will publish a message to a file write topic in Pub/Sub, which triggers a cloud function that will write the translated image to a file.

This sequence illustrates a typical use case of Cloud Functions for event based processing.

<br>

#### Lab Intro: Deploying Apps to Google Cloud

In the first lab of this course, you used Cloud Build to create Docker images and store those images in container registry.

If you follow the 12-Factor best practices when writing your applications, you should be able to create applications that are portable across different cloud providers and also portable between different deployment services provided by the cloud.

That's why in this lab, you deploy code to App Engine, Google kubernetes Engine and Cloud Run.

Let's quickly go over why we chose those services for this lab.

Deploying your dockerized application to a virtual machine using computer engine in the first lab was easy. But that might not be the most effective option.

A more automated way might be using App Engine, which will be the first compute platform of this lab.

App Engine is great for those who just want to focus on their code and not worried at all about the underlying infrastructure like networks, load balancers and auto scalers, which are completely managed by App Engine.

Now, sometimes developers want more freedom to customize their environments. Google Kubernetes Engine or GKE provides a balance where you have a lot of customization over your environment similar to Compute Engine. However, GKE also helps you optimize your spend by allowing you to deploy multiple services into the same cluster of virtual machines.

This provides an excellent balance between flexibility, portability and cost optimization.

Kubernetes can get pretty complicated though. That's where Cloud Run comes in.

Cloud Run allows you to deploy your own stateless dockerized services onto Kubernetes clusters that are managed by Google. Google Cloud takes care of the hard parts of managing the cluster and configuring the load balancers, auto scales and health checkers, so that you just focus on the code.

Deploying a single application on all of these platforms might help you choose the right platform for your own services.

<br>

#### Lab Review: Deploying Apps to Google Cloud

In this lab, you saw how to deploy an application to App Engine, GKE and Cloud Run. Hopefully, this lab gives you a better feel for how each of these compute platforms work, and will help you choose the right platform for your own services. I recommend that you follow the 12-factor best practices that we covered earlier in this course. Automate as much as possible by using continuous integration and infrastructure as code tools, and containerize your services using Docker. If you do that, your apps will be very portable, and deployment will become easier and more flexible. No matter which Compute platform you use. You can stay for a lab walk-through, but remember that Google Cloud's user interface can change, so your environment might look slightly different. So here I'm in the Cloud console, and the first thing we're going to do is activate Cloud Shell, and within any project you will have to say continue, and I like opening this in a new window. So what we're going to do is we're going to create a directory and navigate to it, and then we're going to clone a GitHub repository that we have, we make a directory, then we navigate to that directory and we're going to clone our GitHub repository. We use this for a lot of other courses. It's a public GitHub repository, and the benefit of that is it actually allows you to contribute. So if you think there could be a great modification we can make, either because something's broken or we could enhance something, you can actually make a pull request and we'll review that. We're cloning that, and once that is done, we're going to navigate to the folder that it has created, and we're just going to test the program that is in here. The Python Flask-app. So let me navigate to that and then we're going to launch this. Here it is running and since it's running on port 8080, and Kaltura gives you a Preview button, so we can actually go in and see what that looks like. It's currently just saying, "Hello GCP." So somewhere there's a file in here that defines that. Great, so we can now close that. So that's really the first step. We just wanted to see what this application is. Now we're going to move on and apply this to App Engine, Kubernetes Engine, and Cloud Run, and look at some of the differences and similarities between those. Now, first we're going to do App Engine. For that, I'm going to open the editor and we're going to create a file called app.yaml. In that file, we need to define the runtime. App Engine actually runs with multiple languages. You can use Python, Java, JavaScript, and Go. So I'm going to define that by going into here, Courses, Design and Process is the same directory that we are currently in down here and here by the way, if I go to main py, we can see this is where it said, Hello GCP. So within this folder, I'm going to create a new file and call it app.yaml. In there, I'm going to define the runtime. Now there are other settings that we could specify here, but in this case, the language runtime is the required one. So let's go, File, Save. We're going to make this a little bit bigger, so we can see bit more here. Now we're going to run Digital Cloud App Create Command. For that, we need to specify the region where this app is created. So we're going to use the instructions to specify this in US central. It is telling us that currently, it hasn't picked up the project. There's actually pretty good error that you might get. So let's actually work through this. So it currently says that the project property is set to an empty string and that's invalid. So let's go to G Cloud Config Set Project, it's telling us to run that command. Let me run that. I'm going to go grab my project ID by going to the Cloud console. I actually have it here, or I could go in here and grab it as well, or you can even grab it from your Qwiklabs UI. So let me go ahead and set that. It has updated that, now let me just try to run that command again, and now we can see that is creating an App Engine application for that project in the region that we specified. Now once this is complete, we're going to deploy the app, we'll just initially going to call it Version 1. So let's do that. This is going to take a couple minutes. Once this is complete, we're going to go into App Engine and actually test this program. So we can see that the command is complete. So now I'm going to go to Cloud Console by switching tabs, and we're going to navigate to App Engine. Navigation menu, App Engine, and create some more space here, hide some of these things. So here we see our dashboard. We currently have one version. It's certainly all about traffic, and if I click on this link, which by the way, by default this URL is always going to be in a format HTTPS, the Project ID, appspot.com. So you click on that, and we should see Hello GCP. So we now have this running on App Engine. Great. So let's actually make a change to the program and see how easy App Engine makes managing versions. So I'm going to go back to Cloud Shell, and I mentioned earlier that this main py file here says Hello GCP, and that's what we're seeing. So let's change this to Hello App Engine. So we're going to make that change and save it. What we need to do now is we need to redeploy this. But rather than overwriting our existing version, let's actually create a new version. So I'm going to run the command gcloud app deploy Version 2, and I'm going to use the no promote parameter to tell App Engine to continue serving the request to the old version, Version 1. This is great because it allows us to test a new version before putting it into production. So let's wait for this to complete. So we can see that this has been completed, and if I go back to my application by just changing tabs to it, and click the Refresh button, you see it still says Hello GCP, and that's because Version 1 is the one that's serving all the traffic. So let's explore that more. I'm going to go back to App Engine, and specifically the dashboard. On the left here, I can click on Versions, and if I click Refresh, we can see that we currently have two versions, but the original one, Version 1, is still serving all of our traffic. So what we can do now is we could test this and once it's ready, we can migrate our traffic. So let me actually test this. I can click on Version 2 and I can see that, yeah, this is how App Engine, and this is a very simplification, you would want to do some more testing here. But once I'm comfortable with this, I can go back to Versions and I can go to Split Traffic, traffic allocated to two, and there's some different options here. You can split by IP address, cookie, or random, and I'm going to click Save because I'm going to say this is going to receive 100 percent of the traffic. If I add a version that could actually split and split by. In this case, I'm really just saying, "Hey, all traffic should go to Version 2." So this is going to take a minute or two now to complete, and once this is done, it actually says saved successfully. So let's go back. We can see that it is saying that all the traffic is there, and now if I go back to the dashboard and use the link, we can see that it now says Hello App Engine. That's it for deploying this in App Engine.

So now what we're going to do is, we're going to go ahead and deploy this to Kubernetes Engine. Kubernetes Engine allows you to create a cluster of machines and deploy any number of applications to it. So before we get into that, I'm going to close some of these tabs just to make some space here. We're going to go now in the Navigation menu to Kubernetes Engine. So Navigation menu, it's under Compute, click on Kubernetes Engine. Within here, we're going to create a cluster. There are a lot of different settings in here. This course is not really an introduction course on Kubernetes. There's this new experience here that you can now use. We're just going to accept the defaults. So we see it just has a name, it has a region. You can specify the version of the master and nodes and so on. But I'm just going to keep all the defaults for now and just click Create because really what we're doing is we're comparing how to deploy an application to App Engine, Kubernetes Engine and Cloud run. So once this cluster is up and running, we're going to connect to it, which is really going to give us some commands for Cloud Shell. So let's wait for this cluster to be ready, and while we wait, feel free to go to the navigation menu and head over to Compute Engine. If you refresh this here, they're not quite here yet, you will see the different nodes that are going to be created because they're actually Compute Engine instances. So I'll go right back, refresh, we could sit in here for a while, and then we'll see that we actually get some Compute Engine instances. Let's wait for that to complete and come back. So here we can see that the Kubernetes cluster is now cleared, it's running, and if I head back to Compute Engine as I showed earlier, here you can see the actual nodes. So Kubernetes Engine is using Compute Engine virtual machines as a nodes, but they're being managed for you. If you remember back in the previous lab, you actually launched a container on a Compute Engine in instance. Here, we are not using Kubernetes Engine to have all of this be managed for us. So we want to connect to this. So if we go to Kubernetes Engine, we can see there's a Connect button here, and here's the command line way of connecting very specifically for the cluster that we have, the zone it's in, and the project. I could run this in culture with this button, or I can just copy this and go to my existing cultural session over here and paste the command in there. So we're going to run that, and now we can see this configured. We're going to now run the command `kubectl get nodes`. This is just going to show us the node. So here we can see again these nodes, and these are the same that I can see in Compute Engine as well. So now we're going to want to make some changes to this main.py file. I'm already in the code editor. Rather than saying, "Hello App Engine Kubernetes", I would like it to say, "Hello Kubernetes Engine." So let's type that in there and let's save that. Now we haven't deployed anything to the cluster yet, so we're going to have to do that now. Specifically, we're going to create a configuration file in YAML format. So within the developing apps, the GCP folder, I'm going to right-click and say New File, give it the name Kubernetes-config.yaml,and we already have a configuration for you. Again, this course is not about how to really work with Kubernetes, we're really just comparing. But if we scroll through here, we can see some of the configurations in here. You can see information of the front end. We see information about the container, and the image. We actually don't have an image yet, so we're going to have to put that there. We can see this is going to be load balancer on port 80. So it's, it's just an HTTP application. So again, first section of this YAML file is really about the configuration. We're deploying three instances, so three rapid class of the Python web app. We have these image attributes again. If you want more information, the lab instructions actually have some links on deployment and creating the external load balancer. So we see here this load balancer. In our case, we want to now really just create and we're going to build a Docker image. So for that, let's first make sure we're on the right folder. You can copy that in there, which we still are. Then we're going to run the command `gcloud build summit`. That's going to take a project ID, which is again an environment variable, and we're now going to create an image, and we're going to call it version 0.2. So we're going to let this build now, and at the end, we should see the image with our project ID, the name, and the version. I'm going to copy that and we're going to paste it into our Kubernetes-config.yaml file.

So the image is complete and it's right here. So we can now take that and paste it into our configuration file. So there we go, and we can save that. Now we're going to have to apply this configuration. So the command for that is in the lab instructions `kubectl apply`, and we specify the YAML file. So now we can look at the pods. There should be three replicas. There we can see that the container is being created. It's only been eight seconds, so we can wait for that. You want to make sure that you wait for all of these to be ready, and you can just keep cryint to check on the status of these.

So here we can see I query just 20 seconds later, and now all of these are running. Now the configuration file also mentions a load balancer. So if we go down here, we can see a load balancer. So let's actually get to the services.

Here we have an external IP address. So let's go grab that external IP address and navigate to it, and see if we can already see this application. So I'm going to just open a new tab, navigate to that by typing the external IP address, and there we can see it says Hello Kubernetes Engine. That really completes task 3. So we've seen App Engine, we've seen Kubernetes Engine. There's one more to go.

Let's move onto Cloud Run. Now, Cloud Run simplifies and automates deployments kubectl Kubernetes. So when you use Cloud Run, you don't need a configuration file. You simply choose a cluster for your application. With Cloud Run, you can use a cluster managed by Google or you can use your own Kubernetes cluster. So we wanted to do the same thing we did before. We want to change this main.py file, and then we're going to have to, in this case, need to create a new Docker image. So let's go back to Cloud Shell again. I don't need a configuration file. I needed that both for App Engine and for Kubernetes Engine. So I'm just going to main.py, and call this our Cloud Run and save. Now to use Cloud Run, we need to build a Docker image. So in Cloud Shell, we're going to add to some commands to use Cloud Build to create the image and store it in our container registry. So let me just clear this here and let me make sure I navigate to the right directory and then create a new image here. Once that is complete, we're going to go to Cloud Run, and create a service from here. So we can see the build completed. In here we have the image. So now let's navigate to Cloud Run. So I'm going to switch to the Cloud Console, go to the navigation menu and under Compute, select Cloud Run. Now in case Cloud Run was enabled, which is the case here, we can see Start using Cloud Run. This is going to enable the API. See it's enabling the Cloud Run API, encloses panel here, and we're going to now create a service.

t's telling us the API has been enabled. So let's do that one more time, and we're going to now select the container Image. So under Cloud Run image, we can see this image that we just created just now. Let's go click continue. Then there's some other things we can set here while this is running and so on. Let's just expand all these options. The most important one that we're going to select is the allow unauthenticated invocations because we're creating a public API website. Scroll all the way down, we can leave all these other defaults and click Create. Now it really shouldn't take too long for this service to deploy, and we should see a green check once this is ready, and then we can click on the URL that will automatically generated and test it, and hopefully it will say, "Hello Cloud Run." This took maybe 1-2 minutes, which was not as long as the Kubernetes, but it still takes some time. You can see the green checkmark here, we see the URL. So if I click on that, you can see Hello Cloud Run. That's the end of the lab.

<br>

### Review

In this module, we covered the various deployment services provided by Google.

These include compute engine, if you need complete control over your deployment environment.

Google Kubernetes Engine if you want the flexibility, portability and automation that is provided by Kubernetes.

And App Engine and Cloud Run if you want a completely managed platform-as-a-service.

Again, each of these choices has advantages and disadvantages, make sure you understand each one. So that you can make an informed decision when deploying your services

<br>

## Module Overview: Designing for Reliability

In this module, we talked about how to design reliable systems. Specifically will go over how to design services to meet requirements for availability, durability, and scalability.

We will also discuss how to implement fault-tolerant systems by avoiding single points of failure, correlated failures, and cascading failures.

Overload can also be a challenge in distributed systems, and we will see how to avoid overload failures by using design patterns such as the circuit breaker and truncated exponential back-off.

How does design resilient data storage systems with lazy deletion is introduced. When things go wrong, we want our system to stay in control. So we discuss design decisions for different operational states, including normal, degraded, and failure scenarios.

Finally, we cover how to analyze disaster scenarios and plan, implement, and test for disaster recovery.

<br>

### Key Performance Metrics

Let's start by considering the key performance metrics for reliable systems.

When designing for reliability, consider availability, durability, and scalability as the key performance metrics.

<br>

<img src="../assets/key_performance_metrics.png" alt="Key Performance Metrics" width="50%" height="50%">

<br>

Let me explain each of these. Availability is the percent of time a system is running and able to process requests, to achieve high availability, monitoring is vital.

Health checks can detect when an application reports that it is okay. More detailed monitoring of services using white box metrics to count traffic successes and failures will help predict problems.

Building in fault tolerance by, for example, removing single points of failure is also vital for improving availability. Backup systems also play a key role in improving availability.

Durability is the chance of losing data because hardware or system failure. Ensuring that data is preserved and available is a mixture of replication and backup. Data could be replicated in multiple zones. Regular restores from backup should be performed to confirm that the process works as expected.

Scalability is the ability of a system to continue to work as user load and data grow. Monitoring and auto scaling should be used to respond to variations and load. The metrics for scaling could be the standard metrics like CPU or memory, or you can create custom metrics like number of players on a game server.

<br>

### Designing for Reliability

Now that we've covered the key performance metrics, let's design for reliability.

<br>

<img src="../assets/single_points_of_failure.png" alt="Avoid Single Points of Failure" width="50%" height="50%">

<br>

Avoid single points of failure by replicating data and creating multiple Virtual Machine instances. It is important to define your unit of deployment and understand its capabilities.

**To avoid single points of failure, you should deploy two extra instances, or N+2 to handle both failure and upgrades.**

These deployments should ideally be in different zones to mitigate for zonal failures.

Let me explain the upgrade consideration. Consider three VMs that are load balanced to achieve N+2. If one is being upgraded and another fails, 50 percent of the available capacity of the compute is removed, which potentially doubles alone on the remaining instance and increases the chances of that failing.

This is where capacity planning and knowing the capability of your deployment unit is important.

Also, for ease of scaling, it is a good practice to make the deployment units interchangeable stateless clones. It is also important to be aware of correlated failures.

<br>

<img src="../assets/correlated_failures.png" alt="Correlated Failures" width="50%" height="50%">

<br>

These occur when related items fail at the same time. At the simplest level, if a single machine fails, all requests served by that machine fail. At a hardware level, if a top of rack switch fails, the complete rack fails. At the Cloud level, if a zone or region is lost, all the resources are unavailable. Servers running the same software suffer from the same issue. If there is a fault in the software, the servers may fail at a similar time.

Correlated failures can also apply to configuration data.

If a global configuration system fails and multiple systems depend on it, they potentially fail too. When we have a group of related items that could fail together, we refer to it as a failure or fault domain.

<br>

<img src="../assets/avoid_correlated_failures.png" alt="Avoid Correlated Failures" width="50%" height="50%">

<br>

Several techniques can be used to avoid correlated failures. It is useful to be aware of failure domains. Then servers can be decoupled using microservices distributed among multiple failure domains. To achieve this, you can divide business-logic into services based on failure domains and deploy to multiple zones and, or regions.

At a finer level of granularity, it is good to split responsibilities into components and spread these over multiple processes. This way, a failure in one component will not affect other components. If all responsibilities are in one component, a failure in one responsibility has a high likelihood of causing all responsibilities to fail.

When you design microservices, your design should result in loosely coupled, independent but collaborating services. A failure in one service should not cause a failure in another service. It may cause a collaborating service to have reduced capacity or not be able to fully process it's workflows, but the collaborating service remains in control and does not fail.

<br>

<img src="../assets/cascading_failures.png" alt="Cascading Failures" width="50%" height="50%">

<br>

Cascading failures occur when one system fails, causing others to be overloaded and subsequently fail.

For example, a message queue could be overloaded because a backend fails and it cannot process messages placed on the queue. The graphic on the left shows a Cloud Load Balancer distributing load across to backend servers. Each server can handle a maximum of 1,000 queries per second. The load balancer is currently sending 600 queries per second to each instance. If Server B now fails, all 1,200 queries per second have to be sent to just Server A as shown on the right.

This is much higher than the specified maximum and could lead to cascading failure.

So how do we avoid cascading failures? Cascading failures can be handled with support from the deployment platform. For example, you can use health checks in Compute Engine or readiness and liveliness probes in GKE to enable the detection and repair of unhealthy instances. You want to ensure that new instances start fast and ideally do not rely on other backends or systems to startup before they are ready.

<br>

<img src="../assets/avoid_cascading_failures.png" alt="Avoid Cascading Failures" width="50%" height="50%">

<br>

The graphic on this slide illustrates a deployment with four servers behind a load balancer. Based on the current traffic, a server failure can be absorbed by the remaining three servers as shown on the right-hand side. If the system uses Compute Engine with instance groups and auto healing, the failed server would be replaced with a new instance.

As I just mentioned, it's important for that new server to startup quickly, to restore full capacity as quickly as possible. Also, this setup only works for stateless services.

<br>

<img src="../assets/query_of_death_overload.png" alt="Query of Death Overload" width="50%" height="50%">

<br>

You also want to plan against query of death, where a request made to a service causes a failure in the service. This is referred to as the query of death because the error manifests itself as over consumption of resources, but in reality is due to an error in the business-logic itself.

This can be difficult to diagnose and requires good monitoring, observability and logging to determine the root cause of the problem.

When the requests are made, latency, resource utilization, and error rates should be monitored to help identify the problem.

<br>

<img src="../assets/positive_feedback.png" alt="Positive Feedback Cycle" width="50%" height="50%">

<br>

You should also plan against positive feedback cycle overload failure, where a problem is caused by trying to prevent problems. This happens when you try to make the system more reliable by adding retries in the event of a failure.

Instead of fixing the failure, this creates the potential for overload. You may actually be adding more load to an already overloaded system. The solution is intelligent retries that make use of feedback from the service that is failing.

Let me discuss two strategies to address this.

If a service fails, it is okay to try again, however, this must be done in a controlled manner. One way, to use the exponential backoff pattern.

<br>

<img src="../assets/Truncated_exponential_backoff_pattern.png" alt="Truncated Exponential Backoff Pattern" width="50%" height="50%">

<br>

This performs a retry, but not immediately. You should wait between retry attempts, waiting a little longer each time a request fails, therefore, giving the failing service time to recover. The number of retries should be limited to a maximum, and the length of time before giving up should also be limited.

As an example, consider a failed request to a service. Using exponential backoff, we may wait one second plus a random number of milliseconds and try again. If the request fails again, we wait two seconds plus a random number of milliseconds and try again. Fail again, then wait four seconds plus a random number of milliseconds before retrying and continue until a maximum limit is reached.

<br>

<img src="../assets/circuit_breaker_pattern.png" alt="Circuit Breaker Pattern" width="50%" height="50%">

<br>

The circuit breaker pattern can also protect a service from too many retries. The pattern implements a solution for when a service is in a degraded state of operation. It is important because if a service is down or overloaded, and all it's clients are retrying, the extra requests actually make matters worse.

The circuit breaker design pattern protects the service behind a proxy that monitors the service health. If the service is not deemed healthy by the circuit breaker, it will not forward request to the service. When the service becomes operational again, the circuit breaker will begin feeding request to it again in a controlled manner.

If you are using GKE, then Istio's service mesh automatically implements circuit breakers.

<br>

<img src="../assets/lazy_deletion.png" alt="Lazy Deletion" width="50%" height="50%">

<br>

Lazy deletion is a method that builds in the ability to reliably recover data when a user deletes the data by mistake. With lazy deletion, a deletion pipelines similar to that shown in this graphic, is initiated and the deletion progresses in phases.

The first stage is that the user deletes the data, but it can be restored within a predefined time period. In this example, it's 30 days. This protects against mistakes by the user.

When the predefined period is over, the data is no longer visible to the user, but moves to the soft deletion phase. Here, the data can be restored by user support or administrators. This deletion protects against any mistakes in the application.

After the soft deletion period of 15, 30, 45 or even 50 days, the data is deleted and no longer available.

The only way to restore the data is by whatever backups or archives were made of the data.

<br>

### Activity Intro: Designing Reliable Scalable Applications

In this design activity, you draw a diagram that depicts how you can deploy your application for high availability, scalability, and durability.

Let me show you an example of what to draw.

<br>

<img src="../assets/reliable_example.png" alt="Design for Reliable Scalable Apps" width="50%" height="50%">

<br>

This diagram is for an online bank application with customers in the United States. I want the web UI to be highly available. So here I depicted as being deployed behind a global HTTP load balancer across multiple regions and multiple zones within each region.

I chose us-central-1 as the main region because it's somewhat in the middle of the US. I also have a backup region in us-east-1, which is on the east coast of the US.

I deploy the accounts and products services as the back ends to just the us-central-1 region, but I'm using multiple zones us-central1-a and us-central1-b for high availability.

I even have a failover cloud sequel database. The Filestore database for the product service is multiregional, so I don't need to worry about it failover.

In case of a disaster, I'll keep backups in a multi regional cloud storage bucket. That way, if there is a regional outage, I can restore in another region.

Refer to activity 10 in your workbook to create a similar diagram for your services.

<br>

### Activity Review: Designing Reliable Scalable Applications

In this activity, you are tasked to draw a diagram that depicts how your application can be deployed for availability, scalability, and durability.

<br>

<img src="../assets/reliable_example_2.png" alt="Design for Reliable Scalable Apps #2" width="50%" height="50%">

<br>

For our online travel application, Click Travel, I'm assuming that this is an American company, but that have a large group of customers in Europe. I want the UI to be highly available.

So I've placed it into US Central 1, and Europe West 2 behind a global HTTP load balancer. This load balancer will send user requests to the region closest to the user unless that region cannot handle the traffic.

I could also deploy the backends globally, but I'm trying to optimize cost. I could start by just deploying those in US Central 1. This will create a latency for our European users, but I can always revisit this later and have a similar backend in Europe West 2. To ensure high availability, I've decided to deploy the orders and inventory services to multiple zones.

Because the analytics service is not customer facing, I can save money by deploying it to a single zone. I, again, have a failover Cloud SQL database and the Filestore database in BigQuery data warehouses are multi-regional, so I don't need to worry about a failover for those.

In case of a disaster, I'll keep backups in a multi-regional Cloud storage bucket. That way, if there's a regional outage, I can restore it in another region.

<br>

### Disaster Planning

Now that we've designed for reliability, let's explore disaster planning.

<br>

<img src="../assets/high_availability.png" alt="High Availability" width="50%" height="50%">

<br>

High availability can be achieved by deploying to multiple zones in a region. When using compute engine for higher availability, you can use a regional instance group, which provides built-in functionalities to keep instances running.

Use auto healing with an application health check and load balancing to distribute load.

For data, the storage solution selected will affect what is needed to achieve high availability. For cloud SQL, the database can be configured for high availability, which provides data redundancy and a standby instance of the database server in another zone.

This diagram shows a high availability configuration with a regional managed instance group for a web application that's behind a load balancer. The master cloud SQL instance is in `us-central 1-a`, with a replica instance in `us-central 1-f`. Some data services such as Firestore or Spanner, provide high availability by default.

<br>

<img src="../assets/regional_managed_instance.png" alt="regional managed instance" width="50%" height="50%">

<br>

In the previous example, the regional managed instance group distributes VMs across zones. You can choose between single zones and multiple zones or regional configurations when creating your instance group, as you can see in this screenshot.

<br>

<img src="../assets/kubernetes_cluster.png" alt="Kubernetes cluster" width="50%" height="50%">

<br>

Google Kubernetes engine clusters can also be deployed to either a single or multiple zones, as shown in this screenshot. A cluster consists of a master controller and collections of node pools. Regional clusters increase the availability of both a cluster's master and its nodes by replicating them across multiple zones of a region.

<br>

<img src="../assets/health_check.png" alt="health check" width="50%" height="50%">

<br>

If you are using instance groups for your service, you should create a health check to enable auto healing. The health check as a test endpoint in your service, it should indicate that your service is available and ready to accept requests and not just that the servers running.

A challenge with creating a good health check endpoint is that if you use other back end services, you need to check that they are available to provide positive confirmation that your service is ready to run. If the services it is dependent on are not available, it should not be available.

If a health check fails the incidence group, it will remove the failing instance and create a new one. Health checks can also be used by load balancers to determine which instances to send requests to.

<br>

<img src="../assets/storage_high_availability.png" alt="storage high availability" width="50%" height="50%">

<br>

Let's go over how to achieve high availability for Google Cloud's data storage and database services. For Google Cloud Storage, you can achieve high availability with multi-region storage buckets if the latency impact is negligible. As this table illustrates, the multi-region availability benefit is a factor of two as the unavailability decreases from 0.1% to 0.5%.

<br>

<img src="../assets/cloud_sql_high_availability.png" alt="cloud sql high availability" width="50%" height="50%">

<br>

If you are using Cloud SQL and need high availability, you can create a failover replica. This graphic shows the configuration where a master is configured in one zone and a replica is created in another zone but in the same region. If the master is unavailable, the failover will automatically be switched to take over the master.

Remember, that you are paying for the extra instance with this design.

<br>

<img src="../assets/spanner_firestore_high_availability.png" alt="spanner firestore high availability" width="50%" height="50%">

<br>

Firestore and Spanner both offer single and multi-region deployments. A multi-region location is a general geographic area such as the United States. Data in a multi region location is replicated in multiple regions. Within a region data is replicated across zones.

Multi-region locations can withstand the loss of entire regions and maintain availability without losing data. The multi-region configurations for both Firestore and Spanner offer five nines of availability, which is less than six minutes of downtime per year.

Now, I already mentioned that deploying for high availability increases cost because extra resources are used. It is important that you consider the costs of your architectural decisions as part of your design process. Don't just estimate the cost of the resources used, but also consider the cost of your service being down.

<br>

<img src="../assets/cost_of_availability.png" alt="cost of availability" width="50%" height="50%">

<br>

This table shown is a really effective way of assessing the risk versus cost, by considering the different deployment options and balancing them against the cost of being down.

Now, let me introduce some disaster recovery strategies.

<br>

<img src="../assets/cold_standby.png" alt="Cold Standby" width="50%" height="50%">

<br>

A simple disaster recovery strategy may be to have a cold standby. You should create snapshots of persistent disks, machine images, and data backups and store them in a multi-region storage. This diagram shows a simple system using the strategy.

Snapshots are taken that can be used to recreate the system. If the main region fails, you can spin up servers in the backup region using the snapshot images and persistent disks. You will have to route requests to the new region and it's vital to document and test this recovery procedure regularly.

<br>

<img src="../assets/hot_standby.png" alt="Hot Standby" width="50%" height="50%">

<br>

Another disaster recovery strategy is to have a hot standby where instance groups exist in multiple regions and traffic is forwarded with a global load balancer. This diagram shows such as configuration. I already mentioned this, but you can also implement this for data storage services like multi-regional cloud storage buckets and database services like Spanner and Firestore.

<br>

<img src="../assets/disaster_recovery_planning.png" alt="disaster recovery planning" width="50%" height="50%">

<br>

Now, any disaster recovery plan should consider its aims in terms of two metrics, the Recovery Point Objective and the Recovery Time Objective.

The Recovery Point Objective is the amount of data that would be acceptable to lose.

And the Recovery Time Objective is how long it can take to be back up and running.

You should brainstorm scenarios that might cause data loss or service failures and build a table similar to the one shown here. This can be helpful to provide structure on the different scenarios and to prioritize them accordingly.

You will create a table like this in the upcoming design activity along with the recovery plan.

<br>

<img src="../assets/disaster_recovery_scenarios.png" alt="disaster recovery scenarios" width="50%" height="50%">

<br>

You should create a plan for how to recover based on the disaster scenarios that you define. For each scenario, devise a strategy based on the risk and recovery point and time objectives. This isn't something that you want to simply document and leave.

**You should communicate the process recovering from failures to all parties.**

The procedures should be tested and validated regularly at least once per year. And ideally, recovery becomes a part of daily operations, which helps streamline the process.

This table illustrates the backup strategy for different resources along with the location of the backups and the recovery procedure. This simplified view illustrates the type of information that you should capture.

<br>

<img src="../assets/disaster_prep.png" alt="disaster prep" width="50%" height="50%">

<br>

Before we get into our next design activity, I just want to emphasize how important it is to prepare a team for disaster by using drills.

Have you decided what you think can go wrong with your system? Think about the plans for addressing each scenario and document these plans, then practice these plans periodically in either a test or production environment. At each stage, assess the risks carefully and balance the cost of availability against the cost of unavailability.

The cost of unavailability will help you evaluate the risk of not knowing the system's weaknesses.

<br>

### Activity Intro: Disaster Planning

In this design activity, you brainstorm disaster scenarios for your case study and formulate a disaster recovery plan.

Here's an example of such a brainstorming activity.

<br>

<img src="../assets/disaster_example.png" alt="disaster example" width="50%" height="50%">

<br>

The purpose of this activity is to think off disaster scenarios and assess how severely they would impact your services. The recovery point objective represents the maximum amount of data you would be willing to lose. Obviously, this would be different for your orders database where you wouldn't want to lose any data, and your products rating database where you could tolerate some loss. The recovery time objective represents how long it would take to recover from a disaster.

In this example, we are estimating that we could recover our product ratings service database from a backup in an hour and our order service within two minutes.

Now, like all things in life, we should prioritize, there's never time to get everything done. So work on the highest priority items first.

Once you've identified these scenarios, come up with plans for recovery. These plans will be different based on your recovery point and recovery time objectives as well as the priorities.

In this example, performing daily backups of our ratings database is good enough to meet our objectives. For the orders database, that won't be adequate. So we'll implement a failover replica in another zone.

Refer to activities 11A, B and C in your design workbook to documents similar disaster scenarios for your case study and formulate a disaster recovery plan for each.

<br>

### Activity Review: Disaster Planning

n this activity, you were asked to come up with disaster recovery scenarios and plans for the case study you've been working on.

Here's an example of some disaster scenarios for our online travel portal, Click Travel.

<br>

<img src="../assets/disaster_recovery_example.png" alt="disaster recovery example" width="50%" height="50%">

<br>

Each of our services use different database services and has different objectives and priorities. All of that affects how we design our disaster recovery plans. Our Analytics service in BigQuery had the lowest priority. Therefore, we should be able to re-import data to rebuild Analytics tables if a user deletes them.

Our order service can't tolerate any data loss and has to be up and running almost immediately. For this, we need a failover replica in addition to binary logging and automated backups.

Our inventory service uses Firestore. For that, we can implement daily automated backups to a multi-regional Cloud Storage bucket. Cloud Functions and Cloud Scheduler can help with this recovery procedure.

<br>

### Review

In this module, we covered how to deploy our applications for high availability, durability, and scalability.

For high availability, we can deploy our resources across multiple zones and regions.

For durability, we can keep multiple copies of data and perform regular backups.

For scalability, we can deploy multiple instances of our services and set up auto scalars.

We also introduced disaster recovery planning, which is defined by coming up with the scenarios that would cause you to lose data and having a plan in place for recovering if a disaster happens.

<br>

## Module Overview: Security Concepts

In this module, we cover security.

Google has been operating securely in the cloud for 20 years. There's a strong belief that security empowers innovation. The approach of the cloud architect should be that security should be put first. Everything else will follow from this.

In this module, you will learn how to design secure systems using industry best practices.

<br>

<img src="../assets/security_learning_objectives.png" alt="Learning Objectives" width="50%" height="50%">

<br>

For example, when designing a secure system, you will learn how to apply the principle of least privilege and the practice of separation of concerns.

Performing regular audits is also a key part of running a secure system.

Leveraging Google's Security Command Center can help to identify vulnerabilities as part of your process. Also when securing systems, governance is a major consideration. You will learn how organization policies and folders can simplify governance.

Preventing access to unwanted visitors is always a challenge. Authentication and authorization is one approach and can be implemented in many different ways. You will learn how best to use IAM roles, Identity-Aware proxy and Identity Platform.

You'll also learn to manage the access and authorization of resources by machines and processes using service accounts.

At a lower level of access control, you will learn how to secure network access using private IP's, firewalls, and Google Cloud private access.

Last but not least, you'll learn how to mitigate DDoS attacks by leveraging Cloud DNS and Google Cloud Armor.

As you see there is a lot to security. Let's get started.

<br>

### Security Concepts

Let's begin by talking about some security concepts and introducing some of the best practices for security design.

When you move an application to Google Cloud, Google handles many of the lower layers of the overall security stack. Because of its scale, Google can deliver a higher level of security at these layers than most of its customers could afford to do on their own. This does not mean that Google is responsible for all the security aspects.

<br>

<img src="../assets/security_responsibility.png" alt="Security is a shared responsibility" width="50%" height="50%">

<br>

Google Cloud security is a shared responsibility between you and Google. So it is important that there is a clear separation of duties, and there is no ambiguity between what is provided by the platform and what you are responsible for.

For this, there needs to be transparency. There are certain actions you as a client are responsible for, and some that Google is responsible for. Google Cloud provides the controls and features required to leverage the platform together with the tools to monitor your services.

Google implements security in layers.

<br>

<img src="../assets/security_layers.png" alt="GCP security layers" width="50%" height="50%">

<br>

At the base is custom built hardware and servers that are loaded using a verified boot loading system. All the way through the stack, security is at the forefront. When you take your part in security, for example, establishing firewall rules or configuring IAM, as long as they are configured correctly, you have a safe environment.

There are tools Google Cloud provides that can be used for monitoring and auditing your networks, which we will discuss shortly, or you can also install your own tools.

<br>

<img src="../assets/least_privileged.png" alt="Principle of least privileged" width="50%" height="50%">

<br>

Let's talk about some best practices when implementing security. The principle of least privilege is the practice of granting a user only the minimal set of permissions required to perform a duty. This should apply to machine instances and processes, as well as users.

Google Cloud provides cloud IAM to help apply this principle. You can use it to identify users with their login or identify machines using service accounts. Roles should be assigned to users and service accounts to restrict what they can do, always following the principle of least privilege.

<br>

<img src="../assets/separation_of_duties.png" alt="Separation of Duties" width="50%" height="50%">

<br>

Separation of duties is another best practice and it has two primary objectives. One, prevention of conflict of interest and two, the detection of control failures. For example, security breaches and information theft. From a practical perspective, this means that no one person can change or delete data without being detected. No one person can steal sensitive data and no single person is in charge of designing, implementing, and reporting on sensitive systems.

For example, a developer who writes the code should not be responsible for deploying that code, and anybody that has the permission to deploy should not be able to change the code. One approach to achieve this separation of duties in Google Cloud is to use multiple projects to separate duties. Different people can be given suitable rights to different projects, with these permissions following the principle of separation of duties. Folders are especially useful for organizing multiple projects.

<br>

<img src="../assets/log_audit.png" alt="Audits" width="50%" height="50%">

<br>

It is also vital to audit Google Cloud logs to discover attacks and potential security breaches. All Google Cloud services write to audit logs, so there is a rich source of information available. These logs include admin, data access, VPC flow, firewall, and system logs. So an in-depth view of activity is provided for audit.

<br>

<img src="../assets/compliance.png" alt="GCP Compliance" width="50%" height="50%">

<br>

Now, moving to the cloud often requires maintaining compliance with regulatory requirements, or guidelines. Google Cloud meets many third party and government compliance standards worldwide. While Google cloud has been certified as secure, for example to ISO/IEC 27001, HIPAA and SOC 1, that does not mean your application running on Google Cloud is certified.

Your concern should always be on what you build.

<br>

<img src="../assets/security_command_center.png" alt="GCP Security Command Center" width="50%" height="50%">

<br>

Google Cloud also offers the Security Command Center, which provides access to organizational and project security configuration. As as you can see in this screenshot, the Security Command Center provides a dashboard that reports security health analysis, threat detections, anomaly detection, and a summary report.

Once a threat is detected, a set of actionable recommendations is provided.

<br>

### Securing People

Let's move on to talk about securing people.

<br>

<img src="../assets/granting_access.png" alt="Granting Access" width="50%" height="50%">

<br>

When granting people access to your projects, you should add them as members and assign them one or more roles. Roles are simply a list of permissions. To see what permissions are granted to roles, use the Cloud Console as shown on the right. Here, you can see the role BigQuery user and the associated 15 permissions the role has assigned to it.

You can assign these predefined roles to its members or customize your own roles.

Now, any member added to your project will be identified by their login. For simplifying management of members and their permissions, I recommend that you create groups, that way you just need to add members to a group and new members automatically acquire the permissions of the group.

The same applies for removing members from a group, which also removes the permissions of that group.

<br>

<img src="../assets/identity_access_management.png" alt="identity access management" width="50%" height="50%">

<br>

I also recommend using organizational policies and folders to simplify securing your environments and managing your resources. Organizational policies applied to all resources underneath an organization and Cloud IAM policies are also inherited top to bottom as shown on the right.

Folders inherit policies of the organization.

Projects inherit policies of the folders, and so on.

I already mentioned that role should be granted to groups, not individuals because it simplifies management. Make sure to define groups carefully and make them more granular than job roles. It's better to use multiple groups for better control.

When it comes to roles, it's better to use predefined roles over custom roles. Google has defined the roles for a reason, and it should be an exceptional case that a role does not fit your use case. When granting roles, remember the principle of least privilege. Always grant the smallest scope required. Owner and editor role should be limited. These are not or should not be required by the majority of users.

<br>

<img src="../assets/identity_aware_proxies.png" alt="identity aware proxies" width="50%" height="50%">

<br>

I also recommend leveraging Cloud Identity Aware Proxy or Cloud IAP.

Cloud IAP provides managed access to applications running in App Engine standard environment, App Engine flexible environment, Compute Engine, and GKE. It allows employees to securely access web-based applications deployed on Google Cloud without requiring a VPN. Administrators control who has access and users are required to log on to gain access to the applications.

The screenshots on the right show Cloud IAP being enabled on an App Engine application and the dialogue for adding new members or permissions.

<br>

<img src="../assets/identity_platform.png" alt="Identity Platform" width="50%" height="50%">

<br>

Google Cloud also offers identity platform, as a Customer Identity and Access Management, CIAM platform for adding identity and access management to applications. In other words, Identity Platform provides sign-up and sign-in for end-user applications.

Now, you need to select a service provider to use Identity Platform. A broad range of protocol support is available including SAML, OpenID, email and password, phone, social, and Apple. This graphic shows a part of the configuration with a list of potential providers.

<br>

### Securing Machine Access

We just talked about assigning roles to members. We focused on users and Google groups, but there's another kind of member that helps secure machine access.

<br>

<img src="../assets/service_accounts.png" alt="Identity Service Accounts" width="50%" height="50%">

<br>

A service account is a special kind of account used by an application, a virtual machine instance or a GKE node pool. Applications or services use service accounts to make authorized API calls. The service account is the identity of the service and defines permissions which control the resource is that service can access.

**A service account is both an identity and resource.**

A service account is used as an identity for your application or service to authenticate. For example, a compute engine VM running as a service account. To give the VM access to the necessary resource is you need to grant the relevant cloud IAM rolls to the service account. At the same time you need to control who can create VMS with the service account. So random VMS cannot assume the identity.

Here the service account is the resource to be permission.

<br>

<img src="../assets/service_accounts_2.png" alt="Machine Service Accounts" width="50%" height="50%">

<br>

You assign the service account user role to the users you trust to use the service account. Each service account is associated with public private RSA key pairs that are used to authenticate to Google. These keys can be Google managed or user managed. Google managed keys, both the public and private keys, are stored by Google, and they are rotated regularly.

**The maximum usage period is two weeks for user managed keys.**

The developer owns both public and private keys. They could be used from outside Google Cloud. User managed keys can be managed by the cloud IAPI, `gcloud` command line tool or the service accounts page in the cloud console. It is possible to create up to ten key pairs per service account to support key rotation.

User managed keys are extremely powerful credentials, and they can represent a security risk if they are not managed correctly. You can limit their use by applying the constraints `/iam.disabled-service-account-creation-organization-policy` constraint to projects, folders or even your entire organization.

After applying the constraint, you can enable users managed keys in well controlled locations. To minimize the potential risk caused by unmanaged keys, consider using cloud key management service, Cloud KMS to help securely manage your keys.

The slide shows the generation of a key using the cloud console, The private key can be seen in the screenshot. It's your responsibility for storing the private key securely for developers to gain control access to resources without acquiring access to the cloud console.

<br>

<img src="../assets/service_account_keys.png" alt="Service Account Keys" width="50%" height="50%">

<br>

It is possible to configure the G Cloud command line utility to use service account credentials to make requests. The command on this slide `gcloud auth activate-service-account` serves the same purpose as `gcloud auth login` but uses the service account instead of user credentials.

The key file contains the Private Key and JSON Format, which I just discussed.

<br>

### Network Security

In our previous module, we talked about networks, but didn't get into a lot of network security concepts. Let's do that now.

<br>

<img src="../assets/remove_external_ips.png" alt="Remove External Ips" width="50%" height="50%">

<br>

First, I recommend removing external IPs to prevent access to machines from outside their network whenever possible.

Several options are available for securely communicating with VMs that do not have public IP addresses. These services do not have a public IP address because they are deployed to be consumed by other instances in the project, or maybe through dedicated interconnect options.

However, for those instances that do not have an external IP address, it can be a requirement to gain external access, for instance, for updates or patches to be applied. The options for accessing the VMs include a bastion host for external access to private machines, Identity-Aware Proxy to enable SSH access or Cloud NAT to provide egress to the Internet for internal machines.

The diagram on the right shows an external client accessing Compute Engine resources via a bastion host. The host is behind a firewall where access can be filtered. Whichever method you choose, all internet traffic should terminate at a load balancer, third-party firewall or API Gateway or through Cloud IAP. That way, internal services cannot be launched and get public IP addresses.

<br>

<img src="../assets/private_access.png" alt="Private Access w/ internal address" width="50%" height="50%">

<br>

Now, VM instances that only have internal IP addresses can use private Google access to access Google services that have external IP addresses. The diagram on the right shows a Compute Engine instance accessing a Cloud storage bucket using its internal IP address.

Private Google access must be enabled when creating the subnet. You can achieve this either with the gcloud command shown here or through the Cloud Console.

Regardless of whether you're VM instances have public IP addresses, you should always configure a firewall rules to control access.

<br>

<img src="../assets/firewall_rules.png" alt="Firewall Rules" width="50%" height="50%">

<br>

By default, ingress on all ports is denied and all egress is allowed. It's your responsibility to define separate rules to allow or deny access to specific instances for specific IP ranges, protocols, and ports.

This graphic shows some scenarios where firewall rules can be configured. Egress from Compute Engine to external servers is the first scenario. For ingress, firewall rule should be configured if direct access to an instance is being provided or of via a load balancer. The right-hand graphic shows the scenario of VM instance to instance communication.

Firewall rules should be considered here to control access also. Remember, you're still responsible for application level security.

<br>

<img src="../assets/cloud_endpoints.png" alt="cloud endpoints" width="50%" height="50%">

<br>

If you need to manage APIs, you can use Cloud Endpoints. Endpoints is an API management gateway that helps you develop, deploy, and manage APIs on any Google Cloud backend. It provides functionality to protect and monitor your public APIs, control who has access, using, for example, Auth0 and validate every call with a JSON Web Token signed with the service account private key.

Cloud Endpoints also integrates with Identity Platform for authentication.

<br>

<img src="../assets/restrict_access.png" alt="Restrict Access" width="50%" height="50%">

<br>

All Google Cloud Service Endpoints use HTTPS. I recommend that you use TLS for your service endpoints and it is your responsibility to configure your service endpoints for TLS. When configuring load balancers, only ever create secure front ends.

This dialog shows the configuration of a front end and the protocol selected is HTTPS, with the certificate also being selected.

<br>

<img src="../assets/ddos_protection.png" alt="DDoS Protection" width="50%" height="50%">

<br>

Google provides Infrastructure DDoS support through global load balancers at level 3 and level 4 traffic. If you have enabled CDN, this will also protect backend resources because a DDoS results in a cache hit instead of hitting your resources as shown on the right.

<br>

<img src="../assets/cloud_armor.png" alt="cloud armor" width="50%" height="50%">

<br>

We already mentioned Google Cloud armor in the networking module. For additional features over the built-in DDoS protection, you can use Google Cloud armor to create network security policies.

For example, you can create allow lists that allow known slash required addresses through and deny lists to block known attackers.

This dialog shows a typical security policy configuration where you begin by selecting it as an allow list or a deny list with allow or deny for the rule.

If it's a deny, the appropriate action in this example should be a 403 error.

<br>

<img src="../assets/cloud_armor_2.png" alt="Cloud Armor Layer 7" width="50%" height="50%">

<br>

In addition to layer 3 and layer 4 security, Google Cloud armor supports layer 7 application rules.

For example, predefined rules are provided for cross-site scripting, XSS, and SQL injection attacks. Google Cloud armor provides a rules language for filtering request traffic.

As an example, consider the first expression on this slide. In IP range `origin.ip 9.9.9.0/24`. In this case, the expression returns true if the origin IP and our request is within the `9.9.9.0/24` range.

The second line, `request.headers['cookie'].contains('80=BLAH')` returns true if the cookie 80 with value blah exists in the request header and the third line is true if the origin region code is AU. The expressions can be combined logically with logical AND, and OR. The expressions are all assigned to an allow or deny rule that is then applied to incoming traffic.

<br>

### Encryption

Last, but certainly not least, let's go over encryption.

<br>

<img src="../assets/gcp_encryption.png" alt="Encryption" width="50%" height="50%">

<br>

Google Cloud encrypts customer data stored at rest by default, with no additional action required from users. A data encryption key orDEK using AES 256 Symmetric key is used, and the key itself is encrypted by Google using a key encryption key, KEK. This is so that the DEK could be stored local to the encrypted data for fast decryption, with no visible performance impact to the user.

To protect the KEKs, they're stored in Cloud KMS. The keys are rotated periodically and automatically for added security.

This diagram shows a simple app engine application that uses cloud storage. The data is encrypted using AES 256 using a DEK and decrypted transparently to the application when the data is read.

<br>

<img src="../assets/compliance_key_management.png" alt="Key management for compliance" width="50%" height="50%">

<br>

Now for compliance reasons, you may need to manage your own encryption keys rather than the automatically generated keys as just discussed. In this scenario, you can use Cloud Key Management Service or Cloud KMS to generate what are known as customer managed encryption keys, CMEK.

These keys are stored in cloud KMS for direct use by cloud services. You can manually create the key using a dialogue similar to the one shown here and specify the rotation frequency, which defaults to 90 days. The keys you create can then be used when creating storage re sources such as disks or buckets.

When you're required to generate your own encryption key or manage it on premises, Google Cloud supports customer supplied encryption keys CSEK. Those keys are kept on premises and not in Google Cloud. The Keys are provided as part of API service calls and Google only keeps the key in memory and uses it to decrypt a single payload or block of returned data. Currently, customer supplied encryption keys can be used with cloud storage and compute engine.

<br>

<img src="../assets/data_loss_prevention.png" alt="Data Loss Prevention API" width="50%" height="50%">

<br>

You should also consider the data loss prevention API to protect sensitive data by finding it and redacting it. Cloud DLP provides fast scalable classification and redaction for sensitive data elements like credit card numbers, names, Social Security numbers, US and Selected International Identify our numbers, phone numbers and Google Cloud credentials.

Cloud DLP classifies this data using more than 90 pre defined detectors to identify patterns, formats and check sums and even understands contextual clues. Some of these are shown on the right. You can optionally redact data as well, using techniques like masking, secure hashing, tokenization, bucketing and format preserving encryption.

<br>

### Activity Intro: Modeling Secure Google Cloud Services

In this design activity, you'll draw a diagram that depicts your case study security requirements.

Let me show you an example of what to draw.

<br>

<img src="../assets/modeling_security_example.png" alt="Modeling secure services" width="50%" height="50%">

<br>

This diagram illustrates a custom VPC network with two subnets in the US. Maybe US Central 1 is our primary region and US East 1 is our backup region. The firewall rules allow HTTPS ingress from the internal and SSH from known sources. Otherwise all other incoming traffic is disabled by the implied deny all ingress firewall rule that every VPC network has.

Because we're allowing HTTPS from anywhere, it's useful to configure Google Cloud Armor on a global HTTP load balancer to block any denied IP addresses at the edge of Google Cloud's network. This is a simple design, but a great starting point because it allows us to grow our backends without changing our security design.

Refer to Activity 12 in your workbook to create a similar diagram for your case study.

<br>

### Activity Review: Modeling Secure Google Cloud Services

In this activity, you were asked to draw a diagram depicting the security requirements for your case study.

Here's the diagram that I drew for our online travel portal, Click Travel.

<br>

<img src="../assets/modeling_security_example_2.png" alt="Modeling secure services" width="50%" height="50%">

<br>

This is a similar design to what I showed you earlier. First, I configured Google Cloud Armor on a global HTTP load balancer to block any denied IP addresses.

My Custom VPC network has subnets in US Central 1 for my American customers, and a backup subnet in US East 1, and a subnet in Europe West 2 for my European customers. My firewall rules only allow SSH from known sources. Although I allow HTTPS from anywhere, I can always deny IP addresses with Google Cloud Armor at the edge of Google Cloud's network.

I also configured Cloud VPN tunnels to securely communicate with my on-premises network for my reporting service. Now, while my load balancer needs a public IP address, I can secure my backend services by creating them without external IP addresses.

In order for those instances to communicate with the Google Cloud called database services, I enable private Google access.

This enables the inventory, orders, and analytic services traffic to remain private while reducing my networking costs.

<br>

### Review

In this module, we covered how to secure our Google Cloud resources.

This includes securing both the network and our stored data.

We also covered how to secure people using IAM, Cloud Identity, and Identity Aware Proxy, and how we can secure our applications and machines using service accounts.

Remember, security should be put first.

Everything else will follow from this.

<br>

## Module Overview: Managing Versions & Cost Control

In this final module of this course, we cover application maintenance and monitoring.

Maintenance is primarily concerned with how updates are made to running applications, the different strategies available, and how different deployment platforms support them.

For monitoring, I discussed this vital error for Cloud native applications from two perspectives. First, I will talk about the cost perspective to make sure that resources are being best provisioned against demand. After all, why should you pay for resources that you don't need.

Second, I will discuss how to implement monitoring and observability to determine and alert on the health of services and applications using Cloud Monitoring and Dashboards.

This will also allow us to define Uptime Checks and use Cloud Monitoring Alerts to identify service outages.

<br>

### Managing Versions

Let's begin by taking a look at version management.

<br>

<img src="../assets/version_management.png" alt="Microservice Version Management" width="50%" height="50%">

<br>

A key benefit of a microservice architecture is the ability to independently deploy microservices. This means that the service API has to be protected. Versioning is required and when new versions are deployed, care must be taken to ensure backward compatibility with a previous version. Some simple design rules can help, such as indicating the version in the URI and making sure you change the version when you make a backward incompatible change.

Deploying new versions of software always carries risk. We want to make sure we test new versions effectively before going live and when ready to deploy a new version, we do so with zero downtime. Let me discuss some strategies that can help achieve these objectives.

<br>

<img src="../assets/rolling_updates.png" alt="Rolling updates" width="50%" height="50%">

<br>

Rolling updates allow you to deploy new versions with no downtime. The typical configuration is to have multiple instances of a service behind a load balancer. A rolling update will then update one instance at a time. This strategy works fine if the API is not changed or is backward compatible or if it is okay to have two versions of the same servers running during the update. If you are using instance groups, rolling updates are a built-in feature. You just define the rolling update strategy when you perform the update.

For Kubernetes, rolling updates are there by default. You just need to specify the replacement Docker image. Finally, for App Engine, rolling updates are completely automated.

<br>

<img src="../assets/blue_green_deployment.png" alt="Blue/green Deployments" width="50%" height="50%">

<br>

Use a blue/green deployment when you don't want multiple versions of a service to run simultaneously. Blue/green deployments use two full deployment environments. The blue deployment is running the current deployed production software while the green deployment environment is available for deploying updated versions of the software. When you want to test a new software version, you deploy to the green environment. Once testing is complete, the workload is shifted from the current, which would be the blue in this case to the new, the green environment. This strategy mitigates the risk of a bad deployment by allowing the switch back to the previous deployment if something goes wrong.

For Compute Engine, you can use DNS to migrate requests while in Kubernetes, you can configure your service to route to new pods using labels, which is just a simple configuration change. App Engine allows you to split traffic which you explored in the previous lab of this course.

<br>

<img src="../assets/canary_releases.png" alt="Canary releases" width="50%" height="50%">

<br>

Now, you can use canary releases prior to a rolling update to reduce risk. With a canary release, you make a new deployment with the current deployment still running. Then you sent a small percentage of traffic to the new deployment and monitor it.

Once you have confidence in your new deployment, you can route more traffic to the new deployment until 100% is routed this way.

In Compute Engine, you can create a new instance group and add it to the load balancer as an additional backend. In Kubernetes, you can create a new pod with the same labels as the existing pods. The service will automatically divert a portion of the request to the new pod.

In App Engine, you can again use the Traffic Splitting feature to drive a portion of traffic to the new version.

<br>

### Cost Planning

Cost planning is an important phase in your design that starts with capacity planning.

<br>

<img src="../assets/capacity_planning.png" alt="Capacity Planning" width="50%" height="50%">

<br>

I recommend that you treat capacity planning not as a one off task but as a continuous iterative cycle. As illustrated on this slide start with a forecast that estimates the capacity needed. Monitor and review this forecast, then allocated by determining the resources required to meet the forecasted capacity. This allows you to estimate costs and balance them against risks and rewards.

Once the design and cost is approved, deploy your design and monitor it to see how accurate you forecasts were. This feeds into the next forecast as the process repeats.

<br>

<img src="../assets/optimize_compute_costs.png" alt="Optimize compute costs" width="50%" height="50%">

<br>

A good starting point for anybody working on cost optimization is to become familiar with the VM instance pricing. It is often beneficial to start with a couple of small machines that can scale out through auto scaling as demand grows.

To optimize the cost of your virtual machines. Consider using committed use discounts as these can be significant. Also, if your workloads allow for preemptible instances, you can save up to 80 and use auto healing to recover when instances are preempted.

Compute engine also provides sizing recommendations for your VM instances as shown on the right. This is a really useful feature that can help you select the right size of VM for your workloads and optimize costs.

<br>

<img src="../assets/optimize_disk_cost.png" alt="" width="50%" height="50%">

<br>

A common mistake is to over allocate disk space. This is not cost efficient but selecting a disk is not just about size. It is important to determine the performance characteristics your applications display, the I/O patterns, do you have large read small writes, vice versa, mainly read only data...

This type of information will help you select the correct type of disk. As the table shows. SSD persistent disks are significantly more expensive than standard persistent disks. Understanding your I/O patterns can help provide significant savings to optimize network costs.

<br>

<img src="../assets/optimize_network_costs.png" alt="optimize network costs" width="50%" height="50%">

<br>

It is best practice to keep machines as close as possible to the data they need to access. This graphic shows the different types of egress within the same zone. Between zones in the same region, intercontinental egress and internet egress. It is also important to be aware of egress charges.

**These are not all straightforward.**

Egress in the same zone is for you. He goes to different good cloud service within the same region using an external IP address. Or an internal IP addresses free except for some services such as memory store for Redis. Egress between zones in the same region is charged and all internet egress is charged. One way to optimize your network costs is to keep your machines close to your data.

<br>

<img src="../assets/gke_usage_metering.png" alt="GKE usage metering" width="50%" height="50%">

<br>

Another way to optimist cost is to leverage GKE usage metering which can prevent over provisioning your kubernetes cluster. With GKE usage metering an agent collects consumption metrics. In addition to the resource requests by polling pot metric objects from the metrics server. The resource requests, record and resource consumption records are exported to two separate tables and BigQuery data sets that you specify. Comparing requests that with consumed resources makes it easy to spot waste and take corrective measures.

This graphic shows a typical configuration where BigQuery is used for requests based metrics collected from the usage metering agent. And together with data obtained from building export, it is analyzed in a data studio dashboard.

<br>

<img src="../assets/compare_storage_costs.png" alt="Comparing Storage Costs" width="50%" height="50%">

<br>

Earlier in the course we talked about all of the different storage services. It's important to compare the costs of the different options as well as their characteristics. For example, as of this recording Firestore provides one gigabyte of storage for free, under the free access to tier. If you sort the same amount of data in Cloud BigTable, you could pay over one $1,000 per month. Because you'd need at least three BigTable nodes. In other words, your storage and database service choice can make a significant difference to your bill.

<br>

<img src="../assets/cost_saving.png" alt="Cost saving w/ alternative storage" width="50%" height="50%">

<br>

Your architectural design can also help you optimize your costs. For example, if you use Cloud CDN for static content or Memorystore as a cache, you can save instead of allocating more resources. Similarly, instead of using a data store between two applications, considering messaging and queuing with Pub/Sub to the couple communicating services and reduce storage needs.

<br>

<img src="../assets/pricing_calculator.png" alt="Pricing Calculator" width="50%" height="50%">

<br>

The pricing calculator should be your go to resource for estimating costs. Your estimates should be based on your forecasting and capacity planning. The tool is great for comparing costs of different compute and storage services and you will use it in the upcoming design activity.

<br>

<img src="../assets/billing_report.png" alt="Billing report" width="50%" height="50%">

<br>

To monitor the cost of your existing service, leverage the cloud billing reports page as shown here. This report shows the changes in costs compared to the previous month. And you can use the filters to search for particular projects, products and regions as shown on the right.

The sizing recommendations for your compute engine instances will also be in this report.

<br>

<img src="../assets/adv_cost_analysis.png" alt="Advanced cost analysis" width="50%" height="50%">

<br>

For advanced cost analysis, I recommend exporting your billing data to BigQuery. As shown in the screenshot. You can then analyze the billing data to identify large expenses and optimize your google cloud spend. For example, let's assume you label VM instances that are spread across different regions. Maybe these instances are sending most of their traffic to a different continent which could incur higher costs. In that case you might want to consider relocating some of those instances or using a caching service like CloudCDN. To cache content closer to your users, which reduces your networking spend.

<br>

<img src="../assets/data_studio.png" alt="Data Studio" width="50%" height="50%">

<br>

You can even visualize spend over time with google data studio. Which turns your data into informative dashboards and reports that are easy to read, easy to share and fully customizable. The service data is displayed in a daily and monthly view, providing at a glance summaries that can also be drilled down in to provide greater insights.

<br>

<img src="../assets/budgets_and_alerts.png" alt="Budgets and Alerts" width="50%" height="50%">

<br>

To help with project planning and controlling costs. You can set a budget, setting a budget lets you track how your spend is growing towards that amount. This screenshot shows the budget creation interface.

First set a budget name and specify which project this budget applies to. Then set the budget at a specific amount or match it to the previous month spent last set the budget alerts. These alerts, sent emails to billing admins after spending exceeds a percent of a budget or a specified amount.

In our case, It would send an email when spending reaches 50, 90 and 100 of the budget amount. You can even choose to send an alert when the spend is forecasted to exceed the percent of the budget amount by the end of the budget period.

In addition to receiving an email, you can use pop up notifications to programmatically receive spend updates about this budget.

You could even create a cloud function that listens to the pub sub topic to automate cost management.

<br>

### Monitoring Dashboards

Let's get into monitoring and visualizing information with dashboards.

<br>

<img src="../assets/monitoring_tools.png" alt="monitoring tools" width="50%" height="50%">

<br>

Google Cloud unifies the tools you need to monitor your service, SLOs and SLAs in real-time. These tools include Monitoring, Logging, Trace, Debugger, Error Reporting, and Profiler. All of these enable you to gain the insights you need to achieve your SLOs and determine the root cause in those rare cases that you do not achieve your SLOs.

<br>

<img src="../assets/monitoring_dashboards.png" alt="monitoring dashboards" width="50%" height="50%">

<br>

Dashboards are one way for you to view and analyze metric data that is important to you. This includes your SLIs to ensure that you are meeting your SLAs.

The monitoring page of the Cloud Console automatically provides predefined dashboards for the resources and services that you use. It is important that you monitor these things you pay for to determine the trends, bottlenecks, and potential cost savings.

<br>

<img src="../assets/example_charts.png" alt="example monitoring charts" width="50%" height="50%">

<br>

Here's an example of some charts in a monitoring dashboard. On the left, you can see the CPU usage for different compute engine instances, and on the right is the ingress traffic for those instances. Charts like these provide valuable insights into usage patterns.

<br>

<img src="../assets/default_dashboards.png" alt="default dashboards" width="50%" height="50%">

<br>

To help you get started, Cloud monitoring creates default dashboards for your project resources, as shown in this screenshot. You can also create custom dashboards which you can explore in the upcoming lab.

<br>

<img src="../assets/uptime_checks.png" alt="uptime checks" width="50%" height="50%">

<br>

Now, it's a good idea to monitor latency because it can quickly highlight when problems are about to occur. As shown on the slide, you can easily create uptime checks to monitor the availability and latency of your services.

So far, there is a 100 percent uptime with no outages.

Latency is actually one of the four golden signals called out in Google's Site Reliability Engineering, or SRE book.

SRE is a discipline that applies aspects of software engineering to operations whose goals are to create ultra scalable and highly reliable software systems. This discipline has enabled Google to build, deploy, monitor, and maintain some of the larger software systems in the world. I've linked the SRE book and the slides of this module.

<br>

<img src="../assets/slo_alerts.png" alt="SLO Alerts" width="50%" height="50%">

<br>

Your SLO will be more strict than your SLA. So it is important to be alerted when you are not meeting an SLO because it's an early warning that the SLA is under a threat.

Here's an example of what creating an alerting policy looks like. On the left, you can see an HTTP check condition on the `summer01` instance. This will send an e-mail that is customized with the content of the documentation section on the right.

<br>

### Activity Intro: Cost Estimating & Planning

In this design activity, use Google Cloud's pricing calculator to create an initial estimate for deploying your case study application.

The pricing calculator gives you a form for each service, which you fill out to estimate the cost of using that service.

<br>

<img src="../assets/custom_sql_example.png" alt="custom sql example" width="50%" height="50%">

<br>

For example, in this screenshot, I calculate the cost of one custom SQL instance with four cores, 16 gigabytes of RAM, and 500 gigabytes of SSD storage. This could represent the orders database of my online travel application. Some of these estimates aren't easy to generate because you might not know how much data your storage and database services need, and how much compute your deployment platforms require.

However, it can be more challenging to estimate things like network egress or the number of reads and writes. Start with a rough estimate and refine it as your capacity plans improve.

Refer to activity 13 in your workbook for similar cost estimates for your case study.

<br>

### Activity Review: Cost Estimating & Planning

In this activity, you were asked to use the Google Cloud pricing calculator to estimate the cost of your case study application.

<br>

<img src="../assets/example_sql_cost.png" alt="" width="50%" height="50%">

<br>

Here is a rough estimate for the database applications of my online travel portal, Click Travel. I adjusted my orders database to include a failover replica for high availability and came up with some high level estimates for my other services. My inventory services uses Cloud storage to store JSON data stored in text files.

Because this is my most expensive service, I might want to reconsider the storage class or configure Object Lifecycle Management.

Again, this is just an example and your cost would depend on your case study.

<br>

#### Lab Intro: Monitoring Applications in Google Cloud

We started this course with a discussion on defining SLOs and SLIs for your services. This helps with the detailed design and architecture and helps developers know when they're done implementing a service.

However, the SLIs and SLOs aren't very useful if you don't monitor your applications to see whether you are meeting them. That's where the monitoring tools come in. In this lab, you will see how to use some of these tools.

Specifically, you will examine logs, view profile information, explore tracing, monitor your resources using dashboards, and create uptime checks and alerts.

<br>

#### Lab Review: Monitoring Applications in Google Cloud

In this lab, you saw how to monitor your applications using built-in Google Cloud tools. First, you deployed an application to App Engine and examined Cloudlocks. Then you viewed profile information and explored Cloud Trace. Last, but not least, you monitored your applications with dashboards and created uptime checks and alerts. You can stay for our lab walk-through, but remember, Google Cloud's user interface can change, so your environment might look slightly different.

So the first thing we're going to do is Activate Cloud Shell and then we're going to use that to download a sample app from GitHub. So I'm just going to click continue, because this is a new project, and I like to open this in a new window just so I have a little bit more space. That's just telling us that the Cloud SDK is pre-installed, that's great, and I'm going to wait for the machine to be provisioned. I'm going to create a directory, navigate to that directory, and then clone a simple Python Flask application from GitHub.

So let me just make that directory, going to navigate to that directory, and then I'm going to git clone from the same repository that we saw in the previous lab.

So this is not been completed, so let me change directories to that, and then I'm also going to launch the code editor, and in here, I am also going to navigate through courses, design-process, to this application.

And here we can see the main file.

So what I'm going to do now is I'm going to make some modifications to the main file because I want to use the Google Cloud profile. The first thing I'm going to do is import the profiler. I'm going to specify that on line 2, import profiler, and this allows the profiler to monitor the resources the application uses.

Now I'm also going to, after the main function, add a code snippet to start the profiler. So let me go down here, and maybe add this on line 13, and then they're going to try to add that. And now I'm going to confirm that the code in here matches what is shown in the lab instructions, and that looks good to me. So this code simply turns the profiler on and once the profiler is on, it starts reporting application metrics to Google Cloud.

Now, we also have to add the profiler to, the profiler library, I should say, to our requirements.txt. So let me go do that, I'm going to open the requirements.txt, and on line 2, I'm just going to specify that we're going to use the Google Cloud profiler.

And so I've added it everywhere. Now, the last thing I need to do is enable it for the project. We can do that directly in Cloud Shell.

So I'm just going to clear this to give myself more space and I'm going to run the command and lab instructions to enable the cloud profiler from the Google APIs. So let me run that, and once that has been completed, we're going to test the program by first installing the requirements and then starting the program.

And there we can see the Google profiler in here, that's successfully built, and let's test that. Now, within Cloud Shell, I have the web preview option to preview this import 8080.

And if I do that, we see that the program is currently working and it's just displaying, HELLO GCP.

So that's it for task one. Now, in task two, we're going to take this application and deploy it to an App Engine application.

So let me go back, we are going to stop this.

And I'm now going to create a new file, the app.yaml, which we did similarly in the previous lab, so I'm just going to, oops, right click here on this folder, New File, app.yaml.

And the minimum that we need to specify in here is the runtime. So I'm going to specify python, then Save those changes, and now we're going to start off by specifying the region where we want this app to be created. So I'm going to use the gcloud app create region us-central1, and that's now creating that for our project in that region. And once that's up and running, we're going to deploy our app.

Okay, so now I can deploy it and we're going to wait for that to complete. So the app has been deployed, so let's go to the Cloud Console to view it. So I'm just going to navigate to the Cloud Console, can make this a bit smaller here. And in the navigation menu, I'm going to go to App Engine. Collapse these two so I have a bit more space, and we currently only have one version, and here's our application, and if I click on that, we should see the same page we saw earlier, Hello GCP. And I can refresh this a couple times now to start generating some traffic and we're going to do a little bit more of that in a second for the profiler. But first, let's go to task three and examine the Cloud Locks.

So for that, I'm going back to App Engine, and I'm going to click on Versions.

Here is my version that's serving all of the traffic. And if I go to the right under Diagnose, tools, I'm going to leverage Logs.

And we'll see here some of the requests I've been making, and we will also see here that the Stackdriver profiler agent has started and has created a profile, so we can see that that has been successful.

So now we can move on to task four and view the profiler information. So I can go to the navigation menu, scroll down to Operations, and here is the Profiler.

So this gray bar here at the top represents the total amount of CPU time used by the program. And the bars below that represent the amount of CPU time used by the program's function relative to the total. At this point there's no traffic, really, so the chart is not very interesting. So what we're going to do now is we're going to throw some load at the application. We're going to do that by creating a virtual machine using Compute Engine that is in a different region than our App Engine app, and then we will use Bench to create some traffic on here.

So let me go to the navigation menu, go to Compute Engine, and I'm going to click Create.

And in here now, we're going to just choose a different region.

So instead of us-central1, we're going to place this in, let's say, europe-west1, and then I'm just going to click Create.

And once this virtual machine is up and running, we're going to SSH to this instance. We're going to run sudo apt update and then also install apache2 utils. So we go to SSH and resize this window a little bit.

And then we're going to go ahead and run that and then use Apache Bench to generate the traffic. So first, I'm going to update.

Then install Apache Bench.

And when I run the Apache Bench command now, I'm going to run it 1,000 times, 10 requests at a time, but I need the site, the HTTPS address, for my App Engine application. This is always in the form of, by default, of project ID.appspot.com, so I could just use that, or I am going to go back and just grab it in my browser, I still have it in there. And it's important that you have the slash at the end. So I'm going to run that, and we can run that a couple times to just generate some traffic. It might take a while for the profiler to show something very interesting. But if you generate enough traffic, and again, you might have to try just a couple times for the information to start showing up, you will definitely see him some more interesting graphs, that again, where you have these bars. And each bar represents a function and the width of the bars represent how much CPU time each function consumed, so I'm just going to keep generating some more traffic. I'll look at the profiler and then move on to task five. All right, so I've generated some more traffic. So I think it's time to go back to the Cloud Console, and from the navigation menu, I'm going to go back to Profiler, and indeed, this looks a lot more interesting. So again, each of these bars is a function and the width of the bar represents the amount of CPU time that the program has consumed for each of those functions.

So that finishes task four, so it's time to move on to task five where we're going to explore Cloud Trace.

So every request to your application is added to a trace list. So let's go to the navigation menu and as well under operations go to trace.

So this is an overview screen and it shows recent requests allows you to create reports to analyze traffic. But because our program is new and really only has one page is not very interesting but in a real lab, there will be lots of useful information in here.

So I'm going to first click on the trace list and this is going to show a history of the requests and their latency. So here are all of the different requests. I've made just over the last couple of minutes. I can see all the latency. Some of them definitely took a little bit longer and I Also see all of them here and there latency so we could do now is I could go back to my SSH window of my virtual machine. I could just go ahead and generate more and more traffic and I'm going to do that. I'm going to come back and look at this Trace list again.

So I've run the Apache bench command a couple more times. And what I did is I've actually changed it and you could do that to to just play a little bit with the values of N and C. So I'm requesting it 10,000 times and a hundred times a time.

So now let me go in here and reload my Trace list and now you can see that I have a lot more requests and because I'm requesting so many do so many question the same time some of them certainly have a higher latency. So again, you could keep playing with this. Keep in mind, the lab is only open for so long. But this is just to give you an idea of Trace and how to use the Trace lists.

I'm now going to move on to Task 6 where we're going to monitor resources using dashboards. So in the Cloud Console, I'm going to navigate to Monitoring which again is under the Operations section.

And what this is gong to do is it's going to first set up a Workspace for us. So let's wait for this to complete.

So the Workspace is now established, so we get this Welcome page here and we can now use the navigation bar over here on the left. So first I'm going to head to Dashboards and here we can see Dashboards for different resources. It's currently not showing GC instances. We might have to refresh and wait for a while it to come back. For now let's just go to App Engine and here we see our project and our application. And I can click on that to just see a dashboard for our application. Now it's just just showing me some responses on HTTP. I can also go to SYSTEM and DATASTORE and look at a couple different options or I could actually go ahead and create my own custom dashboard. So if I go back to Dashboards, I could also click CREATE DASHBOARD, give it a name, My Dashboard.

And since it's currently not showing GC instances, let's just create something ourself. So dashboard is just sort of a canvas and you just add Charts to it. So I'm going to look for GCE VM instance. There we go, and I'm going to select CPU utilization.

No, I only have one instance, so that is the one shown here. And here I get a little bit idea of what kind of load the Apache Bench command has put in my instance that I have. So obviously, when I run the command there's high utilization than when I don't, you can see that here. And I could put other things in here like Filters or Group this or I could just save it and have this chart. So here we can now see my CPU utilization, and I could create other charts in here that might be interesting.

Now, that's it for Task 6, so let's move to Task 7 where we're going to create uptime checks and alerts. So here in the left hand side I'm going to click on Uptime checks and CREATE UPTIME CHECK. Now we're just going to give it a name, so let's make this the Uptime Check for our App Engine application. The check type is going to be HTTPS. We're just going to use a resource by URL and now I need to put in the Hostname and then .appspot.com. So I'm just going to grab that again, I'm navigating back to the browser where I have this app open already and put that in here. I already set this to HTTPS. And this is the path, so I can remove that up here and then I can just say, sure, check every minute. And I could now test this to see this working, response okay. Great, and then I can Save that.

Now it's saying, hey, great, we've created this uptime check, but do you also want to create an alert policy? This is actually pretty useful because if for whatever reason you have some down time in your application and you're not currently looking at this uptime check, you won't be notified unless you create a policy. So let's create an alert policy.

So it's already looking at that and making sure that's uptime.

So this is the uptime check sort of metric itself the condition so I can just give that a name. Say My Uptime Alert.

Or actually the, sorry, the lab instructions are saying, Uptime Check Alerts. So let's do that because a lot of times the scores that we're giving the labs require that you follow the instructions.

And then I'm going to, this is the, sorry, this is the condition. I can also put that same name in here and then I could have several conditions. So if anything else is going on and I could say, hey, it's either an or or an and condition with these triggers. And then really importantly, optional, but important you should add a notification channel. So if I click on that in here you have different types. So you could use, for example, Email and you could send yourself an email. I don't really recommend putting your own email in here. You could and test it, but the App Store not going to go down until this project is deleted and then you might get tons of emails that you may not like. So as an example, I can just put in the email from this qwiklabs project and add that.

And then also importantly is to actually put in some documentation. So whoever gets this email, what should they be doing when they receive this alert? I'd be very specific, I'd have the actual disaster plan in here, right? If this application goes down, do XYZ, notify these people, do that. So that's really what you want to put into the documentation. So I'm just going to go ahead and save that because that's required for the scoring that we have in here.

And actually what you can do is you could now go ahead and disable the application and just see that the uptime check will then fail. So let's actually look at the uptime check. Currently, if I go to the up time check, we see these different continents from where we're checking. This uptime check, it's working from everywhere. I can click on the name to actually get more information. I see so far it's been 100% uptime. I see the latency and I can drill down into that by looking at the latency from different regions. So here we can see this is actually being tested from different regions, specifically in these different continents. We have different regions from where we're checking this and here we can see our overall configuration one more time. We also see that we have an Alert Policy and we could create some other Alert Policies. So let's go ahead and disable the application. So I'm going to go into the navigation menu and go back to App Engine.

All right, so here I am on App Engine, since I'm going to scroll down and go to Settings. And I'm going to click Disable application. Now for safety reasons, it's telling me that I need to type in the name. So let's type in the App ID, I can actually copy that and click Disable. So this is now getting disabled and now I can go back to the Dashboard. And if I try that URL, we see we get a 404. Great, that's what we're trying to replicate. So let me go to the navigation menu and let's go back to Monitoring and head to our Uptime check. And we're going to wait until this check is run again, which keep in mind, is being run every minute and see that this should then be failing.

Okay, so here we can see it's already failing, only took a couple seconds. In Europe it's failing, here one out of three tests have failed, and if I just navigate to Alerting and back to Uptime checks, I can see, what? All of North America, all of South America, Asia Pacific, probably needs to run one more time. If I go in here now, we see the Percent Uptime is already down over the last hour. My Uptime Latency Zone and here apac-singapore's the last region and if we refresh there we go, all of these have failed. So if I go to Alerting, I see that I have my Alert policy. They should be firing any moment now to send me an actual alert depending on the the conditions that are defined in this alert, which is just at what point does it actually send that alert? And if you've put in your own email address, you will actually be getting that alert.

So we could refresh this a couple times and wait for that and once you actually see that the incidence fired or you get the alert, you do want to go back here and edit the notification channel of this alert. And remove your email address so that you don't accidentally get any spam about this failing in the future because it's going to keep failing so you will keep getting alerts.

So you can do that in here by just editing this.

And clicking the trash icon next to the email and then clicking Save. And then you could also go to the Uptime check and delete the Uptime check itself, as well, just for safety so that, again, you're not being notified about this. And that's the end of the lab.

<br>

### Module Review

In this module, you learned about managing new versions of your microservices using rolling updates, canary deployments, and blue green deployments.

It's important when deploying microservices that you deploy new versions with no downtime, but also that the new versions don't break the clients that use your services.

You also learned about cost planning and optimization and you estimated the cost of running your case study application. You finished the module by learning how to leverage the monitoring tools provided by Google Cloud.

These tools can be invaluable for managing your services and monitoring your SLIs and SLOs.

<br>

### Reading: What's Next? Get Certified

What???s Next? Get Certified

Depending on your planned career path, there are different learning paths and certifications that you can pursue. The Architecting with Google Cloud: Design & Process course that you have just completed forms part of the following learning paths:

[Cloud Architect learning path](https://cloud.google.com/training/cloud-infrastructure#cloud-architect-learning-path)

**Cloud Architects** have a thorough understanding of cloud architecture. They design, develop, and manage robust and scalable cloud architecture solutions. The next course in this learning path is [Getting started with Google Kubernetes Engine](https://google.qwiklabs.com/courses/1574), where you will explore how to implement solutions using Google Kubernetes Engine (GKE).

The Cloud Architect learning path aims to assist you in obtaining the **Professional Cloud
Architect** certification. Complete the curated quests for further hands-on learning and to earn
Google Cloud skill badges. The final course in this learning path is [Preparing for the Professional Cloud Architect Examination](https://google.qwiklabs.com/courses/1491). You will analyze use cases, identify technical watchpoints, and develop proposed solutions. You can test your abilities with hands-on labs and with sample questions similar to those on the exam.

[Cloud DevOps Engineer learning path](https://cloud.google.com/training/application-development#cloud-devOps-engineer-learning-path)

Cloud DevOps Engineers are responsible for maintaining the efficient operations of the full software delivery pipeline. They also oversee that production balances both service reliability and delivery speed. The next course in this learning path is [Logging, Monitoring, and Observability in Google Cloud](https://google.qwiklabs.com/courses/1597) where, guided by the principles of Site Reliability Engineering (SRE), you will learn the techniques for monitoring, troubleshooting, and improving infrastructure and application performance in Google Cloud.

The Cloud DevOps Engineer learning path also has a series of quests that enable you to earn Google Cloud skill badges as you progress on your way to the **Professional Cloud DevOps Engineer** certification.

<br>

### Reading: Workbook Example Solution

[Sample Workbook | Architecting with Google Cloud: Design and Process v2.0.3](../assets/Architecting_GoogleCloud:Design_and_Process_v2.0.3.pdf)

<br>
