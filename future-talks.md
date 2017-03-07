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

## Automating Cloud Infrastructure with Terraform in a CI/CD pipeline
* Needs a good title
* Infrastruce is code
* Terraform is multi-cloud enabled
* [New Terraform Oracle BMC provider](https://blogs.oracle.com/developers/terraform-and-oracle-bare-metal-cloud-services) released (not official)

### Abstract
Your challenge: Deploy your ground-breaking industry disrupting software project onto one or more cloud platforms, do it quickly, and do it repeatedly. 

This is the very challenge being solved by nearly every tech team around the world on a daily basis. And don't let anyone fool you, it's easier said than done, and the landscape is always moving. 

When deploying to a cloud platform, it is expected that resources can and will disappear without notice. Some cloud platforms are more volital than others, but regardless, the ability to re-establish your infrastructure quickly, into a known working configuration, is crucial to success. When you can automate your infrastructure deployment, you are one step closer to a self-healing infrastructure.

In this presentation we'll talk about Infrastructure as Code, and the value gained from codifying your infrastructure within a revision control system. Throughout the presentation we will introduce [Terraform](http://terraform.io), a tool that defines cloud infrastructure in configuration files that can be shared, edited, reviewed, and versioned. 

Attendees will learn how we tackled the challenge of deploying directly to a production cloud infrastructure from a CI/CD pipeline for automated deployment.

### Introduction
TBD

#### Notes for the GHC 2017 submission
For the GHC 2017 Software Engineering Foundations
Submissions to “Foundations” are expected to describe the outcomes, experiences, and challenges related to work in the foundations of engineering software as they relate to any of the listed topic areas.

The Reviewers are looking for information on the following items:
* Is the topic relevant to a track's theme?
* Are the objectives clear and well-described?
* Is this paper written clearly?
* Will this presentation draw an audience?
* Is this paper well-organized and does it flow logically?
* Does this paper make sure that the topic is not a rehash of established facts?
* Does this paper provide details on how the results can be repeatable?
* Does this paper mention alternate explanations or methodologies?
* This paper focuses purely on the technology and is not a recruiting or a product pitch. 

### Outline for GHC Software Engineering Foundations focus tract
1. Introduction
2. The Cloud -- it disappears
3. Problem ... deploy into the cloud in a repeatable manner
3. Infrastructure as Code
  a. Repeatability
  b. Audit Trail for Changes
  c. Incorporate into CI/CD pipeline
4. Terraform Introduction
5. How We utilized Terraform and Docker in Jenkins to solve our automated deployment challenge

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

