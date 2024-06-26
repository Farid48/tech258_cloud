# Cloud Computing

## What is Cloud Computing?
Imagine you need electricity for your home. Instead of building your own power plant, maintaining it, and managing all the infrastructure, you simply connect to the electricity grid provided by a utility company. You pay for the electricity you use, and the utility company takes care of generating and distributing it to you.

![img.png](images%2Fimg.png)

Similarly, with cloud computing, you need computing resources like processing power and storage for your applications or data. Instead of building and maintaining your own data center with servers and networking equipment, you **connect** to a cloud service provided by companies like **Amazon Web Services (AWS)**, **Microsoft Azure**, or **Google Cloud Platform (GCP)**. You pay for the **resources** you use, and the cloud provider takes care of all the **infrastructure**, including **maintenance**, **security**, and **updates**.

Just like you can plug into the electricity grid and use as much or as little electricity as you need, you can connect to the cloud and access computing resources on-demand, scaling up or down as your needs change. This makes cloud computing convenient, flexible, and cost-effective, similar to using utility services in your everyday life.

* Cloud Providers manage the infrastructure
* Can tinker with every little bit on what you use
* Physical severs that you are renting and having access to
* Typically placed in locations where electricity is cheaper or is colder as these data centers are massive.


## How do we know if something is on the cloud? What is the difference between on-prem and the cloud?

If something is on the cloud, it means that infrastructure is managed and hosted by a third party in an of-site data center. Users will be able to access it from anywhere that has a valid internet connection (sometimes requiring a VPN), such as websites. However, On-prem typically means that the servers are located and hosted within the organisation. They are responsible for managing the server infrastructure to ensure that they are always running.

Cloud allows for scalability and flexibility as cloud providers offer a range of services for these businesses. However, On-prem solutions will have limited scalability as businesses would need to invest more into the infrastructure, ensuring the hardware can accommodate the growth.

## The Four development models

### Private Cloud :
A Cloud computing environment dedicated to a single organisation. All resources are isolated and are controlled by the single organisation. It is be your own-dedicated cloud.

### Public Cloud :
A type of computing where resources are offered by third-party provider, and are shared by organisations or individuals who want to use or buy these services. An example of this is the Google Cloud Platform, which provide a very scalable solution to organisations, as if they require more resources, they can pay a bit extra.

![img_1.png](images%2Fimg_1.png)

### Hybrid Cloud :
A hybrid cloud is a mixed computing environment where applications are run using a combination of computing, storage, and services in different environments. An example can be using AWS's services alongside with on-prem databases.

![img_4.png](images%2Fimg_4.png)

### Multi Cloud :
When an organisation uses cloud computing services from at least two cloud providers to run their applications.

## Types of Cloud Services

### Infrastructure as a Service (IaaS):

* Provides virtualised computing resources over the internet.
* Users manage and control the operating systems, applications, and development frameworks. **offering users more direct control over their services.**
* Offers scalability and flexibility in managing virtualised resources.
* Would not be responsible to upgrade the physical hardware, only the software side (in a VM)
* Example Providers: AWS EC2, Microsoft Azure VMs, Google Compute Engine.


### Platform as a Service (PaaS):

* Offers a complete development and deployment environment in the cloud. 
* Abstracts away the underlying infrastructure, focusing on building and deploying applications. **Making it easier to use and more flexibility.**
* Provides pre-built development frameworks, middleware, and tools.
* Dev focused service, write the code, and should not set up the environment
* Example Providers: Heroku, Microsoft Azure App Service, Google App Engine.


### Software as a Service (SaaS):

* Delivers software applications over the internet as a service.
* Users access and use applications via a web browser or API.
* Eliminates the need for local installation and management of software.
* Example Providers: Salesforce (CRM), Google Workspace, Microsoft Office 365.


In summary, IaaS provides virtualised resources for users to manage and control, PaaS offers a complete development and deployment environment with abstracted infrastructure, and SaaS delivers ready-to-use software applications accessible over the internet. Each type of cloud service caters to different user needs and levels of abstraction.

## Advantages of Cloud Computing for Businesses:

* Cost Savings:
  * No upfront capital investment in hardware or infrastructure.
  * Pay-as-you-go pricing model allows businesses to only pay for the resources they use.
* Scalability and elasticity:
  * Easily scale resources up or down based on demand.
  * Accommodate growth without the need for extensive hardware procurement and setup.
