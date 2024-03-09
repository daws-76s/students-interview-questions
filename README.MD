# Interview Questions

## Terraform

1. **What is Terraform?**

- Terraform is a popular IaC (Infrastructure as a Code) tool. It is the best in the market now. It has multiple advantages.
- **Version Control**:
Since it is code, we can maintain in Git to version control. We can completely maintain the history of infra and collaboration is easy.
- **Consistent Infra:**
Often we face the problem of different configurations in different environments like DEV, QA, PROD, etc. Using terraform we can create similar infra in multiple environments with more reliability.
- **Automated Infra CRUD:**
Using terraform we can create entire infra in minutes reducing the human errors. Updating infra using terraform is also easy. Using Terraform we can delete infra.
- **Inventory Management:**
If we create infra manually it is very tough to maintain the inventory of resources in diff regions. But by seeing terraform you can easily tell the resources you are using in different regions.
- **Cost Optimisation:**
When you need infra you can create in minutes. When you don't you can delete in minutes, so you can save the cost.
- **Automatic dependency management:**
terraform can understand the dependency of resources. It can tell us the dependency clearly.
- **Modular Infra:**
Code reuse. We can develop our own modules our use open source modules to reuse the infra code. instead of spending more time to create infra from the scratch we can reuse modules.
Describe your experience wth Terraform modules and how you organize and reuse infrastructure configurations.
Can you explain how Terraform integrates with cloud providers such as AWS and Kubernetes for infrastructure provisioning?

Questions from Interview I faced <br/>
Q1. explain about Release management how it saves time and error free <br/>

Q2.  What is devops & agile <br/>

Q3. the DevOps implementation requires many cultural and mindset changes to ensure its adoption amongst our customers. What do you see as main challenges to successfully implement DevOps in an organization with classic Agile way of Working way <br/>

Q4. What types of testing can be automated. What are the benefits of doing so? How do you think it could be effect the traditional role of test engineer in the future? <br/>

Q5. How did you manage working with less experience persons <br/>

Q6. What skills have learned recently and how did manage to learn <br/>

Q7. What steps do you take to implement change in your team and overcome resistance? 


Final round 
Technologies and tools you used to achieve your project's goals
Discuss your previous DevOps-related projects and the challenges you encountered
Explain how your contributions impacted the project's success and improved the development workflow
Share examples of issues you faced during deployments and how you troubleshooted and resolved them
Highlight your problem-solving skills and ability to analyze complex technical problems
Discuss 3-4 real-world scenarios you encountered while using DevOps tools and how you resolved any challenges. 
Can you share a challenging DevOps project you worked on and how you overcame obstacles to achieve success?
Discuss your approach to monitoring, logging, and alerting in a DevOps environment.
How do you troubleshoot performance issues and incidents using monitoring data?
What are versions of applications you are using: Terraform, Jenkins, Ansible, Kubernetes, etc. 

Scenario: 
Your team is responsible for managing infrastructure as code using Terraform. A new requirement has emerged to deploy additional resources in AWS, including EC2 instances, RDS databases, and S3 buckets. How would you ensure the reliability and scalability of the Terraform infrastructure?

Your team manages a highly available web application deployed across multiple AWS regions. You receive a notification of an outage in one of the regions. How would you ensure continuity of service for users during the outage?

Your company is planning to migrate an on-premises monolithic application to AWS using a lift-and-shift approach. What are some key considerations and challenges you would anticipate during the migration process?

Your team is tasked with automating the deployment of a new microservice using AWS Lambda and API Gateway. How would you design and implement the deployment pipeline for this microservice?

Your team is responsible for managing a complex web application hosted on AWS. The application consists of microservices deployed using Docker containers on Amazon ECS. Recently, users have reported intermittent performance issues. How would you troubleshoot and resolve these issues?

You're tasked with deploying a microservices-based application on AWS using Kubernetes. Walk me through the steps you would take to set up the environment and deploy the application.

Explain how you would design a scalable and highly available architecture for a microservices-based application on AWS using Kubernetes.


MicroServices: 
How do you design and deploy micro services based applications using containerization and orchestration tools?
Discuss your experience with service discovery, load balancing, and fault tolerance in a micro services environment. 
Describe strategies for managing communication and data consistency between microservices in production. 
How do you monitor and troubleshoot micro services based applications to ensure reliability and performance?

AWS:
Can you explain the key components of AWS architecture and how they interact?
Describe your experience with AWS services such as EC2, S3, RDS, and VPC.
How do you ensure security and compliance in an AWS environment?
Explain the difference between IAM policies and resource-based policies in AWS.
Can you discuss your experience with AWS Lambda and how it differs from traditional server-based architectures?

Lambda:
Hod do you trigger Lambda functions?
How do you deploy and manage serverless applications using AWS Lambda?
What are the advantages and limitations of AWS Lambda compared to traditional server-based architectures?
Describe a scenario where you implemented AWS Lambda functions to automate tasks or improve system efficiency.
How do you handle error handling and monitoring for AWS Lambda functions?
Can you discuss best practices for optimizing performance and cost-effectiveness when using AWS Lambda?


Monitoring:
What are the key metrics and indicators you monitor in a DevOps environment?
How do you set up monitoring and alerting for AWS resources and applications?
Can you explain the role of tools like Prometheus, Grafana, and ELK stack in monitoring and logging?

