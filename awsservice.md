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

---

### Networking and Content Delivery:

- **Elastic Load Balancing**: automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. Offers four types of load balancers that all feature the high availability, automatic scaling, and robust security necessary to make applications fault tolerant.
    | Load Balancer | Functions |   Layer |
    | ------------- | --------- | --------------- |
    | Application | Provides advanced load balancing for traffic (HTTP, HTTPS, and  Google Remote Procedure Call, gRPC). Is used for flexible application management.| Operates at the application level (layer 7.)| 
    |     |     |
    |    |      |
    |      |      |
    








---

### Security, Identity, and Compliance

- [AWS Identity and Access Management (IAM)](./AWS_IAM.md)

- **Amazon Inspector**: 

- **Amazon Guard Duty**: 

- **AWS Artifact**: 

- **AWS Key Management Service (KMS)**:

- **AWS Shield**: 

- **AWS Web Application Firewall (WAF)**:

- **Amazon Macie**: 











