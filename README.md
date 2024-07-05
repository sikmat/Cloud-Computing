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

## The Computing Resources Life Cycle

CSPs cannot predict when users will place their requests, how many resources they will require, the magnitude of those resources, and the duration they will retain those resources, the design must ensure a surplus of resources is constantly accessible for use. 

The CSP must monitor all resource usage so that users can be accurately charged based on a pay-as-you-go model. When users are done using the resources, the cloud platform must reintegrate those resources into the pool of available resources for other users to utilize.

There are instances where a service provider may not be able to foresee a customer's requirements. In such cases, it is typical for a service provider to enhance capacity by resorting to a third-party service provider.

### Understanding Self-Service Provisioning and Elasticity

With _self-service_, cloud consumers can use a website in the cloud to select and purchase cloud services, configure them, launch them into the cloud environment, and start using them within minutes or perhaps even seconds.

Elasticity, means cloud resources can automatically change their own provisioned size. The basic meaning of elasticity is that many cloud resources can be selected at a specific size or quantity, but when the usage of those resources starts to approach the original size, they automatically increase their own size.

### Establishing a Dynamic Life Cycle across Workloads and Data

A cloud is a combination of resources that may be spread across systems and geographies. A workload is an independent service or collection of code that can be executed. So, you need to think about the cloud as a group of workloads that are managed as though they were a single cohesive environment. Within a well-designed cloud or multicloud environment, workloads and data can move across multiple cloud providers, geographic regions, or service levels. Because, in the real world, you will use a combination of services, it’s important to think not just about an individual workload but also about a combination of workloads and how they interact with each other and with collaborators.

Other issues to consider include locating workloads and data in the same region as your primary customers to optimize performance, understanding the life cycle of your application and data to select optimizations based on increasing — or decreasing — demand, and even moving workloads to alternate cloud providers when the differential of costs, reliability, or features make it advantageous.

### Management Services

Management services are mandatory for ensuring that the operation of your cloud workloads and resources meets constituent needs (whether they are customer, employee, or partner) needs. This is the case regardless of the cloud deployment and delivery model

- Network monitoring and management is critical because outages and slowdowns can have a dramatic impact on the customer experience of cloud applications.
- Application and workload health monitoring can provide warnings of impending problems and can inform a support organization so they can provide the best service to customers.
- Security and governance are key services that ensure your applications and data are protected.
- Data management in a hybrid environment is also critical since data will be moving between cloud and physical environments.

## The Changing Role of the Data Center

When companies implement hybrid clouds, their data centers don't disappear. Most medium and large companies still need their own data centers for essential systems like accounting and inventory. Many data centers have developed over decades and house a mix of hardware, operating systems, and applications, which can be expensive to maintain.

To improve efficiency, companies use technologies like server virtualization, which separates software from hardware by using virtual machines. This makes managing applications on servers easier.

Despite these improvements, cloud computing shows that more can be done. Companies are now evaluating how to best use their traditional data centers along with private, public, hybrid, and multicloud environments to manage workloads and data effectively.

_There are still good reasons to run certain workloads on premises — for example, legacy applications that are not prepared to take advantage of the scalability and elasticity of the cloud, or applications that have dependencies on external services or hardware that are not available in the cloud. In many cases, there may simply not be a reasonable business case to move an application to the cloud._

### Evolution of the Data Centre into a Private Cloud

IT organizations have discovered that it’s much more efficient and effective to create private cloud services for developers to create new applications and services. Therefore, companies are setting up a highly automated computing environment enabled with a self-service portal. This portal is often designed with business process rules that dictate what services a developer or an authorized partner can use. 

### Seeing how the Public Cloud Fits

Mr. Price, a retailer, uses a public cloud for its annual sale, expanding this year to Zimbabwe and Mauritius. The global cloud provider simplifies application setup and takedown in these regions, saving on server costs. Mr. Price also adopts cloud-based CRM and human resources platforms, forming a hybrid cloud with their on-premises data center. This integration enhances sales performance and avoids extra hardware and IT expenses. The public cloud enables quick service launches, providing a competitive edge, while the hybrid setup allows for efficient data management and analytics, creating new revenue opportunities.

### Knowing When the Private Cloud Shines

In some cases, a private cloud is preferable to a public cloud, especially for sensitive applications and data. Imagine you are an IT manager at a financial services company that offers products to global business partners via an online portal. While it makes sense to use a public cloud for the portal due to its wide reach, legal requirements mandate that sensitive financial data be stored in a physical data center. A private cloud, integrated with the public cloud to form a hybrid cloud, meets these needs by providing scalability and legal compliance.