* Flexibility and Accessibility:
  * Access computing resources from anywhere with an internet connection.
  * Support remote work and collaboration among distributed teams.
* Reliability and Redundancy:
  * Cloud providers offer high availability and redundancy across data centers.
  * Minimal risk of downtime due to hardware failures or maintenance.
* Security and Compliance:
  * Cloud providers invest in advanced security measures and compliance certifications.
  * Access controls, encryption, and regular audits enhance data security and compliance.

## Disadvantages of Cloud Computing for Businesses:

* Data Security and Privacy Concerns:
  * Businesses may have concerns about data security and privacy in a shared environment.
  * Data breaches or compliance violations can have serious consequences.
* Dependence on Internet Connectivity:
  * Reliance on internet connectivity for accessing cloud services and resources.
  * Downtime or disruptions in internet connectivity can impact business operations.

## Difference between OpEX and CapEX

### Operating Expenses (OpEx):

* Ongoing costs for day-to-day business operations.
* Examples: Rent, utilities, salaries, and cloud services.
* Recorded on income statement, paid immediately, and flexible.
* Allows you to be more agile.

### Capital Expenses (CapEx):
* Investments in long-term assets with future benefits.
* Typically one time purchases
* Examples: Buildings, equipment, and infrastructure.
* Recorded on balance sheet, require upfront expenditure, and depreciate over time.
* Can be viable if there are promotions
* 
![img_5.png](images%2Fimg_5.png)

### How do they relate to Cloud Computing?

* For the most part, OPex is better as in the long run, cloud can be cheaper as you do not need to maintain the electricity/ infrastructure.
* Businesses pay for cloud services as operational expenses.
* Reduces upfront investment in hardware and infrastructure.
* Enables flexibility, scalability, and focus on innovation.


## Is migrating to the cloud always cheaper?

There are a lot of advantages when migrating to the cloud related to costs. These include:
* Reduced Capital Expenditure - Eliminates the need for upfront investment
* Pay as you go model - Pay for only the resources you use
* Scalability and Flexibility - Allows businesses to scale up or down based on demand
* Reduces maintenance or management costs - Third party companies such as the cloud provider will handle maintaining the infrastructure

However, it is not always cheaper for the business to migrate. These costs can include:
* Usage Patterns and hard to predict - There can be unexpected spikes in usage, leading to higher bills
* Data transfer and storage costs - Transitioning between cloud providers can be complex and very costly, offsetting the initial cost savings
* Compliance and Security requirements - May require additional investments to meet security requirement

## What Are the 3 Largest Cloud Providers? What makes them so popular?
Currently, the biggest 3 cloud providers are Amazon Web Services (AWS), Google Cloud Platform (GCP) and Microsoft Azure. Together they take up 66% of the worldwide cloud infrastructure market. Each of these services have features that stand out and are appealing to different businesses.

![img_2.png](images%2Fimg_2.png)

### AWS:
* Extensive range of **services and global infrastructure.** (EC2, S3, RDS)
* Strong **ecosystem** and marketplace for **third-party integrations**.
* Widely adopted by enterprises and startups alike.

### GCP:
* **Advanced data analytics** and **machine learning capabilities** with BigQuery and **TensorFlow**.
* Emphasis on **open-source** technologies and **developer-friendly tools**.
* Global network infrastructure optimised for performance and scalability.

### MS Azure:
* Strong and heavy Integration with **Microsoft products and services**, such as Windows Server and Office 365.
* Strong **hybrid cloud capabilities**, including Azure Stack and Azure Arc.
* Comprehensive **compliance** and **security** offerings.

## Best Cloud Provider? Why?

From market share alone, you can see that AWS has a lot more usage compared to the other cloud providers. This is because:
* AWS offers a **variety** of services, ranging from infrastructure, to storage and database technologies. 
* It had a big head start out of the big 3, being more mature and showing **reliability**. It also means that it had a head start in d**eveloping infrastructure and service offerings**. It also means that there were more **experienced users** compared to other cloud platforms.
* AWS excels at **scalability**, able to fluctuate according to demands.
* AWS also has a strong reputation for **security**, and it also offers a variety of services to help with security
* **Pay As You Go Pricing**  - Charging Customers based on their actual usage!

![img_3.png](images%2Fimg_3.png)