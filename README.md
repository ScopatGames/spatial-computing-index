# AWS Spatial Computing Index Page

This page provides a single-source of discovery for spatial computing related AWS sample projects on Github.

## Contents
- [Projects](#projects)
    - [Amazon Visual Asset Management System](#amazon-visual-asset-management-system)
    - [NVIDIA Omniverse Nucleus on Amazon EC2](#nvidia-omniverse-nucleus-on-amazon-ec2)
    - [Amazon Polly with Epic Games Metahumans](#amazon-polly-with-epic-games-metahumans)
    - [Amazon Sumerian Hosts for Web3D](#amazon-sumerian-hosts-for-web3d)
    - [Deploying Unreal Engine Pixel Streaming Server on Amazon EC2](#deploying-unreal-engine-pixel-streaming-server-on-amazon-ec2)
    - [Amazon GameLift Unreal Engine](#amazon-gamelift-unreal-engine)
    - [Amazon GameLift Unity](#amazon-gamelift-unity)
    - [Amazon EC2 Cluster for Unreal Swarms](#amazon-ec2-cluster-for-unreal-swarms)
    - [Simple Game Studio on AWS](#amazon-ec2-cluster-for-unreal-swarms)
    - [Game Production in the Cloud Example Pipeline](#game-production-in-the-cloud-example-pipeline)
    - [AWS Gaming Unity Labs Sample](#aws-gaming-unity-labs-sample)
    - [AWS Spatial Computing Samples](#aws-spatial-computing-samples)
- [Security](#security)
- [License](#license-summary)

## Projects

### [Amazon Visual Asset Management System](https://github.com/awslabs/visual-asset-management-system)

Visual Asset Management System (VAMS) is a purpose-built, AWS native solution for the management and distribution of specialized visual assets used in spatial computing. VAMS offers a simplified solution for organizations to ingest, store, and manage visual assets in the cloud, which empowers any user with a web browser to upload, manage, visualize, transform, and retrieve visual assets. Existing workflows that leverage both custom code and pre-built or third-party applications can also be migrated to VAMS and ran in the AWS cloud, as opposed to being limited by the on-premise capacity available. VAMS is customizable and expandable with option of being further tailored to specific use-cases by development teams.

### [NVIDIA Omniverse Nucleus on Amazon EC2](https://github.com/aws-samples/nvidia-omniverse-nucleus-on-amazon-ec2)

NVIDIA Omniverse Nucleus is the database and collaboration engine that enables real-time exchange of USD data. With Omniverse Nucleus, you can connect multiple users working in their preferred 3D applications, providing a single source of truth for their 3D data. Nucleus operates under a publish-and-subscribe model and enables efficient live synchronization between Omniverse applications. It transmits changes to USD scenes in real-time between connected applications. This repository provides the steps and infrastructure for an Omniverse Enterprise Nucleus Server deployment on Amazon EC2.

### [Amazon Polly with Epic Games Metahumans](https://github.com/aws-samples/amazon-polly-metahumans)

This Unreal Engine sample project demonstrates how to bring Epic Games' MetaHuman digital characters to life using the Amazon Polly text-to-speech service from AWS. Use this project as a starting point for creating your own Unreal Engine applications that leverage Amazon Polly to give voice to your MetaHumans using one of 16 different English language voices spanning 5 dialects. Or extend this project to use any of Polly's 60+ voices covering 20+ languages and 13+ dialects.


### [Amazon Sumerian Hosts for Web3D](https://github.com/aws-samples/amazon-sumerian-hosts)

Amazon Sumerian Hosts (Hosts) is an experimental open source project that aims to make it easy to create interactive animated 3D characters for Babylon.js, three.js, and other web 3D frameworks. It leverages AWS services including Amazon Polly (text-to-speech) and Amazon Lex (chatbot).

### [Deploying Unreal Engine Pixel Streaming Server on Amazon EC2](https://github.com/aws-samples/deploying-unreal-engine-pixel-streaming-server-on-ec2)

Amazon Sumerian Hosts (Hosts) is an experimental open source project that aims to make it easy to create interactive animated 3D characters for Babylon.js, three.js, and other web 3D frameworks. It leverages AWS services including Amazon Polly (text-to-speech) and Amazon Lex (chatbot).

### [Amazon GameLift Unreal Engine](https://github.com/aws-samples/amazon-gamelift-unreal-engine)

This sample is for those who use Unreal Engine 4 to build content and wish to deploy this content to an audience via UE4 pixel streams. Content examples include but are not limited to: interactive entertainment, architectural visualization, high fidelity car configurators, or anyone who needs to let users access high quality interactive content via thin clients such as web browsers.

### [Amazon GameLift Unity](https://github.com/aws-samples/amazon-gamelift-unity)

This sample code shows how to set up a basic GameLift server and client for games using the Unity Game Engine. It consists of a Unity project that has been configured to be built in two ways, as a SERVER or a CLIENT. In CLIENT configuration, the preprocessor symbol CLIENT is defined. In SERVER configuration, the preprocessor SERVER is defined. 

### [Amazon EC2 Cluster for Unreal Swarms](https://github.com/aws-samples/ec2-cluster-for-unreal-swarms)

This example allows you to run Unreal Swarm cluster on AWS. The CDK or Cloudformation templates create a new VPC for the Swarm EC2 instances to run in and it also uses EC2 Image Builder to automatically create a custom AMI as the base for your cluster. It also creates a S3 bucket where you will upload the Unreal Engine 4 dependencies packaged into a ZIP archive. This S3 bucket is also used as destination for EC2 Image Builder logs.

### [Simple Game Studio on AWS](https://github.com/aws-samples/simple-game-studio-on-aws)

With this CDK application, you can easily build a simple and customizable game studio on AWS. The default setting covers a build farm, a source code repository, CI tool, workstation, and backups. If you are suffered from long build time, build farm management, slow response from CI tool, this project could help your time.

### [Game Production in the Cloud Example Pipeline](https://github.com/aws-samples/game-production-in-the-cloud-example-pipeline)

Quickly deploy a Cloud Game Development environment for you and your team, with this AWS Sample. Once deployed, you will have high performance virtual workstation, central version control system, and acceleration of compute heavy tasks by distributing the work to other machines on demand. 

The CDK (or CloudFormation templates) creates a new AWS Virtual Private Cloud (VPC), a customizable virtual workstation, a Perforce Helix Core server, and an Unreal Engine 4 Swarm cluster. The latter can be used to accelerate Unreal Engine 4 lighting builds using the vast compute resources available in AWS.

### [AWS Gaming Unity Labs Sample](https://github.com/aws-samples/aws-gaming-unity-labs-sample)

This repository contains a sample Unity game project that is used by several Self Paced Labs to demonstrate the use of the AWS Mobile SDK for Unity.

### [AWS Spatial Computing Samples](https://github.com/aws-samples/aws-spatial-computing-samples)

This repository contains sample code for Spatial Computing applications on AWS

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License Summary

The documentation is made available under the Creative Commons Attribution-ShareAlike 4.0 International License. See the [LICENSE](./LICENSE) file.
