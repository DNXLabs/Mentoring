# Mentoring


A summary of what will be given

<b>(Day 1)</b>

#### Cloud

<details>
<summary> Types of Cloud Computing services</summary><br><b>

1 - IAAS (Infrastructure as a service)<br><br>
  IaaS stands for Infrastructure-as-a-Service. It allows organizations to purchase resources like networking and storage on-demand instead of having to buy costly hardware. IaaS is highly scalable and offers businesses more flexibility than on-premise solutions.

  IaaS can be seen as the basic layer in cloud computing. The virtualized components available through the internet are equivalent to the servers and hardware companies would traditionally store in their building.

  1.1 - When to use IaaS?
  
  Organizations of all sizes can benefit from IaaS. Small companies who want to avoid purchasing hardware or don’t have the time, staff, or ability to host large data centers on-premise, as well as larger businesses who want to stay in control of their apps and only want to consume the resources they actually need. The scalability of IaaS is also great for companies that experience rapid growth.

  1.2 - IaaS delivery
  
  With IaaS, enterprises get a full cloud computing infrastructure including network, servers, operating system, and data centers/storage. Full access is granted through virtualization technology via dashboard or API. This way, clients have complete control over their computing infrastructure.

  The IaaS provider is responsible for managing and maintaining servers, hard drives, storage, and virtualization tools. However, applications, runtime, OS, middleware, and data still need to be managed by the client.

  1.3 - IaaS benefits
  * Flexibility: IaaS is more flexible than all the other cloud computing models.
  * Automation: With IaaS, you can easily automate the deployment of servers, storage, and networking.
  * Cost-reduction: IaaS lets you purchase resources on an as-needed basis, so you only pay for what you’re actually using.
  * Control: IaaS lets you retain complete control of your infrastructure.
  * Scalability: Since you’re only “renting” IT components, you can easily upscale or downscale your resources.

  1.4 - IaaS disadvantages
  * Legacy systems: Before migrating to the cloud, legacy apps might have to be enhanced for the new type of infrastructure.
  * Internal training: Staff might have to undergo additional training to effectively manage and monitor IaaS.
  * Security: While you are in control over your apps, data, middleware, and the OS platform, you are also responsible for mitigating new security threats.

  
  2 - PAAS (Platform as a Service)<br><br>
  PaaS stands for Platform-as-a-Service. The platform that can be accessed through the internet provides developers with a framework and tools to build apps and software that are tailored to the organization’s individual needs.

  PaaS can be seen as a scaled-down version of IaaS. Just like IaaS, the customers have access to servers and data centers which are maintained and managed by the third-party provider. However, they mainly use PaaS for building custom SaaS applications.

  2.1 - When to use PaaS?
  
  There are several situations when a Platform-as-a-Service would be a good idea. For example, if you have several developers working on the same development project, PaaS is a great way to streamline workflows.

  You can even include other vendors and stay flexible during the entire process. PaaS is also the way to go if your organization requires customized applications that need to be developed and deployed in a short amount of time.

  2.2 - PaaS delivery
  
  PaaS delivery can be compared to the way SaaS is delivered. The only difference is that customers don’t access online software, but an online platform for the creation of software. And since tools and environment are ready-to-use, software engineers and developers can concentrate on building applications without having to worry about other components like operation systems, storage, and infrastructure.

  2.3 - PaaS benefits
  * Cost-reduction: PaaS is a simple, cost-effective way to quickly develop and deploy new apps.
  * Scalability: PaaS service models can easily be adjusted to a developer’s needs.
  * Migration: With PaaS, it’s easy to migrate to a hybrid cloud model.
  * Less coding: Your developer teams have to do a lot less coding than before.
  * Freedom: PaaS frees up time as developers can customize apps without having to maintain the software.

  2.4 - PaaS disadvantages
  * Data security: Using third-party vendor-controlled servers means that there are various security risks to look out for.
  * Runtime issues: Some PaaS solutions are not optimized for the language or framework that your development teams are used to.
  * Integrations: You might encounter some challenges with integrating new applications as not every component of your legacy IT system is built for the cloud.
  * Limitations: Customized cloud operations tend to have automated workflows that might not be compatible with PaaS solutions, thus limiting operational capabilities for your end-user.
  
  
  3 - SAAS (Software as a Service)<br><br>
  SaaS stands for Software-as-a-Service. These entire cloud application services are the most common form of cloud computing. They are ready-to-use and often run directly through the client’s web browser, meaning there is no need for installations or downloads like it with on-prem solutions.

  SaaS is hosted on remote servers and fully managed, updated, and maintained by a third-party vendor. This results in less responsibility but also less control for the end-user.

  3.1 - When to use SaaS?
  
  SaaS is ideal for small companies or startups that don’t have the capacity to develop their own software applications. From e-commerce to short-term projects, SaaS is the quickest and easiest solution if you don’t need highly customized applications. SaaS is also a great option for applications that are not used very often, e.g. tax software.

  3.2 - SaaS delivery
  
  SaaS is delivered as a fully functional service and can be accessed remotely via any web browser, allowing clients to work from anywhere. The users connect to the app through a dashboard or API and rely on the SaaS provider when it comes to bug fixes, middleware, support, and any potential technical issues.

  3.3 - SaaS benefits
  * Cost-reduction: SaaS usually resides in a shared or multi-tenant environment. When managed correctly, the license costs are lower compared to traditional models.
  * Scalability: SaaS solutions are easy to scale up or down based on your specific needs.
  * Integration: Many SaaS solutions have integrations with other SaaS offerings, so you don’t have to buy another server or software.
  * Upgrades: With SaaS, you instantly benefit from new software releases and upgrades.
  * Ease of use: Without installation or download, SaaS is easy to use and comes with baked-in best practices.

  3.4 - SaaS disadvantages
  * Data security: Since large volumes of sensitive data are being exchanged with off-premise servers, security and compliance might be compromised.
  * Limited customization: SaaS only allows for minimal customization when it comes to features and capabilities.
  * Interoperability: It might be difficult to integrate SaaS with existing apps and services due to dependencies.
  * Less control: Users have very little control over functionalities, performance, downtime, or how their data is governed.
  * Wasted resources: With the ease of use and scalability SaaS provides, an organization's SaaS stack includes many overlapping, underutilized, or unused apps. The value of SaaS apps in the organization can drop without automated SaaS Management or SaaS optimization processes in place.  
  * Shadow IT: Employees often purchase or sign up for new SaaS without the knowledge of IT. Unmanaged SaaS apps could have potential security gaps.
 
