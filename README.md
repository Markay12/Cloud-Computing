![Cloud](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fimg14.deviantart.net%2Fe2eb%2Fi%2F2014%2F247%2Fa%2F3%2Fcloud_01_png_by_heroys-d7xym3w.png&f=1&nofb=1)

# Table of Contents
1. Cloud Service Models
2. Cloud Visibilities

---
---

With Operating Expenses, the user is responsible for the computing resources that are used  


## Cloud Service Models

1. IaaS : Infrastructure-as-a-Service
	
	* Close to managing a physical server; cloud provider (Microsoft) will keep hardware here up-to-date. However, operating system maintenence and network configuration is up to the user

	* Setting up a new virtual machine is quicker than procuring, installing and configuring a physical server

2. PaaS : Platform-as-a-Service
	
	* Managed hosting environment. Cloud provider manages the vm's and networking resources, user deploys their application to the managed hosting environment

	* Upload your web application without worrying if you personally have enough resources

3. SaaS : Software-as-a-Service

	* Cloud provider manages all aspects of the application environment (vm's, network resources, data storage and applications). The user only needs to add input

	* Program running online that only asks for your user data

![Cloud Models](https://docs.microsoft.com/en-us/learn/azure-fundamentals/fundamental-azure-concepts/media/iaas-paas-saas-expanded.png#lightbox)


## IaaS - Infrastructure as a Service

The most flexible, giving complete control over the hardware running the application. 

* You don't have to buy the hardware, only rent it

### Advantages

1. **No CapEx** Users will have no upfront costs
2. **Agility** Applications can be made accessible quickly and deprovisioned whenver needed
3. **Management** user manages and maintains the services they provisioned, cloud provider manages and maintains the cloud infrastructure
4. **Consumption-Based Model** Organizations pay for what they want to use and work under the OpEx model
5. **Flexibility** IaaS is the most flexible giving the user control to configure and manage the hardware of the application



## PaaS - Platform as a Service

Additional benefits and downsides from IaaS

### Advantages

1. **No CapEx** Users will have no upfront costs
2. **Agility** PaaS is quicker than IaaS, as users do not need to configure servers for running applications
3. **Consumption-Based Model** Organizations pay for what they want to use and work under the OpEx model
4. **Cloud Benefits** Take advantage of the skills and expertise of the cloud provider to ensure workloads are secure and available. 
5. **Productivity** Allows for greater productivity because the cloud provider handles platform management

### Disadvantages

However, this PaaS as some **Platform limitations** which may affect how the program will run. 

## SaaS - Software as a Service

Software that is centrally hosted and managed for users and customers. One version for all users that is licensed through a subscription (Microsoft Online, Google Drive, etc...)

### Advantages

1. **No CapEx** Users will have no upfront costs
2. **Agility** Users provide staff with access quickly and easily
3. **Pay as you Go** a model that allows the user to pay for software that they will use. Different models of payment for different things. Yearly, monthly subscription or 5Gb - 10Gb - 20Gb etc.. of data

By far the greatest advantage here and with most of these is flexibility to access the same application from anywhere

### Disadvantages

**Software Limitations** Software as-is, we don't have direct control over features. Consider what is being given and work with what you can. Find the right software

## What is serverless computing?

* Like PaaS, serverless computing enables developers to build applications faster by eliminating the need for them to manage infrastructure. 

With serverless applications, the cloud service provider automatically provisions, scales, and manages the infrastructure required to run the code. Serverless architectures are highly scalable and event-driven, only using resources when a specific function or trigger occurs.

# Cloud Visibility

## Public, Private and Hybrid Clouds

### Public Cloud

Services are offered over the public internet and available to anyone that would like to purchase it  
Cloud resources (servers, storage) are owned and operated by a third party and delivered over the internet

* A great example of this would be Google Drive where you can create and share files but do not handle the storage. This follows our SaaS model

### Private Cloud

Private consists of computing resources used exclusively by users from a business or organization  
This is managed by the organization it belongs to or by a third party provider used only for this organization

### Hybrid Cloud

Combines these two by allowing data and applications to be shared between them

![Cloud Computing](https://docs.microsoft.com/en-us/learn/azure-fundamentals/fundamental-azure-concepts/media/cloud-computing-continuum.png)



