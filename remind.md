# The Tweleve-Factor App

- Software Commonly delived as service like web apps or saas 
- The tweleve factor app is a **methodology** for building saas apps 

- **Declarative Formats** [ Setup Automation , Minimize Time & Cost ] -> For New Developers Joining the project 
- **Clean Contract** [ Underlaying OS , Maxium Portability between execution environments]
-**Minimize Divergence** between **development** and **production** enability CD for maximum agility. 
-- And can scale up without significant changes to **tooling** , **architecture** or **development practices** 

1. **CODEBASE** : One codebase tracked in revision control , many deploys 

Terms : VCS , Revision tracking database , Code repisotory , repo , code repo  
Tools : 

codebase : Single repo(Centralized revision control system like subversion) or any set of repos who share a root commit ( ina decentralized revision control system like Git )

**There is always a one-to-one correlation between the codebase and the app:**

**If there are multiple codebases, it’s not an app – it’s a distributed system. Each component in a distributed system is an app, and each can individually comply with twelve-factor.**
**Multiple apps sharing the same code is a violation of twelve-factor. The solution here is to factor shared code into libraries which can be included through the dependency manager.**

**A deploy is a running instance of the app.** 

2. **DEPENDENCIES** : Explicitly declare and isolate dependencies 

Codebase ----mapsto--> Deploys ( production , staging , developer 1 , deveroper 2 )







The services you've listed are indeed essential for building a wide range of applications on AWS. Below is a detailed description of each service, along with external links for further reading, organized in a tabular format.

| **Service**               | **Description**                                                                                                                                                    | **External Link**                                          |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| **IAM (Identity and Access Management)** | Manages user access and permissions to AWS services and resources securely.                                                                                   | [Learn more](https://aws.amazon.com/iam/)                |
| **EC2 (Elastic Compute Cloud)**          | Provides resizable compute capacity in the cloud, allowing users to run virtual servers and manage their applications.                                        | [Learn more](https://aws.amazon.com/ec2/)                |
| **Elastic Beanstalk**                   | A Platform as a Service (PaaS) that simplifies the deployment and management of applications in the cloud.                                                    | [Learn more](https://aws.amazon.com/elasticbeanstalk/)   |
| **ECS (Elastic Container Service)**      | A fully managed container orchestration service that allows you to run applications in Docker containers.                                                    | [Learn more](https://aws.amazon.com/ecs/)                |
| **EKS (Elastic Kubernetes Service)**     | A fully managed Kubernetes service that simplifies running Kubernetes on AWS without needing to install and operate your own control plane.                   | [Learn more](https://aws.amazon.com/eks/)                |
| **S3 (Simple Storage Service)**          | An object storage service that offers scalability, data availability, security, and performance for storing and retrieving any amount of data.                 | [Learn more](https://aws.amazon.com/s3/)                 |
| **Block Storage (EBS - Elastic Block Store)** | Provides block-level storage volumes for use with EC2 instances, offering high performance and low latency.                                                | [Learn more](https://aws.amazon.com/ebs/)                |
| **DynamoDB**                             | A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability.                                               | [Learn more](https://aws.amazon.com/dynamodb/)           |
| **RDS (Relational Database Service)**    | Makes it easy to set up, operate, and scale a relational database in the cloud, supporting multiple database engines like MySQL, PostgreSQL, and Oracle.      | [Learn more](https://aws.amazon.com/rds/)                |
| **DocumentDB**                           | A fully managed document database service that supports MongoDB workloads, providing scalability and performance.                                             | [Learn more](https://aws.amazon.com/documentdb/)         |
| **VPC (Virtual Private Cloud)**          | Allows you to provision a logically isolated section of the AWS cloud where you can launch AWS resources in a virtual network that you define.               | [Learn more](https://aws.amazon.com/vpc/)                |
| **CloudFront (CDN)**                     | A fast content delivery network (CDN) that securely delivers data, videos, applications, and APIs to customers globally with low latency.                     | [Learn more](https://aws.amazon.com/cloudfront/)         |
| **Route 53 (DNS)**                      | A scalable and highly available Domain Name System (DNS) web service designed to route end users to Internet applications by translating domain names into IP addresses.  | [Learn more](https://aws.amazon.com/route53/)            |
| **Certificate Manager**                  | Simplifies the process of provisioning, managing, and deploying SSL/TLS certificates for use with AWS services and your internal connected resources.        | [Learn more](https://aws.amazon.com/certificate-manager/)|
| **Auto-Scaling**                         | Automatically adjusts the number of EC2 instances or other resources based on demand to ensure optimal performance and cost-efficiency.                      | [Learn more](https://aws.amazon.com/autoscaling/)        |
| **NLB (Network Load Balancer)**          | Distributes incoming traffic across multiple targets at the transport layer (TCP), providing high performance for applications requiring low latency.         | [Learn more](https://aws.amazon.com/elasticloadbalancing/network-load-balancer/) |
| **ALB (Application Load Balancer)**      | Operates at the application layer (HTTP/HTTPS) allowing you to route traffic based on content of the request, ideal for microservices architectures.         | [Learn more](https://aws.amazon.com/elasticloadbalancing/application-load-balancer/) |
| **Bastion Host**                         | A special-purpose instance that acts as a gateway between a trusted network and an untrusted network, typically used to access instances in a private subnet.  | [Learn more](https://aws.amazon.com/architecture/bastion-hosts/) |

### Additional Recommendations
While the listed services cover many essential aspects of cloud application development on AWS, consider adding:

- **AWS Lambda**: For serverless computing.
- **Amazon API Gateway**: To create and manage APIs.
- **AWS CloudFormation**: To automate resource provisioning through Infrastructure as Code.
- **AWS CloudWatch**: For monitoring your AWS resources.

These services enhance functionality regarding serverless architectures, API management, infrastructure automation, and resource monitoring.

Feel free to explore each link for deeper insights into how these services can be utilized effectively in your application development process on AWS.

Citations:
[1] https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/
[2] https://aws.amazon.com/getting-started/cloud-essentials/
[3] https://aws.amazon.com/modern-apps/services/
[4] https://aws.amazon.com/modern-apps/
[5] https://aws.amazon.com/application-hosting/
[6] https://aws.amazon.com/jp/solutions/app-development/?awsm.page-solutions-all=2
[7] https://allcode.com/top-aws-services/
[8] https://aws.amazon.com/training/classroom/aws-technical-essentials/


































# AWS Essentials 

1. IAM : 