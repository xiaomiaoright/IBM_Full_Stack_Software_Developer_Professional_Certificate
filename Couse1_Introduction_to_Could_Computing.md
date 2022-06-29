# MODULE 1: Overview of Cloud Computing

## LESSON 1: Introduction to Cloud Computing

### Definition and essential characteristics of cloud computing

1. 5 Essential characteristics
   - On demand self-service
   - Broad Network access
   - REsource Pooling
     - Economies of scale
     - cost-efficient
     - Resources dynamically assigned based on demand
   - Rapid Elasticity
     - Access resources when needed and release when don't need
   - Measured Service
     - Pay for what used (utilization)

Cloud Computing as a Service (CssA) using technology as a service; leveraging remote system on-demand over internet

2. 3 Cloud Deployment Models

   - Public
   - Private
   - Hybrid

3. 3 Service Models

   - Three layers in computing stack:
     - Infrastructure(IaaS),
     - Platform,(PaaS)
     - Application(SaaS)

### A brief history and evolution of cloud

### Key considerations for cloud computing

- Agility
- Flexibility
- Competitiveness

1. Infrastructure and workloads -> Cost saving by pay as you go
2. SaaS and development platforms
3. SPeed and Productivity

### Key cloud service providers and their services

- Aliyun
- AWS
- Google Cloud Platform (GCP)
- IBM Cloud

## LESSON 2: Business case for Cloud Computing

### Cloud adoption - No longer a choice

### Cloud adoption - Some case studies

 

## LESSON 3: Emerging Technologies accelerated by cloud

### Internet of Things on the cloud

### Artificial Intelligence on the cloud

### Blockchain and Analytics on the cloud

 

# MODULE 2: Cloud Computing Models

## LESSON 1: Service Models

### Overview of cloud service models

1. IaaS: Leasing

   - IaaS Cloud Provide manages physical resources, data centers, cooling power, network and security, computing resources

2. PaaS: Renting
   - PaaS Cloud provider manager the platform infrasture, including: Operating system (OS), Development tools, Dtabases, Business Analytics
3. SaaS: Uber
   - SaaS cloud provider also manages and hosts: applications, data

### Infrastructure-as-a-Service

* A form of cloud computing that delivers fundamentals: compute, network, storage to consumers on-demand, over the internet, on a pay as you go basis.
* IaaS providers host INF components present in on premises data center and virtualization or hypervisor layer
* Customers create VMs, with abilities to track and monitor the performance and usage of their cloud services, and manage disaster recover
* IaaS Key components:
    * Physical data centers (physical machines)
    * Compute
    * Network: access virtually or through API
    * Storage: object storage
* Applications of IaaS
    * Test and development
        * set up test/dev. faster
        * help developer focusing on business logic than infrasture management
    * Business Coninuity and Disaster Recovery
        * make applications and data accessable during a disaster or outage
    * Faster Deployments and Scaling    
        * Deploy faster
        * Scale infrasture up and down as demand fluctuates
    * High performance computings
        * Solve complex problems involing millions of variables and calculations
        * weather prediction, financial modeling
    * Big Data Analysis
        * Patterns, trends, assocaitions requires huge amount of processing power
        * Cloud computing provide high performance and make it economically viable
* IaaS Concerns
    * Lack of transparency
    * dependency on third party

### Platform-as-a-Service

* PaaS: a cloud computing model that provides customers a complete platform to develop deploy, manage, and run applications created by them or acquired from a third party
* PaaS provider host and manage:
    * Servers
    * Networks
    * Storage
    * Operating systems
    * Application runtimes
    * APIS
    * Middleware
    * Databases
    * provider also responsible for installation, configuration, operation of application infrasture
        * User only responsible for application codes and maintainance
* IaaS provider offers access to raw computing resources: servers, storage, networking; Users responsible for the platform and application

* PaaS Characteristics:
    * high level of abstraction
        * Eliminate complexity of deploying applications
    * Support services and APIS
    * Run time environments
        * Excute codes according to application owner and cloud provider policies
    * Rapid deployment mechanisms
    * Middleware capabilities
        * supppor a range of application infrastructure capabilities
* Use cases:
    * API development and management
    * IoT
    * Business analytics and intelligences
    * Business Process Management 
    * Master data management
* Advantages:
    * Scalability
    * Faster time to market
    * greater agility and innovation