Years ago, your company moved its data center to a virtualized environment to reduce costs and manage workloads better. However, this led to "virtual machine sprawl," making management difficult. The company aimed to transition to a public cloud but needed to control VM sprawl and update some applications to be cloud-ready. They created a private cloud as an intermediary step, using it to upgrade applications and manage VMs before moving to the public cloud. This approach minimized risks and improved management, ultimately leaving them with a modern private cloud and a hybrid cloud setup for efficient data and workload management.

# EMbracing the Business Imperative

## Understanding IT Transformation

Cloud computing is changing the role of IT from managing data centers to overseeing and managing a mix of cloud and on-premises services. IT needs to help businesses integrate data and processes across different systems and ensure security and compliance. This may require modernizing legacy applications to make them more flexible. Companies that invest in cloud technologies and application modernization will be more successful in transforming their IT infrastructure.

## Escaping the IT Legacy Trap

Legacy applications, though crucial for businesses, are often outdated and difficult to update due to their complex architecture. Simply moving them to the cloud isn't effective. It's expensive because all dependent applications need to be migrated as well. Additionally, these applications weren't built for the cloud's efficiency, so they'll require a lot of resources and offer no real benefit in their new environment.

_What is the solution? The applications have to be transformed and modernized, which means that dependencies are removed from the applications. The application is redesigned as a set of modular services. When possible, frequently used services are written once and reused. The bottom line is that it is imperative that these legacy applications are updated and modernized to gain the innovation benefits of the cloud._

## Preparing for the Cloud

You have to make sure that everyone is educated about what the cloud can and can’t do. Everyone should understand how the cloud would play a pivotal role in redefining the pace of business. It should be clear to everyone that adopting the cloud for the business is a team sport and requires that IT and business units collaborate. It also means that there needs to be a balance between total freedom to use whatever cloud or cloud services that seems useful and the need for management of computing. The more that everyone understands about responsibility and goals for the cloud, the more successful the company will be. Have a well-established set of guidelines that are agreed upon and well understood.

Moving to the cloud requires modernizing applications or finding cloud-based SaaS options. Here's how to approach it:

1. **Modernization with SaaS:** Evaluate if existing applications can be modernized for the cloud or if cloud-based SaaS applications are a better fit for current business needs.
2. **SaaS Implementation:** If SaaS is chosen, consider how it will be used, any needed process changes, and department adoption. Negotiate a favorable licensing agreement with the vendor.
3. **DevOps adoption:** Cloud environments benefit from DevOps practices, which combine development and operations for faster software delivery. This might be a new approach for some businesses but is still essential.

## Building Innovation

The cloud simplifies connections between employees, business partners, and customers. Innovative companies must break down strict boundaries between business units, subsidiaries, partners, suppliers, and customers. Strengthening these relationships through improved communication, feedback, and transparency is crucial for success and benefits all parties involved.

As IT transforms itself to help guide the cloud strategy, the organization can become an agent of change. With the use of well-defined cloud services supported by standard Application Programming Interfaces (APIs), it is possible to more quickly establish new innovative applications and services to support partners and suppliers. With the use of either public or private cloud services, a business can pilot new services with selected partners and iterate based on feedback. The ability to build quickly, test, change, and execute is the best way to experiment with new business models without requiring a massive capital investment.

## The Business Imperatives

In the past, businesses could design long-lasting applications and computing platforms. However, the competitive landscape has shifted due to cloud services. Now, new companies can quickly leverage inexpensive cloud services to innovate and disrupt established markets without the burden of legacy systems. Modernizing IT and adopting a cloud strategy is essential to stay competitive. By collaborating across the business to streamline IT, modernize applications, and move key workloads to the cloud, companies can make informed decisions about which services should be cloud-based or on-premises. Establishing guidelines for security, governance, and vendor management will prepare businesses to innovate and maintain strong customer and partner relationships.

**Cycle of Innovation**

