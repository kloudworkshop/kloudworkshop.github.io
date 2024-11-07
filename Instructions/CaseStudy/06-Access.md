---
casestudy:
    title: 'Design authentication and authorization solution'
    module: 'Authentication and authorization solutions'
---


# Design authentication and authorization solutions

## Requirements

The local authoring is moving all schools to the cloud, they need help in deciding how to arrange their Microsoft Entra ID.

**New user accounts**

  * All students from each school will need an account in the Microsoft Entra ID, currently all schools have their own Active directory domain.

  * There will be a need for 15 employees form a neighbouring local authoring to access the system. These employees already have their own Microsoft Entra ID. 

  * The main IT department wants to include new identity security features. 

**New application access**

  * Each school has an application that is running on a VM in Azure and the data is stored on an Azure SQL database. They need to securely allow the VM to query the Azure SQL database. 
  * They also need to allow an on-premises server to securely access the SQL database without storing credentials in the application code or configuration files..

## Tasks

**New user accounts**

  * Diagram the process for bringing in the acquired user accounts.

  * Diagram the process for adding the new partner accounts. 

  * For the above requirements, be sure to include any tools that will be used. List at least three benefits of your suggested solution. 

* Provide at least three recommendations for improving Tailwind Traders user identity solutions. Rank the recommendations in order of importance. Include your reasons for making these suggestions. 

**New application access**

  * Provide an access solution for the business development application.

  * Provide an access solution for the on-premises resources.

How are you incorporating the Well Architected Framework pillars to produce a high qua