* Risks:
    * Information security threats
    * Dependency on service providers infrastructure
    * Customer lack control over changes in strategy, service offerings, or tools


### Software-as-a-Service
* SaaS is a cloud offering that provides access to a service provider's cloud based software
* SasS providers maintains: 
    * Servers
    * Databases
    * Application codes
    * security
* SaaS providers manage application:
    * Security
    * Availability
    * Performance
* SaaS supports:
    * Email and collaboration: office, gmail
    * Customer relationship mgt.: saleforce ...
    * human resource mgt. workda, SAP, etc
    * Financial mgt.
* Key characteristics
    * Multitenant architecture
    * Mng. privileges and monitor data
    * security, compliance, maintenance
    * customize applications
    * subscription model
    * scalable resources
* Key benefits:
    * Greatly reduce the time from decision to value
    * Increase workforce productivity and efficiency
        * users can access core business apps from anywhere
        * buy and deploy apps in minutes
    * Spread out software cost over time
* Use Cases:
    * Reduce on premises IT infrastructure and capital expenditures
    * avoid on going upgrades, maintenances, patching
    * run application with minimal input
    * manage websites, marketing, sales, etc
    * Gain resilience and business continuity of cloud provider
* COncerns:
    * Data ownership and safety
    * Third party maintains business critical data
    * needs good internet connection


## LESSON 2: Deployment Models
Deployment models indicate:

* where tehe infrastructure resides
* who owns and manages it
* how cloud resources and services are made available to users

### Public Cloud
* Providers owns, manages, provisions and maintains the infrastures
* Users using web consoles and APIs, users can provision the resources and services they need
    * Users do not own the servers their applications run on, or storage, or management operation
    * user like utilities
* Good
    * Cost savings!
    * esay scalibility
* Bad
    * use do not have any control over environment
* Public cloud characteristics
    * Multi tenants share computing resources
    * On demand resources
    * Economies of scale
    * highly reliable
* Concerns
    * Security
    * data soverignty compliance


### Private Cloud
* cloud infrastructure provisioned for exclusive use by a signle organization comprising multiple consumers. Owned managed by the organization a third party or some combination of them. on off promisis

* Internal Infras. on-premises, owned and managed by organization
* external Infrs. owned managed by service provider
* Virtual Private Cloud (VPC)
    * An external cloud that offers a private secure, computing environment in a shared public cloud

### Hybrid Cloud
* Connects an organizations' on premise private cloud and third party public cloud
* Felxibility
* Workloads move freely
* Choice of security and regulation features
* Benefits:
    * Interoperable
        * Pub. Priv. clouds understand each other's APIs
    * Scalable
        * private clouds can leverage public cloud capacity
    * Portable
* Types of hybrid clouds
    * Hybrid monocloud: one provider
    * Hybrid multicloud
    * Composite multicloud
* Use cases:
    * SaaS integration
    * Data & AI integration
    * Enhancing legacy apps
    * VMware migration


 

# MODULE 3: Components of cloud computing

## LESSON 1: Cloud Infrastructure

### Overview of cloud infrastructure
* Cloud Region
    * Multiple Availability Zone (AZ)
    * Have their own power, cooling, networking resurces
    * Isolation of zone improves the cloud's fault torerance, decreases latency and more
    * Very high bandwidth connectivity with other AZs, data centers, internet
* Data center is a huge room or a warehouse containing cloud infrastructure
    * Standarized containers of computing resources, servers, storage, networking equipment
* Coomputing Resources:
    * Cloud providers offer several compute options - 
        * Virtual Servers, 
            * Most of the servers in a cloud datacenter run hypevisors to create VM
            * Software based
        * Bare Metal Servers, 
            * Physical Servers that aren't virtualized
            * Cutomers can provision VMs and bare metals servers as and when they need them and run their workloads on them

        * Serverless computing resources
            * An abstraction layer on top of virtual machines
* Storage
    * Local storage: Default
        * Any info stored in a local drive can be lost when you delete or decomission a cloud server
    * Other cloud storage options
        * Tpyes
            * Block storage
            * File storage
            * Object storage
        * Features:
            * Block & File storage: traditional data centers
                *  Often struggle with scale, performance, and distributed characteristics of clouds
            * Obj storage: most common mode
                * Highly distributed and resilient
