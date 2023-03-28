# Cloud Computing Fundamentals
## What is Cloud Computing?
The delivery of a shared pool of on-demand computing services over the public internet, that can be rapidly provisioned and released with minimal management effort or service provider interaction.

## 5 Characteristics of Cloud
- **On-demand Self Service:** Provision resources automatically without requirung human interaction
- **Broad Network Access:** Available over the network.
- **Resource Pooling:** Pooled resources to support a multi-tenant model allowing multiple customers to share the same applications or the same physical infrastructure.
- **Rapid Elasticity:** Rapidly provision and de-provision any of the cloud computing resources.
- **Measured Service:** Resource usage can be monitored, controlled and reported using metering capabilities.

## Cloud Deployment Models
- **Public Cloud:** A cloud that is offered over the public internet such as Google Cloud, AWS, Azure. 
- **Multi-Cloud:** A cloud deployment model where public clouds are connected and used together within a single environment for various use cases. 
- **Private Cloud:** Refers to architecture that exists on-premise and restricted to business itself with no public access. 
Each Clous Providers have their own flavour of Private Cloud.
    - GCP- Anthos
    - AWS- AWS Outposts
    - Azure- Azure Stack
- **Hybrid Cloud:** A single sytem used as a conjuction of public cloud and private cloud.

## Cloud Service Models
Commonly referred to as **XaaS**- standing for (anything-as-a-service).

### **Cloud Service Model Concepts**
Lets take an example of a data centre to understand the concept.
- **Traditional On-Premise** - All the components are managed by the customer, purchasing of data centre, all the network and storage involved, virtualization, purchasing/licensing of OS, staff needed for racking/stacking/cabling and physical security.
- **Infrastructure as a Service (IaaS)** - In this model, all the layers upto virtualization are taken care by the vendor.
    - Most basic model which is basically VMs in a cloud data centre.
    - Setup, configure and manage instances that run in the data centre.
    - In GCP, **Google Compute Engine** would satisfy this model. 
- **Platform as a Service (PaaS)** - In this model, cloud provider provides a computing platform typically including the operating system, the programming language execution environment, database and webserver. In GCP, example would be **Google App Engine**. 
- **Software as a Service (SaaS)** - All the layers taken care of by the vendor. G-Suite and Microsoft's 365 are great examples of this model. 

## Compute Service Options
- Complete control and flexibility
- Flexible container technology
- Managed application platform
- Serverless Environments


- Infrastructure as a service (IaaS): Google Compute Engine
- Container as a Service (CaaS): Google Kubernetes Engine (GKE)
- Platform as a Service (PaaS): Google App Engine
- Function as a Service (Faas): Google Functions 
