## AWS Foundational Services:

### Core Services:

- [Amazon VPC](./VPC.md)
- [Amazon EC2](./EC2.md)
- [Amazon S3](./S3.md)
- [Amazon RDS](./RDS.md)
- [AWS IAM](./AWS_IAM.md)
- [AWS Lambda](./AWS_Lambda.md)
- [Amazon CloudWatch](./CloudWatch.md)

---
### Analytics:
- **Amazon Athena**: Interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Since Athena is serverless, pay only for the queries that are ran. Integrates with **AWS Glue** Data Catalog to create a unified metadata repository across services, discover schemas through crawling the data, and update repo with new and modified tables. 

- **Amazon EMR**: Serverless;  

- **Amazon RedShift**:

- **AWS Glue**: 


---

### Admin and Dev Tools (Automation):

- **AWS Tools and SDKS**: Software Development Kits that access AWS services programmatically and write adminstrative scripts in different programming languages.

- **AWS CloudFormation**: Create, update, and delete a set of AWS resources as a single unit using a JSON or YAML template.

- **AWS OpsWorks**: automates how servers are confirgured, deployed and managed using Chef or Puppet.

- **AWS CodeWhisperer**: AI-powered code generator for IDEs and code editors. Generates code suggestions with an option to accept of reject them. Security scanner identifies hard-to find vulnerabilites. Refers various standards and best practices to follow. All of this results in more secure code. Support open-source and all experience-level developers. 

- [AWS_Systems_Manager](./AWS_SYS_MAN.md)

- [AWS_Cloud9](./AWS_CLD_9.md)

---

### Compute Services:

- [Amazon EC2](./EC2.md)

- **AWS Elastic Beanstalk**: A fully-managed platform as a service (PaaS) that facilitates the quick deployment, scaling, and management of applications. When an application is uploaded, **Elastic Beanstalk** automatically handles the deployment details of capacity provisioning, load balancing, auto scaling, and application health monitoring. Benefits: increases productivity, built-in scalability, fully-managed.
    - Supports web applications written for common platforms, including Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker.
    - gives control over key runtime configuration options and resources.
    - No charge to use; pay for resources that stores and runs applications. 

- **AWS Fargate**:

- **AWS Lambda**:

- **AWS Lightsail**: 

---

### Management and Goverance

- **AWS CloudTrail**: Records AWS API calls for accounts and delivers log files. History of API calls recorded from the Management Console, SDKs, REST APIs, command line tools and higher-level AWS services such as CloudFormation. This history enables security analysis, tracking changes of resources and compliance auditing. CloudTrail logs are encrypted and stored in a AWS S3 bucket. Best practice: use with Amazon CloudWatch. 

- **AWS CloudWatch**: Monitor and manage various metrics. configures alarms actions based on data from those metrics. alarms automatic perform actions if the value of the metrics goes above or below a predefined threshold.  Access to all metrics from a central location through the dashboard. Visibility into applications, infrastructures and services, reduce MTTR and improve TCO insights to optimize apps and operational procedures. Manages Performance optimization. 

- **AWS Trusted Advisor**: Evaluates your AWS environment in real-time using best practice checks across the categories of cost optimization, performance, resilience, security, fault tolerance, and service limits, and recommend actions to remediate any deviations from best practices in Trusted Advisor Priority. 

- **AWS Config**: Configuration Manager for AWS account. Keeps a record of the configuration settings for AWS resources, such as virtual machines, databases, and security groups. Detects and notifies of any changes to these configurations, helping to stay on top of updates and potential issues. Ensures resources comply with industry standards and best practices, reducing security risks and errors. Offers a centralized dashboard to view and manage AWS resources, making it easier to understand resource usage and optimize the infrastructure.

---

### Networking and Content Delivery:

- **Elastic Load Balancing**: automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. Offers four types of load balancers that all feature the high availability, automatic scaling, and robust security necessary to make applications fault tolerant.
    | Load Balancer | Functions |   Layer |
    | ------------- | --------- | --------------- |
    | Application | Provides advanced load balancing for traffic (HTTP, HTTPS, and  Google Remote Procedure Call, gRPC). Is used for flexible application management.| Operates at the application level (layer 7.)| 
    | Gateway | Provides load balancing for virtual appliances and network traffic destinations (all types of IP traffic). Is  used for virtual appliance management. | Operates as a gateway at the network level (layer 3) and as a load balancer at the transport level (layer 4) |
    | Network | Provides load balancing for TCP traffic (TCP, UDP, and TLS). Is used for extreme performance and as a static IP address for your application. | Operates at the transport level (layer 4). |
    | Classic | Provides support and load balancing for HTTP, HTTPS, SSL/TLS, and TCP traffic on the EC2-Classic platform(previous generation. Is used for existing applications that were built on the EC2-Classic platform. | Operates at both the application level (layer 7) and the transport level (layer 4). |



---

### Security, Identity, and Compliance

- [AWS Identity and Access Management (IAM)](./AWS_IAM.md): Secures control access to AWS resources, uses ACL to control access to resources. Configure Role-based permissions. Controls access to AWS resources by using authentication and authorization. Authentication: Use IAM to control who can sign in and Authorization: Use IAM to control who has access to resources. 

- **Amazon Inspector**: Checks apps for security vulnerabilities. Runs automated security assessments. Makes recommendations. 

- **Amazon Guard Duty**: Provides intelligent threat detection for AWS infrastructures and resources. Analyzes data from multiple AWS sources (VPC Flow and DNS logs). 

- **AWS Artifact**: On-demand access to AWS security and compliance report. Two Sections: Agreements and Reports. Access to Compliance reports. AWS Compliance Regulations and Reports for Data Storage. Emphasis on Shared Responsibilities. Customer Compliance Center is a resource for customers

- **AWS Key Management Service (KMS)**: Manage and create encryption operations through cryptographic keys. Can store keys in the default key store or connect to **AWS CloudHSM** to store keys in its key store. This technique helps satisfy compliance obligations to use HSMs while providing the AWS service integrations of AWS KMS. Integrates with AWS services to simplify the process of using your keys to encrypt data across your AWS workloads. Is fully managed. 

- **AWS Shield**: protects applications against DDoS attacks. Two levels of protections: Standard, a free service and Advanced, paid services that connected to other AWS security service.

- **AWS Web Application Firewall (WAF)**: works with **AWS CloudFront** and *Application Load Balancer*. A web application firewall. black or allows access to web apps.  **AWS WAF** is a web application firewall service that helps protect your web apps from common exploits that could affect app availability, compromise security, or consume excessive resources. **AWS Shield** provides expanded DDoS attack protection for your AWS resources. The difference between them is that **AWS WAF** provides protection on the application layer and AWS Shield protects the infrastructure layers of the OSI model.

- **Amazon Macie**: 

- **AWS Organizations**: manages multiple AWS accounts in a central locations (containers). Group accounts in Organization Units (OU) based on duties and responsibilities. Service Control policies (SCPs) can be applied to OUs and individual member accounts. Every organization in AWS Organizations has a management account that pays the charges of all the member accounts. At no additional cost.
    - *Consolidate billings* provides one bill for multiple accounts, tracks the charges across multiple accounts and download the combined cost and usage data.  Itemized charges can be reviewed as well. Companies can combine the usage across all accounts in the organization to share the volume pricing discounts, Reserved Instance discounts, and Savings Plans. This can result in a lower charge for a project, department, or company than with individual standalone accounts. 









