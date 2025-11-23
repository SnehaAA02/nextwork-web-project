# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app develoopment and AWS CI/CD tools.
<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Conclusion](#conclusion)
<br>

## Introduction
This project is used for a introduction to creating and deploying a Java based web app using AWS, especilly their CI/CD tools.

## Technologies

Here's what I'm using for this project:

*Amazon EC2*: I'm developing my web app on Amazon EC2 virtual servers, so that software development and deployment happens entirely on the cloud.
Key pirs, SSH coonections, Git, Maven and Java.

*VSCode*: For my IDE, I chose Visual Studio Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.

*GitHub*: All my web app code is stored and versioned this GitHub repository.

*AWS CodeArtifact*: Once it's rolled out, CodeArtifact will store my artifades and dependencies, which is great for high availability and speeding up my project's build process.

*AWS CodeBuild*: Once it's rolled out, CodeBuild will take over my build process. It'll compile the source code, run tests, and produce ready-to-deploy software packages automatically.

*AWS CodeDeploys*: Once it's rolled out, CodeDeploy will automate my deployment process across EC2 instances.

*AWS CodePipeline*: Once it's rolled out, CodePipeline will automate the entire process from Github to CodeDeploy, integrating build,test, and deployment steps into one efficient workflow.
<br>

## Setup
To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
```
bash
git clone https://github.com/SnehaAA02/nextwork-web-project.git
```
2. Navigate to the project directory:
```
bash
cd nextwork-web-project
```
3. Install dependencies:
```
bash
mvn install
```
<br>

# Conclusion
Thank you for exploring this project! I'll continue to build this pipeline and apply my learnings to future projects.
A big shoutout to **[NextWork](https://learn.nextwork.org/app)** for their project support snd guidance.