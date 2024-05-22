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

### Management and Goverance

- **AWS CloudTrail**: Records AWS API calls for accounts and delivers log files. History of API calls recorded from the Management Console, SDKs, REST APIs, command line tools and higher-level AWS services such as CloudFormation. This history enables security analysis, tracking changes of resources and compliance auditing. CloudTrail logs are encrypted and stored in a AWS S3 bucket. Best practice: use with Amazon CloudWatch. 

-