* Networking
    * Traditonal hardwares: routers, swithces
    * SDN: previsioned
        * public 
        * proviate interfaces
    * Network interfaces in the clouds need:
        * IP addresses
        * subnets
        * security groups
        * ACLs
        * VLANs
        * Firewalls
        * load balancers
        * gateways
        * traffic analyzers
        * CDNs



### Virtualization and Virtual Machines explained
* Hypervisor
    * A piece of software that runs above the physical server or host
    * Pull resources from physical server and allocate to vitual env.
* Types of hypervisors
    * Type 1 
        * INstalled directly on top of physical server
        * most frequently used, secure
    * Type 2 (hosted)
        * a layer of ost OS that sits between the physical server and the HV.
        * less frequently
* VM
    * Software based computer
    * Extremely portable
* Benefits:
    * Cost saving
    * Agility and speed
    * Lower your downtime

### Types of Virtual Machines
* Shared or public cloud VMs
    * Pre-defined sizes and configurations
        * Cores
        * RAM
        * Storage
            * Pricing options
    * Transient or Spot VMS
        * take adv. of unused capacity ina cloud data center
        * Good for:
            * non produc tion workloads
            * testing& developing
            * running stateless workloads, testing scalability
            * running big data and HPC worloads at a low cost
    * Reserved virtual serve instances
        * reserve capacity resouces for future deployments          
* Dedicated HOsts
    * Signle tenant isolation
    * Specify the data center and pod
    * allows max control over workload placement
    * used for meeting compliance & Regulatory requirements or lisencing terms


### Bare Metal Servers
* Signle-tenant dedicated physical server
* Cloud provider manages the server up to the OS
* Customer is responsible for adminitersing and managing everything else on the server
* Configuration 
    * Preconfigured by cloud provider or custom-configured as per customer specifications
        * Processors
        * RAM
        * Hard drives
        * Specializaed components
        * The OS
        * Install HV and create own VMS
        * Add GPUs
* Charateristics
    * Take longer to provision
    * min to hrs
    * more expensive than VMs
    * only offered by some cloud providers

* Workloads:
    * Fully customizable/demanding env.
    * Dedicated or long-term usage
    * High performance computing
    * Highly secure/isolated env.
    * Good for HPC/Bigdata/GPU intensive/ERP/AI
* Bare Metal servers vs. Virtual servers
    * Customer need
    * Bare Metal 
        * Work best for CPU and I/O intensive workloads
        * Excel with highest performance and security
        * satisfy strict compliance requirements
        * Offer complete flexibity contral and transparency
        * Come with aded management and operational overhead

    * VM
        * Repidly provisioned
        * provide an elastic & Scalable env
        * Low cost to use

### Secure Cloud Networking
* Cybersecurity threats
    * Could network vs. on premise data centers
        * Logical instances vs. physical devices
        * Networking functions as a Service vs. Networking equipment in physical racks
* How
    * Define the size of the network using IP address range
    * Cloud network deployed on networking spaces that are logically separated segments of the networks using options, including Virtual proviate cloud (VPC) that in turn can be divided into smaller segments called subnets
        * Logically segmented cloud networks are private carveout of the cloud that offer customers the security of private clouds and the scalability of public clouds. Cloud resources, such as VMs or Virtual Server Instances (VSIs), storage, network connectivity and load balancers are deployed into subnets.
        * Using subnets allows users to deploy enterprise applications using the same multi-tier concepts used in on-premises environments. 
        * Subnets are also the main area where security is implemented in the cloud. 
        * Every subnet is protected by Access Control Lists (ACLS) that serve as a subnet-level fire wall.
        *  Within the subnet, one could create Security Groups that provide security at the instance level such as VSIs. 
        * Once you build a subnet, then it is time to add some VSIs and storage to it so that you could run your applications. 
* Direct Connectivity

### Containers
* Containers do not need to include a guest OS in every instances because they leverage host OS
 

## LESSON 2: Cloud Storage and Content Delivery Networks

### Basics of cloud storage
* Compute node vs. public/private
* Cloud storage Host/Secure/Manage/Maintain infrustructure
* Pay for what used
* 4 types
    * Direct Attached
        * Local storage: within the same rack/fast/OS
        * temporary ephemeral/not shared/not resilient
    * File Storage
        * NFS storage
        * Connected to computing node
        * Slower
        * Lower cost
        * attached to multiple servers
    * Block Storage
        * Read/write fast speed
        * IOPS: how quickly can be read/written
        * Persistence
        * Snap short: a point in time image of the storage
    * Object Storage
        * access via API
        * SLowest
        * Cheapest
        * Infinite size


