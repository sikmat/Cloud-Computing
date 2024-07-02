# Module One
# Part 1: Understanding Cloud Concepts

## What is the Cloud?

In computing, "the cloud" refers to a network of servers that are hosted on the internet rather than on a local server or personal computer. These servers are typically owned and operated by a third-party cloud service provider, such as Amazon Web Services (AWS), Microsoft Azure, or Google Cloud Platform.

### Key Characteristics of Cloud Computing:

1. **On-Demand Service:** Users can access computing resources (such as storage, processing power, and applications) on-demand and pay only for what they use, typically on a subscription or pay-as-you-go basis.

2. **Scalability/Elasicity:** Cloud computing allows users to scale resources up or down easily based on their needs. This flexibility enables businesses to handle varying workloads without investing in additional hardware.

3. **Resource Pooling:** Cloud providers pool computing resources to serve multiple customers simultaneously. This efficiency allows for cost savings and optimal resource utilization.

4. **Broad Network Access:** Cloud services are accessible over the internet from anywhere, using a variety of devices (e.g., laptops, smartphones, tablets), enabling remote access and collaboration.

5. **Measured Service:** Cloud computing resources are monitored, controlled, and reported transparently. Users can track their usage, performance, and costs, providing transparency and accountability.

### Types of Cloud Services:

Cloud computing offers various types of services, categorized into three main models:

1. **Infrastructure as a Service (IaaS):** Provides virtualized computing resources over the internet, such as virtual machines, storage, and networking. Users have control over operating systems, applications, and development frameworks.

2. **Platform as a Service (PaaS):** Offers a platform allowing customers to develop, run, and manage applications without dealing with the underlying infrastructure. PaaS providers manage the infrastructure, including hardware and operating systems.

3. **Software as a Service (SaaS):** Delivers software applications over the internet on a subscription basis. SaaS applications run on cloud infrastructure and are accessible through a web browser, eliminating the need for users to install and maintain software locally.

### Benefits of Cloud Computing:

- **Cost Efficiency:** Eliminates upfront investment in hardware and reduces IT maintenance costs.
- **Scalability:** Easily scale resources up or down to accommodate changing business needs.
- **Flexibility and Accessibility:** Enables remote access to applications and data from anywhere with an internet connection.
- **Reliability and Disaster Recovery:** Cloud providers offer redundant systems and backups to ensure data availability and minimize downtime.
- **Security:** Cloud providers implement robust security measures to protect data and comply with industry regulations.

In essence, cloud computing revolutionizes the way organizations and individuals access, store, process, and manage data and applications, offering flexibility, efficiency, and innovation in computing services.

## Cloud Computing Ecosystems

- **Consumers of Services**: Typical day-to-day users, with little understanding of how the cloud service is build or designed. Their focus is just using it to complete tasks. ie., OneDrive, Google Drive, iCloud etc.

- **Providers of Services**: Providing cloud services, infrastructure, applications and tools. ie., AWS, Azure, Google Cloud, IBM Cloud, Oracle, Alibaba.

- **Designer of Services**: Builders of the tools, designed for a specific cloud system or can augment a packaged cloud application. ie., Accenture, Deloitte, Capgemini, IBM, PricewaterhouseCooper(PwC), Cognizant, Wipro, Tata Consultancy Services(TCS), Infosysy, DXC Technology.

### Cloud Concepts

_Cloud computing is_ is a method of providing shared computing resources, including applications, computing, storage, networking, development, and deployment platforms as well as business processes. Cloud computing makes computing resources easier to use by providing standardization and automation.

_Standardization_ is the implementation of services using a consistent approach supported by a set of consistent interfaces. Likewise, the cloud generally requires that processes be implemented through the use of automation.

_Automation_ is a process that’s triggered based on business rules, resource availability, and security demands. Automation is required to support a self-service provisioning model. To promote efficiency, automation can ensure that after a provisioned service is no longer needed, it is returned to the resource pool. This type of rules-based automation can help with capacity planning and overall workload management.

## Cloud Deployment Models

### Cloud Components and Clients
1. Client device/platform, where the services are being accessed.
2. Data center, where services are hosted.
3. The Network connection the first two components.

### Types of Cloud Computing/Deployment Models
There are two deployement models to managing cloud service infrastructure, and a third being a combination of the two:

**Public cloud**:  A CSP owns the cloud deployment and allocates its resources to external, unaffiliated customers. Those customers share the public cloud’s resources without knowing precisely where their data is in relation to that of any other organization. The _public cloud_ is a set of hardware, networking, storage, storage, services, applications, and interfaces owned and operated by a third party for use by other companies.

**Private cloud**:  Services are provided to only a single organization. similar to public cloud, but tools are owned and operated by an organization for the use of its employees, partners, or customers. It can be created and managed by a third party for the exclusive use of one enterprise. It is a highly controlled environment, sitting behind a firewall. Meaning it's not open for public use. It is highly automated with a focus on governance, security, and compliance.

