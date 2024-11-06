---
casestudy:
    title: 'Design a compute solution'
    module: 'Compute solutions'
---
# Design a compute solution

## Requirements

The local authority is migrating each school’s curriculum catalogue to the cloud. The application is a three-tier configuration using SQL as the data store.

![compute architecture](media/compute.png)

* The frontend application is a .NET core-based web app. 

* The application runs on IIS web server in the front tier. This service is only used at peak periods but during that time the system struggles with the requests the IT department is considering adding more servers but is concerned about them being ideal during off peak periods.

* The middle tier hosts a business logic that can process all the catalogue request from the staff 

* The back-end tier uses SQL Server database.

* While high availability is a concern, due to legal requirements the loacl authority must keep all the resources in a single region.

## Tasks

* **Front-end tier**. Which Azure compute service would you recommend for the front-end tier?  

* **Middle tier**. Which Azure compute service would you recommend for the middle tier?
  
