# AZ-900: Describe Cloud Concepts (15-20%)

## Describe the benefits and considerations of using cloud services

* Describe terms such as:
    * [High Availability](https://docs.microsoft.com/en-us/azure/architecture/checklist/availability)
        - not likely your app becomes unavailable because of high SLA and resource redundancy
        - Azure promises high-uptime in their SLAs
        - availability sets and availability zones help with VM uptime
    * Scalability
        - up your CPU processing power, data storage whenever necessary
    * [Elasticity](https://azure.microsoft.com/en-ca/overview/what-is-elastic-computing/)
        - scale up or scale down as needed
        - pay for what you use
        - scale sets add/remove VMs as needed
    * Agility
        - quickly deploy new resources
    * Fault Tolerance
        - use redundancy to keep your data and apps safe from local disasters or server/datacenter failures
    * [Disaster Recovery](https://docs.microsoft.com/en-ca/azure/site-recovery/site-recovery-overview)
        - use automatic backups to get back up and running after a failure
* Describe the Principles of Economies of Scale [(PDF)](http://download.microsoft.com/download/6/e/4/6e4cb3d1-5004-4024-8d90-6c66c83c17aa/the_economics_of_the_cloud_white_paper.pdf)
    - Azure has made the huge investment in all the infrastructure, and because they own so much it's cheaper for them to run all that than if they didn't run so much "in bulk"
    - Azure passes those saving down to the customer
* Describe the differences between:
    * Capital Expenditure (CapEx)
        - the initial cost of starting out
    * Operational Expenditure (OpEx)
        - recurring costs
* Describe the consumption-based model
    - you pay only for what you use

## Describe the differences between Infrastructure-as-a-Service (IaaS), Platform-as-a-Service (PaaS) and Software-as-a-Service (SaaS)

* Describe [Platform-as-a-Service (PaaS)](https://azure.microsoft.com/en-ca/overview/what-is-paas/)
    - the cloud provider runs the infrastructure and servers running in the background, you provide the software/code you want to run
* Describe [Software-as-a-Service (SaaS)](https://azure.microsoft.com/en-ca/overview/what-is-saas/)
    - the cloud provider manages the infrastructure and runs the servers and the software for you to use
* Describe [Infrastructure-as-a-Service (IaaS)](https://azure.microsoft.com/en-ca/overview/what-is-iaas/)
    - the cloud provider manages the phsyical servers/harddrives and you can configure them and run whatever you want on them
* [Compare and contrast the 3 different service types](https://azure.microsoft.com/en-ca/overview/types-of-cloud-computing/)
    - IaaS: for when you need control over the OS/software/servers/etc. but don't want to own/maintain the hardware
    - PaaS: for when you want control over the software but not the underlying OS or hardware
    - SaaS: when you want to just use software but don't want to maintain/update it

## Describe the differences between Public, Private and Hybrid cloud models

* Describe [Public cloud](https://azure.microsoft.com/en-ca/overview/what-is-a-public-cloud/)
* Describe [Private cloud](https://azure.microsoft.com/en-ca/overview/what-is-a-private-cloud/)
* Describe [Hybrid cloud](https://azure.microsoft.com/en-ca/overview/what-is-hybrid-cloud-computing/)
* Compare and contrast the 3 different cloud models

[Return to Table of Contents](README.md)
