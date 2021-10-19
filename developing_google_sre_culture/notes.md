- [Getting Started](#getting-started)
  - [Course Intro](#course-intro)
    - [Module 1 Key Points and Reflection](#module-1-key-points-and-reflection)
  - [DevOps, SRE & Why they exist](#devops-sre--why-they-exist)
  - [DevOps & SRE](#devops--sre)
    - [Module 2 Exercise](#module-2-exercise)
  - [SLOs with Consequences - Module Intro](#slos-with-consequences---module-intro)
  - [SRE Value](#sre-value)
  - [Postmortems](#postmortems)
  - [Blamelessness and Psychological Safety](#blamelessness-and-psychological-safety)
  - [SLOs and Error Budgets](#slos-and-error-budgets)
  - [Share Vision & Knowledge](#share-vision--knowledge)
    - [Module 3 Exercise - Reading](#module-3-exercise---reading)
- [Make Tomorrow Better Than Today: Module Intro](#make-tomorrow-better-than-today-module-intro)
  - [Continuous Integration, Continuous Delivery, and Canarying](#continuous-integration-continuous-delivery-and-canarying)
  - [Design Thinking and Prototyping](#design-thinking-and-prototyping)
  - [Toil](#toil)
  - [Psychology of Change](#psychology-of-change)
    - [Module 4 Exercise - Reading](#module-4-exercise---reading)
- [Regulate Workload - Module Intro](#regulate-workload---module-intro)
  - [Toil & Reliability](#toil--reliability)
  - [Goal Setting](#goal-setting)
    - [Module 5 Exercise - Reading](#module-5-exercise---reading)
- [Apply SRE in Your Organization - MOdule Intro](#apply-sre-in-your-organization---module-intro)
  - [Organizational Maturity](#organizational-maturity)
  - [Skills & Training](#skills--training)
  - [SRE Teams](#sre-teams)
    - [Module 6 Exercise - Reading](#module-6-exercise---reading)

## Getting Started

Welcome to Developing a Google SRE Culture! By enrolling in this course, you’ll be joining a huge, international community of business and IT leaders who are helping their organizations work towards adoption of Site Reliability Engineering technical and cultural practices.

What is Site Reliability Engineering (SRE)?

Site Reliability Engineering, or SRE, is both a practice and a job role, where engineering directly supports software operations. At Google, SRE is described by its founder as "what happens when you ask a software engineer to design an operations team."

What to expect during this training course?

During this training course, you will be presented with a series of modules that will take you through the journey to SRE. You will learn about how both DevOps and SRE emerged in software engineering, and get an overview of important technical and cultural practices that are critical to an organization’s success in adopting SRE. The modules in this course may have videos, exercises, and quizzes.

In order to pass the quizzes, remembering details from the videos and exercises is advised.

In order to get the best training experience, please ensure that you are prepared:

- Ensure that you have headphones or your speakers are on, if you're in an enclosed space.
- Watch videos in their entirety and review the recommended module exercises.

What's Next?

- Watch the Course introduction video and then move onto the next lesson!

<br>

### Course Intro

Welcome to Developing a Google SRE Culture. I've teamed up with experts from Google Cloud, SRE and Professional Services teams to create this course for IT and business leaders who want to learn about and embrace SRE culture in their organizations.

Have you ever had a concern about the reliability of your services? Have you ever seen a decline in customer engagement, but when you question your team, they can't explain why it's happening? Both your development and operations teams say, "Everything's green." But you know, there must be something wrong because your end users, your customers, are telling you so.

If you've spent any significant amount of time producing and running production software, you've probably also felt the frustration of negatively impacting customers when deploying minor updates. You've probably also questioned whether the production freeze your ops team ordered is really based on fact, because you're desperate to push your next release for the important features.

If these situations seem familiar to you, you're probably wondering why your development and operations teams often have conflicting priorities, and why they continue to work in silos. Google has spent years running systems in massive scale. Over time, we've standardize our practices to balance our velocity of features with the risk to reliability, both for us and for our customers. Those practices, combined with a culture to support them, we call Site Reliability Engineering or SRE.

Whether you're still deciding how and when to make the move to the Cloud, or you're already an adopter of Cloud technology, this course can help you understand how practical and cultural SRE principals could have a lasting positive impact on both your IT transformation projects and day-to-day work. You'll also learn how an organization size and maturity level for SRE can affect the implementation of these principles.

This course will give you an overview of SRE technical and cultural fundamentals, and will explain where and how you can apply them in your organization. Because SRE principles are closely aligned with DevOps philosophy practices, the course will also cover the basics of DevOps. Even if you're already familiar with DevOps practices, you'll hear how Google interprets the philosophy, so hopefully you'll learn something new.

This course has several overall learning objectives. By the end of this course, you'll be able to
- discuss Google's view on DevOps philosophy, and the relationship between DevOps and SRE;
- understand the value SRE can provide to your IT operations;
- articulate Google's technical and cultural fundamentals of SRE;
- assess your organization's maturity level in adopting SRE;
- identify what skills to look for in a Site Reliability Engineer, and how to train your existing workforce;
- understand how Google can help you jumpstart SRE in your organization.

Now let's review the course components in structure. This course has seven modules. The first six consists of video lessons, activities, and quizzes. In the seventh module, you'll need to pass a graded assessment to show what you've learned.

The first module is the course introduction and structure, which I'm covering right now. In the second module, DevOps, SRE, and why they exist, you'll be introduced to DevOps philosophy and how SRE practices emerged. Modules 3-5 will cover the journey to SRE.

In module 3, SLOs with Consequences. You'll learn about the SRE concepts of service level objectives, error budgets, blamelessness, and psychological safety. Module 4, Make Tomorrow Better Than Today, will cover the concepts of toil monitoring, implementing gradual change, and the impact automation has on IT teams. The fifth module, Regulate Workload, covers topics around measurement and SRE practices related to measuring toil and reliability.

Once you've learned about the key SRE technical and cultural fundamentals, the sixth module, Apply SRE in Your Organization will discuss steps to begin SRE implementation in your organization. Finally, the last module contains a summative graded assessment to evaluate the knowledge you've acquired throughout the course. I hope you're excited to dive in. Now, let's get started.

<br>

#### Module 1 Key Points and Reflection

1. Key Points

- Customers’ experiences with your service tell you how reliable it is.
- In many IT organizations, development and operations teams have conflicting priorities.
- Site Reliability Engineering (SRE) is the practice of balancing the velocity of development features with the risk to reliability.
- SRE can benefit IT teams, regardless of whether they are using cloud or on-premises technology, for both large projects and daily work.

2. Refection Activity

- Have you ever had a concern about your service’s reliability? If so, what caused this concern? Were there internal or external factors? How did you address it?
- Write down your thoughts, and keep your experience in mind as you learn about Google’s SRE practices.

<br>

### DevOps, SRE & Why they exist

Now that you understand what this course will cover, let's get started. In this module, you'll learn about the practice of DevOps, why Site Reliability Engineering, or SRE was developed, and who in an organization can and should apply these practices. But first, I want to tell you the story of an online retailer. Their application is similar to so many other online retailers. Customers browse the catalog, add items to their carts, and then complete their purchases.

The operations team at this online retailer holds weekly reviews of key metrics. At a recent review, the team noticed that the time between the customers clicking pay and the status coming back as confirmed, was slowly increasing. They recognize that this was not a critical issue, but it did need to be addressed. The team spent some time quietly working on addressing the latency issue.

Over time, on the business side of things, the product development team kept pushing features. Can you guess what happened? Well, developers started working overtime, not only to keep up with the business requests of pushing out new features, but also to resolve the small latency bug that was identified earlier.

The product teams still weren't pleased with the pace of development. Basically, the IT teams put forth a heroic effort to both satisfy the business and also fix the bug. They suffer from burnout in order to meet the needs of both the business and reliability.

Later, when the IT team's efforts became apparent, the product teams agreed that if they had known about the latency bug they definitely would have prioritize fixing that first before pushing new features. But because the business and IT didn't have shared standards for communication, this didn't happen.

So what can you learn from this? Do you think there are ways that the business and IT can communicate better? How do you think you could achieve this in your organization?

Google thought a good place to start was changing the way we think about, measure, and incentivize reliability. We call this collection of principles and practices Site Reliability Engineering, or SRE.

Perhaps you've heard of the DevOps movement. It is a movement that like SRE, strives to align principles, practices and incentives across teams. DevOps and SRE have a lot in common, and they're often discussed together. In fact, you may be wondering how they are different. We will explore some of the common aspects between the two, and how they complement one another in the next video.

<br>

### DevOps & SRE

So what is DevOps? To understand what it is, you first need to understand why DevOps exists. Traditionally, IT teams consist of developers and operators. Developers are responsible for writing code for systems and operators are responsible for ensuring that those systems operate reliably, so customers are happy. Developers are expected to be agile and are often pushed to write and deploy new code as quickly as possible. Essentially, developers want to work faster, innovating, and succeeding or failing quickly.

This resulted in developers throwing their code over the wall to operators who then had to deal with code that was written without much understanding of how it would run in production. Operators who are expected to keep systems stable would prefer to work slower, focusing on reliability and consistency. Quite understandably, this way of working wasn't sustainable between these two groups. Their priorities caused tension between the two teams, and they were not necessarily aligned with the needs of the business.

As a way to knock down the wall and close the gap between developers and operators, a culture instead of practices known as DevOps was born. Let's take a look at how Google categorizes DevOps.

There are five key areas.

<br>

<img src="../../assets/devops_5.png" alt="5 key areas of devops" width="50%" height="50%">

<br>


The first is to reduce organizational silos. You can increase and foster collaboration by breaking down barriers across teams.

Second, you need to accept failure is normal. Computers are inherently unreliable, so you can't expect perfect execution, and when you introduce humans into the system, you get even more imperfection. Things failing will inevitably become part of the process.

Third, you'll want to implement gradual change. Small incremental changes are easier to review, and if a gradual change does release a bug in production, it allows you to reduce the time to recover making it simple to roll back.

Fourth, you need to leverage tooling and automation. Identifying manual work that you can then automate is key to helping your IT team work efficiently and focus on the tasks that matter.

Finally, you'll want to measure everything. Measurement is a critical gauge for success. There's no way to tell whether what you're doing is successful if you have no way to measure it.

It's important to understand that DevOps is a philosophy versus a development methodology or technology. Although DevOps philosophy highlights critical ways for IT teams to operate, it doesn't give explicit guidance on how an organization should implement practices to be successful.

That's where SRE comes in. So what is SRE? SRE evolved at Google in early 2000's separately from DevOps. Back in 2003, Benjamin Treynor Sloss, currently a VP of engineering at Google, was tasked with managing a team of engineers who are responsible for keeping Google's websites up and running. You're probably wondering, "Wait, so a bunch of software engineers who write the code now also have to be responsible for running their production systems? But doesn't the Ops team do that?" Well the answer, at least traditionally, is yes. However, this team only had software engineers, so Ben had them spend some of their time on operations tasks in addition to development tasks. So they could better understand how their code ran and production.

This way of working is what led the team to site reliability engineering and the associated job role were SREs, who are generally engineers, are responsible for operations. Just as DevOps aims to close the gap between software development and software operations, this new SRE approach is a concrete way to solve problems that the DevOps philosophy addresses.

Note that SRE is both a practice and a role.

Not every organization that follows SRE principles necessarily must have engineers with the title SRE. This course mostly focuses on the practices and principles themselves, things like titles and team structures are implementation details.

Several SRE practices align to Google's categorizations of DevOps, and in addition to implementing SRE technical practices, you'll also want to implement cultural practices. Without a culture to sustain them, it is not possible to maintain the practical aspects of SRE.

Let me explain where these fundamentals fit into the key areas of DevOps we discussed. With regard to reducing organizational silos, SREs share ownership of production with developers. Together they define service level objectives or SLOs and error budgets, and share responsibility of how they determine reliability and prioritize work.

<br>

<img src="../../assets/sre_devops_5.png" alt="" width="50%" height="50%">

<br>

Culturally, this promotes shared vision and knowledge as a well as a need for improved collaboration and communications. Complex systems fail in interesting and complex ways. Accepting failure as normal state is an important practice within SRE. A blameless postmortem is held after an incident to improve the understanding of the failure mode and to identify effective preventive actions to reduce the likelihood or impact of a similar incident. Learning from incidents in this matter requires a culture of psychological safety and blamelessness.

When implementing gradual change, SREs aim to reduce the cost of failure by rolling out changes to a small percentage of users before making them generally available. Culturally, this promotes more of design thinking and prototyping.

Next, in order to leverage tooling and automation. SREs focus on toil automation reducing the amount of manual repetitive work. Automating this year's job away can undoubtedly be met by resistance, that's why teams need to talk about and understand the psychology of change and how to address resistance to change within the team.

Finally, measuring everything means that SREs work to measure everything related to toil, reliability, and the health of their systems. To foster these practices, organizations need a culture of goal setting, transparency, and data-driven decision-making.

Before diving into each of these pillars as they relate to SRE, I want to acknowledge that sometimes people can see these practices aligning with different or many of the pillars of DevOps. It is likewise important to acknowledge that the language and definitions across different organizations, are less critical than driving towards the goal of your organization, and the outcomes you are trying to deliver for your customers. In other words, we may disagree on the precise terminology, but many of the underlying principles are the same. The goal of SRE is to serve the business and the user, not the other way round. The next three modules will dig a bit deeper into all of these SRE practices and cultural concepts.

<br>

#### Module 2 Exercise

1. Key Points

  - DevOps emerged to help close gaps and break down silos between development and operations teams
  - DevOps is a philosophy, not a development methodology or technology.
  - SRE is a practical way to implement DevOps philosophy
  - Developers focus on feature velocity and innovation; operators focus on reliability and consistency
  - SRE consists of both technical and cultural practices.
  - SRE practices align to DevOps pillars:

<br>

<img src="../../assets/sre_devops_5.png" alt="" width="50%" height="50%">

<br>

2. Reflection Activity

- In this module, you heard the story of an online retailer whose developers suffered from burnout due to the demands of increased feature deployment while addressing reliability issues on the side.

- Have you ever noticed this type of behavior with your development teams? If so, what do you think caused it?

<br>

### SLOs with Consequences - Module Intro

If you think about SRE as a journey, the first step is to develop service level objectives or SLOs with consequences.

The performance of your service relative to SLOs should guide your business decisions.

In this module, we'll first discuss the value of SRE to your organization, that is, what your IT team and its members will gain from SRE implementation, and the role middle managers and top leadership play.

After that, we will cover the first two pillars of DevOps;
- accepting failure as normal
- reducing organizational silos, and some of the SRE technical practices and cultural fundamentals that Google aligns to them.

We'll then discuss post mortems and how teams can and should foster blamelessness and psychological safety. You'll also learn about the practices of SLOs and error budgets, and the importance of sharing vision and knowledge across your team.

<br>

### SRE Value

Throughout this course, you'll learn about the key concepts of SRE and how they could be applied in your business. Before we explore each practice, it's important for you to understand how SRE adoption and implementation could provide value to your organization.

The mission of SRE is to protect, provide for, and progress software and systems with consistent focus on availability, latency, performance, and capacity. By adopting SRE in your business, you're looking after both your internal developer teams and the customers that consume your services.

SRE practices support engineering teams working at a high velocity to release features. At the same time, they maintain practical goals and measures to prevent failures so that your end users are happy.

As you learned in the previous module, SRE teams focus on practices such as automation, learning from failure, and reducing the cost of failure.

By following principles like these, your teams will be less stressed and less inundated with mundane, repetitive work; they'll be able to do more valuable work at a quicker pace while also focusing on the reliability of your services.

Automation in particular creates opportunities for upscaling and innovation. If you incentivize your engineers to automate processes where they can, they'll be making time for other creative projects that they otherwise might not have the capacity for.

SRE also accelerates innovation with practices of launching and iterating, which allows teams to fail fast, learn from failure, and try again. But remember that they will need cultural and organizational support to be successful in the long-term, and that's where you come in.

Understanding SRE practices and norms will help you build a common language to speak with your IT teams and support your organization's adoption of SRE both in the short and in the long-term.

In the next video, you'll start learning about SRE practices in a bit more detail, starting with blameless postmortems.

<br>

### Postmortems

When working at high-velocity in development operations, or really at any speed, mistakes are inevitable.

That's why Google sees accepting failure as normal, as a pillar of DevOps philosophy. But how exactly can you implement this philosophy in your organization?

Experienced site reliability engineers are comfortable with failure, and know that incidents and outages are going to occur, even if they've taken all the necessary precautions. Before an outage, SREs seek to eliminate ambiguity by building monitoring and observability in the platform, and establishing and documenting processes for incident response and management, handoffs, and other outage activities. This allows them to confidently focus on the relevant issue during an incident. After an outage, it's important to understand why an incident occurred, and then take steps to make sure it doesn't happen again in the same way.

SREs do this by documenting and conducting a blameless postmortem. Some people also call this a retrospective. In fast-paced environments where new problems are being addressed constantly, it's easy to just address one incident and then move on to the next without taking the time to actually learn from what happened.

To avoid doing this, SREs take a systematic approach to ensure that the team collectively learns from the incident.

So what is the purpose of a postmortem? A postmortem's ultimate deliverable is a written record of the incident that consists of specific parts.

<br>

<img src="../../assets/postmortem.png" alt="postmortems" width="50%" height="50%">

<br>

Details of the incident and its timeline. The actions taken to mitigate or resolve the incident. The incidents impact.

It's trigger or root cause or causes. The follow-up actions to prevent its recurrence. Particularly, a blameless postmortem only focuses on the root causes of an incident without accusing a particular person or team, or their actions or behavior. Specific people will write and review the postmortem, but everyone who had a role in the event will be a part of the postmortem process so you can collect as much information as possible. Now, you might be wondering why you should conduct a postmortem beyond identifying the root cause or causes. If it was just about fixing it or preventing the issue, it might seem like it's unnecessary if you've already accomplished that goal.

A postmortem has several specific and important goals. You want to ensure that all the root causes are properly understood by the team.

Almost all outages have multiple causes at their root. Many times, each of those causes taken in isolation may not have been enough to cause a failure, but when combined, they lead to an incident. Tactics like the five whys are used to probe deep into what caused an incident in all of the contributing factors, not just what first appears to be the culprit. You want to define or take effective actions to prevent the issue from occurring again.

At this point, you've probably taken some actions to resolve the immediate user impact, but in the long or even short term, the outage might happen again. You need to prevent recurrence and prioritize the work to do so.

You want to reduce the likelihood of stressful outages. Every outage is a stressor on the team. Google wants its SREs to spend their time improving its systems not dealing with incidents. Good system hygiene, including outage prevention, is a key quality of life factor for your engineers.

You want to avoid multiplying complexity.

Much of the time, quick fixes are involved in solving incidents and preventing their immediate recurrence. Each of those fixes is like a Band-Aid or patch on the system. If you don't perform good postmortems and permanently prevent recurrence, over time, fixes will become interdependent and sticky as each one stacks on the other. This makes the system more complex than necessary, and less maintainable, and ultimately increases the likelihood of future failure.

You want to learn from your mistakes and those of others.

Every failure is an opportunity to learn. Good SREs are constructive pessimists, and a lot of their instincts come from experiencing past failure.

In addition to creating a documented record for your team to learn from, the practice of writing a postmortem provides additional value to your organization. Focusing on blamelessness helps to increase the effectiveness of your teams. They become 100% focused on preventing a problem from occurring, instead of worrying about being blamed if something goes wrong. It also promotes a culture of psychological safety, which we will discuss in the next video.

<br>

### Blamelessness and Psychological Safety

SREs believe that failure is normal and that progress is about learning from mistakes and ensuring that they don't make the same one in the same way again.

As you learned in the previous video, a key practice of SRE is conducting a postmortem after an incident or outage occurs. An SRE postmortem is blameless, which means that the incident is looked at objectively without designating a person or team as the root cause. Blamelessness can have an immense positive effect on the culture of your organization. Specifically, it creates a culture of psychological safety for your teams.

So what is meant by psychological safety? Psychological safety is the belief that a person will not be punished or humiliated for speaking up with ideas, questions, concerns, or mistakes.

Thinkback to a time when you had a concern about a task you are asked to perform as a manager or individual contributor. Maybe there was an approach your manager asked your team to take, and while everyone else agreed, you had some reservations.

What did you do in that situation? Did you speak up and voice your concerns, or did you stay quiet? If you stayed quiet, do you remember why you did?

In work environments with low psychological safety, team members are more likely to keep their concerns or ideas to themselves because they feel that they will look incompetent, or ignorant, or even be ridiculed for having a different opinion. This fear can have a lasting impact on your teams. So what do you think is a consequence of low psychological safety among teams?

When you don't say what you want to say, you're actually robbing yourself and your team members of small moments of learning. Maybe the concern or question you have has a simple clarification or answer. If you express it, you and others can easily learn what that answer is, but maybe what you have to say or ask isn't so straightforward. Perhaps it will cause others to think differently, spark a new conversation, or lead to a new idea.

When people are busy managing impressions, they don't contribute to creating a better organization. In short, low psychological safety in the workplace can stifle learning and innovation. Knowing that psychological safety is important in your organization is the first step. Next, how do you build it?

As a leader, you can start with three simple steps.

Framework as a learning problem and not an execution problem. Let your people know that you need everyone's voice and ideas.

Acknowledge your own fallibility, let them know that you may miss something you need from them, and encourage them to ask questions.

Model curiosity, make sure that you yourself ask a lot of questions.

How do psychologically safe environments affect software delivery? Well, research has shown that they have high impacts on it. In these work environments:

- Bridging is encouraged
- There is high cooperation
- Messengers are not punished when delivering bad news
- Failure is treated as an opportunity for improvement
- new ideas are welcomed

These attributes lead to improvements in lead time, deployment frequency, and time to restore. Psychological safety plays a key role in both boosting SRE team dynamics, and also directly influencing operational excellence and software delivery. Google has seen it working with our customers and partners, and also within Google itself.

Shifting team focus from blaming individuals to analyzing processes is a transformation in how engineering teams operate and has long-term benefits in fostering psychological safety, and establishing trust.

Now let's talk a bit about blamelessness.

In order to truly employ the practice of postmortems, you need to foster psychological safety in your organization. Blamelessness is the behavior that fosters psychological safety. But why do people blame?

Research has shown that there are two major factors that fuel people's tendencies to blame others:

- hindsight bias
- discomfort discharge

Hindsight bias is the tendency of people to overestimate their ability to have predicted an outcome, even though it could not have possibly been predicted. People often fail to realize that it's only obvious now that it has already happened. A simple example of hindsight bias is insisting that you knew that the losing team of a sporting event was going to lose all along just because you originally said you predicted it. In working environments, however, hindsight bias can often lead to blaming the person in charge, saying that they should have seen the obvious and planned for it.

The second factor is discomfort discharge, which says that blame exist to discharge comfort and pain at a neuro-biological level. Sociologist Renee Brown claims that we are pretty much wired for blame because it's a natural way to release discomfort, but blaming people only hinders the ability to learn from mistakes. People tend to hide information or don't declare incidence because they're scared of punishment.

Similarly, people are afraid to ask questions that may lead to identifying the root causes of an incident if they feel their question may lead to punishment or ridicule for themselves or their peers.

Mistakes are valuable opportunities to learn and improve only if the correct procedural and systematic causes of the mistake are properly identified. In short, blaming people creates environments that are not psychologically safe. So how can you focus on blamelessness in your organization and with SRE practices such as postmortems?

Blamelessness is the notion of switching responsibility from people to systems and processes. In finger pointing organizations where the first question of manager asks after an incident is, who did this? Employees become much more risk averse and fearful. It's best practice to assume that individuals act in good faith and make decisions based on the best information available. Investigating the source of misleading information is much more beneficial to the organization than assigning blame. In short, don't focus on people, focus on systems, and processes to better support people making the right choices when designing and maintaining complex systems.

It's also important to mention that aside from the ability to learn from previous mistakes, blaming people instead of systems and processes has a negative impact on the organization's ability to innovate and improve. As innovation inherently requires some degree of risk taking, no new product, service, or process has 100 percent probability of success. So no one wants to propose improvements if they're going to be blamed for if it fails. Google's professional services teams has taken this topic to several of its customers who, like you, are interested in developing SRE culture within their business. They were able to help expose certain aspects of team culture that needed attention and offer SRE culture focus training to create a plan for improvement.

A top online retailer in the Netherlands learned about psychological safety for the first time during one of Google's SRE workshops. They were very enthusiastic about the concept, but found it very difficult to implement. Due to their then current blaming culture, they considered identifying the person to blame as a solution to their incidents. Google introduced them to SRE philosophy and through intense internal training coupled with performance management changes, they're now on the right path to create a psychologically safe environment.

You can see how blamelessness and psychological safety are important organizational aspects to foster in developing your business, especially if you want to implement SRE. The success of shifting your IT teams to SRE is highly dependent on your commitment to these as cultural norms.

<br>

### SLOs and Error Budgets

As you learned in the last module, DevOps philosophy emerged in part due to the siloed nature of software development and operations. Developers generally aren't very familiar with the systems their code runs on and operators have to deal with code that may be unstable. And that code just keeps coming over to them at a high velocity from agile developers to be an effective team that isn't stuck in break fits mentality. The walls between the business, development and operations teams need to be knocked down.

Software engineering as a discipline focuses on designing and building rather than operating and maintaining. Despite estimates that 40-90% of total costs are incurred after launch. If the majority of the total cost of ownership of software is maintaining it after it's in production and developers aren't working on this then who is sorry? Employees practices that effectively break down these silos and promote shared ownership between development and operations teams. More importantly, these fundamentals help teams maintain reliability of their services. There are several practices that support this. But in this course you'll learn about two specific ones,

- error budgets
- service-level objectives or SLOs

SRE, get everyone to agree on how to measure service reliability and what to do if you fall short from individual contributors all the way up to VPs. Thus ensuring that responsibility for reliability is shared. In order to agree on a target for reliability. You'll first have to define what reliable means and how you're determining it. A simplistic way to think about reliability is that it equals your services `good time` divided by its `total time`, which gives a numerical fraction of time that the service is available in working.

While this is relatively easy to measure and understand, it doesn't work very well for distributed complex systems. For example, how do you measure good time of a server that currently doesn't receive requests or what if one of three servers is down? Does that mean your services down or is it up?

The more sophisticated approach is to define availability as a number of good interactions divided by the number of total interactions. This leaves you with a numerical fraction of real users who experience a service that is available and working. In essence, service reliability is about determining the amount of reliability you are trying to reach and the amount of downtime you are willing to tolerate. That amount of reliability you are willing to tolerate is your error budget.

If you're thinking that 100% reliability is what your goal should be, you'd be wrong. If you spend all of your time targeting 100% reliability, you'll slow the release of new service features which is what helps drive your business. This is where the error budget comes in as long as the measured up time is above your target, meaning as long as you have narrow budget remaining, you can push new feature releases.

Alternatively, you can spend this remaining budget on something else such as expected system changes inevitable failures and hard wearing networks planned downtime or risky experiments. Essentially an error budget is an agreement that helps prioritize engineering work.

Error budgets create a common incentive for developers and SRE to find the right balance between innovation and reliability. Developer teams can manage the error budget on their own knowing that unrealistic reliability targets will slow down innovation. It creates a shared responsibility between teams for system up time as infrastructure failures takeaway developers error budget.

Another SRE practice that ties to error budgets and creates shared responsibility between develops teams or service-level objectives or SLOs. SLOs are precise numerical targets for system reliability. These targets are agreed upon between stakeholders, thereby sharing ownership of reliability and hopefully mitigating any future confusion or conflict. Since you want your dev teams to work at a high velocity SLOs can help determine how fast is too fast.

Measuring SLOs performance gives real time indication of the reliability cost of new features. If everyone agrees that the SLOs represents the point at which you are no longer meeting the expectations of your users. Then broadly speaking, being well within your SLOs is a signal that you can move faster without causing those users pain.

How can you define SLOs for your service? Well, you first need to understand service-level indicators or SLOs. An SLI essentially tells you at any moment in time how well your services doing. It's a quantifiable measure of service reliability. We recommend that SLIs are expressed as the number of good events divided by the number of valid events times 100%. This gives you a range of 0% to 100%. Where zero equals nothing works and 100 equals nothing's broken. SLIs should map to user expectations such as response time, latency and quality, data processing, correctness and freshness or storage latency and throughput. And so an SLIs is your target for SLIs aggregated overtime assuming you've expressed your SLIs as a percentage between zero and 100. Your SLO should generally be just short of 100 like 99.9% or three nines.

SLOs draw the line between happy and unhappy customers. A typical customer should be happy if you barely meet your SLO. Anything below your SLO will result in an unhappy customer who's expectations for reliable service are not being met.

Lastly in SLA which are likely familiar with already is the promise you make about your services, health to your customers. It defines what your business is willing to do if you fail to meet your SLOs. For example, refunding money.

In the next video we'll discuss the sorry cultural practices that align with the practices of SLOs and error budgets

<br>

### Share Vision & Knowledge

The practices of defining SLOs in error budgets help to reduce and break down silos in organizations focused on SRE. It's also important to understand and build certain cultural practices in your business to help support these technical practices.

Specifically, organizations developing SRE culture should focus on:

- creating a unified vision
- determining what collaboration looks like
- sharing knowledge among teams

Let's take a closer look at each of these. Unified vision, all companies have vision statement that serves as their guide for the work they do. To give a sense of direction, your IT team's vision should support the company's vision.

A team's vision is everything about what drives its work and includes:

- core values
- purpose
- mission
- strategy
- goals

What is your company's vision? How about your team's vision? Does it encompass all of these things? If you're unsure, think about the team's vision statement as you learn about each aspect that should be included in it.

First, values refers to how you can achieve your vision and what guides your behaviors. Values can be expressed by:

- your response to others
- your commitment to personal and organizational goals
- the way you spend your time
- the way you operate as a team.

By developing core values, you could help your team:

- build trust and psychological safety with each other
- be more willing to take risks
- be more open to learning and growing
- feel a greater sense of inclusion and commitment

A team's purpose refers to why it exists. Internal research by Google has shown that teams that have a purpose and meaning to their work have:

- higher life and work satisfaction
- stronger inter-team connections
- less conflict.

Team mission articulates a clear and compelling goal that the team strives to achieve. For example, Google's mission statement is to organize the world's information and make it universally accessible and useful. The Google Cloud change in culture team's mission statement is to bring Google's unique people, culture, and change management expertise to Google Cloud Enterprise customers, helping them to successfully embed new behaviors and new ways of working via adoption of Google Cloud technology.

Your team's strategy is how it'll realize its mission. Strategic action takes on many forms. It can be a single initiative designed to meet a specific future goal. It can be leveraged. A single project can mean multiple future goals, or it requires change, a change in investment of resources and people, and the change in habits and how work gets done.

Some basic building blocks of strategy are to:

- look outside to identify threats and opportunities
- look inside resources, capabilities, and practices
- consider strategies for addressing threats and opportunities
- create alignment on communicating and coordinating work processes

Lastly, setting specific goals aligns your team on what they're striving to attain. At Google, we use OKRs, which are Objectives and Key Results, to set ambitious goals and track our progress. In practice, using OKRs is different from other goal-setting techniques. The idea behind OKRs is to set very ambitious goals. When used this way, OKRs can enable teams to focus on big bets and accomplish more than the team thought was possible, even if they don't fully attain their intended goal. OKRs can encourage people to try new things, prioritize work, and learn from both successes and failures.

While the team may not reach every OKR, it gives them something to strive for together.

Next, let's talk about collaboration and communication. Given the globally distributed nature of SRE teams, effective communication has always been a high priority in SRE. Collaboration between SRE teams has its challenges but has potentially great rewards including common approaches to platforms for solving problems, which lets teams focus on solving more difficult problems.

Let's look at some examples of how SRE teams can communicate effectively. One way is through service-oriented meetings. This is a special kind of meeting where an SRE team reviews the state of the service or services in their charge to increase awareness of all stakeholders involved and to improve the operation of the service or services.

Service-oriented meetings usually happen weekly for 30-60 minutes and should have a designated lead. Attendance should be compulsory for all team members because this is a major opportunity to interact as a group. Setting a defined agenda is important.

For example, your agenda could be to cover:

- upcoming production changes
- metrics
- outages
- paging events
- non-paging events
- prior action items

Another way to create effective communication is to have a good team composition. SRE is usually a distributed organization spread across different countries and time zones. Because of this, the definition of team is variable. There can be local teams, the team on the site, the cross-continental team, various virtual teams, and everything else in between.

Google recommends a few specific roles in any SRE team. A Tech lead who sets the technical direction of the team. This person comments on everyone's code, holds quarterly direction presentations and builds consensus in the team.

A manager who runs performance management and access the first point of contact for the team.

A project manager who comments on a design doc and writes code.

For all these roles, excellent communication skills are required to effectively collaborate across time zones. In module 6, you will learn more about suggested SRE team composition and skills.

Collaboration between SRE teams and other teams is equally as important as communication. Specifically, effective collaboration between product development in SRE teams is vital. This collaboration is at its best when it occurs as early in the design phase as possible that is, before any line of code has been committed. SRE is usually make recommendations about architecture and software behavior. They also use OKRs to track progress of their work with other teams.

At Google, it's common for cross-functional teams to share an OKR, creating a shared agreement on output.

Lastly, let's look at how knowledge sharing helps reduce organizational silos.

Well hired and trained SRE teams are adept at performing more than one job function and have the skills to step into another if needed. In order to create this, your organization needs to focus on cultivating knowledge sharing among its team members.

There are a few ways to ensure that this happens on your team.

The first is to make cross-training a key competency when hiring SREs. This involves training an employee for a flexible response to changing production schedules. In practice, it means teaching an employee who was hired to perform one job function, the skills required to perform other job functions.

A well-designed SRE cross training program can help reduce costs, improve employee morale, reduce turnover, and increase productivity. It can also give a company greater scheduling flexibility and may even lead to operational improvements. Perhaps the most important benefit to companies that implement cross-training programs is greater job satisfaction among employees.

Cross-training demonstrates that the company has faith in employees' abilities and wants to provide them with opportunities for career growth.

Another practice Google recommends is creating an employee to employee network. Employees can develop and grow by teaching others, given that they have firsthand knowledge on a topic. At Google, 80 percent of all track and trainings are run through an employee-to-employee network called g2g or `Googler to Googler`. The volunteer teaching network of Google employees dedicate a portion of its time to helping peers learn new skills. Volunteers, known internally as g2gers can participate in a variety of ways, such as teaching courses, providing one-to-one mentoring, and designing learning materials. They come from every department in Google.

Thirdly, job shadowing is an effective means of generating knowledge sharing. Some examples of job shadowing benefits in IT teams include:

- expert knowledge and exposure for new hires to what others in the team do every day
- hands-on experience for how the system should be maintained
- an opportunity to ask an expert any questions
- a good introduction to the concept of gradual change and broader explanation of what it means to the team
- a way to spot opportunities for cross-functional collaboration
- a great way to understand the nuances of what a particular job entails
- a psychologically safe environment where it's normal to ask questions and learn
- a way to pair up your team members that helps to scale and retain knowledge

Lastly, it's worth noting that although we aligned postmortem practice to the accept failure as normal pillar of develops. It also has overlap in reducing organizational silos, specifically with knowledge sharing. Postmortems are SRE practice that helps you learn from your mistakes. But the means of delivering a postmortem helps when fostering collaboration and knowledge sharing.

Postmortem workflows include collaboration and knowledge sharing at every stage. It's crucial to use technology such as Google Docs that enables some key features:

- Real-time collaboration, which enables data and ideas collection
- Open commenting annotation system, which makes crowd-sourcing solutions easy and improves coverage
- E-mail notifications, which directs collaborators or as used to loop in others to provide input

At Google, we've held numerous customers figuring out ways to employ cultural SRE practices of collaboration, communication, and knowledge sharing in their organizations.

Take a look at a top provider of online solutions in Germany. This customer formed an SRE team, and through an on-site Google workshop on SRE culture fundamentals, they were able to identify the rules of engagement for this new team. They highlighted the importance of reducing the number of communication channels and clearly describing what channels should be used for what purpose. They invested in technology that help them collaborate in real-time directly in project documents via comments or chat. They also use collaborative tools to create their SRE knowledge repository.

You can see how these SRE cultural practices are just as important as the technical practices to help produce silos within IT teams.

In the next module, the SRE journey continues with making tomorrow better than today, where you'll learn about SRE practices that align with implementing gradual change in leveraging tooling and automation.

<br>

#### Module 3 Exercise - Reading

1. Glossary

- Blameless postmortem: Detailed documentation of an incident or outage, its root cause, its impact, actions taken to resolve it, and follow-up actions to prevent its recurrence.
- Reliability: The number of “good” interactions divided by the number of total interactions. This leaves you with a numerical fraction of real users who experience a service that is available and working.
- Error budget: The amount of unreliability you are willing to tolerate.
- Service level indicator (SLI): A quantifiable measure of the reliability of your service from your users' perspective.
- Service level objective (SLO): Sets the target for an SLI over a period of time.

2. Key Points

- The mission of SRE is to protect, provide for, and progress software and systems with consistent focus on availability, latency, performance, and capacity
- Understanding SRE practices and norms will help you build a common language to use when speaking with your IT teams and support your organization’s adoption of SRE both in the short and long term
- Experienced SREs are comfortable with failure
- Failures are documented in postmortems, which focus on systems and processes versus people
- 100% reliability is the wrong target because it slows the release of new features, which is what drives your business.
- SLOs and error budgets create shared responsibility and ownership between developers and SREs
- Fostering psychologically safe environments is necessary for learning and innovation in organizations
- Organizations developing an SRE culture should focus on creating a unified vision, determining what collaboration looks like, and sharing knowledge among teams

3. Reflection

- Think about your IT teams. List some scenarios where working in a psychologically safe environment would benefit them.

- Do you think blamelessness is achievable in your organization? How can you support and encourage blamelessness and psychological safety within your teams? Write down as many ideas as you can. Share these with your leadership team when you start your SRE implementation conversations.

<br>

## Make Tomorrow Better Than Today: Module Intro

In the previous module, we discussed the first step on the journey to SRE, SLOs with consequences. The next step on the journey is to make tomorrow better than today.

In this module, you'll learn about the SRE concepts of continuous integration, continuous delivery or `CI/CD`, and canarying as they relate to the DevOps pillar of implementing gradual change.

We'll also look at the concepts of toil and automation and the idea of automating this year's job away. Along with these technical concepts, you'll also learn about the cultural concepts of design thinking, prototyping and how you can support your teams through change.

<br>

### Continuous Integration, Continuous Delivery, and Canarying

In the world of IT, there are different perspectives on how to approach software development.

Culturally, developers tend to focus on moonshot thinking, where they can implement massive software changes that create breakthroughs and could fundamentally change society, but have a high likelihood of failing.

In contrast, SREs focus on gradual change, where they can test smaller changes that will have less impact on users if they fail.

The DevOps pillar of implementing gradual change is practically implemented by SREs in a few different ways to reduce the cost of failure. SREs believe that change is best when it is small and frequent.

Although change is risky, it's less disruptive to users when rolled out in smaller waves. Google SRE culture focuses on practices of continuous integration, continuous delivery, or CI/CD, and canarying.

Let's first define CI/CD.

Continuous integration, usually refers to building, integrating, and testing code within the development environment. The main goal of this practice is to enable engineers to work on code and test more often. As a result, code quality increases and critical issues can be avoided earlier.

Continuous delivery just means that you can deploy to production frequently, but may choose not to, usually due to businesses preferring a slower rate of deployment. This stage involves continuous integration, testing automation, and deployment automation.

If you think of software development as a process, you can divide it into these categories:

- code
- build
- integrate
- test
- release
- deploy
- operate

In agile development, the process covers code and build. DevOps philosophy spans from code to operate. Continuous integration and continuous delivery fill in the middle with code to test; to release and to deploy.

So how does the practice of CI/CD help reduce the cost of failure when implementing gradual change?

1. It helps to overcome agile transformation challenges.
1. It minimizes code integration headaches.
1. It reduces human error.
1. It promotes higher code quality.
1. It's easier to recover after something goes wrong.
1. You can automate everything, which saves time and money.
1. It provides visibility on project completion.
1. Time to market is shorter.
1. It provides you with more metrics to review and act on.

The other practice SREs use for implementing gradual change is canarying. You may have heard of the phrase "Canary in a coal mine," which is a metaphor for an advanced warning of danger. Coal miners would bring canaries into coal mines to detect dangerous gases. Canaries are smaller and breathe faster than humans, so if they died, the miners knew there was danger.

Let's simplify this metaphor a bit. We have something large that we don't want to harm. We have something small that we are okay losing. The small thing detects danger as we go into the unknown. Now let's see how this relates in terms of SRE practice in production systems.

We have a large service that we want to sustain. We are okay losing a small portion of it. We employ a production change with unknown impact to the small portion to detect danger.

So what exactly does this mean?

Canarying is deploying a change in service to a group of users who don't know they are receiving the change, evaluating the impact to that group, then deciding how to proceed. If the change contains bugs, the cost is much less than if it was rolled out to the whole system and can be reversed quickly.

So what are requirements for canarying? The canary population should be large enough to be a representative subset when compared to the control population. The difference between the canary and the control population should, to the greatest extent practically possible, be only the production change that you are testing.

The canary population should be small enough to not endanger the quality of service as a whole if the canary is broken.

The canary deployment should not be overly complicated, and impose significant cognitive load on the operator. In other words, it should be easy enough to reason about the canary process so that's easy to understand how it can impact current service health overall and easy to cancel in case of problems.

It's true that these three points are to some degree in conflict with each other. This generic requirements also do not include any additional requirements specific to a service.

In the next video, we'll talk about the SRE cultural concepts of design thinking and prototyping, that relate to implementing gradual change.

<br>

### Design Thinking and Prototyping

When you reduce the cost of failure by implementing gradual change practices such as CI/CD and canarying, you open up your teams to be more innovative. Knowing that any change will be tested allows individuals to think big and not restrict their creativity or ideas. This is why design thinking and prototyping are key aspects of SRE organizational culture.

Design thinking is one approach that combines creativity and structure to solve complex problems. Google uses design thinking as one method to teach teams and individuals to think creatively, which is an important step in the process of innovation.

Design thinking methodology has five phases.

First, empathize. In this phase, you want to observe and engage with your intended users to learn more about them and immerse yourself in their environments. Empathy helps you set aside your own assumptions in order to gain insight into your users and their needs.

Second, define the problem you are attempting to solve. Express the problem in the form of a point of view of the user versus what you want to accomplish.

Third, ideate. Now that you've defined the problem, you can start generating ideas for solutions. This is the time to think outside the box.

Fourth, it's time to prototype. In this phase, you can get the ideas out of your head and into the real world. It's meant to be experimental, so you can identify the best possible solution before committing.

Finally, test. You'll want to test your prototype solutions in a real-world setting with your intended users.

If you analyze this even more simply with a software development mindset, you want to first focus on the user, then do some 10x thinking, and then prototype to test your solution.

This approach encourages your teams to think about what they are trying to solve for from the user's perspective. Then they can brainstorm expansively on the solution, and then prototype their solution. Finally, they can then test gradually using SRE practices such as CI/CD and canarying, which you learned about in the last video. It's very important for organizations with SRE teams to promote being prototype driven. Without prototyping, fewer ideas are tested. This creates slower failures versus fast ones, which can lead to fewer successes. However with a prototyping culture, teams are encouraged to try more ideas. This leads to an increase in faster failures versus slow ones, and ultimately can lead to more successes than without prototyping.

Remember that there is no right way to prototype. Here are some examples of how teams can prototype fast to test their solutions.

1. Physical prototyping. Build a model with Legos or other small building blocks.
1. Paper and drawing. Use pencil and paper to wireframe out ideas.
1. Clickable. Create a clickable solution using software that simulates a solution.
1. Role play. Find people to role play testers and try out the prototype.
1. Video. Use video to record a solution and see how users interact with it.

No matter how you prototype, try to make it real enough for users to feel. More concrete prototypes increase the likelihood of actionable feedback. We at Google have learned, based on our customer interactions, that with the help of simple prototypes, customers are able to improve the most complex processes by activating imaginative thinking. Individuals feel motivated and encouraged to have audacious ideas that they might not have by sitting at their desk or during a regular meeting. Some of the examples of prototypes we've seen from our customers include a video panel of a discussion, a heat map, and banner with post-it notes.

One of the leading online retailers in the Netherlands use the design thinking methodology to brainstorm about changes to their production process. The participants arranged paper cups to represent each step in the process. While prototyping, the team used different colored cups to mark the steps needed to be improved or deprecated.

Hopefully now you understand how your organization can benefit from a culture of design thinking and prototyping. Your teams will need your support to help promote and encourage that culture. In the next video, you'll learn about the ways SREs leverage automation in order to put more time and focus into software development versus operations, which is vital for any business's success.

<br>

### Toil

A Google SRE once said:

> "if a human operator needs to touch your system during normal operations, you have a bug. The definition of normal changes as your systems grow."

As discussed earlier in the course, a key pillar of DevOps philosophy for Google is leveraging tooling and automation.

Focusing on this allows your engineering teams to focus on development work instead of operational work. SREs do this by eliminating that operational work, which we call toil.

So what exactly do we mean by toil?

Toil is work directly tied to a service that is:

- manual
- repetitive
- automatable
- tactical
- without enduring value
- that scales linearly as the service grows

Toil isn't just administrative work or work that you don't want to do, because that kind of work can still be very important. Different types of people like different types of work and administrative work can be necessary overhead such as team meetings or HR paperwork. This type of work also isn't tied to running a production service.

By eliminating toil, SREs can focus the majority of their time on work that will either reduce future toil or add service features which generally focus on improving reliability, performance, or utilization.

Until now, you've learned a lot about the reliability part of Site Reliability Engineering. Reducing toil and scaling up services is now the engineering part of Site Reliability Engineering. Engineering work is what enables an SRE team to scale up and to manage services more efficiently than either a peer dev team or a peer ops team. By keeping your SREs working on toil less than 50% of the time, you're also distinguishing the SRE role as clearly different from a typical operations role.

So why is toil really a problem?

Toil can create multiple issues in your organization. Toil can lead to career stagnation. Individual team member's career progress will slow down or stop if they spend too little time on projects. While it's true that Google rewards undesirable work when it's inevitable and has a large positive impact, you can't make a career out of it. It promotes low morale.

People have different levels of tolerance for how much toil they can do, but everyone has a limit. Too much toil leads to burnout, boredom, and discontent. It creates confusion. At Google, we work hard to ensure that everyone who works in or with the SRE organization understands that we are an engineering organization. Individuals or teams within SRE that engage too much in toil undermine the clarity of that communication and confuse people about the SRE role.

Toil slows progress. Excessive toil makes a team less productive. A product's feature velocity will slow if the SRE team is too busy with manual and reactionary work to roll out new features promptly. It sets precedence. If you're too willing to take on toil, your developer counterparts will have incentives to load you down with even more toil, sometimes shifting operational tasks that should rightfully be performed by developers to SRE.

Other teams may also start expecting SREs to take on such work, further perpetuating the issue.

It promotes attrition. Even if you're not personally unhappy with toil, your current or future teammates might like it much less. If you build too much toil into your team's procedures, you motivate the team's best engineers to start looking elsewhere for a more rewarding job.

Lastly, toil causes a breach of faith. New hires or transfers who joined SRE with the promise of project work will feel cheated, which is bad for morale. Even though a lot of toil is unhealthy when running a service, there are some positives for having a little bit of toil. Toil doesn't make everyone unhappy all the time, especially in small amounts. Predictable and repetitive tasks can be quite calming. They produce a sense of accomplishment and quick wins. There can be low risk and low stress activities. Some people gravitate towards tasks involving toil and may even enjoy that type of work, but it should never be the primary work for an SRE.

Toil isn't always and invariably bad and everyone needs to be absolutely clear that some amount of toil is unavoidable in the SRE role and in almost any engineering role. Toil becomes toxic when experienced in large quantities. You should be concerned if your teams complain about being burdened with too much toil.

Now, you may be wondering how you can balance toil with project work. Toil must be a bounded part of the SRE role. If SREs don't have time for anything else, they're doing traditional sysadmin tasks that DevOps advocates against. If you put a threshold for toil at 50% for SREs, they are free to do project work that supports your engineering and reliability goals the rest of the time.

Priority project work for SREs is work that impacts or might impact the team's SLOs. After that, their focus should be work that causes SREs toil. A key aspect of eliminating toil is Automation. SREs strive to automate this year's job away, that is, determining what to automate, under what conditions and how to automate it.

Automation in a production service provide several values.

First, it can provide consistency. Any action performed by a human is prone to error, especially the same action performed hundreds of times. A person isn't likely to be as consistent as a machine. Lack of consistency leads to mistakes, oversights, issues with data quality, and even reliability problems. Automation remedies this by creating consistency.

Next, automated systems provide a platform that can be extended and applied to more systems. A platform also provides a way to centralize mistakes so that a bug is fixed once in one place. With humans, you'd have to communicate that fix across multiple people and there's more room for error and for the bug to be re-introduced.

Additionally, a platform can execute additional tasks faster and with more accuracy than humans, and can also export performance metrics more easily than a manual system. If Automation runs regularly and successfully enough, any common faults can be resolved more quickly. You can then spend your time on other tasks instead, which promotes increased developer velocity since you don't have to spend time either preventing a problem or more commonly cleaning up after it. A problem discovered later in the product life cycle is more expensive to fix. Generally, problems that occur in actual production are the most expensive to fix, both in terms of time and money.

This means that an automated system looking for problems as soon as they arise, has a good chance of lowering the total cost of the system.

Another value of automation is faster action. Machines react faster than humans. For large production services, automating is necessary for survival, since the amount of work required is usually beyond a manageable manual threshold.

Finally, automation saves time. Even though it may be a significant time investment to code a particular automated process, once done, there is no need for continual training of humans in maintenance of the process. Once a task is automated, anyone can execute it.

If automation is not common in your organization, you're likely to see some resistance to change from your teams as you start to introduce it or any SRE practices.

In the next video, you'll learn about the psychology of and resistance to change and how you can help support your teams through SRE adoption.

<br>

### Psychology of Change

When you start to implement the SRE practice of automation to eliminate toil, some individuals will probably begin to resist. It's important to acknowledge that people react to a push for automation in different ways, and that some may resist it more than others. Individuals may feel as though their jobs are in jeopardy, or they may disagree that certain tasks are toil, and don't need to be automated. Because of this, it's important to understand how to address resistance to change in your organization.

But first, let's start with the psychology of change. Change elicits emotions, there are hundreds of different types of reactions and emotions. You should always expect to get positive and negative reactions, even if the change is for the good. Broadly, people and their emotions fall into four categories, let's talk about each group and how you can support them.

1. Navigators, these are the people who will make teams and businesses successful, as leaders, spot them and celebrate their behaviors, use them as champions for the change.

2. Critics, these are the second type of individuals that you should care about, they have passion and energy, critics care, and they have valid fears, so it's important not to ignore them. Spend time with them, because they will be very powerful advocates if you can persuade them.

3. Victims, often this type of individual just needs to get their emotions out, victims tend to take organizational change very personally. Your role as a leader is to listen to them and empathize, once they feel heard, then they can start to listen.

4. Bystanders, these people are tricky because you never know what they are thinking. Often, bystanders have no idea what's going on, and they will just continue as if nothing or no change is happening, you should try to communicate with them, to ascertain their feelings.

Sometimes one person can fall into several categories, remember that it's likely you've experienced all these phases of change at some point in your career. As a leader, the way you navigate your own emotions to change will highly impact the teams you lead, teams look to their leaders to get signals on how to react to change.

Brains are hard wired to reflect emotions, people experience reactions to change not because they're trying to be difficult, but because it's natural.

<br>

<img src="../../assets/brain.png" alt="change responses in the brain" width="50%" height="50%">

<br>

Take a look at how the brain responds to change biologically. When you experience the feeling of being excluded from something, it triggers response in the anterior cingulate, which is the same part of the brain that deals with physical pain. When you realize that something you were told in the past is unrealistic or untrue, the prefrontal cortex switches to high alert, looks for other signs of deception, and triggers feelings of heightened anxiety. When you solve your own problems, you get a rush of adrenaline. The prefrontal cortex can only deal with a few concepts at a time, when you are overwhelmed by unfamiliar concepts, your amygdala is triggered, making you feel anxious, afraid, depressed, tired, or angry. When you pay a greater amount of attention to something, you find it easier to adapt, habitual tasks feel easy and comfortable, because they are hardwired and require little conscious thought. So how can you address these responses?

<br>

<img src="../../assets/brain2.png" alt="manage change responses" width="50%" height="50%">

<br>

Google has some recommended ways to manage and account for people's reactions to change in the teams you lead, exclusion is painful, involve people in the change. Deception anxiety, set realistic expectations. Self-solve adrenaline, identify opportunities for co creation and provide coaching rather than solutions. Amygdala hijack, simplify messaging, and focus on key concepts per user group. Attention density, ensure that communications are engaging and training is interactive.

Unconscious habit, allow people time to build new habits, keeping the neuroscience of change in mind, let's discuss the stages of transition the individuals experience when going through change. There are different versions of the change curve, but this is the way we'll look at it today.

<br>

<img src="../../assets/change_curve.png" alt="change curve" width="50%" height="50%">

<br>

As you can see, there is a beginning, middle and an end, yet it is completely normal for people to move backward and forward, at different times. It's important to understand how to support your teams in each stage, remember to present change as an opportunity, not a threat to your teams. To do this, you'll want to connect with individuals on three levels.

1. Head, which is rational
2. heart, which is emotional
3. feet, which is behavioral.

For the head, talk about why the change is happening and the strategic mission, vision and rationale behind it.

For the heart talks about why people should care, remember that people can be egotistical and self motivated, address how the change will affect them personally in their day to day role, and how it will impact them positively. Find a way to make them feel like they are part of the change, people often just want to feel like they are part of something.

And lastly, for the feet, talk about the knowledge, skills and resources you will provide to make sure they're successful in this change. Teams need support to make sure they are and feel competent when asked to change what they know.

Now that you've learned some ways to address change in your organization, let's look at how to handle a resistance to change. Research has shown that resistance is the primary reason changes fail in businesses. Resistance to change is usually fear of loss, specifically, people fear losing security or control, competence, relationships or sense of direction. Human reaction to loss is much stronger than human reaction to gain, so how can you handle resistance to change? Keep this checklist in mind as you navigate your business's adoption of SRE practices:

- Are all your leaders and managers role modeling the new processes and behaviors?
- Do people understand the reason for the change?
- Do people care about the change being successful?
- Do people have the knowledge and ability to be successful in your new world?
- Are the right reinforcement and recognition programs in place?

If the answers to any of these are no, we recommend that your leadership teams brainstorm how to address them, because all of these pieces need to happen for any successful organizational changes.

Let's look at how one of our customers experience resistance to change.

One of the leading commercial banks in Spain identified a number of processes that they wanted to automate. Their VP of engineering, and the executive sponsor of SRE implementation, was eager to showcase the benefits of the project to the business by investing in automation. The teams on the ground were very reluctant and skeptical about automating the earlier identified processes.

It turned out that they had perceived automation as a direct threat to their jobs.

Because they hadn't been supported during the SRE implementation with a proper explanation of what the changes entailed and the impact changes would have on their projects, their resistance was prominent.

Now that we've covered the SRE concepts that help organizations make their tomorrow better than today, the next module will cover the last step of the SRE journey, regulating workload.

<br>

#### Module 4 Exercise - Reading

1. Glossary

- Continuous integration: Building, integrating, and testing code within the development environment.
- Continuous delivery: Deploying to production frequently, or at the rate the business chooses.
- Canarying: Deploying a change in service to a group of users who don’t know they are receiving the change, evaluating the impact to that group, and then deciding how to proceed.
- Toil: Work directly tied to a service that is manual, repetitive, automatable, tactical, or without enduring value, or that scales linearly as the service grows.

2. Key Points

- Change is best when small and frequent.
- Design thinking methodology has five phases: empathize, define, ideate, prototype, and test.
- Prototyping culture encourages teams to try more ideas, leading to an increase in faster failures and more successes.
- Excessive toil is toxic to the SRE role.
- By eliminating toil, SREs can focus the majority of their time on work that will either reduce future toil or add service features.
- Resistance to change is usually a fear of loss
- Present change as an opportunity, not a threat.
- People react to change in many ways, and IT leaders need to understand how to communicate with and support each group.

3. Reflection Activity

1. Think about work your IT teams do that could be considered toil. How much of that toil is bad? How much is good? Write down your thoughts about the type of toil that you would consider automating, and the toil that you would consider keeping.
2. How might you present adoption of SRE culture and practices as an opportunity to your IT teams and other leadership? Brainstorm some ideas.

<br>

## Regulate Workload - Module Intro

The final step on the journey to SRE is regulating workload.

In this module, you'll learn about the SRE practices related to measuring everything, specifically reliability and toil and the concept of monitoring. We'll also cover the cultural fundamentals of goal-setting, transparency, and making data-driven decisions.

As we discuss the cultural concepts, you'll start to see some overlaps with the other DevOps pillars. This module will connect together what you've learned as measurement truly applies to all the SRE practices discussed in this course.

<br>

### Toil & Reliability

The last pillar of DevOps philosophy we will look at is measuring everything. Measurement helps you clearly see what's happening with your services. At Google, we believe there are three main goals of measuring everything.

First, the IT team in the business can understand the current status of the service objectively. You've already learned how you can measure reliability with SLIs and SLOs.

Second, the team can analyze the data and identify necessary actions to improve the status.

And third, the IT team can collaborate with the business to start making better decisions and impact across the broader organization.

Measuring everything with these goals in mind makes your business data driven and ultimately helps you make better decisions based on operational data you're collecting.

You can't improve what you don't measure. In Site Reliability Engineering, there are three core practices that align to this pillar, measuring reliability, measuring toil, and monitoring. Let's start with reliability. In an earlier module, you learned about quantifying reliability with error budgets, SLIs, and SLOs.

Recap from earlier:

> An error budget is what you deem an acceptable level of unreliability that you can allocate other engineering work to. Product and engineering teams decide what the reliability target is together. Engineering teams inform the target, while product management defines it. This is not really a technical decision, but instead is defined by customer expectations, the competitive landscape, and the position you have in the market.

An SLI is a quantifiable measure of a single aspect of service reliability that ideally has a close linear relationship with your users’ experience with your service.

An SLO combines an SLI with a target reliability—that is, it’s the threshold that, if crossed, turns happy customers into unhappy customers.

Choosing good SLIs is key to measuring reliability. You are making a connection between your SLIs and your user's experience so you'll want to decide what to measure based on their perspective.

For example, it doesn't matter to a user whether your database is down or if your load balancers are sending requests to bad backends. They experience a slowly loading web page, and that makes them unhappy.

If you can quantify slowness, you can then tell how unhappy your users are in aggregate, which lets you define your SLO.

So what should you measure? CPU utilization? Memory usage? Load average? Well, as we just mentioned, these metrics don't necessarily reflect whether your users are happy.

To illustrate the difference, let's look at the signal from these two metrics for the same outage in your service.

<br>

<img src="../../assets/metrics.png" alt="unhappy metrics" width="50%" height="50%">

<br>

If you assume that you have some way of knowing that your users were too unhappy with your service and that this time period is represented by the red area on these two graphs, then you can show that the metric on the right is a far more useful representation of user happiness.

Your bad metric does show an obvious downward slope during the outage period, but there is a large amount of variance. The expected range of values seen during normal operation, shown in blue to the left, has a lot of overlap with the expected range of values seen during an outage shown in red on the right.

This makes the metric a poor indicator of user happiness.

On the other hand, your good metric has a noticeable dip that matches closely to the outage period. During normal operation, it has a narrow range of values that are quite different from the narrow range of values observed during an outage. The stability of the signal makes overall trends more visible and meaningful. This makes the metric a much better indicator of user happiness.

SLIs need to provide a clear definition of good and bad events and a metric with a lot of variance and poor correlation with user experience is much harder to set a meaningful threshold for. Because the bad metric has a large overlap in the range of values, our choices are to set a tight threshold and run the risk of false positives or to set a loose threshold and risk false negatives. Choosing the middle ground also means accepting both risks.

The good metric is much easier to set a threshold for because there is no overlap at all. The biggest risk you have to contend with is that perhaps the SLI doesn't recover after the outage as quickly as you might have hoped for. The second aspect to measure is toil.

As you've learned, toil is work that is directly tied to running a service that is manual, repetitive, automatable, tactical, and without enduring value.

You can measure toil in three steps.

First, identify it. Who is best positioned to identify toil depends on your organization. Ideally, these people are stakeholders and those who perform the actual work.

Next, select an appropriate unit of measure. This unit needs to express the amount of human effort applied to this toil.Minutes and hours are a good choice because they are objective and universally understood.

And third, track the measurements continuously. Do this before, during, and after toil reduction efforts. Streamline the measurement process using tools or scripts so that collecting these measurements doesn't create additional toil.

Start simple, count the number of tickets you receive, count the number of alerts, collect alert stats on cause and action.

These can prove useful in identifying the source of toil. You can measure actual human time spent on toil by collecting data, either in the ticketing system directly or by asking your team to estimate the time spent on toil every day or week.

There are clear benefits of measuring reliability of your services. But you may be wondering what the benefits of measuring toil are. First, it triggers a reduction effort. Identifying and quantifying toil can lead to eliminating it at its source. And second, it empowers your teams to think about toil. A toil-laden team should make data driven decisions about how best to spend their time and engineering efforts.

Additional benefits include:

- growth in engineering project work over time, some of which will further reduce toil
- increase team morale and decrease team attrition and burnout
- less context switching for interruptions, which raises team productivity
- increased process clarity and standardization
- enhanced technical skills and career growth for team members
- reduced training time
- fewer outages attributable to human errors
- improved security
- shorter response times for user requests

Finally, measuring everything involves monitoring. Monitoring allows you to gain visibility into a system, which is a core requirement for judging service health and diagnosing your service when things go wrong.

Let's first look at what you should monitor. It's best practice to alert on symptoms rather than causes. Users don't care whether they can't get to your website because your router is rebooting or because the database is overloaded. Similarly, they don't care if CPU utilization is very high if they can still access the system and it feels fast.

Creating a separate alert for each cause typically results in a lot of spam alerts. It's better to have fewer symptom-based alerts combined with good debugging tools, like dashboards that will allow responders to more easily identify specific cause. Ideally, Google recommends alerting based on error budget burn. You might page someone when you are consuming your error budget very quickly.

For example, when you spend ten hours worth of error budget within one hour, you might just create a ticket for a lower burn rate. For example, if you spent three days worth of budget within three days, basically only escalate to a human if you risk dropping below the SLO for the month. If your SLO is set correctly, you won't be paging people for problems that users don't care about.

There are exceptions to this rule of course, because there might be a problem that does not result in user-visible symptoms.

Capacity alerts can be an example of this. If you know you will exhaust a particular limit soon, it wants an alert even if there is no user-visible symptom yet.

To simplify things, Google recommends monitoring for the four golden signals:
1. latency
1. traffic
1. errors
1. saturation

You can see how measurement and monitoring are important SRE practices that allow your development teams to focus on business critical work.

In the next video, we'll discuss the cultural concepts of goal setting, transparency, and database decision-making, and how supporting these practices is important for measurement.

<br>

### Goal Setting

As we discussed, an important SRE practice is to measure everything, specifically reliability and toil. However, in order to measure everything, you need to ensure that you have a culture of goal setting, transparency, and data-driven decision making in your organization.

So how can you achieve this?

Let's start with goal setting. For this, you'll want to create a data-driven goal setting process. You should look at KPIs for who and for what you are measuring and an approach, what to measure and how?

As you learned in an earlier module, Google uses OKRs, objectives and key results, as KPIs.

OKRs are usually graded on a scale of 0.0 to 1.0, where 1.0 indicates a fully achieved objective. Consider these things when grading OKRs. The optimal point for an OKR grade is 60 to 70%. Think big when developing your OKRs. OKRs are not synonymous with performance evaluation, instead they show individuals' contributions and impact.

Organizational OKRs are graded publicly, so everyone can see their progress. Frequent check-ins throughout the quarter help teams and individuals maintain progress.

Next, you want your organization to embrace transparency. Laszlo Bock, the former SVP of People Operations at Google, once said that transparency is the only way to demonstrate to your employees that you believe they are trustworthy adults and have good judgment. And giving them more context about what is happening, and how and why, will enable them to do their jobs more effectively.

In terms of SRE practice and culture, there are some specific ways of promoting transparency, sharing monitoring tools and sharing communications and feedback loops. In terms of tools, Google uses an issue tracker called Organizer.

Everyone in the company can access this tool.

Specifically, the development and operations teams can review issues and see progress towards their resolutions. Shared tools for development and operations teams promote transparency.

However, it's not just tool sharing that will help your organization maintain transparency. A culture of sharing information needs to come from your systems as well. In communication transparency it's important to remember feedback loops. Feedback loops are simple to understand. You produce something, measure information on the production, and use that information to improve production. It is a constant cycle of monitoring and improvement. IT leaders need to make it a priority in their organizations. To do this, think about the head, heart, feet model you learned about in the previous lesson about resistance to change.

Data-driven decision making is another important aspect of SRE culture. To make truly data-driven decisions, you need to remove any unconscious biases. Unconscious biases or social stereotypes about particular groups that people form without realization. There are several common biases that show up in organizations and influence the way decisions are made.

- Affinity bias, this is a bias towards those who are similar to you. This could mean similar in many different ways, such as race, gender, socioeconomic background, or education level. People tend to gravitate towards those who are like them.
- Confirmation bias, this bias is the tendency to find information, input, or data that supports your preconceived notions.
- Labeling bias, this bias is making opinions based on how people look, dress, or show up externally.
- Selective attention bias, this bias is when you pay attention to things, ideas, and input from people you tend to gravitate toward.

All of these biases can create environments that are not very diverse or inclusive. They can also impact the creativity, innovation, morale, engagement, and turnover in an organization. When employees see decisions being made based on any of these biases, it corrupts their work environment.

So how can you help remove these unconscious biases? First, question your first impressions. Don't stop with the first decision that comes to your mind, especially when you're determining whom to promote, hire, or add to the team.

Next, justify your decisions, if you're held accountable, you'll be less unconsciously biased. Tell people why you decided what you did, if no one will listen to you, write it down.

Lastly, make decisions collectively, ask people to repeat back what they heard, and keep each other's unconscious biases in check. Calling out unconscious bias can be a learning moment, so when you think you see it, speak up.
Sometimes you'll be wrong, and that's okay.

When you create a culture of data-driven decision making and removing unconscious bias, it makes decision making easier. Teams can look at the data objectively and decide what should be done without bias.

Even if there is bias, you have empowered people to call it out when they believe it's influencing decisions. You've now learned about Google's SRE technical and cultural fundamentals, and how they fit into an organization's journey to SRE adoption.

In the next module, we'll discuss how you can apply SRE in your organization by upscaling and hiring team members, understanding various SRE team implementations, and engaging with Google Cloud's Professional Services Organization.

<br>

#### Module 5 Exercise - Reading

1. Glossary

- Affinity bias: Tendency to gravitate toward those who are similar to you, such as with race, gender, socioeconomic background, or education level.
- Confirmation bias: Tendency to find information, input, or data that supports your preconceived notions.
- Selective attention bias: Tendency to pay attention to things, ideas, and input from people whom you tend to gravitate toward.
- Labeling bias: Tendency to form opinions based on how people look, dress, or appear externally.

2. Key Points

- Measure reliability with good service level indicators (SLIs).
- A good SLI correlates with user experience with your service; that is, a good SLI tells you when users are happy or unhappy.
- Measure toil by identifying it, selecting an appropriate unit of measure, and tracking the measurements continuously.
- Monitoring allows you to gain visibility into a system, which is a core requirement for judging service health and diagnosing your service when things go wrong.
- Goal-setting, transparency, and data-driven decision making are key components of SRE measurement culture.
- To make truly data-driven decisions, you need to remove any unconscious biases.

3. Reflection Activity

1. Think about how your IT teams work. What are some things you know they are already measuring? What are some things you think they should measure that they don’t already measure?
2. How do you currently set and measure goals in your organization? Is there anything you think you could improve about the process?

<br>

## Apply SRE in Your Organization - Module Intro

Throughout the last several modules, you've learned about Google's SRE practical and cultural fundamentals, and ways you can adopt them in your own organization. Before you can start employing many of these technical principles, it's important to understand a few additional points.

In this module, we'll discuss how you can assess and understand your organization's maturity and readiness for adopting SRE principles, practices, and culture.

You'll also learn what skills are necessary in an SRE and how to train your current workforce.

Lastly, we'll provide examples of SRE team implementations, and the additional support our Google Cloud Professional Services teams can provide as you continue on your journey to SRE.

<br>

### Organizational Maturity

It's important that you assess your organization's maturity level for adopting SRE, before you implement the various principles.

We've looked at site reliability engineering as a three-part journey;

- SLOs with consequences
- make tomorrow better than today
- regulate workload.

Organizational maturity is considered low if your organization has not yet adopted SRE principles, practices, and culture. Organizational maturity is considered high if you have a well-established SRE team, or if SRE principles, practices, and culture are widely understood, implemented, and embraced.

An organization with high SRE maturity is expected to have the following.

- Well-documented and user-centric SLOs, where a target level of reliability is ideally correlated with customer happiness.
- Error budgets, which are budgets for failure. The error budget is the difference between perfection and your SLO. They allow IT teams to move fast as long as the budget is not exhausted, but with defined actions to improve reliability if the production service fails.
- A blameless postmortem culture. This culture recognizes that things will go wrong and that human errors are really systems problems.
- A low tolerance for toil. Again, toil is work that tends to be manual, repetitive, automatable, tactical, and devoid of enduring value, and that scales linearly as a service grows.

These principles can be adopted by any team responsible for production systems regardless of its name before and in parallel to staffing in SRE team. As you can see, these are many of the technical principles we've discussed throughout the course.

At Google, we believe that we can achieve the business goals mentioned earlier, such as aligning development and operations incentives, balancing feature velocity with reliability, and fostering effective collaboration without first defining SLOs and error budgets and setting policies around them.

It's possible that your journey to SRE may have a different first step based on your organizational culture and business needs. However, these are the Google recommended first steps.

After setting up your SLOs, error budgets, and postmortem culture, you will be better prepared to start defining and organizing your SRE teams. After that, you can start implementing practices for automation and regulating workload.

You can also use this tool called the DORA DevOps Quick Check for a recommendation on how to get started. It's a quick five question assessment about your current engineering practices.

Access the tool [here](https://www.devops-research.com/quickcheck.html)

Work with your engineering and operations teams to understand where your organization fits into this journey. Your organization might not use SRE principles yet, and that's okay.

Hopefully you now have a clearer understanding of the principles to start with.

We at Google want to help you get started. We'll talk about how this works at the end of this module.

In the next video, we'll talk about the types of skills site reliability engineers need to have and develop, to make your SRE team productive and successful.

<br>

### Skills & Training

In addition to understanding the practical and cultural fundamentals that we've discussed so far in this course, SRE should have several skills to support your organization's adoption of site reliability engineering.

Who to hire. As you've learned, in SRE, is an engineer who also runs operations. Unless you're hiring an engineer who has already worked as an SRE, you'll likely need to upskill any current or new engineers you put into the role. SRE concepts are not often taught in school or university. At Google, we also hire SREs that were systems administrators, who have worked operations, and who also have some scripting experience. We offer them software engineering training to improve their engineering skills.

Since you're making a large organizational shift to SRE, it's important to understand that you'll need to provide necessary training and resources for people moving into SRE roles. It's an investment that will benefit your organization in the long run.

What skills to train and hire. At Google, we've discovered that there are particular skills to focus on when training and hiring new SREs. This is by no means a comprehensive list, but it's what Google recommends as essentials when getting started.

- Operations and software engineering. Running applications and production gives invaluable insights that can not be easily gained otherwise. So engineers with little or no experience in operation will need to be upskilled. Additionally, systems administrators or other operators can also make great SREs. So they'll need to understand the software they are supporting and be empowered to improve it.
- Monitoring systems. SRE principles require SLOs that can be measured and accounted for so that understanding of monitoring systems is necessary.
- Production automation. Scaling operations requires automation. Your SREs will need an understanding of how to automate processes.
- System architecture. Scaling an application requires good architecture. So SREs should have a skill set that includes understanding system architecture and how to work with and create it.
- Troubleshooting, SREs are regularly on call, and therefore requires sharp troubleshooting skills. They should be inquisitive and follow an analytical approach to solving problems.
- Culture of trust. Because SREs and developers share ownership of services and what customers experience, they need to have a good relationship. At Google, we've learned that the top three characteristics of a healthy culture between SREs and developers are communication, agreement, and trust. It's important to extend this culture to other teams as well, such as security and privacy teams.
- Incident management. Incident management has two sides; technical troubleshooting and communication framework. For timely resolution for incidents, SREs will need to both technically resolve problems and interact with many other people. They should be adept and explicit and clear communication, time and task management, and record keeping, to name a few skills.

As you build out your SRE team, you should remember that these individuals will be in a difficult and ambiguous position between feature velocity and reliability goals. Important character traits to look for are resilience and flexibility, because SREs will need to provide the right balance between enabling product development and doing what's right for your customers.

If you start with these skills and begin adopting the practices at SLOs, error budgets, and post-mortems, you'll be well-prepared to start implementing your first SRE team. In the next video, we'll give you an overview of several different types of SRE teams that you can consider for your organization.

<br>

### SRE Teams

Once you've established some key practices and have begun training and hiring for the SRE role in your organization, you can start thinking about how to implement your SRE team. This implementation can, and will look different depending on the size of your organization, and where you are on your SRE journey.

In this video, we'll give you an overview of the different types of implementations, and the benefits, and disadvantages of each.

We've categorized the recommended implementations into six different categories.
- Kitchen sink or everything SRE
- infrastructure
- tools
- product/application
- embedded
- consulting

The first is kitchen sink or everything SRE. Scope is usually unbounded with this type of team. If you've never created an SRE team, this is a good place to start. We recommend this approach for organizations that have few applications and user journeys. Where the scope is small enough that only one team is necessary, but a dedicated SRE team is needed in order to implement its practices.

There are several benefits to kitchen sink implementation. There are no coverage gaps between SRE teams given that only one team is in place.

It's easy to spot patterns and draw similarities between services and projects. SREs tend to act as glue between disparate developer teams, creating solutions at a distinct pieces of software. There are also several disadvantages. There's usually a lack of an SRE team charter, or the charter states that everything in the company can be in scope, running the risk of overloading the team.

As the company and system complexity grows, the team tends to move from having a deep positive impact on everything, to making more shallow contributions. And issues involving a team may negatively impact your entire business.

The second implementation, is infrastructure. This type of team focuses on behind the scenes tasks, that help make other team's jobs easier and faster. They work on maintaining shared services and components related to infrastructure, versus an SRE team dedicated to working on services related to products, like customer facing code. We recommend this implementation for a company with several development teams since they probably need to staff an infrastructure team to define common standards and practices.

It is common for large companies to have both an infrastructure DevOps team and SRE team, where the DevOps team focuses on features, and SRE focuses on reliability.

A benefit of the infrastructure implementation is that it allows product developers to use DevOps practices to maintain user facing products, without divergence in practice across the business. Additionally, SREs can focus on providing a highly reliable infrastructure. They will often define production standards as code, and work to smooth out any sharp edges to greatly simplify things for the product developers running their own services.

However, there are some disadvantages. Depending on the scope of infrastructure, issues involving such a team may negatively impact your entire business. Similar to an everything SRE team implementation.

Lack of direct contact with your company's customers can lead to a focus on infrastructure improvements, that are not necessarily tied to the customer experience.

As the company and system complexity grows, you may be required to split infrastructure teams, which can lead to duplication of base infrastructure, or divergence of practices between teams. Which is inefficient and limits knowledge sharing and mobility.

Third is a tools-focused SRE team. This type of SRE team tends to focus on building software to help their developer counterparts measure, maintain, and improve system reliability or other aspects of SRE work, such as capacity planning.

A tooling SRE team risks solving the wrong problems for the business. So it needs to stay aware of the practical problems frontline reliability teams are addressing. This kind of team is recommended for any organization that needs a highly specialized reliability-related tooling.

The benefits and disadvantages of infrastructure in tools SRE teams tend to be similar. Additional disadvantages for tools teams include, ensuring that the team doesn't unintentionally turn into an infrastructure team and vice versa.

Running the risk of an increase of toil and overall workload. This is usually contained by establishing a team charter that business leaders approve.

The next implementation is product/application. This kind of SRE team works to improve the reliability of a critical application or business area. We recommend this implementation for organizations that already have a kitchen sink, infrastructure, or tools-focused SRE team, and have a key user facing application with high reliability needs. Having each of these aspects, justifies the relatively large expense of a dedicated set of SREs.

The benefit of this approach, is that it provides a clear focus for the team's effort, and creates a clear link between business priorities and where the team spends effort.

The disadvantage is that as the company and system complexity grow, the organization will require new product application teams. As with an infrastructure team, the focus of each team can lead to duplication of base infrastructure or divergence of practices which is inefficient and limits knowledge sharing and mobility.

The fifth type of SRE team implementation is an embedded team. This team has SREs embedded with their developer counterparts, usually one developer team in scope. And embedded SRP usually shares an office with a developer, but the embedded arrangement can be remote. The work relationship between the embedded SREs and developers tends to be project or time-bounded. During embedded engagements, the SREs are usually very hands-on, performing work like changing code, and configuration of the services and scope.

We recommend this implementation to either start an SRE function, or scale another implementation. This model is useful when you've had a project or team that needs SRE for a period of time.

This type of team can also augment the impact of the tools or infrastructure team by driving adoption.

A benefit of an embedded SRE team is that focused SRE expertise can be directed to specific problems or teams. It also allows side-by-side demonstration of SRE practices, which can be a very effective teaching method.

Disadvantages are that it may result in a lack of standardization between teams, or divergence in practice. And SREs may not have the chance to spend time with peers to mentor them.

Our last recommended SRE implementation is consulting. This implementation is very similar to embedded implementation. The difference is that consulting SREs are less hands-on. These SRE's tend to avoid changing customer code and configuration of the services and scope. However, they may write code and configuration to build and maintain tools for themselves or their developer counterparts. Which is a hybrid of the consulting and tools-focused SRE role.

We recommend waiting to staff a dedicated SRE team of consultants, until your organization, or complexity is considered to be large. And when demands have outgrown what can be supported by existing SRE team implementations. We also recommend staffing one or two part-time consultants before you staff your first SRE team.

The benefit of a consulting SRE team is that it can help with additional scaling of an existing SRE team's positive impact, by being decoupled from directly changing code and configuration.

The disadvantage is that consultants may lack sufficient context to offer useful advice. Additionally, a common risk for consulting SRE teams is being perceived as hands-off. Given that they typically don't change code and configuration, even though they are capable of having indirect technical impact.

Do one or any of these SRE team implementations resonate or appeal to you for your organization?

Remember that it's important to assess your organization's maturity for SRE adoption, and identify areas for training before creating your first SRE team.

In the next and final video, you'll learn how Google can help your organization get started with SRE.

<br>

### Getting Started

So you see the value of implementing SRE practices in teams in your organization, what now? Google Cloud is here to support you. We want to make sure we provide valuable experience to our customers.

Google Cloud's Professional Services team specializes in supporting organizations like yours in jump starting its SRE journey. To request Google Cloud's Professional Services consultation, be sure to reach out to your account director or account executive to start the conversation.

Thank you so much for coming along this SRE journey with us.

We hope you've gained valuable insights into Google SRE culture, and how it can benefit your IT operations and your business.

To make sure you fully grasped the SRE concepts we've covered, and to get credit for this course, complete the final assessment in the last module.

Finally, please be sure to review the resources section at the end of this course for additional materials on Google SRE. You can also find these resources in your learner workbook. Good luck on your SRE journey, we hope to hear from you soon.

<br>

#### Module 6 Exercise - Reading

1. Key Points

- Kitchen Sink/”Everything SRE” team: We recommend this approach for organizations that have few applications and user journeys and where the scope is small enough that only one team is necessary, but a dedicated SRE team is needed in order to implement its practices.
- Infrastructure team: This type of team focuses on maintaining shared services and components related to infrastructure, versus an SRE team dedicated to working on services related to products, like customer-facing code.
- Tools team: This type of SRE team tends to focus on building software to help their developer counterparts measure, maintain, and improve system reliability or other aspects of SRE work, such as capacity planning.
- Product/Application team: This type of SRE team works to improve the reliability of a critical application or business area. We recommend this implementation for organizations that already have a Kitchen Sink, Infrastructure, or Tools-focused SRE team and have a key user-facing application with high reliability needs
- Embedded team: This team has SREs embedded with their developer counterparts, usually one per developer team in scope. The work relationship between the embedded SREs and developers tends to be project- or time-bounded and usually very hands-on, where they perform work like changing code and configuration of the services in scope.
- Consulting team: This implementation is very similar to the embedded implementation, except SRE are usually less hands-on. We recommend staffing one or two part-time consultants before you staff your first SRE team.

- Organizations with high SRE maturity have well-documented and user-centric SLOs, error budgets, blameless postmortem culture, and a low tolerance for toil.
- Engineers with operations experience and systems administrators with scripting experience are good first SREs to hire.
- Upskill current team members with necessary SRE skills such as operations and software engineering, monitoring systems, production automation, system architecture, troubleshooting, culture of trust, and incident management.
- Contact your Account Executive or Account Director to learn how the Google Cloud Professional Services team can support your organization’s adoption of SRE.

2. Reflection Activity

1. What do you think is your organization’s maturity level for adopting SRE? Where does it fit into the SRE journey? Write down your ideas.
2. Think about your IT team composition. Are there already employees with the skillset for SRE? How might you quickly upskill and train these employees to move into the SRE role?


<br>

## [SRE Learner Workbook](../../assets/SRE_learner-workbook.pdf)

## Resources

[Site Reliability Engineering](https://landing.google.com/sre/sre-book/toc/)
Members of the SRE team explain how their engagement with the entire software lifecycle has enabled Google to build, deploy, monitor, and maintain some of the largest software systems in the world.

[The Site Reliability Workbook](https://landing.google.com/sre/workbook/toc/)
The Site Reliability Workbook is the hands-on companion to the bestselling Site Reliability Engineering book and uses concrete examples to show how to put SRE principles and practices to work. This book contains practical examples from Google’s experiences and case studies from Google’s Cloud Platform customers. Evernote, The Home Depot, The New York Times, and other companies outline hard-won experiences of what worked for them and what didn’t.

[Google Cloud Consulting Services](https://cloud.google.com/consulting/?utm_source=google&utm_medium=cpc&utm_campaign=emea-gb-all-en-dr-bkws-all-solutions-trial-e-gcp-1008073&utm_content=text-ad-none-any-DEV_c-CRE_340468586137-ADGP_Hybrid+%7C+AW+SEM+%7C+BKWS+~+EXA_1:1_EMEA_EN_VM+migration_gcp+professional+services-KWID_43700042357065337-kwd-380758056939-userloc_1006886&utm_term=KW_gcp%20professional%20servicesg&ds_rl=1242853&ds_rl=1245734&ds_rl=1245734&gclid=Cj0KCQjw9ZzzBRCKARIsANwXaeIPLV6niFcKgzkeOSZH5z6fj95vu61t48KjkwKY_Q1gXJY7_mUVCXcaAvN9EALw_wcB)
When you choose a Google Cloud consultant, you’ll be working hand in hand with experts who will educate your team on best practices and guiding principles for a successful implementation. Our deep technical expertise and services help you unlock business value from the cloud across a range of solutions—including infrastructure, application modernization, data management and analytics, machine learning, and security.

[Site Reliability Engineering: Measuring and Managing Reliability](https://www.coursera.org/learn/site-reliability-engineering-slos/home/welcome)
This course teaches the theory of service level objectives (SLOs), a principled way of describing and measuring the desired reliability of a service. Upon completion, learners should be able to apply these principles to develop the first SLOs for services they are familiar with in their own organizations. Learners will also learn how to use service level indicators (SLIs) to quantify reliability and error budgets to drive business decisions around engineering for greater reliability. The learner will understand the components of a meaningful SLI and walk through the process of developing SLIs and SLOs for an example service.

[DORA DevOps Quick Check](https://www.devops-research.com/quickcheck.html)
Measure your team's software delivery performance and compare it to the rest of the industry by responding to five multiple-choice questions. The quick check takes less than a minute to complete, and we don't store your answers or personal information. Immediately compare your team's performance to others.

<br>
