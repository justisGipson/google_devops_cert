# Course Intro

Welcome to Introduction to Google Cloud Monitoring Tools.

In this module, we'll take some time to do a high-level overview of the various products that constitute Google Cloud's logging, monitoring and observability suite.

The core operations tools in Google Cloud breakdown into two major categories.

The operation's focus components including logging, monitoring, error reporting and service monitoring, tend to be more for personnel who are primarily interested in infrastructure and keeping that infrastructure up, running and error-free.

The application performance management tools including debugger, trace and profiler in contrast, tend to be more for developers who are trying to perfect or troubleshoot applications that are running in one of the Google Cloud compute products.

But it isn't fair to think of these tools as belonging purely to either one of these two groups. A developer would, of course, sometimes need access to logs or monitoring metrics, just like an operations team member might need to trace latency.

For reference the homepage for documentation related to this course can be found at https://cloud.google.com/stackdriver/docs

<br>

## Overview of Monitoring Tools

Let's start with an overview of why we need these tools and then we'll spend a little time getting to know both operations and the application performance management products.

If you've ever worked with on premise environments, you know that you are someone in your organization, can actually physically touch any of your servers. If an application becomes unresponsive, someone can walk in and physically investigate in the cloud though the servers aren't yours there Google's and you won't be able to inspect them physically. So the question becomes, how do you know what's happening with your server or database or application? The answer is the tools discussed in this course, it all starts with the signals metrics, logging and trace data capturing is integrated into Google products from the hardware layer up from those products. The signal data flows into Google Cloud's operations tools where you can visualize it in dashboards and through the metrics explorer. You can dissect and analyze automated and custom logs in the log viewer monitor services for compliance with service level objectives, SLS and track error budgets. Use health checks to check up time and latency for external facing sites and services. You can also debug in profile running applications when indicators pick up possible problems. Signal data can generate notifications to code or through various information channels to keep personnel. Error reporting can help operations and developer teams spot count and analyze crashes in cloud based services.

The visualization and analysis tools can then help troubleshoot what's exactly happening in Google cloud.

Ultimately you won't miss that easy server access because Google is going to allow you more precise insights into your cloud installed than you ever had on premise.

Google cloud has many products from kubernetes to big query to spanner and they all stream metrics and logs into Google cloud's logging and cloud monitoring components. The logs rather determines where the data goes and can be used to exclude some type of entries. Or to route logs to external locations like pub sub or big query perhaps for automated handling and for long term storage and analysis. An auditor might inspect the log viewer to see when a given spanner instance was created and by whom. Security personnel could use threat detection or the security command center to spot and analyze intrusion attempts. A network engineer might run SQL queries and big query to better understand network flow.

In addition to raw monitoring metrics and logging entries, Google cloud also helps ESOPS SRE and DevOps personnel analyze and improve application performance. Take as an example in http based java service running inside of a compute engine. VM Debunker would allow the inspection of the services code state without stopping or degrading its performance. It helps answer the question what was happening in the code when this particular line executed similarly. Profiler can also be used to examine CPU and memory, used to help spot bottlenecks and improve algorithmic performance traces all about analyzing latency in a multi layer micro service application and the logs. API can be used by developers to write directly to Google cloud logs.

<br>


### Operations-Based Tools


<br>

### Application Performance Management Tools


<br>

### Review: Product Knowledge


<br>

## Overview: Why Monitor?


<br>

### Why Monitor?


<br>

### Critical Measures


<br>
