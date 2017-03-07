# Future talk ideas

Feedback welcome! Please open an issue or make a pull request.

## Polychronic vs Monochronic culture and DevOps
* needs a title for sure
* A monochronic time system means that things are done one at a time and time is segmented into precise, small units. Under this system, time is scheduled, arranged and managed.
* A polychronic time system is a system where several things can be done at once, and wider view of time is exhibited and time is perceived in large fluid sections.
* how to corodinate time sensitive personalities with those who see time as a little more fluid
* take advantage of the strengths in each to build a better culture and produce more work
* build polychronic approach into Agile planning
* for polychronics the 'how it fits into the bigger picture' is more important than 'how long it takes (will take)' to get done.
	* what's the value

## Automating Your Way to the Cloud: Serverless Architecture with Terraform
* Infrastruce is code
* Terraform is multi-cloud enabled
* [New Terraform Oracle BMC provider](https://blogs.oracle.com/developers/terraform-and-oracle-bare-metal-cloud-services) released (not official)

### Abstract
There is no cloud, it's just someone else's computer.

With the industry move away from datacenters to the cloud, costs and accessibility and speed are balanced against the loss of control, and the need to manage and orchestrate infrastructure in repeateable, automated and auditable manner.  

This presentation will share experiences and lessons learned developing a deployment strategy for a cloud-first service. Our goal: initial production deployment of a Serverless Architected service directly from our CI/CD pipeline, with no manual intervention in resource deployoment. 

Through this talk attendees will be introduced to [Terraform](http://terraform.io), a tool that defines cloud infrastructure in configuration files that can be shared, edited, reviewed, and versioned. 

Using Jenkins as a build tool and Terraform modules for infrastructure codification, we are able to repeatedly build and destroy our service for testing purposes and ship updates through continuous deployment.

### Introduction
This presentation is intended for Beginner and Intermediate level software developers, and technical managers who are interested in speeding up the time to deployment for cloud based services. 

In the area of sofware automation, the mantra of Infrastructure is Code, is often spouted, but rarely followed. In this presentation I will walk through how a cloud-first service differs in deployment strategy from traditional deployments. 

With a Serverless Architecture, the testing and validation of code modifications in a CI/CD pipeline necessitate deploying a testbed infrastructure for automated testing prior to deploying changes into production. This differs from the usual functional test runs due to the need to deploy test-run specific infrastructure. As these are "one-use" resources, ensuring they are properly destroyed after test runs is a crucial part of controlling costs. Using an orchestration tool such as Terraform allows for automating these tasks. 

This presentation will include architecture considerations, deployment strategy and testing practices that support rapid iterations and fit into a Continuous Integration / Continuous Deployment pipeline strategy.

### Outline for GHC 2017 Software Engineering Foundations focus tract
1. Introduction
2. The Cloud -- it disappears
3. Problem ... deploy into the cloud in a repeatable manner
	a. Differences from a traditional DataCenter deployment
	b. Serverless Architecture, what it is and how we used it.
4. Infrastructure as Code
  a. Repeatability
  b. Audit Trail for Changes
  c. Incorporate into CI/CD pipeline
5. Terraform Introduction
6. Terraform State files
	a. What they are
	b. When they are used
	c. Remote state storage in multi-user environments
7. How We utilized Terraform and Docker in Jenkins to solve our automated deployment challenge
	a. Why Docker?
	b. Jenkins Build pipeline

### Outline for "How To"
1. Introduction
2. Infrastructure as Code
  a. Repeatability
  b. Audit Trail for Changes
  c. Incorporate into CI/CD pipeline
3. The Cloud -- it disappears
4. Terraform Introduction
5. Terraform Examples of Cloud Infrastructure Definitions
	a. AWS
	b. Oracle Bare Metal Cloud
6. Terraform Example of infrastructure management
	a. plan
	b. apply
	c. destroy
6. Adding Terraform Infrastructure to a build pipeline
	a. Jenkins as build tool for CI/CD
		* Why using Docker containers in Jenkins works better than installing tools directly
	b. Using Terraform Docker Image in Jenkins build job
7. Topics we didn't have time for
	a. Multi-cloud deployments
	b. monitoring
	c. self-healing cloud infrastructure

## Less fleshed out ideas

* git training for the CLI impaired