</b></details>


<details>

<summary> Cloud Computing Deployments:</summary> <br><b>


  * Public
  * Hybrid
  * Private
  </b></details>

#### AWS Global Infrastructure

<details>
<summary>Explain the following

  * Availability zone
  * Region
  * Edge location</summary><br><b>
AWS regions are data centers hosted across different geographical locations worldwide, each region is completely independent of one another.<br>

Within each region, there are multiple isolated locations known as Availability Zones. Multiple availability zones ensure high availability in case one of them goes down.<br>

Edge locations are basically content delivery network which caches data and insures lower latency and faster delivery to the users in any location. They are located in major cities in the world.
</b></details>

#### AWS Networking

<details>
<summary>What is VPC?</summary><br><b>

"A logically isolated section of the AWS cloud where you can launch AWS resources in a virtual network that you define"
Read more about it [here](https://aws.amazon.com/vpc).
</b></details>

<details>
<summary>What is an Internet Gateway?</summary><br><b>

"component that allows communication between instances in your VPC and the internet" (AWS docs).
Read more about it [here](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html)
</b></details>

<details>
<summary>NACL - Network Access List -</summary><br><b>
 allow or deny traffic on the subnet level
</b></details>

<details>
<summary>Route Tables - traffic flow AWS </summary><br><b>

</b></details>

<details>
<summary>SG - Security Groups - </summary><br><b>
allow or deny traffic on the intance level
  
* NACL - security layer on the subnet level.
* Security Group - security layer on the instance level.

Read more about it [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html) and [here](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html)
</b></details>

<b>(Day 2)</b>

#### AWS Compute

<details>
<summary>What is EC2?</summary><br><b>

"a web service that provides secure, resizable compute capacity in the cloud".
Read more [here](https://aws.amazon.com/ec2)
</b></details>

<details>
<summary>What is AMI?</summary><br><b>

Amazon Machine Images is "An Amazon Machine Image (AMI) provides the information required to launch an instance".
Read more [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html)
</b></details>

<details>
<summary>What is instance type?</summary><br><b>

"the instance type that you specify determines the hardware of the host computer used for your instance"
Read more about instance types [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-types.html)
</b></details>

<details>
<summary>What is EBS?</summary><br><b>

"provides block level storage volumes for use with EC2 instances. EBS volumes behave like raw, unformatted block devices."
More on EBS [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html)
</b></details>

#### AWS Containers

<details>
<summary>What is Amazon ECS?</summary><br><b>

Amazon definition: "Amazon Elastic Container Service (Amazon ECS) is a fully managed container orchestration service. Customers such as Duolingo, Samsung, GE, and Cook Pad use ECS to run their most sensitive and mission critical applications because of its security, reliability, and scalability."

Learn more [here](https://aws.amazon.com/ecs)
</b></details>

<details>
<summary>What is Amazon ECR?</summary><br><b>

Amazon definition: "Amazon Elastic Container Registry (ECR) is a fully-managed Docker container registry that makes it easy for developers to store, manage, and deploy Docker container images."

Learn more [here](https://aws.amazon.com/ecr)
</b></details>

<details>
<summary>What is AWS Fargate?</summary><br><b>

Amazon definition: "AWS Fargate is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS)."

Learn more [here](https://aws.amazon.com/fargate)
</b></details>

#### AWS IAM

<details>
<summary>What is IAM? What are some of its features?</summary><br><b>

Full explanation is [here](https://aws.amazon.com/iam)
In short: it's used for managing users, groups, access policies & roles
IAM configuration is defined globally and not per region
</b></details>

<details>
<summary>What are Roles?</summary><br><b>

A way for allowing a service of AWS to use another service of AWS. You assign roles to AWS resources.
For example, you can make use of a role which allows EC2 service to acesses s3 buckets (read and write).
</b></details>

<details>
<summary>What are Policies?</summary><br><b>

Policies documents used to give permissions as to what a user, group or role are able to do. Their format is JSON.
</b></details>

<b>(Day 3 and 4)</b>

#### AWS Storage
 
<details>
<summary>Explain what is AWS S3?</summary><br><b>

S3 stands for 3 S, Simple Storage Service.
S3 is a object storage service which is fast, scalable and durable. S3 enables customers to upload, download or store any file or object that is up to 5 TB in size.

More on S3 [here](https://aws.amazon.com/s3) 
</b></details>

<details>
<summary>What is a bucket?</summary><br><b>

An S3 bucket is a resource which is similar to folders in a file system and allows storing objects, which consist of data.
</b></details>

<details>
Explain the following:

  * Object Lifecycles - Transfer objects between storage classes based on defined rules of time periods
  * Object Sharing - Share objects via a URL link
  * Object Versioning - Manage multiple versions of an object
</b></details>

<details>
<summary>Explain Object Durability and Object Availability</summary><br><b>

Object Durability: The percent over a one-year time period that a file will not be lost
Object Availability: The percent over a one-year time period that a file will be accessible
</b></details>

<details>
<summary>What is a storage class? What storage classes are there?</summary><br><b>

Each object has a storage class assigned to, affecting its availability and durability. This also has effect on costs.
Storage classes offered today:
  * Standard:
    * Used for general, all-purpose storage (mostly storage that needs to be accessed frequently)
    * The most expensive storage class 
    * 11x9% durability
    * 2x9% availability
    * Default storage class

  * Standard-IA (Infrequent Access)
    * Long lived, infrequently accessed data but must be available the moment it's being accessed
    * 11x9% durability
    * 99.90% availability

  * One Zone-IA (Infrequent Access):
    * Long-lived, infrequently accessed, non-critical data
    * Less expensive than Standard and Standard-IA storage classes
    * 2x9% durability
    * 99.50% availability
    
  * Intelligent-Tiering:
    * Long-lived data with changing or unknown access patterns. Basically, In this class the data automatically moves to the class most suitable for you based on usage patterns
    * Price depends on the used class
    * 11x9% durability
    * 99.90% availability

  * Glacier: Archive data with retrieval time ranging from minutes to hours
  * Glacier Deep Archive: Archive data that rarely, if ever, needs to be accessed with retrieval times in hours
  * Both Glacier and Glacier Deep Archive are:
    * The most cheap storage classes
    * have 9x9% durability 

More on storage classes [here](https://aws.amazon.com/s3/storage-classes)

</b></details>

<details>
<summary>What is Amazon EFS?</summary><br><b>

Amazon definition: "Amazon Elastic File System (Amazon EFS) provides a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources."

Learn more [here](https://aws.amazon.com/efs)
</b></details>

##### AWS ELB

<details>
<summary>What is ELB (Elastic Load Balancing)?</summary><br><b>

AWS definition: "Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions."

More on ELB [here](https://aws.amazon.com/elasticloadbalancing)
</b></details>

<details>
<summary>What is ALB (Application Load Balancing)?</summary><br><b>
</b></details>

##### AWS ASG

<details>
<summary>What is auto scaling?</summary><br><b>

AWS definition: "AWS Auto Scaling monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost"

Read more about auto scaling [here](https://aws.amazon.com/autoscaling)
</b></details>

#### AWS Databases

<details>
<summary>What is AWS RDS?</summary><br><b>
</b></details>

<details>
<summary>What is AWS DynamoDB?</summary><br><b>
</b></details>


<details>
<summary>What is AWS Redshift and how is it different than RDS?</summary><br><b>

cloud data warehouse
</b></details>


<details>
<summary>What is Amazon Aurora</summary><br><b>

A MySQL & Postgresql based relational database. Also, the default database proposed for the user when using RDS for creating a database.
Great for use cases like two-tier web applications that has a MySQL or Postgresql database layer and you need automated backups for your application.
</b></details>

<details>
<summary>What is Amazon DocumentDB?</summary><br><b>

Amazon definition: "Amazon DocumentDB (with MongoDB compatibility) is a fast, scalable, highly available, and fully managed document database service that supports MongoDB workloads. As a document database, Amazon DocumentDB makes it easy to store, query, and index JSON data."

Learn more [here](https://aws.amazon.com/documentdb)
</b></details>

#### AWS ROUTE53

<details>
<summary>What is Route 53?</summary><br><b>

"Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service"
Some of Route 53 features:
  * Register domain
  * DNS service - domain name translations
  * Health checks - verify your app is available

More on Route 53 [here](https://aws.amazon.com/route53)
</b></details>

<b>(Day 4 and 5)</b>

#### AWS Monitoring & Logging

<details>
<summary>What is AWS CloudWatch?</summary><br><b>

AWS definition: "Amazon CloudWatch is a monitoring and observability service..."

More on CloudWatch [here](https://aws.amazon.com/cloudwatch)
</b></details>

<details>
<summary>What is AWS CloudTrail?</summary><br><b>

AWS definition: "AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account."

Read more on CloudTrail [here](https://aws.amazon.com/cloudtrail)
</b></details>


<details>
<summary>First Challange</summary><br><b>

→ Deploy Web Application in EC2.
Requirements:      
  - Create an Custom VPC (Network: "10.100.0.0/16")
  - Create an EC2 Instance inside this network 
  - Page returning describe-instances and describe-vpcs in a Table
  - Language:  Up to you
Ref.: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/API_DescribeInstances.html
PS: If you are not a developer, in JSON format is fine (We're going to support you if you need it)
    If you judge it's too easy for you, Add AWS Cognito Authentication to the page

* DNX Foundation
  * https://modules.dnx.one/
 
</b></details>

<b>(Day 6 and 7)</b>

#### AWS Serverless Compute

<details>
<summary>Explain what is AWS Lambda</summary><br><b>

AWS definition: "AWS Lambda lets you run code without provisioning or managing servers. You pay only for the compute time you consume."

Read more on it [here](https://aws.amazon.com/lambda)
</b></details>

<details>
<summary>Which of the following set of languages Lambda supports?

 - R, Swift, Rust, Kotlin, Python, Ruby, Go PHP
</b>
</details>


#### AWS API Gateway 

<details>
<summary> What is API Gateway</summary><br><b>
</b></details>

<details>
<summary>What is AWS Cognito?</summary><br><b>
</b></details>

<details>
<summary>Building a REST API with AWS Lambda and API Gateway</summary><br><b
</b></details>

<b>(TO BE DONE)</b>

#### AWS CloudFront

<details>
<summary>what is CloudFront?</summary><br><b>

AWS definition: "Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment."

More on CloudFront [here](https://aws.amazon.com/cloudfront)
</b></details>

<details>
<summary>Explain the following

  * Origin
  * Edge location
  * Distribution</summary><br><b>
</b></details>

#### AWS SNS

<details>
<summary>What is Simply Notification Service?</summary><br><b>

AWS definition: "a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications."

Read more about it [here](https://aws.amazon.com/sns)
</b></details>


#### AWS Security 

<details>
<summary>What is the shared responsibility model? What AWS is responsible for and what the user is responsible for based on the shared responsibility model?</summary><br><b>

The shared responsibility model defines what the customer is responsible for and what AWS is responsible for.

More on the shared responsibility model [here](https://aws.amazon.com/compliance/shared-responsibility-model)
</b></details>


<details>
<summary> "Shared Controls" in regards to the shared responsibility model</summary><br><b>

AWS definition: "apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives. In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services"

Learn more about it [here](https://aws.amazon.com/compliance/shared-responsibility-model)
</b></details>


<details>
<summary>What is AWS Inspector?</summary><br><b>

AWS definition: "Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices.""

Learn more [here](https://aws.amazon.com/inspector)
</b></details>

<details>
<summary>What is AWS Guarduty?</summary><br><b>
</b></details>

<details>
<summary>What is AWS Shield?</summary><br><b>

AWS definition: "AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS."
</b></details>

<details>
<summary>What is AWS WAF? Give an example of how it can used and describe what resources or services you can use it with</summary><br><b>
</b></details>

<details>
<summary>What AWS VPN is used for?</summary><br><b>
</b></details>

<details>
<summary>What is the difference between Site-to-Site VPN and Client VPN?</summary><br><b>
</b></details>


<details>
<summary>What is AWS Key Management Service (KMS)?</summary><br><b>

AWS definition: "KMS makes it easy for you to create and manage cryptographic keys and control their use across a wide range of AWS services and in your applications."
More on KMS [here](https://aws.amazon.com/kms)
</b></details>


<details>
<summary>What is Amazon Cognito?</summary><br><b>

Amazon definition: "Amazon Cognito handles user authentication and authorization for your web and mobile apps."

Learn more [here](https://docs.aws.amazon.com/cognito/index.html)
</b></details>

<details>
<summary>What is AWS ACM?</summary><br><b>

Amazon definition: "AWS Certificate Manager is a service that lets you easily provision, manage, and deploy public and private Secure Sockets Layer/Transport Layer Security (SSL/TLS) certificates for use with AWS services and your internal connected resources."

Learn more [here](https://aws.amazon.com/certificate-manager)
</b></details>

#### AWS Automation

<details>
<summary> what is CloudFormation</summary><br><b>
</b></details>

<details>
<summary>What is AWS CodeDeploy?</summary><br><b>

Amazon definition: "AWS CodeDeploy is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers."

Learn more [here](https://aws.amazon.com/codedeploy)
</b></details>

