###﻿Day wise Lesson Plan for Advanced Devops and Cloud Training




Containerization and Orchestration

Day 1: Containers & Configuration Management

- Deep dive into Docker and containerization.
- Docker image and container quick refresher
- Docker volume deep dive
- Docker networking deep dive

Day 2: Kubernetes from an SRE Perspective

- Kubernetes deployment
- Orchestration introduction
- Kubernetes architecture
- Pods
- Replicaset
- Deployment
- Scale out/scale in
- Update/rollback

Day 3:

- Kubernetes services
- ClusterIP
- NodePort
- Loadbalancer

Scaling kubernetes cluster

- Kubernetes auto scaling
- Deep dive into Kubernetes operations and best practices.

Day 4:

- securing Kubernetes clusters.
- RBAC
- 4 C's of security discussion
- Network policies

Monitoring kubernetes cluster

- Deploy Prometheus and Grafana to monitor kubernetes

Day 5:

Setting up a Jenkins pipeline to do CI/CD

- Setup a java project
- Download code
- Unit test
- Build artifact
- Dockerize it
- Push docker image to DockerHub
- Run integration test
- Deploy to kubernetes cluster


Day 6: Advanced Monitoring & Alerting

- Tools from an SRE perspective:

Datadog,

Dynatrace,

Prometheus (already covered).

- Setting up alerts and incident management.
- Hands-on: Advanced monitoring setup for a complex application.
- Install dynatrace
- Configure dynatrace to monitor Docker and kubernetes cluster
- Configure dynatrace to monitor aws services

Monitoring, Audit & Observability

- Importance of monitoring and observability.
- Tools: New Relic, Dynatrace, Datadog.
- Hands-on: Setting up monitoring for a cloud application.


Day 7: Infrastructure-as-Code & Pipelines-as-Code

- IaC introduction
- Infrastructure provisioning tool - Terraform
- Creating a complete cluster with an ec2 instance using Terraform

- Configuration Management tool - Ansible
- Setup Configuration management using Ansible
- Hands-on: Deploying infrastructure using Terraform and setting up a CI/CD pipeline.
- Introduction to Ansible for configuration management.
- Hands-on: Containerizing an application and managing configurations with Ansible.


Day 8: High Availability & Scalability

- Concepts of High Availability (HA) and its importance.
- Designing for HA in the cloud.

Definition of High Availability (HA)

Significance of High Availability

Understanding Redundancy

Fault Tolerance vs. High Availability

Downtime and Its Impact

Recovery Time Objective (RTO) and Recovery Point Objective (RPO)

Clustering and Load Balancing

- Hands-on: Setting up a highly available application using AWS or Azure services.
- Create an Auto scaling group
- Deploy it with a load balancer
- See the ec2 instance increase and reduce as the load increase/reduce

Day 9: Serverless Architecture & Solutions

- Introduction to serverless computing.

What is Serverless Computing?

Evolution of Cloud Computing

Key Concepts in Serverless

- AWS Lambda, Azure Functions.
- Hands-on: Building a serverless application.

Day 10: Security & Encryption

Importance of Cloud Security

- Cloud security best practices.

Shared Responsibility Model

Identity and Access Management (IAM)

- Encryption at rest and in transit.
- Hands-on: Encrypting data in AWS S3 or Azure Blob Storage.

Day 11: Sample Solution Architectures & Cost Management

- Review of common cloud architectures.
- Cost optimization strategies.

The Importance of Cloud Architectures

The Significance of Cost Optimization

Monolithic Architecture

Microservices Architecture

Serverless Architecture

N-Tier Architecture

Event-Driven Architecture

- Hands-on: Analyzing costs using AWS Cost Explorer or Azure Cost Management.

Day 12: Common PaaS Solutions & Autoscaling

- Overview of Platform as a Service (PaaS).

What is AWS Elastic Beanstalk?

Key Features and Benefits

Use Cases

- AWS Elastic Beanstalk, Azure App Service.
- Introduction to autoscaling.
- Hands-on: Deploying an app on PaaS and setting up autoscaling.


Day 13: Application Performance Monitoring (APM)

- Importance of APM in DevOps.
- Tools: New Relic, Dynatrace.

Monitoring Applications with Dynatrace

Setting up Application Monitoring

Auto-Discovery of Application Components

Customizing Application Monitoring Settings

Alerting and Notifications

- Hands-on: Setting up APM for a sample application.

Day 14: Chaos Engineering & Internal Developer Platforms (IDP)

- Principles of chaos engineering.
- Introduction to IDPs and their benefits.

Understanding Internal Developer Platforms

Benefits and Significance of IDPs

IDP Components and Architecture

IDPs in the Software Development Lifecycle

- Hands-on: Running a chaos experiment using Chaos Monkey/Kube-Monkey.

Day 15: Introduction to SRE & Service Level Objectives (SLO)

- Overview of SRE and its principles.
- Understanding SLOs and Error budgets.
- Hands-on: Setting up SLOs for a sample service.

Setting up SLO with dynatrace

Day 16: Toil Concepts & Reduction

- Understanding toil and its impact.
- Strategies for toil reduction.
- Hands-on: Identifying and addressing toil in a sample DevOps process.

Observability & Service Level Indicators (SLI)

- Deep dive into observability.
- Understanding SLIs and their importance.
- Hands-on: Setting up observability tools and defining SLIs.


Day 17: Organizational Impact due to SRE

- How SRE impacts teams, culture, and processes.
- Case studies of organizations adopting SRE.
- Group discussion: Sharing experiences and challenges.

Frameworks & Trends in SRE

- Overview of popular SRE frameworks.
- Latest trends in SRE.
- Hands-on: Exploring a trending SRE tool or practice.

Explore dynatrace as an SRE tool

Day 18: Advanced Security & Compliance

- Security practices in SRE.
- Compliance and audit in cloud environments.
- Hands-on: Setting up security scanning and compliance checks.

aws security hub

Day 19: Continuous Learning & Improvement in SRE

- Importance of feedback loops in SRE.
- Continuous improvement strategies.
- Hands-on: Analyzing incident reports and suggesting improvements.



Day 20: Project

- Participants work on an end-to-end project encompassing all concepts learned.
- Review of key concepts and Q&A session.
