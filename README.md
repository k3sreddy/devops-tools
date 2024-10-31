# Curated List of Best DevOps Tools for 2024

A curated collection of the most effective and popular DevOps tools to streamline your development and operations processes for 2024

This repository aims to provide a comprehensive list of DevOps tools, along with brief descriptions. Whether you're new to DevOps or looking to optimize your existing workflow, you'll find valuable resources here.

## Contributing

✍️ We welcome contributions! If you know of a great DevOps tool that's not listed here, please submit a pull request with your addition.! Read the [contribution guidelines](https://github.com/techiescamp/devops-tools/blob/main/CONTRIBUTING.md) to know more. 

## Hit the Star! :star:

If you are planning to use this repo for reference, please hit the star. Thanks!

## Table of Contents

- [Development Environment Tools](#development-environment-tools)
- [Source Code Management](#source-code-management)
- [Build Tools](#build-tools)
- [Continuous Integration Tools](#continuous-integration-tools)
- [Artifact Management Tools](#artifact-management-tools)
- [Code Analysis Tools](#code-analysis-tools)
- [Continuous Delivery & GitOps Tools](#continuous-delivery--gitops-tools)
- [Infrastructure Provisioning Tools](#infrastructure-provisioning-tools)
- [Cloud Cost Management Tools](#cloud-cost-management-tools)
- [Configuration Management Tools](#configuration-management-tools)
- [Secret Management Tools](#secret-management-tools)
- [Config/Service Discovery Tools](#configservice-discovery-tools)
- [Containerization Tools](#containerization-tools)
- [Container Orchestration Tools](#container-orchestration-tools)
- [Container Autoscaling and Load Balancing](#container-autoscaling-and-load-balancing)
- [Container Security Tools](#container-security-tools)
- [Policy Management Tools](#policy-management-tools)
- [Service Mesh Tools](#service-mesh-tools)
- [Logging Tools](#logging-tools)
- [Monitoring & Observability Tools](#monitoring--observability-tools)
- [Visualization Tools](#visualization-tools)
- [Internal Developer Platform Tools](#internal-developer-platform-tools)
- [API Tools](#api-tools)
- [Collaboration Tools](#collaboration-tools)
- [Backups and Restoration Tools](#backups-and-restoration-tools)
- [Cloud Providers](#cloud-providers)

## Development Environment Tools

Development environment tools are essential for maintaining consistency in software configurations and versions. They ensure reproducibility in minutes in case of a crash, increasing developer productivity.

* **[Virtual Box](https://www.virtualbox.org/)** (Open Source): A powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use.
* **[Qemu](https://www.qemu.org/)** (Open Source): A generic and open source machine emulator and virtualizer.
* **[Vagrant](https://www.vagrantup.com/)** (Open Source): A tool for building and managing virtual machine environments in a single workflow.
* **[Docker Desktop](https://www.docker.com/products/docker-desktop)** (Open Source): An application for MacOS and Windows machines for the building and sharing of containerized applications.
* **[Minikube](https://minikube.sigs.k8s.io/)** (Open Source): A tool that makes it easy to run Kubernetes locally.
* **[Minishift](https://www.okd.io/minishift/)** (Open Source): A tool that helps you run OpenShift locally by running a single-node OpenShift cluster inside a VM.
* **[Podman Desktop](https://podman.io/)** (Open Source): A daemonless container engine for developing, managing, and running OCI Containers on your Linux System.
* **[Rancher Desktop](https://rancherdesktop.io/)** (Open Source): Rancher Desktop is a tool that enables developers to manage and deploy Kubernetes clusters effortlessly on their local machines.
* **[kind](https://kind.sigs.k8s.io/)** (Open Source): kind is a tool that uses Docker containers as nodes to facilitate the creation of local Kubernetes cluster primarly used for local development and testing.
* **[k3d](https://k3d.io/)** (Open Source): k3d is a lightweight wrapper to run k3s in Docker and makes it easy to create single and multi-node k3s clusters.

## Source Code Management

In the DevOps world, everything is treated as code (e.g., code, shell script, configurations, etc.). Robust source code management tools are a must.
* **[Github](https://github.com/)** (Free & Paid): A web-based hosting service for version control using Git. It offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features.
* **[Bitbucket](https://bitbucket.org/)** (Free & Paid): A web-based version control repository hosting service owned by Atlassian, for source code and development projects that use either Mercurial or Git revision control systems.
* **[Gitlab](https://about.gitlab.com/)** (Free & Paid): A web-based DevOps lifecycle tool that provides a Git-repository manager providing wiki, issue-tracking and CI/CD pipeline features, using an open-source license.
* **[AWS CodeCommit](https://aws.amazon.com/codecommit/)** (Free & Paid): A fully-managed source control service that makes it easy for companies hosting their own repositories to collaborate on code in a secure and highly scalable ecosystem.
* **[Google Cloud Source Repositories](https://cloud.google.com/source-repositories)** (Free & Paid): Fully-featured, scalable, private Git repositories hosted on Google Cloud.
* **[Azure Repos](https://azure.microsoft.com/en-us/services/devops/repos/)** (Free & Paid): Provides Git repositories or Team Foundation Version Control (TFVC) for source control of your code.
* **[Codeberg](https://codeberg.org/)** (Free & Paid): Cloud-based instance of Forgejo.
* **[Forgejo](https://forgejo.org/)** (Open Source): Open-source fork of Gitea.
* **[Fossil](https://fossil-scm.org/home/doc/trunk/www/index.wiki)** (Free): Open-source distributed SCM that includes a wiki, issue management, and other features. Not compatible with git.
* **[Gitea](https://about.gitea.com/)** (Open Source, Free, Paid Support Available): Open-source fork of Gogs.
* **[Gogs](https://gogs.io/)** (Open Source): Open-source git-based SCM, loosely based on Github's UI.


## Build Tools

Build tools are essential for automating package creation or deployable artifacts.

* **[Maven](https://maven.apache.org/)** (Java) (Open Source): A software project management and comprehension tool, primarily used for Java projects.
* **[Gradle](https://gradle.org/)** (Java, Kotlin, Groovy, Scala, Python, C++) (Free & Paid): An open-source build automation system that builds upon the concepts of Apache Ant and Apache Maven.
* **[npm](https://www.npmjs.com/)** (Javascript): A package manager for JavaScript, used to install, share, and distribute code.
* **[pnpm](https://pnpm.io/)** (Open Source): A fast, disk space efficient package manager for JavaScript.
* **[yarn](https://yarnpkg.com/)** (Open Source): A fast, reliable, and secure dependency manager for JavaScript and TypeScript.
* **[Rake](https://ruby.github.io/rake/)** (Ruby) (Open Source): A software task management and build automation tool for Ruby.
* **[MSBuild](https://github.com/dotnet/msbuild)** (.Net) (Open Source): The build platform for .NET and Visual Studio.
* **[Pybuilder](https://pybuilder.io/)** (Python) (Open Source): A software build tool written in pure Python mainly for Python applications.

## Continuous Integration Tools

Continuous Integration provides continuous feedback on code integrations, helping solve issues faster and decreasing time in software release cycles.

* **[Jenkins](https://www.jenkins.io/)** (Open Source): An open-source automation server, helps to automate parts of the build, test, and deployment process. Java-based, with Groovy-based pipeline definition.
* **[Github Actions](https://github.com/features/actions)** (Free & Enterprise): A CI/CD solution that integrates with GitHub repositories to run a series of commands automatically.
* **[Gitlab CI](https://docs.gitlab.com/ee/ci/)** (Free & Enterprise): A continuous integration service included with GitLab that builds and tests the software whenever the developer pushes code to the application. YAML-based pipelines. Can be self-hosted or use the cloud offering.
* **[CircleCI](https://circleci.com/)** (Free & Paid): YAML-based CI/CD hosted in the cloud.
* **[Drone](https://www.drone.io/)** (Free & Paid): YAML-based CI/CD that is container-first. Can self-host or use the cloud version.
* **[TeamCity](https://www.jetbrains.com/teamcity/)** (Free & Enterprise): A build management and continuous integration server from JetBrains.
* **[Travis CI](https://travis-ci.org/)** (Open Source): A cloud-based continuous integration service that automatically builds and tests code changes in GitHub repositories.
* **[Bamboo](https://www.atlassian.com/software/bamboo)** (Free & Enterprise): A continuous integration and deployment tool that ties automated builds, tests, and releases together in a single workflow.
* **[RazorOps CICD](https://razorops.com/)** (Free & Paid): YAML-based CI/CD that is container-first SaaS cloud version and On-Prems with large Enterprise.
* **[Buildkite](https://buildkite.com/)** (Free & Paid): YAML-based CI/CD.
* **[DeployBot](https://www.deploybot.com/)** (Free & Paid): A cloud-based CI/CD service that supports building, deploying and automating any project.

## Artifact Management Tools

Artifact management tools store and version code/binary that has to be deployed into production. They centralize repositories specifically made for this purpose.

* **[Nexus](https://www.sonatype.com/nexus/repository-oss)** (Free & Enterprise): A repository manager that allows you to proxy, collect, and manage your dependencies.
* **[Jfrog Artifactory](https://jfrog.com/artifactory/)** (Enterprise): An enterprise-grade universal binary repository manager solution that could handle end-to-end artifact management.
* **[npm](https://www.npmjs.com/)** (Free): A package manager for JavaScript, used to install, share, and distribute code.
* **[Nuget](https://www.nuget.org/)** (.Net) (Free): A free and open-source package manager for the Microsoft development platform.

## Code Analysis Tools

Code analysis tools are a crucial component of any DevOps toolkit. They scrutinize the code before deployment, pinpointing potential issues. This allows developers to enhance the quality of the software by making necessary modifications.

Code analysis can be categorized into two types:

* **Static Analysis (SAST)** – This method inspects the source code without executing it, identifying bugs, security vulnerabilities, and quality issues.
* **Dynamic Analysis (DAST)** – This approach involves running the code to uncover performance bottlenecks and behavioral anomalies.

Here are some notable tools in this category:

* **[Sonarqube](https://www.sonarqube.org/)** (Free & Enterprise): SonarQube offers a comprehensive suite for continuous code quality inspection. It automates reviews with static code analysis to detect bugs, code smells, and security vulnerabilities.
* **[Checkmarx](https://www.checkmarx.com/)** (Enterprise): Checkmarx is a leading solution in software security, adept at identifying, tracking, and rectifying both technical and logical security flaws in the source code.
* **[PMD](https://pmd.github.io/)** (Open Source): PMD is a versatile static code analyzer. It can detect a wide range of programming flaws across multiple languages.
* **[Acunetix](https://www.acunetix.com/)** (Enterprise): Acunetix is a proprietary web vulnerability scanner capable of autonomously crawling and scanning web applications to identify diverse security concerns. It comes under DAST tools.

## Continuous Delivery & GitOps Tools

Continuous Delivery is more of an approach rather than a toolset, aiming to ensure that software can be reliably and immediately deployed at any time. While there's no specific tool labeled solely for continuous delivery, several process-oriented tools can be leveraged to achieve this goal within your projects.

GitOps, a subset of DevOps, uses Git as a single source of truth for declarative infrastructure and applications. Here are some prominent tools that align with Continuous Delivery and GitOps principles:

* **[Jenkins](https://www.jenkins.io/)** (Open Source): A widely-used open-source automation server that supports building, deploying, and automating any project.
* **[Argo CD](https://argoproj.github.io/argo-cd/)** (Open Source): A declarative, GitOps continuous delivery tool for Kubernetes.
* **[Flux CD](https://fluxcd.io/)** (Open Source): A tool that automates the deployment of containers to Kubernetes, following the GitOps principles.
* **[Go CD](https://www.gocd.org/)** (Open Source): An open-source continuous delivery server designed to model and visualize complex workflows.
* **[Gitlab CD](https://docs.gitlab.com/ee/ci/)** (Free & Enterprise): GitLab's continuous delivery solution, allowing automated deployment and monitoring of applications.
* **[Weave GitOps](https://www.weave.works/oss/gitops/)** (Enterprise): An enterprise-grade GitOps solution, providing a set of best practices for deploying and managing applications and infrastructure.
* **[Jenkins X](https://jenkins-x.io/)** (Open Source): An open-source project that provides automated CI/CD for Kubernetes, with preview environments and promotion across environments.
* **[Tekton](https://tekton.dev/)** (Open Source): A powerful and flexible open-source framework for creating CI/CD systems, allowing developers to build, test, and deploy across cloud providers and on-premises systems.

## Infrastructure Provisioning Tools

Infrastructure provisioning tools play a vital role in automating the setup of computing infrastructure. This includes the creation and management of virtual machines, networks, storage, and various cloud resources. By automating these processes, these tools enable more efficient and consistent infrastructure deployment.

Here are some of the leading tools in this category:

* **[Terraform](https://www.terraform.io/)** (Open Source & Enterprise): Terraform is an open-source tool that allows you to define and provision a datacenter infrastructure using a declarative configuration language. It supports various cloud providers and offers an enterprise version with additional features.
* **[Pulumi](https://www.pulumi.com/)** (Open Source & Enterprise): Pulumi provides a way to create, deploy, and manage infrastructure using programming languages you already know. It offers both open-source and enterprise solutions.
* **[CloudFormation](https://aws.amazon.com/cloudformation/)** (AWS Service): An AWS service that helps you model and set up Amazon Web Services resources. It allows you to use a template to describe all the AWS resources you need, automating the provisioning process.
* **[Azure Resource Manager](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview)** (Azure Service): Azure Resource Manager enables you to work with the resources in your solution as a group. You can deploy, update, or delete all the resources for your solution in a single, coordinated operation.
* **[Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/)** (Azure Service): Azure Bicep is a simple and user-friendly domain-specific language (DSL) for describing Azure cloud resources. It helps to create, deploy, and manage Azure resources more easily and efficiently compared to traditional ARM templates. Bicep simplifies the process by offering a cleaner and more concise syntax, making it quicker to write and maintain Azure infrastructure code.
* **[opentofu](https://opentofu.org/)** (Open Source): OpenTofu is an infrastructure as code tool that lets you define both cloud and on-prem resources in human-readable configuration files that you can version, reuse, and share. You can then use a consistent workflow to provision and manage all of your infrastructure throughout its lifecycle. OpenTofu can manage low-level components like compute, storage, and networking resources, as well as high-level components like DNS entries and SaaS features.

## Backups and Restoration Tools
Backup and restoration tools helps in making periodic copies of data and applications to a separate, secondary device and then using those copies to recover the data and applications.

* **[Velero](https://velero.io/)** (Open Source ): Velero is an open source tool to safely backup and restore, perform disaster recovery, and migrate Kubernetes cluster resources and persistent volumes.
* **[Kasten K10](https://www.kasten.io/)** (Free & Enterprise): Kasten K10 is a data management platform that provides robust Kubernetes backup and disaster recovery solutions for seamless containerized application deployment and data protection.
* **[Cloudcasa](https://cloudcasa.io/)** (Free & Enterprise): CloudCasa is a cloud-native backup and disaster recovery solution designed to protect and manage data for Kubernetes applications seamlessly.

## Cloud Cost Management Tools

Cloud Cost Management Tools help organizations monitor, analyze, and optimize their cloud spending. By providing insights into resource utilization and cost allocation, these tools enable better budgeting and cost control. Here's a list of tools that can be used for Cloud Cost Management:

* **[InfraCost](https://www.infracost.io/)** (Open Source): InfraCost provides cost estimates for Terraform projects, helping developers understand the cost implications of their infrastructure code.
* **[Kubecost](https://www.kubecost.com/)** (Open Source): Kubecost gives you visibility into your Kubernetes usage and cost, allowing you to monitor and optimize your cluster resources.

## Configuration Management Tools

Configuration management tools are pivotal in both application and infrastructure deployment. They assist in managing the state of servers and applications, ensuring that configurations are applied consistently and idempotently. By automating these configurations, these tools enhance the reliability and efficiency of deployment processes.

Here's a look at some of the widely-used configuration management tools:

* **[Ansible](https://www.ansible.com/)** (Open Source & Enterprise): Ansible is a versatile automation tool that can handle configuration management, application deployment, and task automation. It uses a simple, human-readable language, allowing for easy adoption.
* **[Chef](https://www.chef.io/)** (Open Source & Enterprise): Chef is a powerful automation platform that transforms complex infrastructure into code, automating how infrastructure is configured, deployed, and managed across your network.
* **[Puppet](https://puppet.com/)** (Open Source & Enterprise): Puppet is designed to manage the configuration of Unix-like and Microsoft Windows systems declaratively. It provides a way to automate repetitive tasks, quickly deploy critical applications, and proactively manage infrastructure.
* **[Saltstack](https://www.saltstack.com/)** (Open Source & Enterprise): SaltStack is an intelligent IT automation platform that can manage, secure, and optimize any infrastructure. It's built on a unique and responsive remote execution engine, allowing for control over thousands of systems with no performance degradation.

## Secret Management Tools

Secret management tools are essential for safeguarding sensitive information such as passwords, API keys, and other credentials. They provide a secure way to store, distribute, and manage secrets, ensuring that they are accessible only to authorized entities.

Here are some popular secret management tools:

* **[HashiCorp Vault](https://www.vaultproject.io/)** (Open Source & Enterprise): Vault is a tool for securely accessing secrets such as API keys, passwords, or certificates. It provides a unified interface to any secret while providing tight access control and recording a detailed audit log.
* **[External Secrets Operator](https://github.com/external-secrets/kubernetes-external-secrets)** (Open Source): An extension for Kubernetes that allows you to securely manage secrets stored in managed cloud services
* **[AWS Secrets Manager](https://aws.amazon.com/secrets-manager/)**: A service that helps you protect access to your applications, services, and IT resources without the upfront investment and on-going maintenance costs of operating your own infrastructure.
* **[Google Cloud Secret Manager](https://cloud.google.com/secret-manager/)**: A fully managed service on Google Cloud Platform to handle sensitive data like API keys, passwords, and certificates. It provides robust security and convenient access controls.
* **[Azure Key Vault](https://azure.microsoft.com/en-us/services/key-vault/)**: A cloud service provided by Microsoft to securely manage keys, secrets, and certificates.
* **[Teller](https://tlr.dev/)** (Open Source): Teller is a secret management tool for developers enhancing productivity by supporting cloud-native applications and managing secrets across multiple cloud providers.

## Config/Service Discovery Tools

Config and Service Discovery Tools are vital in distributed systems, allowing applications to manage configuration data dynamically and discover services without hard-coded hostnames or ports. These tools provide a centralized repository for configuration and service information, ensuring consistency and availability.

Here are some popular tools in this category:

* **[Consul](https://www.consul.io/)** (Open Source & Enterprise): Consul is a tool for discovering and configuring services in your infrastructure. It provides key/value storage and multi-datacenter support, ensuring high availability and scalability.
* **[Etcd](https://etcd.io/)** (Open Source): A distributed key-value store that provides a reliable way to store data across a cluster of machines. It's primarily used in distributed systems to hold configuration data that needs to be available to all nodes in the cluster.
* **[Apache ZooKeeper](https://zookeeper.apache.org/)** (Open Source): A centralized service for maintaining configuration information, naming, providing distributed synchronization, and group services.
* **[Eureka](https://github.com/Netflix/eureka)** (Open Source): A REST-based service that is primarily used in the AWS cloud for locating services for the purpose of load balancing and failover of middle-tier servers.

## Containerization Tools

Containerization Tools enable the encapsulation of an application and its dependencies into a 'container.' This ensures that the application runs the same way, regardless of where it's deployed. By isolating the application in a container, these tools provide a consistent environment that's abstracted from the host system.

Here are some popular tools in this category:

* **[Docker](https://www.docker.com/)** (Open Source & Enterprise): Docker is a platform that enables developers to create, deploy, and run applications in containers. It's widely used for its ease of use and integration with various orchestration tools.
* **[Podman](https://podman.io/)** (Open Source): Podman is a daemonless container engine for developing, managing, and running OCI Containers on your Linux System. It provides a Docker-CLI-compatible command-line front end and can use many of the same commands.
* **[Buildah](https://buildah.io/)** (Open Source): Buildah is a tool that facilitates building OCI container images. It's a complementary tool to Podman and allows for more fine-grained control over image creation and management.
* **[rkt](https://github.com/rkt/rkt)** (Open Source): An application container engine developed for modern production cloud-native environments, emphasizing simplicity, security, and composability.
* **[CRI-O](https://cri-o.io/)** (Open Source): CRI-O is a lightweight container runtime specifically for Kubernetes. It allows Kubernetes to use any OCI-compliant runtime as the container runtime for running pods. It provides an optimized performance for Kubernetes workloads and is known for its simplicity and reliability.


## Container Orchestration Tools

With the widespread adoption of containerization technologies like Docker, Container Orchestration Tools have become indispensable in microservices-based deployments. These tools manage the lifecycle of containers within clusters, automating tasks such as deployment, scaling, networking, and availability.

Here are some of the leading tools in this category:

* **[Kubernetes](https://kubernetes.io/)** (Open Source): Kubernetes is the de facto standard in container orchestration. It automates the deployment, scaling, and management of containerized applications across clusters of hosts.
* **[OpenShift](https://www.openshift.com/)** (Open Source & Enterprise): OpenShift is a Kubernetes-based container platform that provides developer and operational tools. It extends Kubernetes by adding features such as a web console, monitoring, logging, and more.
* **[Nomad](https://www.nomadproject.io/)** (Open Source & Enterprise): Nomad is a flexible and easy-to-use orchestrator to deploy and manage containers and non-containerized applications. It integrates seamlessly with popular DevOps tools and provides a lightweight solution for container orchestration.
* **[k3s](https://k3s.io/)** (Open Source): k3s is a certified Kubernetes distribution which is highly available and designed for resource-constrained production workloads.

## Container Autoscaling and Load Balancing

Here’s a list of open-source tools for container autoscaling and load balancing:

* **[KEDA](https://keda.sh/)** (Open Source): (Kubernetes Event-driven Autoscaling) - Automatically scales Kubernetes workloads based on external events.
* **[MetalLB](https://metallb.universe.tf/)** (Open Source): -  A load balancer implementation for bare-metal Kubernetes clusters.

## Container Security Tools

* **[Docker Bench](https://github.com/docker/docker-bench-security)** (Open Source): A script that checks for common best-practices around deploying Docker containers in production.
* **[Clair](https://github.com/quay/clair)** (Open Source): A vulnerability analysis tool for containers that inspects containers before they are deployed.
* **[Anchore Engine](https://anchore.com/opensource/)** (Open Source): A service that analyzes and inspects containers for security vulnerabilities and policy issues.
* **[AquaSec](https://www.aquasec.com/)** (Enterprise): A container security platform that provides full lifecycle security for containerized applications.
* **[Notary](https://github.com/theupdateframework/notary)** (Open Source): A project that allows anyone to have trust over arbitrary collections of data.
* **[Falco](https://falco.org/)** (Open Source): A behavioral activity monitor designed to detect anomalous activity in applications.
* **[Trivy](https://github.com/aquasecurity/trivy)** (Open Source): A simple and comprehensive vulnerability scanner for containers.
* **[Twistlock](https://www.paloaltonetworks.com/prisma/cloud)** (Enterprise): Twistlock is an innovator in container security. During runtime, Twistlock scans container images for known vulnerabilities in the software packages and libraries they contain. It's new name is Prisma Cloud.

## Policy Management Tools

Policy Management Tools enable organizations to define, enforce, and manage security policies across their cloud-native environments. They provide a framework for policy definition and evaluation, ensuring compliance with organizational and regulatory requirements.

* **[Open Policy Agent](https://www.openpolicyagent.org/)** (Open Source): A general-purpose policy engine that unifies policy enforcement across the stack.
* **[Kyverno](https://kyverno.io/)** (Open Source): A policy engine designed for Kubernetes, providing validation, mutation, and generation of configurations.
* **[Cloud Custodian](https://cloudcustodian.io/)** (Open Source): A rules engine for managing public cloud accounts and resources.

## Service Mesh Tools

Service Mesh Tools provide a dedicated infrastructure layer for handling service-to-service communication. They make it easy to build and deploy resilient, secure, and observable microservices.

* **[Istio](https://istio.io/)** (Open Source): An open platform to connect, manage, and secure microservices, providing a uniform way to secure, connect, and monitor microservices.
* **[Linkerd](https://linkerd.io/)** (Open Source & Enterprise): A service mesh that gives you observability, reliability, and security without requiring any code changes.
* **[Cilium Service Mesh](https://cilium.io/)**: A next-generation service mesh for transparently securing, observing, and connecting Kubernetes workloads across complex, heterogeneous environments.

## Logging Tools

For any production environment, logging and monitoring for infrastructure & application components are a must-have to avoid system failures and application downtime. Here is the list of tools you could use for your projects:

* **[ELK Stack](https://www.elastic.co/elastic-stack)** (Open Source & Enterprise): A combination of Elasticsearch, Logstash, and Kibana, used for searching, analyzing, and visualizing log data in real-time.
* **[Grafana Loki](https://grafana.com/oss/loki/)** (Open Source and Enterprise): A horizontally scalable, highly available, multi-tenant log aggregation system inspired by Prometheus.
* **[Fluentd](https://www.fluentd.org/)** (Open Source): An open-source data collector for unified logging layers.
* **[Graylog](https://www.graylog.org/)** (Open Source & Enterprise): A leading centralized log management solution for capturing, storing, and enabling real-time analysis of terabytes of machine data.
* **[logz.io](https://logz.io/)** (Enterprise): A cloud-native logging and security platform that enables engineers to use the best open-source tools in the market without the complexity of operating them.
* **[Splunk](https://www.splunk.com/)** (Enterprise): A platform for searching, monitoring, and examining machine-generated big data.
* **[Syslog-ng](https://www.syslog-ng.com/)** (Enterprise): A flexible and highly scalable logging solution enabling you to centralize your log data and sort it in real-time.

## Monitoring & Observability Tools

Monitoring & Observability Tools provide insights into the performance, availability, and overall health of applications, infrastructure, and business processes. They enable proactive monitoring, alerting, and troubleshooting, ensuring optimal performance and reliability.

* **[Prometheus](https://prometheus.io/)** (Open Source): An open-source monitoring and alerting toolkit designed for reliability and scalability.
* **[Thanos](https://thanos.io/)** (Highly Available Prometheus Open Source Tool): A set of components that can be composed into a highly available metric system with unlimited storage capacity.
* **[Cilium](https://cilium.io/)** (Open Source & Enterprise): eBPF-based Networking, Security, and Observability.
* **[Falco](https://falco.org/)** (Open Source & Enterprise): Cloud Native Runtime Security.
* **[Calico](https://www.projectcalico.org/)** (Open Source & Enterprise): Pluggable eBPF-based networking and security for containers and Kubernetes.
* **[Sensu](https://sensu.io/)** (Open Source & Enterprise): A comprehensive monitoring solution for your entire infrastructure and application stack.
* **[Riemann](http://riemann.io/)** (Open Source): A powerful stream processing language that helps you compose, test, and distribute data streams.
* **[Nagios](https://www.nagios.org/)** (Free & Enterprise): A powerful monitoring system that enables organizations to identify and resolve IT infrastructure problems.
* **[Zabbix](https://www.zabbix.com/)** (Open Source & Enterprise): An enterprise-class open-source distributed monitoring solution.
* **[Middleware](https://middleware.io/)** (Free & Enterprise): A full-stack observability platform that offers a free developer account with all features and a paid plan for higher limits/usage.
* **[Data Dog](https://www.datadoghq.com/)** (Enterprise): A monitoring and analytics platform for large-scale applications.
* **[New Relic](https://newrelic.com/)** (Enterprise): A cloud-based platform that gives developers, engineers, operations, and management a clear view of what’s happening in today’s complex software environments.
* **[App Dynamics](https://www.appdynamics.com/)** (Enterprise): An application performance management solution that uses machine learning and artificial intelligence to provide real-time visibility and insight into IT environments.
* **[Sumologic](https://www.sumologic.com/)** (Enterprise): A cloud-native, machine data analytics platform that delivers real-time, continuous intelligence.
* **[Dynatrace](https://www.dynatrace.com/)** (Enterprise): An AI-powered, full-stack, automated performance management solution.
* **[HolmesGPT](https://github.com/robusta-dev/holmesgpt)** (Open Source): An Open Source alert investigation assistant capable of solving alerts like a human. Works with Prometheus alerts, Jira tickets and more.

## Visualization Tools

* **[Grafana](https://grafana.com/)** (Open Source & Enterprise): A leading open-source platform for monitoring and observability, allowing you to query, visualize, alert on, and understand your metrics.
* **[Kibana](https://www.elastic.co/kibana)** (Open Source & Enterprise): A free and open user interface that lets you visualize your Elasticsearch data and navigate the Elastic Stack.
* **[Tableau](https://www.tableau.com/)** (Enterprise): A leading data visualization and business intelligence platform that helps people see and understand their data.
* **[Meshery](https://meshery.io/)** (Open Source): An amazing open-source platform that enables collaborative design and operation of cloud-native infrastructure. Meshery let’s you visually configure and deploy all kinds of Kubernetes-based tools.

## Internal Developer Platform Tools

Platform engineering is becoming a core part of every organization that wants to adopt DevOps. Internal developer platforms or IDP tools play a key part in platform engineering. The following are the key tools that can be used for IDP:

* **[Backstage.io by Spotify](https://backstage.io/)** (Open Source): An open platform for building developer portals, providing a unified frontend for all your infrastructure tooling, services, and documentation.
* **[Port.io](https://www.getport.io/)** (Free & Enterprise): A platform that enables teams to build, test, and deploy applications with ease.
* **[Configure8](https://www.configure8.com/)** (Free & Paid): A platform that provides a unified interface for managing infrastructure as code.
* **[Cortex](https://www.cortex.dev/)** (Enterprise): An enterprise-grade platform that simplifies the deployment, scaling, and management of machine learning models.
* **[Opslevel](https://www.opslevel.com/)** (Enterprise): A platform that provides insights and automation for your microservices and cloud resources.

## API Tools

* **[Postman](https://www.postman.com/)** (Free & Enterprise): A collaboration platform for API development.
* **[Hoppscotch](https://hoppscotch.io/)** (Open Source): Open-source API development Ecosystem.
* **[SoapUI](https://www.soapui.org/)** (Open Source & Enterprise): The world's leading automated testing tool for SOAP and REST APIs.
* **[Swagger](https://swagger.io/)** (Open Source & Enterprise): A framework for API specification that includes a suite of tools for auto-generating documentation, code generation, and API testing.
* **[HTTPie](https://github.com/httpie/cli)** (Open Source): HTTPie (pronounced aitch-tee-tee-pie) is a command-line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible
 
## Collaboration Tools

The following are the collaboration tools that you could use in your DevOps toolchain. These tools support both messaging and video calling:

* **[Slack](https://slack.com/)** (Free & Paid): A collaboration hub that connects your work with the people you work with.
* **[Cisco Webex Teams](https://www.webex.com/team-collaboration.html)** (Free & Paid): A collaboration app that helps you create, meet, message, call, whiteboard, and share, regardless of whether you’re together or apart.
* **[Flock](https://flock.com/)** (Free & Paid): A communication and collaboration platform designed to boost productivity and foster teamwork.
* **[Google Hangouts](https://hangouts.google.com/)** (Free & Paid): A communication platform that includes messaging, video chat, and VOIP features.
* **[Flow Dock](https://www.flowdock.com/)** (Paid): A team collaboration app for desktop, mobile, and web, working seamlessly alongside your existing tools.

## Planning & Project Management Tools

Following are the planning tools that you could use in your DevOps toolchain:

* **[Jira](https://www.atlassian.com/software/jira)** (Free/Paid): A popular project management tool for agile teams.
* **[Trello](https://trello.com/)** (Free/Paid): A collaboration tool that organizes your projects into boards.
* **[Asana](https://asana.com/)** (Free/Paid): A web and mobile application designed to help teams organize, track, and manage their work.
* **[Backlog.com](https://backlog.com/)** (Free/Paid): A project management and collaboration tool for teams that want higher productivity.
* **[Monday.com](https://monday.com/)** (Paid): A work operating system that powers teams to run projects and workflows with confidence.
* **[ClickUp](https://clickup.com/)** (Free/Paid): A cloud-based productivity and project management platform that supports document management. It helps teams collaborate, organize tasks, and streamline workflows, making it easy to store, organize, and collaborate on various documents and files.


## IDE Tools

* **[Visual Studio Code](https://code.visualstudio.com/)** (Free): A free source-code editor made by Microsoft.
* **[Sublime Editor](https://www.sublimetext.com/)** (Free): A sophisticated text editor for code, markup, and prose.
* **[Notepad++](https://notepad-plus-plus.org/)** (Free): A free source code editor and Notepad replacement.

## Bug/Issue Tracking Tools

Bug and issue-tracking tools are a must for any team dealing with code. Here is the list of tools you might want to have a look at:

* **[Backlog](https://backlog.com/)** (Free & Paid): A project management and collaboration tool with bug tracking capabilities.
* **[Bugzilla](https://www.bugzilla.org/)** (Open Source): A server software designed to help you manage software development.
* **[Jira](https://www.atlassian.com/software/jira)** (Free & Paid): Also used for bug tracking, workflow, and issue tracking.
* **[Lean Testing](https://leantesting.com/)** (Free): A free bug tracking and test case management platform.
* **[Mantis](https://www.mantisbt.org/)** (Free): A free web-based bug tracking system.

## Test Automation/Performance Testing Tools

Another important pillar in the CI/CD pipeline is test automation tools. The following are the automation/performance testing tools that top our list:

* **[Selenium](https://www.selenium.dev/)**: A suite of tools to automate web browsers.
* **[UFT](https://software.microfocus.com/software/uft)**: Unified Functional Testing tool for automated functional testing.
* **[Appium](http://appium.io/)**: An open-source tool for automating native, mobile web, and hybrid applications.
* **[Jmeter](https://jmeter.apache.org/)**: An open-source software to test performance both on static and dynamic resources.
* **[Blazemeter](https://www.blazemeter.com/)**: A continuous testing platform for performance testing, monitoring, and more.
* **[Tosca](https://www.tricentis.com/products/automate-continuous-testing-tosca)**: A software testing tool that leverages the TOSCA standard. Tricentis Tosca is an enterprise-level, continuous testing platform that uses model-based test automation to enable accelerated testing.

## Centralized Documentation Management tools

Documentation is an essential aspect of the DevOps culture, facilitating effective collaboration, knowledge management, and overall efficiency in the software development and delivery process. Here is the list of tools you might want to have a look at:

* **[Confluence](https://www.atlassian.com/software/confluence)** (Free & Paid): A collaborative team workspace and wiki-based content management system developed by Atlassian. It is designed to facilitate team collaboration, knowledge sharing, and project documentation within organizations.
* **[Clickup](https://clickup.com/)** (Paid): A cloud-based productivity and project management platform that supports document management. It helps teams collaborate, organize tasks, and streamline workflows, making it easy to store, organize, and collaborate on various documents and files.

## Cloud Providers

Cloud service provider is an information technology (IT) company that provides its customers with computing resources over the internet and delivers them on-demand. CSPs are well-suited for organizations and individuals who don’t want the responsibility of installing software, hardware or network resources — and maintaining them until the end of their life cycles.

* **[AWS](https://aws.amazon.com/what-is-aws/?tag=zd-buy-button-20&ascsubtag=562e79c5abd747da9bae194058a83395%7C70d884bc-9915-4d12-a556-f163e55b789b%7Cdtp)**: World’s most comprehensive and broadly adopted cloud, offering over 200 fully featured services from data centers globally.
* **[Microsoft Azure](https://azure.microsoft.com/en-us/?ranMID=24542&ranEAID=IokOf8qagZo&ranSiteID=IokOf8qagZo-guCnXD6ZPOcQ_KmYuaJ8vQ&epi=IokOf8qagZo-guCnXD6ZPOcQ_KmYuaJ8vQ&irgwc=1&OCID=AIDcmm549zy227_aff_7593_1243925&tduid=%28ir__snsycwhcbgkfd3nmh1j3kz3w0n2xeqhvfdev32mm00%29%287593%29%281243925%29%28IokOf8qagZo-guCnXD6ZPOcQ_KmYuaJ8vQ%29%28%29&irclickid=_snsycwhcbgkfd3nmh1j3kz3w0n2xeqhvfdev32mm00)**: The Azure cloud platform is more than 200 products and cloud services designed to help you bring new solutions to life.
* **[Google Cloud Platform](https://cloud.google.com/?hl=en)** (GCP): A suite of cloud computing services offered by Google. Its technical offerings range from infrastructure and platform services to computing power and database hosting.
* **[IBM](https://www.ibm.com/cloud)**: It has one of the most in-depth and highly developed portfolios of enterprise solutions of any provider across the tech sector. As a cloud provider, it has a global footprint offering its IaaS and PaaS solutions from data centers from all over the world.
* **[Oracle](https://www.oracle.com/cloud/)**: It specializes in developing and marketing computer hardware systems and enterprise-grade software products. It offers a wide range of cloud-based database solutions including its own database-as-a-service offering.


Production Kubernetes Cluster with Complete DevOps Setup
Infrastructure Requirements
plaintext
VerifyOpen In EditorEditCopy code
1Nodes Configuration:
2- 3 Master Nodes: 4 CPU, 16GB RAM, 50GB SSD
3- 4 Worker Nodes: 4 CPU, 16GB RAM, 50GB SSD
4- 1 DevOps Node: 4 CPU, 16GB RAM, 50GB SSD
5- 2 HAProxy Nodes: 4 CPU, 16GB RAM, 50GB SSD
1. Base System Configuration (All Nodes)
bash
VerifyOpen In EditorEditCopy code
1# System Update
2dnf update -y
3dnf install -y epel-release
4dnf install -y vim wget curl net-tools
5
6# Hostname Setup
7hostnamectl set-hostname <node-role>-<number>
8
9# Configure /etc/hosts
10cat >> /etc/hosts << EOF
11192.168.1.10 lb01
12192.168.1.11 lb02
13192.168.1.20 master01
14192.168.1.21 master02
15192.168.1.22 master03
16192.168.1.30 worker01
17192.168.1.31 worker02
18192.168.1.32 worker03
19192.168.1.33 worker04
20192.168.1.40 devops
21192.168.1.50 registry
22EOF
23
24# Disable SELinux
25setenforce 0
26sed -i 's/^SELINUX=.*/SELINUX=disabled/' /etc/selinux/config
27
28# Disable Swap
29swapoff -a
30sed -i '/swap/d' /etc/fstab
31
32# Load Kernel Modules
33cat > /etc/modules-load.d/k8s.conf << EOF
34overlay
35br_netfilter
36EOF
37modprobe overlay
38modprobe br_netfilter
39
40# Kernel Parameters
41cat > /etc/sysctl.d/k8s.conf << EOF
42net.bridge.bridge-nf-call-iptables  = 1
43net.bridge.bridge-nf-call-ip6tables = 1
44net.ipv4.ip_forward                 = 1
45EOF
46sysctl --system
2. Container Runtime Installation (All Nodes except HAProxy)
bash
VerifyOpen In EditorEditCopy code
1# Install Containerd
2dnf config-manager --add-repo=https://download.docker.com/linux/centos/docker-ce.repo
3dnf install -y containerd.io
4
5# Configure Containerd
6mkdir -p /etc/containerd
7containerd config default > /etc/containerd/config.toml
8sed -i 's/SystemdCgroup = false/SystemdCgroup = true/' /etc/containerd/config.toml
9
10# Start Containerd
11systemctl enable containerd
12systemctl restart containerd
3. HAProxy Setup (Load Balancer Nodes)
bash
VerifyOpen In EditorEditCopy code
1# Install HAProxy
2dnf install -y haproxy
3
4# Configure HAProxy
5cat > /etc/haproxy/haproxy.cfg << EOF
6global
7    log /dev/log local0
8    log /dev/log local1 notice
9    daemon
10
11defaults
12    log global
13    mode tcp
14    option tcplog
15    option dontlognull
16    timeout connect 5000
17    timeout client 50000
18    timeout server 50000
19
20frontend kubernetes
21    bind *:6443
22    mode tcp
23    option tcplog
24    default_backend kubernetes-backend
25
26backend kubernetes-backend
27    mode tcp
28    option tcp-check
29    balance roundrobin
30    server master01 192.168.1.20:6443 check fall 3 rise 2
31    server master02 192.168.1.21:6443 check fall 3 rise 2
32    server master03 192.168.1.22:6443 check fall 3 rise 2
33EOF
34
35# Start HAProxy
36systemctl enable haproxy
37systemctl restart haproxy
4. Kubernetes Installation (All Nodes except HAProxy)
bash
VerifyOpen In EditorEditCopy code
1# Add Kubernetes Repository
2cat > /etc/yum.repos.d/kubernetes.repo << EOF
3[kubernetes]
4name=Kubernetes
5baseurl=https://packages.cloud.google.com/yum/repos/kubernetes-el7-\$basearch
6enabled=1
7gpgcheck=1
8gpgkey=https://packages.cloud.google.com/yum/doc/yum-key.gpg https://packages.cloud.google.com/yum/doc/rpm-package-key.gpg
9EOF
10
11# Install Kubernetes Components
12dnf install -y kubelet kubeadm kubectl
13systemctl enable kubelet
14systemctl start kubelet
5. Initialize Kubernetes Cluster (First Master Node)
bash
VerifyOpen In EditorEditCopy code
1# Initialize Control Plane
2kubeadm init --control-plane-endpoint "192.168.1.10:6443" \
3    --upload-certs \
4    --pod-network-cidr=10.244.0.0/16
5
6# Configure kubectl
7mkdir -p $HOME/.kube
8cp -i /etc/kubernetes/admin.conf $HOME/.kube/config
9chown $(id -u):$(id -g) $HOME/.kube/config
10
11# Install Calico CNI
12kubectl apply -f https://docs.projectcalico.org/manifests/calico.yaml
6. Join Other Masters and Workers
bash
VerifyOpen In EditorEditCopy code
1# On other master nodes
2kubeadm join 192.168.1.10:6443 --token <token> \
3    --discovery-token-ca-cert-hash sha256:<hash> \
4    --control-plane --certificate-key <key>
5
6# On worker nodes
7kubeadm join 192.168.1.10:6443 --token <token> \
8    --discovery-token-ca-cert-hash sha256:<hash>
7. Private Registry Setup
bash
VerifyOpen In EditorEditCopy code
1# Install Packages
2dnf install -y podman
3
4# Create Certificates
5mkdir -p /opt/registry/{auth,certs,data}
6openssl req -newkey rsa:4096 -nodes -sha256 \
7    -keyout /opt/registry/certs/domain.key \
8    -x509 -days 365 -out /opt/registry/certs/domain.crt
9
10# Create Registry Auth
11htpasswd -bBc /opt/registry/auth/htpasswd admin <password>
12
13# Run Registry
14podman run -d \
15    --name registry \
16    -p 5000:5000 \
17    -v /opt/registry/data:/var/lib/registry \
18    -v /opt/registry/auth:/auth \
19    -v /opt/registry/certs:/certs \
20    -e "REGISTRY_AUTH=htpasswd" \
21    -e "REGISTRY_AUTH_HTPASSWD_REALM=Registry" \
22    -e "REGISTRY_AUTH_HTPASSWD_PATH=/auth/htpasswd" \
23    -e "REGISTRY_HTTP_TLS_CERTIFICATE=/certs/domain.crt" \
24    -e "REGISTRY_HTTP_TLS_KEY=/certs/domain.key" \
25    docker.io/library/registry:2
8. DevOps Tools Installation (DevOps Node)
bash
VerifyOpen In EditorEditCopy code
1# Install Jenkins
2dnf install -y java-11-openjdk-devel
3wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
4rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
5dnf install -y jenkins
6systemctl enable jenkins
7systemctl start jenkins
8
9# Install SonarQube
10dnf install -y unzip java-11-openjdk-devel
11wget https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-9.x.zip
12unzip sonarqube-9.x.zip -d /opt
13mv /opt/sonarqube-9.x /opt/sonarqube
14useradd sonar
15chown -R sonar:sonar /opt/sonarqube
16systemctl start sonarqube
17
18# Install Argo CD
19kubectl create namespace argocd
20kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
21
22# Install Trivy
23dnf install -y trivy
9. Jenkinsfile Configuration
groovy
VerifyOpen In EditorEditCopy code
1pipeline {
2    agent any
3    environment {
4        ARGOCD_AUTH_TOKEN = credentials('argocd-auth-token')
5    }
6    stages {
7        stage('Checkout') {
8            steps {
9                git 'your-repo-url'
10            }
11        }
12        stage('Security Scan') {
13            steps {
14                sh 'trivy fs .'
15                sh 'sonar-scanner'
16            }
17        }
18        stage('Build') {
19            steps {
20                sh 'docker build -t python-app .'
21            }
22        }
23        stage('Container Scan') {
24            steps {
25                sh 'trivy image python-app'
26            }
27        }
28        stage('Push') {
29            steps {
30                sh 'docker push <registry-url>/python-app'
31            }
32        }
33        stage('Update Manifests') {
34            steps {
35                sh '''
36                    git clone https://github.com/your-org/gitops-repo.git
37                    cd gitops-repo
38                    # Update image tag in deployment yaml
39                    sed -i "s|image: .*|image: <registry-url>/python-app:${BUILD_NUMBER}|" kubernetes/manifests/deployment.yaml
40                    git config --global user.email "ci@example.com"
41                    git config --global user.name "CI"
42                    git add kubernetes/manifests/deployment.yaml
43                    git commit -m "Update image to ${BUILD_NUMBER}"
44                    git push
45                '''
46            }
47        }
48        stage('Sync Argo CD') {
49            steps {
50                sh '''
51                    argocd login <argocd-server> --auth-token $ARGOCD_AUTH_TOKEN --insecure
52                    argocd app sync python-app
53                    argocd app wait python-app
54                '''
55            }
56        }
57    }
58}
10. Argo CD Application Configuration
yaml
VerifyOpen In EditorEditCopy code
1# example-application.yaml
2apiVersion: argoproj.io/v1alpha1
3kind: Application
4metadata:
5  name: python-app
6  namespace: argocd
7spec:
8  project: default
9  source:
10    repoURL: 'https://github.com/your-org/your-repo.git'
11    path: kubernetes/manifests
12    targetRevision: HEAD
13  destination:
14    server: 'https://kubernetes.default.svc'
15    namespace: python-app
16  syncPolicy:
17    automated:
18      prune: true
19      selfHeal: true
20    syncOptions:
21    - CreateNamespace=true
11. GitOps Repository Structure
plaintext
VerifyOpen In EditorEditCopy code
1gitops-repo/
2├── kubernetes/
3│   ├── manifests/
4│   │   ├── deployment.yaml
5│   │   ├── service.yaml
6│   │   ├── ingress.yaml
7│   │   └── configmap.yaml
8│   └── applications/
9│       └── python-app.yaml
10└── README.md
12. Argo CD Notifications (Optional)
yaml
VerifyOpen In EditorEditCopy code
1# notifications-config.yaml
2apiVersion: v1
3kind: ConfigMap
4metadata:
5  name: argocd-notifications-cm
6  namespace: argocd
7data:
8  trigger.on-sync-succeeded: |
9    - when: app.status.operationState.phase in ['Succeeded']
10      send: [slack]
11  template.slack: |
12    message: |
13      Application {{.app.metadata.name}} has been synchronized successfully.
14      Revision: {{.app.status.sync.revision}}
15  service.slack: |
16    token: $slack-token
17    channel: deployments
13. Argo CD RBAC Configuration (Optional)
yaml
VerifyOpen In EditorEditCopy code
1# rbac-config.yaml
2apiVersion: v1
3kind: ConfigMap
4metadata:
5  name: argocd-rbac-cm
6  namespace: argocd
7data:
8  policy.csv: |
9    p, role:developers, applications, get, */*, allow
10    p, role:developers, applications, sync, */*, allow
11    g, developer-group, role:developers
This comprehensive guide provides a complete production-ready Kubernetes cluster with a full DevOps setup, including Jenkins, SonarQube, Trivy, and Argo CD. It covers infrastructure requirements, base system configuration, Kubernetes installation, private registry setup, and DevOps tools installation. Additionally, it provides configuration files for Jenkins, Argo CD, and GitOps repository structure.

![image](https://github.com/user-attachments/assets/3d559cdf-221b-4215-8e76-6ce3501e1a50)