**Hybrid cloud**:  There is a combination of two or more private, public, or community deployments. A hybrid I is a combination of a private cloud combined with the use of public cloud services where the two cloud environments work together to solve business problems. The goal is to create a hybrid cloud environment that can combine services and data from a variety of cloud models to create a unified, automated, and well-managed computing environment

**Deployment Models**
![image](https://github.com/sikmat/Cloud-Computing/assets/111583727/c3524f83-3634-442f-bb90-15bb871bf104)

**Multicloud**: is the use of a variety of public cloud services, to support different business units/functions. This then referred to a multicloud environment. It allows developers to access the platform of their choice with ease, and the business has that flexibility to move between vendors. Multi-cloud deployments reduce reliance on a single vendor, provide greater service flexibility and choice, permit improved geographic control of data, and help manage disaster mitigation.

Combining multiple public services with private clouds and the data center is the definition of _corporate computing_.

A cloud is hybrid or multi in the following situations:

- If a company uses a public development platform that sends data to a private cloud or a data center–based application, the cloud is hybrid.
- When a company leverages a number of SaaS applications and moves data between private or data center resources, the cloud is hybrid.
- When a business process is designed as a service so that it can connect with environments as though they were a single environment, the cloud is hybrid.
- When a SaaS analytics platform is used and data from multiple cloud sources are ingested.
- When your organization can move workloads to different public clouds based on cost or performance concerns.

**Virtual Private Cloud**(Cloud within a Cloud): means a public CSP hosts your organization's cloud services in an isolated segment, separated from any resources shared with other companies. Your cloud services exist in a public cloud but those resources are private and unshared.

VPCs are an example of _single-tenant deployment_. Here are some key differences between VPC and Private cloud deployment:
- VPC - is logical isolation of the cloud deplyment that resides on a CSP's infrastructure, and is therefore scalable.
- Private cloud - is physical isolation of the cloud deployment in a private data center, a community data center, or CSP's infrastructure. It is limited by the available hardware and therefore less scalable.

**Multitenancy**: is the the concept behind public cloud deployments. Multiple consumers, known as tenants, share computing resources owned and managed by the CSP. This is the opposite idea from VPC deployment, where it's a single tenant deployment. Multitenancy provides the cost benefits behind shared resource use. Although customers are sharing resources, their individual configurations and data are isolated.

### Cloud Computing Elements
These are the related elements that come together to create clouds. On the bottom is a set of resource pools that feed a set of cloud delivery services. On the top are the common service elements needed to support the delivery models. 

![image](https://github.com/sikmat/Cloud-Computing/assets/111583727/8eb2ee70-ea45-472f-89de-7fe23a9ba201)

## Cloud Delivery Models

### Infrastructure as a Service (IaaS)
The hardware infrastructure is provided to the consumer. The consumer assumes responsibility for all layers above that hardware, including an operating system, storage, networking, and various utility software elements, on a request basis. The CSP manages hardware failures, firmware updates, device drivers, and hardware compatibility. The consumer installs and manages the operating system on top of the hardware as well as any services and applications that run above that operating system.

In the _public IaaS_, the public cloud provider creates the infrastructure and resources that consumer can use. The user simply needs a credit card to acquire these resources. When that user stops paying, the resource may disappear. 

In a _private IaaS_ service, it is usually the IT organization or an integrator who creates an infrastructure and resources that internal users and sometimes business partners can use on demand.

IaaS examples:
- AWS EC2
- Azure
- Rackspace
- Digital Ocean

Target audience:
IT administrators

![image](https://github.com/sikmat/Cloud-Computing/assets/111583727/528e3f02-3d5c-4745-844a-95de5baa2e73)

### Platform as a Service (PaaS)
The service structure is provided by the CSP. It is up to the consumer to populate that structure, manage it on a day-to-day basis, and assume responsibility for the content. Support for the hardware, as well as the service platform that hosts the content, is offloaded to the CSP. The easiest way to think about PaaS is that it’s an IaaS, but the operating system and development tools are already in place. Because a PaaS environment is ready for development, productivity and time to value are greatly increased.

_A PaaS environment brings development and deployment together to create a more manageable way to build and deploy applications. A PaaS requires an Infrastructure service._

PaaS examples:
- Google App Engine
- Heroku
- AWS ElasticBeanstalk
- Salesforce
  
Target audience:
- Developers
- DBAs

![image](https://github.com/sikmat/Cloud-Computing/assets/111583727/f68c4fe0-c710-48ca-a06e-8ce80483b6d9)

### Software as a Service (SaaS)
The consumer is being provided with the direct use of the software. Responsibility for the hardware where that software runs, the operating system upon which it runs, and the installation and patching of the software itself are all offloaded to the CSP. Software as a Service (SaaS) is a business application created and hosted by a provider in a multi-tenant model. 

_The SaaS application sits on top of both a Platform as a Service and foundational Infrastructure services._

SaaS examples:
- Microsoft Office 365
- Google Apps
- WebEx
- Dropbox
- Netflix

Target audience:
- End users

![image](https://github.com/sikmat/Cloud-Computing/assets/111583727/938dd800-b758-478b-80da-441d3490fab7)