### File Storage
* LIke Directed attached storage, file storage has to be attached to a compute node to store data
* Unlike direct storage:
    * Less expensive
    * more resilient to failure
    * less disk management & maintenance for user
    * Provision much larger amounts of storage
* file sotrage is mounted from remote storage appliances
    * Resilient to failure
    * offer encryption
    * managed by service provider
* File storage mounted on compute nodes via ethernet networks
    * File Storage is mounted to compute nodes via an ethernet network – the same kind of network that you might receive email or browse the internet over, although this ethernet network is normally dedicated to the task. 
    * ‘Network Attached Storage’, ‘Network File Storage’   ‘NFS
    * Speeds vary based on network traffice
    * consistent speed cannot be guaranteed. Therefore, File storage tends to be used for workloads where consistently high network speeds are not a requirement. 
* Multiple Compute Nodes
    * mounted more than one compute node
    * Common workloads
        * Department file share
        * Loading zone for incoming files
        * Repository of files
            * ie speed variance not issue
        * Low cost database storage
* IOPS
    * speed at which the disk can write and read data
    
### Block Storage
* Block storage breaks files into chunks or blocks of data
* Stores each block separately under a unique address
* must be attached to a compute node
* Features;
    * Mounted from remote storage appliances
    * extremely resilient to failure
    * data is more secure
* Mounted as a volume to compute nodes using a dedicated network of optical fibres
    * signals move at the speed of light
    * Higher price point
    * for worklaods that need low latency
    * only one compute node a time
    * consistent high spped
    * databases and mail servers
    * not suitable for shared storage between multiple servers
* IOPS
    * SPecifify
    * adjust as needed
    * Depending on requirements and usage behaviors

* Common attributes of file and block storage
    * Block and file storage is taken from appliances which are maintained by the service provider
    * Both are highly available and resilient
    * Often include data encryption at rest and in transit
 * Differences: file vs. block
    * Attached via ethernet network vs. atached via high speed fibre network
    * speed vary based on loads vs.
    * can attach to multiple compute nodes at once vs. only attach to one node at a time
    * Good for file shares(fast connectivity not required/cost sensitive) vs good for appplication require consistent fast access to disk
    * workload IOPS required for both
### Object Storage Overview
1. can be used without connecting to particular compute node to use it
    * use API
2. less expensive than other storages
    * effectively infinite
* When to use?
    * large amount of unstructured state
    * Bucket- meta data
        * no need of sizing information
        * add data slowly or quickly
* Manageged by service provider
* Resilience options
    * only stored in one data centre vs. stored multiple times in different data centres
* Store any types of data
* Not suitable for operation systems, databases, changing content
### Object Storage - Tiers and APIs
* Tiers/Classes based on how frequently the data is accessed
* Standard tier bucket: frequently accessed data/high cost
* Vault/archive tier: lower frequenct
* Cold vault tier
* automatic archiving rules
* Speed: not IOPS options
    * Slower
* important to keep data in the correct tier
* API, S3 API (AWS) S3 compatible - HTTP based RESTful
* Back solutions/diaster recovery
    * Replacement for offiste backups


### Content Delivery Networks
* Driven by Object Storage 
* distributed server network that delivers temporarily stored, or cached, copies of website content to users, based on the user's geographic location
* Make website faster
* reduction of load in the local server
* local server increased uptime
* increased security
# MODULE 4: Emergent trends & practices

## LESSON 1: Hybrid Multicloud, Micorservices, and Serverless

### Hybrid Multicloud

### Microservices

### Serverless Computing

 

## LESSON 2: Cloud Native, DevOps, and Application Modernization

### Cloud Native

### DevOps on the cloud

### Application Modernization

 

# MODULE 5: Cloud Security and Monitoring, Case Studies, and Jobs

## LESSON 1: Cloud Security and Cloud Monitoring

### What is cloud security - Part 1

### What is cloud security - Part 2

### Identity and Access Management

### Cloud encryption

### Cloud monitoring - Basics and benefits

 

## LESSON 2: Case Studies and Job Roles

### Case studies in different industry verticals

### Career opportunities and job roles in cloud computing

 
