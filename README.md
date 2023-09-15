# divyanshujain11-Research_or_industry_use_cases_of_Openshiftt

![image](https://github.com/divyanshujain11/divyanshujain11-Research_or_industry_use_cases_of_Openshiftt/assets/77712311/dc9b6922-26dc-45f2-8786-a98b5839cda5)


**✔️ What is OpenShift Used For?**
OpenShift is a cloud development Platform as a Service (PaaS) developed by Red Hat. It is an open-source development platform that enables developers to build and deploy their applications on cloud infrastructure. In addition, it is very helpful in developing cloud-enabled services.

**✔️How Does OpenShift Work?**
OpenShift is a Kubernetes-based container platform developed by Red Hat for building, deploying, and managing containerized applications. It provides a comprehensive set of tools and services to simplify container orchestration, application scaling, and continuous integration and deployment (CI/CD) processes. Here’s an overview of how OpenShift works:

**1.Containerization:**
OpenShift relies on container technology, primarily Docker, to package applications and their dependencies into lightweight, isolated containers. Containers ensure consistency and portability across different environments, from development to production.

**2. Kubernetes Orchestration:**
OpenShift uses Kubernetes as its container orchestration engine. Kubernetes is responsible for deploying and managing containers, scaling applications, and ensuring high availability. OpenShift enhances Kubernetes with additional features and tools.

**3. Cluster Management:** 
OpenShift manages Kubernetes clusters, abstracting much of the underlying complexity. It simplifies cluster provisioning, scaling, and maintenance, making it easier to operate and manage containerized workloads.

**4. Developer Tools:**
OpenShift provides various developer-centric tools to streamline the development and deployment process, including:

**Source-to-Image (S2I):**
This feature allows developers to build container images directly from source code, making it easy to create containerized applications without needing in-depth knowledge of Dockerfiles or containerization.
Integrated Developer Environments (IDEs): OpenShift can be integrated with popular IDEs like Visual Studio Code, enabling developers to write, test, and debug code within the OpenShift environment.
Developer Catalog: OpenShift provides a catalog of pre-configured application templates and services, simplifying the process of deploying common application stacks.
**5. Application Lifecycle Management:**
OpenShift offers tools for continuous integration and continuous deployment (CI/CD) pipelines. You can automate the building, testing, and deployment of containerized applications, ensuring a smooth application lifecycle.

**6. Security and Compliance:**
OpenShift emphasizes security by providing features like role-based access control (RBAC), network policy enforcement, image scanning for vulnerabilities, and the ability to isolate applications in separate namespaces.

**7. Service Discovery and Load Balancing:**
OpenShift uses Kubernetes services to enable service discovery and load balancing. This allows applications to communicate with each other seamlessly and ensures high availability by distributing

**OpenShift — Architecture**
OpenShift is a layered system wherein each layer is tightly bound with the other layer using Kubernetes and Docker cluster. The architecture of OpenShift is designed in such a way that it can support and manage Docker containers, which are hosted on top of all the layers using Kubernetes. Unlike the earlier version of OpenShift V2, the new version of OpenShift V3 supports containerized infrastructure. In this model, Docker helps in creation of lightweight Linux-based containers and Kubernetes supports the task of orchestrating and managing containers on multiple hosts.

![image](https://github.com/divyanshujain11/divyanshujain11-Research_or_industry_use_cases_of_Openshiftt/assets/77712311/b386b88d-ddfe-4822-8f7c-e77750c59d4e)

**OpenShift Use Cases (Case Studies).**
Many organizations are opting OpenShift and making use of it to the best of their abilities. So let’s have a quick look at OpenShift Use Cases as per industrial requirements.

**Red Hat OpenShift Container Platform on IBM Z and IBM LinuxONE**

![image](https://github.com/divyanshujain11/divyanshujain11-Research_or_industry_use_cases_of_Openshiftt/assets/77712311/9d3931fa-0cf5-456b-93af-9ccbd8b4cd02)


**Clients business reasons for RHOCP on IBM Z and IBM LinuxONE**
✓ It solves the business problem :Faster time to market, perfect for dynamic workloads

✓ It solves the development challenges :Develop once deploy multiple (CI/CD & DevSecOps)

✓ It enables new ways for hybrid IT projects :Best fit placement for applications

✓ It helps in the Digitalization journey : Global integration with standards and openness

✓ Confidential computing is closer than ever : Secure workloads and Digital Asset Management

✓ Business Continuity is empowered :Inherit availability and stability form IBM Z

**Use case Overview:** 
Red Hat OpenShift Container Platform on IBM Z

![image](https://github.com/divyanshujain11/divyanshujain11-Research_or_industry_use_cases_of_Openshiftt/assets/77712311/b21466cf-684d-442b-9d72-3f9cc098c2ae)


**Ideal Use Cases for RHOCP on IBM Z and IBM LinuxONE**
**Data gravity on IBM Z:**
Take advantage of the IBM Z and IBM LinuxONE platform in a co-location implementation of containerized applications with traditional workloads, like Data lakes, Enterprise databases, transactional services, or other traditional workloads running in Linux on IBM Z or z/OS. The operational advantages of co-located applications and data will optimize:
latency
response time
deployment
end-2-end security from input request, secure execution, secure data processing, encrypted data in flight and on rest
coordinated service and cost
Functional advantages:

enable cloud-native applications close to Systems of Record and enterprise databases
RHOCP integration with REST services and data in z/OS, bidirectional with z/OS Connect EE
High scalability of RHOCP applications integrate with core enterprise databases on Linux on IBM Z and IBM LinuxONE (for example PostgreSQL, MongoDB, DB2, Oracle)
Extend existing core systems with Open Source software and cloud services
Automation of Core Backend (Cloud Broker)
2. Application Development Consistency :

With RHOCP on IBM Z and IBM LinuxONE you can develop once and take advantage of:

cross architecture portability
DevSecOps to deploy on the most securable platform
enabling / disabling and shifting compute capacity
Functional advantages:

develop with the tools of your choice
build the application containers for all platforms using cross architecture build pipelines
CI/CD and automation cross architectures
deploy on the platform of choice using defined criteria or conditions
dynamic workload distribution based on SLA rules
3. Consolidation and TCO Reduction : Consolidating a RHOCP environment to IBM Z and IBM LinuxONE, has economic and operational advantages. The 3-dimension scalability, vertical, horizontal and combined results in a high flexibility without new hardware footprint for dynamic workloads and unpredicted growth.

4. Blockchain and Digital Asset Management :

Blockchain Platform V2.1.3 includes:

RHOCP on LinuxONE and Linux on IBM Z as part of a Multicloud network management
Deploy Blockchain components: peer, orderer, and certificate authority
Integrated hardware security module (HSM) support using PKCS 11
Improved multiorganization resilience with the Raft consensus protocol
Ansible support for simplified network configuration and management
Blockchain Platform extension for Visual Studio Code for development
5. Business Continuity :

Functional advantages:

internal networks deliver high scalability, speed and reliability
highest predictability vs. on distributed servers
Latency between LPARs is much more predictable vs many servers in a network
z/VM SSI / LGR for planned service windows
allocation of resources on demand
dynamically changing of resources — flexibility and shift of resources based on priority and availability
dynamic workload distribution based on SLA rules
Cisco uses OpenShift
To keep up with customer demand, Cisco, a leading provider of network solutions, needs to rapidly implement new IT products and solutions. The challenge is keeping your IT team engaged and productive to drive innovation. With help from Red Hat, Cisco developed its Lightweight Application Environment (LAE), which runs on the Red Hat OpenShift Container Platform, a Platform as a service (PaaS) technology formerly known as Red Hat’s OpenShift Enterprise.


**Challenge faced by Cisco:**
Cisco’s ability to quickly offer innovative IT products and solutions to clients is critical to its success. Delays can cost a firm money. Cisco needed to keep its 1,000+ developers actively engaged in creating and implementing apps to encourage speed to market and boost satisfaction while avoiding high employee turnover, low productivity, and delayed reaction times.

![image](https://github.com/divyanshujain11/divyanshujain11-Research_or_industry_use_cases_of_Openshiftt/assets/77712311/6453ef1f-b9da-4ef0-b184-2c5e32655ff6)


**How did they tackle this:**
Cisco entrusted Red Hat with the design and development of its LAE, a PaaS deployment that supports hundreds of apps that power a wide range of business operations. Developers can use the IT resources they need to develop apps through a self-service platform, which eliminates manual provisioning.

**Result:**
Project provisioning used to take up to three months for Cisco developers. Now, the developers simply press a button, and the service is supplied in a matter of… minutes. Customers will benefit from the speedier delivery of innovative products and services as a result of increased productivity. The approach relieves pressure on limited IT resources and allows developers to devote more time to creative projects.

Thank You……….








