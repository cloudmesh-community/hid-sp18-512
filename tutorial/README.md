<h1> <img alt="icon" src="../images/icon.png" width="100" style ="float:left"> <div style="float:right">GOOGLE CLOUD COMPUTE SERVICES </div></h1>
Getting Started with Google Cloud Compute
<hr>


## 1. Introduction

The very first cloud computing services goes back to about 2002 when Amazon released the AWS platform and exposed the technology to the rest of the world. It enabled technololgy experts to develop innovative applications and changed the way they are built. AWS had an early lead in the cloud computing and has continued to dominate the industry. The Elastic Cloud Compute Engine, a cloud-based virtual machine was one of their first innovations. Over the years, other competitors such as Microsoft, IBM, and Google came with their versions of the compute services that not only compete with Amazon, but continue to change the way developers build applications. With enterprise service-level agreements (SLA), Google launched their first compute engine service in 2013 and availed it to the general public. The Google Cloud Platform currently provides a myriad of services that span from storage,big data tools,networking et cetera. This tutorial will mainly focus on its compute stack, when to chose which service and how to get up and running with each. 

<h2> 2. The Core Google Compute Offerrings</h2>

Google compute comes in three different offerings. These are the Google Compute Engine, Google Kubernetes Engine, and the Google App Engine. The choice of compute service depends on things such as customer demands, the application requirements as well skills when it comes to infrastucture. The image below provides the major difference between the three. This section summarizes these different compute offerings in the google cloud infrastructure.  Then we will explore how to get up and running with each service and also deploy a simple application. 

<br>
<p align="center">
<img src="../images/google_cloudp.png" width="600">
</p>

 <h3>2.1 Google Compute Engine (GCE)</h3>
  
The google cloud compute is an infrastucture as a service offering that provides the power of creating virtual machines and the ability to alocate attributes such as memory, CPU, type of storage, and size of storage as well. It can be compared to building a whole computer with the ability to customizing the features according to your requirements and workloads. This can also be looked as a supplement or even a replacement for traditional on premise IT assets such as servers and routers.

<br>
<p align="center">
<img src="../images/compute.png" width="600">
</p>


<h3>2.2 Google Kubernetes Engine (GKE)</h3>

Kubernetes is a container as a service that is basically an abstraction of the compute engine. It enables customers to run fully managed Docker containers. A container is a service that helps modularize applications. Why containers? Contrary to virtualization with regard to irtual machines, containers virtualize at the level of teh operating system and run the on the operating system directly. They are quite light weight, start fater than conventional VMs and use very small portion of the memory of the operating system. They also allow faster development and reliability. Kubernetes helps with the automation, monitoring, management and the deployment of these containers. 
<br>
<p align="center">
<img src="../images/kubernetes.png" width="600">
</p>

<h3>2.3  Google App Engine (GAE) </h3>
  
Google App Engine is googles dedicated platform as a service(Paas), and is pretty much based on a "bring your code and we'll take care of the rest kind of model. This provides customers with ability to focus on development and not the infrastucture behind the development platform. The customers do have have to deal with underlying requirements of the hardware. In other words, the plaftform is ready to go. It automatically handles scaling to ensure the demands of the customer are met. The app engine can use kubernetes in the background for this cases but the user does not handly what goes on with it. It is therefore ideal for developers that does not need to deal with the idea of server configurations such as load balancing. It it mostly used for web applications.
<br>
<p align="center">
<img src="../images/app_engine.png" width="600">
</p>

<h3> 3. Setting Up a Compute Service</h3>
This section will delve into how the setup and configure each of the above compute services in the google could. Google provides two options on how to perform configurations on these services. One has the option of using the user interface or google's commandline terminal, also know as gcloud. These tutorials will mainly focus on commanline configuration. 