![image](https://github.com/sikmat/Cloud-Computing/assets/111583727/d9db3e44-4124-4d57-9bfd-75582f50761a)

## Embracing Your Existing Business
Before establishing a cloud strategy, consider how your business currently interacts with customers, who are likely already using cloud services. Customers expect businesses to use cloud services and be responsive to their needs for rapid change. If your applications and services can't transform quickly, customers will turn to more responsive providers. Therefore, the agility provided by the cloud is essential to meet customer expectations and stay competitive.

_An old furniture store has years of best practices experience that can be applied to the cloud model. With the cloud, the business can build out innovative services that leaders know are important to their customers and can experiment with new ideas that are managed in the cloud._

## Modern Development and Deployment Strategies

Established businesses can move to an innovative cloud strategy by adopting DevOps, a development approach that combines modern application development and deployment techniques. DevOps uses agile development, which focuses on iteratively building software based on customer needs and success metrics.  

Here's how DevOps helps build innovative cloud applications:

- **Customer-centric:** Development focuses on what users need and how they interact with the software.
- **Flexibility:** Applications are modular and adaptable to changing customer behavior and partnerships.
- **Performance:** Software is designed to perform well across different cloud platforms and on-premises environments.  

## Revisiting Your Business Model

You only have to analyze the success of companies like Uber, Airbnb, Netflix, and hundreds of other businesses that are challenging established businesses because of the cloud. In fact, the success of these types of companies is the fact that they have sophisticated cloud-based services where they can build and modify applications quickly and use data to understand customer expectations. The list of businesses with new business models is long and growing. The mindset in the software world is to find new ways to disrupt businesses — in other words, have a business model that is more compelling than what was previously used.

## Transforming the Business Model

Business models are comprised of a set of characteristics of your business that can be adjusted to change how your company does business and how your customers and partners interact with you.

Offering compelling offerings that solve customer problems encourages them to buy once they get a taste of success. Being able to leverage the cloud to both offer and manage customer interaction transforms your ability to move quickly to increase your business.

The cloud can help by making it easy to experiment with your business model via the agility and flexibility. Instead of changing your business completely overnight, you can set up a subsidiary division or even a stand-alone business, perhaps with a different name and brand. Treat it as a real business but limit the number of customers or services to keep it less complicated, and see whether you get the traction you need. If you do, you can grow the new business at your own rate.

# Part 2: Cloud Architecture Considerations

## Type of Constituents Your Cloud Serves

- **Cloud consumers**:  The individuals and groups within your business unit that use different types of cloud services to get a task accomplished. A cloud consumer could be a developer using computing services from a public cloud.
- **Direct customers**:  Users who often take advantage of services that your business has created within a cloud environment. End users of your service have no idea that you are using a public or private cloud. As far as the users are concerned, they are interacting directly with your services and value.
- **Cloud service provider**:  Commercial vendors or companies that create their own capabilities. Commercial vendors sell their services to cloud consumers. In contrast, a company might decide to become an internal cloud service provider to its own employees, partners, and customers — either as an internal service or as a profit center. These providers also create applications or services for these environments.

The approach to cloud architecture depends on whether your organization is a consumer or a provider of cloud services. As a consumer, focus on selecting the right services that meet your business needs and ensure they are integrated effectively. Avoid creating isolated silos by leveraging containerization and microservices, which abstract content from underlying platforms for easier management.

In contrast, cloud service providers, whether commercial vendors or internal private clouds, must meticulously architect their environments. They design applications and services optimized for the cloud, ensuring consistency and long-term support for customers. Providers must create environments that seamlessly integrate with partner ecosystems to maximize service delivery efficiency.

### Putting the Pieces Together

Components of a cloud model from an architectural perspective

![image](https://github.com/sikmat/Cloud-Computing/assets/111583727/5c5b09d1-f190-4cbe-a10f-c86072ae8019)

**Figure 12**: The NIST Cloud Reference Model provides a depiction of the various services needed to operate in the cloud.

On the left side of Figure 12, the cloud service consumer represents the types of uses of cloud services. 
In addition, this model depicts the role of the cloud auditor. This organization provides oversight either by an internal or an external group that makes sure that the consumer group meets its obligations.
Cloud service providers might be a commercial company or a corporation that decides to become their own cloud service operator. Cloud providers may provide the underlying physical and virtualized resources needed to run various cloud services. They also may create the actual applications and business services that operate in these environments.

_The cloud provider has to support all the important cloud models. In addition to supporting the physical and virtual environment, it is important to remember that all these cloud models and the supporting environment must be linked together in the form of service orchestration. Without service orchestration, each service would become an independent silo._

## Planning for Deployment

The hybrid cloud is not a single architectural model, but a combination of many different services that are on different platforms. In the hybrid cloud, you will never bring all services and elements together as though they were one system. Instead, you need to have a clear understanding of the distributed services and how they relate to each other. Many of the approaches require the creation of best-practices templates that can be used to create the right linkages between services. 

One of the best practices needed is to be able to keep track of what task a specific service executes, the rules for how it can be used, as well as definitions and dependencies. A well-designed hybrid cloud environment must be built to support change.

**Hybrid models have four primary architectural considerations:**

**1. Latency and Performance**

When planning a hybrid cloud, consider performance (latency) across your entire environment. Here's how to manage latency in a hybrid cloud:

- **Critical applications:** Keep transaction processing and applications requiring frequent data access on-premises or in a private cloud for faster response times.
- **SaaS applications:** Use SaaS for applications like customer management where occasional latency is acceptable.
- **Service location:** Consider data exchange needs between services when choosing their location in a public cloud.
- **Flexibility:** Design your cloud architecture to be adaptable for future performance needs. 
- **Composite services:** Combine public cloud services with private cloud or on-premises resources for complex applications, placing each part based on its performance needs. 

A service-based approach to cloud computing involves tightly coupling critical services for low latency. This means these services communicate directly for faster performance. 

Here's how to achieve this:

- **Microservices in containers:** Break down large applications into smaller, modular microservices and place them in containers.
- **Orchestration services:** Use orchestration services to manage the lifecycle and communication of these containers.
- **APIs with caching:** Implement well-defined APIs with caching mechanisms to ensure services can access data quickly, even if it's located outside the cloud environment.

By following these best practices, you can build a high-performing hybrid cloud architecture.

**2. Security: Planning in Context**

Before building your hybrid cloud, consider how sensitive your customer data is.  For public information like product specs, a basic cloud setup might be fine. But for private data like health records, you'll need a more secure cloud environment to meet customer expectations.  Basically, security needs to be planned from the start, not as an afterthought. 

**3. Governance: Getting the right balance**

Just like security, rules and regulations (governance) affect how you design your hybrid cloud. Here's what to consider:

- **Industry regulations:** Some industries have strict data handling practices. Choose cloud partners who meet these standards. 
- **Data privacy laws:** Some countries require data to be stored locally. Make sure your cloud provider can comply with these laws.
- **Process management:** You might need tools to track where data is stored based on regulations.
- **Cloud provider capabilities:**  Verify your cloud provider can meet your specific requirements, like data storage location.

Basically, plan your cloud environment with regulations in mind to avoid compliance issues. 

**Managing Colocation**

In managing a hybrid cloud environment, compromise is necessary to balance performance and cost. Start by selecting applications that align with the benefits and limitations of the cloud. Applications unsuitable for a public cloud should remain on-premises, either on traditional middleware or in a private cloud. Careful architectural planning ensures that applications and services are well-positioned to support a hybrid cloud environment effectively.

**4. Reliability in the Context of Change**

Companies often assume cloud computing is an all-or-nothing model, but it is part of an overall distributed architectural plan. It's important to consider business, performance, and customer goals, including latency and data management. Tightly coupled services with many dependencies may suffer in a public cloud, while well-defined, loosely coupled services perform well. Most organizations need a mix of data center, private cloud, and public cloud services. A holistic architectural approach ensures customer satisfaction and protection. Some vendors offer unified platforms with various deployment options, facilitating a flexible and adaptable architecture.

## Setting the Right Policies and Business Rules

Companies usually think about policies and business rules from a broad governance perspective. However,making policies and rules operational in a hybrid cloud environment means that these must be integrated from an architectural perspective.

In an on-premises setup, incorporating a policy into an application is straightforward. In a hybrid environment, you need to ensure these policies can be applied across components.

For example, if a policy requires that personal data about French customers is stored in a physical server in France, this policy must be designed as a middleware service that controls the movement of data based on rules and conditions. it is not practical to try to implement each rule and policy inside each component of the hybrid environment.

## Navigating the Choices in a Hybrid World

The advantage of a hybrid cloud is its flexibility, allowing you to choose the best service for each task. But how do you find the right balance of services? Consider your business needs and match them with an appropriate architectural approach.

You want platforms that meet the business's service level requirements. For tasks needing real-time performance and guaranteed uptime, choose a public service with high Quality of Service (QoS) or a fully private service your company controls.

For services like customer relationship management, where availability and manageability are crucial, a SaaS environment is ideal. From both an architectural and a business process perspective, you need to determine which services need to interact and which can operate independently.

Ultimately, aim to create an optimized environment that meets your customers' needs effectively.

## Optimizing for Workloads

Optimizing workloads across different environments is a key principle of hybrid cloud computing. Without starting with workload optimization and balancing, meeting customer needs will be challenging.

One approach to enable this is federation, which links different environments at the interface level. This requires common interfaces across public and private cloud services. Even if services are not fully federated, users must have an easy way to access data or business services across various environments and networks. 

However, achieving true portability and interoperability of workloads across hybrid clouds is still in its early stages.

## Supporting a Dynamic Life Cycle

The life cycle of cloud computing differs significantly from traditional computing environments due to its service-oriented architecture, which abstracts details away from users. Unlike traditional setups, cloud environments enforce discipline and are designed to support changes in users, applications, and workloads. This dynamic nature allows businesses to adapt quickly, such as supporting temporary projects with fluctuating developer numbers. Cloud computing speeds up application development and deployment, reduces misunderstandings between development and deployment teams, and simplifies adding capacity or users, especially after acquisitions. Additionally, security updates and changes are more straightforward in a cloud environment.

As you start thinking about supporting a dynamic life cycle to support a hybrid cloud environment, consider the following:

- Think about an overall services-based model that breaks down traditional disconnected silos of applications, processes, and services.
- Think about creating an environment with fewer dependencies so that when you add new cloud services, you will have the flexibility to advance as the industry advances.
- Think about the performance requirements that will give your customers excellent experiences.
- Think about creating a predictable, safe, and well-governed environment that will support business operations in the long run.

# Managing a Hybrid and Multicloud Environment
## Managing SaaS Applications

All SaaS applications are not equal. Some well-designed SaaS applications provide value to the business along with governance and audibility for administrators. On the other hand, other SaaS applications are designed for consumers and do not have the visibility that businesses require. Additionally, the application may not have well-defined interfaces so that it can easily connect to other corporate applications. Furthermore, applications that are not there may have vulnerabilities in the application that can put the business at risk.

But a better solution is for IT to proactively research and approve a full set of tools that the company will use and create a library of easily findable and usable tools in a convenient place. This solution allows employees to self-serve only approved items from the SaaS application library. IT should go further still, to encourage employees to engage with the team when they have a problem that is not met by the standard tools. Rather than push back or delay, IT would be more successful by offering a bonus for finding unmet needs and then providing a commitment to solve the problem quickly. (Service level agreements will be covered later in this chapter.)

Organizations typically do not manage external Software as a Service (SaaS) applications, as these are maintained by the companies that developed them. However, IT departments are still held accountable by users, who expect these applications to be operational at all times. Users are often dissatisfied when IT explains that the SaaS vendor is responsible for managing the application.

For example, if a popular SaaS application hosted in a public cloud like Amazon or Google experiences a prolonged outage, users will contact IT with their frustrations. IT will then contact the SaaS vendor, who may attribute the issue to the cloud provider. Despite this, users will demand a quick resolution.

In such situations, IT must act as an advocate for the users, collaborating with the SaaS vendor and cloud provider to address the issue swiftly. Even though IT doesn't control the external application, their role in communication, coordination, and driving resolution is crucial to minimize the impact on the users' experience.

**Optimizing SaaS Management**
As use of SaaS applications expands through an enterprise, IT and security teams should review use of SaaS applications. Security should examine actual use to understand whether any practices are risking loss of the business’s intellectual property (IP), opening up connections that hackers can exploit or where other insecure activities can occur.

**A SaaS Cautionary Tale**
A business modernized with a cloud-based office productivity suite, enabling employees to create and edit content from anywhere. This facilitated document sharing and reviews across different divisions. Employees quickly depended on the SaaS application’s features. However, an outage occurred, massively impacting the company since nearly all employees had transitioned to the new suite. Employees were furious with IT, who had chosen and deployed the application. IT was not responsible for meeting the SaaS application's SLAs; that was the vendor’s responsibility. Despite this, any downtime still affected the company. The outage could have been caused by various issues, such as a networking switch disrupting communication. IT had to wait for the vendor to fix the problem. This situation highlights that IT needs to ensure continuous access to essential tools by preparing for outages and having failover solutions ready. These solutions could come from another vendor, a better SLA from the original vendor, or a failover to a different region, albeit with greater latency.

Cloud Access Management (CAM) is a specialized form of identity management for cloud services. CAM allows users to be explicitly granted rights to specific SaaS applications and governs the information they can access. It formalizes which company personnel can access which SaaS applications and their rights within those applications. For example, HR employees may update all employees’ job performance ratings, while others can only see their own information.

IT departments are interested in tracking how many employees use each SaaS application and what they use it for. This usage data can help IT negotiate better terms with vendors, potentially leading to more favorable licensing agreements if multiple business units use the same application. Additionally, by observing usage patterns, IT may identify opportunities to purchase other tools to improve business operations or see the need to integrate one SaaS application with others.

## Managing External Cloud Resources

Understanding who is using cloud services is important because that is where management should be focused. Management of cloud services is typically practiced in IT and software development organizations.

### Visibility and Control of External Resources
You need to have the ability to apply controls so that you can gain visibility into the cloud applications and services.

The biggest management challenges of external cloud resources include identifying the most appropriate services, verifying their characteristics (performance, security, cost, etc.), and ensuring exclusive use of these services. Exclusive use is important because once a service is selected, significant investments in training, testing, and infrastructure are made to integrate it effectively. Using a different service with the same functionality can double these costs.

Since using resources and building applications are technical activities, their management should be driven by the development organization or IT. These teams have the necessary knowledge of the required functionality, service integration into the product framework, and the business's long-term technical goals.

**The general cycle for approving, using, and reusing cloud services involves the following steps:**

1. **Identify and define the functional requirements** of the software being developed.
2. **Research available cloud resources** from current providers and, if necessary, extend the search to other providers to ensure a good match or to support a multicloud approach.
3. **Perform tests in a pilot project** to verify that the identified resources meet the functional requirements.
4. **If testing is successful, establish a business relationship** with the service vendor and access the production version of the resource. If unsuccessful, return to step 2 or consider building the resource internally.
5. **Document the new service** and make it available to the full development organization.
6. **Regularly review existing resources**, their requirements, operational history, and issues.

If requirements or resources have changed, consider restarting the process at step 2 to evaluate new resources that may be a better fit.

### The Importance of Self-Service

Creating a catalog of approved computing resources is essential for consistent and predictable management. While cloud providers make their services easily accessible and attractive with low pay-as-you-go prices, companies should limit employee choices to these approved resources to maintain control and manageability.

_The challenge is to make it easier for employees to use the company’s catalogue to select what they want rather than go to the cloud themselves. To do so, the company must get ahead of the curve to understand the requirements and needs of development organizations._

## Service Level Agreements(SLAs)

Every cloud resource includes a service level agreement (SLA) that details the provider's deliverables and the customer's responsibilities. The SLA outlines key characteristics such as availability, accuracy, response time, throughput, and security. These traits are crucial for ensuring the selected resources meet the performance requirements of the services or applications that will use them.

Many grey areas exist with regards to what the vendor is responsible for when disruptions occur. SLAs also include performance claims, with cloud vendors often competing on uptime guarantees. For instance, a 99.99% uptime versus a 99.999% uptime can mean 47 more minutes of uptime annually, which can be either minor or critical depending on the workload, such as a test environment versus a retailer’s transactional system. Failure of a computing resource to meet SLAs can and should be grounds for canceling contracts.

### Addressing Poor Cloud and Computing Behaviors

Many corporate users bring their own devices to the workplace or use them when they are working remotely. The IT organization is responsible for making sure that the right software and the right best practices are in place to ensure safety and security. IT organizations can take steps to avoid these dangerous behaviors, starting with employee education about the dangers of poor security practices. Many companies implement governance strategies that explicitly control which systems employees can access and the data they are qualified to read or modify. Often, governance is based on the specific job the employee is performing with role-based access control (RBAC).

A new generation has grown up with social media and uses it to share information, answer questions, and generally extend the user’s community outside the company’s boundaries. Many social media users do understand the risks, but some do not and may not recognize the danger in sharing corporate information or business practices outside the company.

## Managing Internal Cloud Resources

As cloud usage becomes widespread for delivering services, managing these resources effectively is crucial for a business's success. When a business provides cloud services to its employees and partners, it typically uses private or hybrid clouds instead of public ones. In a hybrid cloud setup, the business might use public cloud services for internal purposes, making it both a consumer and a provider of cloud services.

Many challenges in using cloud services apply whether the business provides these services to its employees, customers, or partners. The main difference is that public cloud services cater to a wide variety of users, while private or hybrid clouds are customized to meet the specific needs of the business.

## Managing a Hybrid Cloud Environment

Businesses are using both public and private clouds together more often. This mix gives them flexibility, scalability, and good performance for their internal computer needs.

Today, public clouds offer strong security along with a wide range of services and resources. Companies that choose to use private or hybrid clouds might have stricter requirements than in the past. As cloud technology grows and becomes essential to business plans, organizations are likely to choose applications and resources that are well-reviewed and have strong security measures. In private or hybrid cloud setups, the approval process for these choices becomes very important.

### Understanding the Role of Internal SLAs

When a company operates as a private or hybrid cloud provider for its internal users, it should set clear SLAs for the resources and services it offers. This formalizes the operational standards that users can expect and increases satisfaction with internal services. SLAs establish measurable targets for performance and other operational aspects like mean time between failures. They help determine whether issues with applications stem from the application itself or from the resources and services it relies on.

In a public cloud environment, managing resources and services is handled by the cloud vendor or third-party software provider. These providers are responsible for monitoring operations to ensure SLAs are met. In contrast, in a private cloud setup, it's typically the IT operations team's responsibility to monitor software performance and adherence to SLAs.

Public cloud providers serve many customers, so they may not always respond immediately to SLA deviations. In contrast, a company managing its own private cloud has a singular customer (itself) and must ensure all applications and resources work effectively. Executives often monitor SLA compliance closely because performance issues can impact the company's profitability.

## Managing Internal Services

### Supporting Cloud Customers

Supporting internal users of private or hybrid cloud applications is essential for managing these environments effectively. Users expect prompt assistance when they encounter issues, whether with third-party applications supported externally or in-house applications developed by internal teams. Support teams aim to deliver high-quality, timely support and often focus on reducing support calls through improved software reliability and usability. Close collaboration between development and support teams is crucial for providing excellent support services.

### Monitoring Resources Imported from the Public Cloud

In a hybrid cloud setup, where public cloud resources complement private cloud services, verifying resource performance and SLA compliance involves several approaches:

1. **Testing in Public Cloud**: Setting up test software in the public cloud allows for independent performance sampling without impacting application performance. However, results may not directly reflect application-specific performance.

2. **Testing in Hybrid Cloud**: Conducting tests within the hybrid cloud offers more consistency with application experience but can affect overall infrastructure performance because that is where the testing is operating.

3. **Utilizing Operational Dashboards**: Checking if tested resources provide operational information or dashboards for performance insights.

4. **Application Instrumentation**: Logging actual resource performance within the hybrid environment minimally impacts application performance. This method is considered optimal for accurate monitoring and integration with broader application monitoring.

# Monitoring the Cloud Infrastructure

Public cloud vendors provide information about the operational status of major subsystems and services within their cloud environments. The same type of information should be maintained for private and hybrid clouds. Although this information is usually high level, ensuring that basic services are working properly should be the first thing that support people look to verify.


# Monitoring Applications and Services

Applications generate valuable insights through user actions and logs, benefiting support, development, and IT teams. Support uses user action data to assist users effectively, while developers analyze logs to troubleshoot crashes. User experience experts leverage this data to enhance interfaces and streamline user experiences, while product managers ensure features are used correctly and explore improvements. Logs also reveal operational patterns for application enhancement, and instrumenting applications with Key Performance Indicators (KPIs) helps assess goal achievement.

_Increasingly, artificial intelligence and machine learning are being applied to old operational data to discover the patterns associated with problems so that current performance can be quickly assessed for recurring problems or the symptoms of problems that can then be evaluated by other tools._

### Constructing Dashboards

Harnessing this information into a form that is useful requires at least two parts:
- Analysis software that processes and reduces the data to a manageable form.
- A visualization technique that makes the information easy for people to recognize.

Dashboards are versatile tools for presenting operational information tailored to different audiences. They can be customized to show specific views for support, displaying data to aid in user issue resolution. Developers benefit from performance metrics and user activity insights. Product managers rely on dashboards for KPIs and usability data, while executives use them for high-level status updates and customer acceptance metrics.

# Managing External Services

One characteristic of a hybrid cloud environment is that an organization will have a variety of services that need to be managed. To be successful, visibility and control over external and internal resources is critical.

### DevOps and Deployment to Public Clouds

Best practices in cloud software development now center around DevOps, which integrates Development with Operations. DevOps enables continuous development and deployment of software by eliminating handoffs between development and operations teams. This approach enhances software robustness as developers focus more on operational considerations.

After deploying an application to the cloud, DevOps engineers monitor it closely. They promptly address operational issues by either resolving them directly in the cloud environment or making necessary application changes and redeploying fixes as quickly as possible, following agile development and testing practices.

### External System Monitoring

When applications and services are used by customers in other companies, effective system monitoring becomes crucial for gathering usage data. Unlike within a single company, where internal feedback is readily available, external customers may have fewer opportunities to provide insights. Therefore, it's essential to proactively communicate product and operational status to external customers. This transparency is vital as external customers may have less awareness of issues and less loyalty to the software compared to internal customers.

### Application and Service Life Cycles

In the public cloud, applications and services must maintain high levels of reliability and availability:

1. **Continuous Deployment in DevOps**: While DevOps aims for continuous development and deployment of new features, applications in the cloud must be upgraded without disrupting customer use. Downtime during upgrades is not acceptable. You cannot take an application down while upgrading.

2. **Failover Capabilities**: Designing applications with failover capabilities is crucial. This ensures that if there is a server or application failure, it causes minimal disruption—a brief pause is preferred over complete unavailability or potential data loss, especially given the potentially large number of users in the cloud environment.

# The Future of Multicloud Management

As businesses embrace hybrid cloud environments, managing a diverse array of services and deployment models becomes critical for operational success. This complexity arises from using multiple public cloud services across departments, alongside private and third-party services.

Key considerations for effective management include:

1. Identifying all services currently used and anticipated future additions.
2. Understanding why each service is used and whether it meets business requirements.
3. Ensuring services meet security and governance standards set by management.
4. Verifying that data generated by applications is stored in compliant geographic locations.
5. Evaluating latency to ensure acceptable performance for all service users.

To address these challenges, organizations need a cohesive multicloud management strategy. This strategy should integrate services seamlessly to provide consistency and predictability across computing, applications, and storage resources, rather than treating them as isolated entities.

# 5. Standards in Multicloud World

It is critical that there are consistent and predictable ways to collaborate across computing services. A variety of standards are important for cloud computing.

## Standards

Standards, particularly open standards, are essential in facilitating interoperability and reducing complexity in cloud computing:

1. **Definition and Development**: Standards are established practices agreed upon by businesses or groups. Open standards, freely available to the public, are developed collaboratively, allowing contributions from stakeholders. This inclusivity ensures robustness and viability.

2. **Benefits of Adoption**: Broad industry adoption of open standards is crucial. They enable software to work together seamlessly, foster competition among implementations, provide consumer choice, and ensure compatibility. Without such standards, multicloud environments would face significant complexity and compatibility issues.

3. **Operational Advantages**: Open standards streamline infrastructure and application migration across cloud providers or from on-premises setups to clouds. They facilitate integration in multicloud models and mitigate risks of vendor lock-in, ensuring security and supporting hybrid cloud environments.

Standards evolve through various methods and stages of maturity:

1. **Establishment Methods**:
   - **Multinational bodies**: Governed by international treaties, these bodies like ISO develop comprehensive standards through lengthy processes involving diplomats and technical experts.
   - **Industry consortiums**: Organized groups within specific industries collaborate to streamline standard development, often involving direct engagement of technical experts.
   - **Ad hoc groups**: Self-organized around initiatives, especially in open-source contexts, these groups are agile but may face challenges in decision-making and consensus.
   - **De facto standards**: Arise organically through widespread industry adoption rather than formal creation, reflecting emerging best practices.

2. **Maturity Levels** (according to NIST):
   - Standards progress through stages including under development, approved, referenced, market accepted (in widespread use), and retired.

# Categories of Cloud-Related Standards
### SDOS vs SSOS
Standards development involves Standards Developing Organizations (SDOs) and Standards Setting Organizations (SSOs), each with distinct roles. SDOs create and develop standards, while SSOs adopt existing technical specifications as standards. Despite this difference, SSOs like the World Wide Web Consortium (W3C) play a significant role in setting influential standards such as HTML, CSS, and XML, which are widely adopted globally. Successful standards must be broadly recognized and adopted by vendors and consumers, and ideally open source. Establishing cloud standards is crucial as they enhance choice, reduce costs, and improve quality, particularly in areas like interoperability, portability, and security.

### Interoperability
Interoperability enables independent systems to work together or share information, crucial in multicloud or on-premises environments and between different cloud deployments. Standardized interfaces, like APIs, are essential for achieving interoperability, as proprietary APIs can lead to complexity and vendor lock-in. Kubernetes and related open-source standards such as Istio, Calico, and Helm facilitate application portability across different clouds, enhancing flexibility and responsiveness to changes.

### Portability
Portability allows applications, data, or instances to move between different cloud environments without modification. Standards like Open Virtualization Format (OVF) and Cloud Data Management Interface (CDMI) support portability of virtual machines and data across cloud environments, reducing dependency on specific platforms or providers.

### Security
Cloud security standards encompass authentication, authorization, data encryption, and policy management to safeguard corporate assets in hybrid environments. Standards like NIST SP 800-53 and FIPS series provide guidelines and controls to mitigate security risks and ensure compliance across cloud deployments.

### Organizations Building Momentum Around Standards
Various organizations, including the Cloud Security Alliance (CSA), Distributed Management Task Force (DMTF), National Institute of Standards and Technology (NIST), and others, play key roles in developing and promoting cloud computing standards. These efforts aim to enhance interoperability, portability, and security while fostering industry-wide collaboration and best practices.

### Vertical Groups
Vertical industry groups such as the TeleManagement Forum (TM Forum) and the Association for Retail Technology Standards (ARTS) are also engaged in developing cloud standards tailored to specific industry needs, promoting interoperability and innovation in cloud services.

# The Impact of Standards on the Multicloud

Key benefits of cloud standards include:

1. **Facilitating Portability:** Standards enable organizations to move infrastructure or applications seamlessly between different cloud providers without needing to rewrite code. This flexibility is particularly valuable in multicloud scenarios where resources may span on-premises and various cloud environments.

2. **Preventing Vendor Lock-in:** By adhering to interoperable standards, organizations avoid becoming overly dependent on a single cloud provider's proprietary interfaces. This reduces the cost and complexity associated with migrating to alternative providers, thereby increasing market choice.

3. **Simplifying Integration:** Standards streamline the integration of applications across diverse environments, including on-premises data centers, private clouds, and public clouds. This simplification reduces time and expense, enhancing operational efficiency and agility.

In essence, cloud standards mitigate risks associated with interoperability, vendor dependency, and integration challenges, empowering organizations to optimize their multicloud strategies effectively.
