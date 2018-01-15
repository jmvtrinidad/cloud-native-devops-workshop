![](common/images/customer.logo.png)
---
# ORACLE Cloud-Native DevOps workshop #

## Introduction ##

Oracle Cloud is the industry’s broadest and most integrated public cloud. It offers best-in-class services across software as a service (SaaS), platform as a service (PaaS), and infrastructure as a service (IaaS), and even lets you put Oracle Cloud in your own data center. Oracle Cloud helps organizations drive innovation and business transformation by increasing business agility, lowering costs, and reducing IT complexity. The workshop content shows different aspects of Application Development in the cloud with different set of Oracle Cloud Services.


### Prerequisites ###

The workshop is intended to work with an Oracle PaaS trial account. To get an account look into [here](common/request.for.trial.md). Get the following account details ready to complete the tutorial and replace to your values when it is required:

+ Oracle Cloud account **username** and **password**
+ Oracle Cloud **identity domain**
+ **Data center/region**

NOTE: Before you start to use your new Oracle Public Cloud services make sure that the replication policy has been set for your account. Otherwise you can not create storage container which is necessary for most of the services. See [Selecting a Replication Policy for Oracle Storage Cloud Service](https://docs.oracle.com/cloud/latest/storagecs_common/CSSTO/GUID-5D53C11F-3D9E-43E4-8D1D-DDBB95DEC715.htm).

### Important ###

During the execution you will create several public cloud service instances what will be available on the world wide web. Even if these instances are for demo purposes keep in mind it is not a best practice to use weak or known (stored here in the tutorial) passwords especially in such open environment. Thus this workshop content does not recommend any password so you need to define those. You will be asked to provide password at certain points and please remember them  for  later usage.

The content contains several independent modules that cover different aspects of the application development in the Oracle Cloud. These modules could be executed independently unless you find in the Prerequisites that they are dependent on each other.

----

#### Support SpringBoot application development lifecycle using Oracle Developer Cloud Service, Application Container Cloud Service and Oracle Enterprise Pack For Eclipse ####

+ [Create Oracle Developer Cloud Service project for SpringBoot application](springboot-sample/create.devcs.project.md)
+ [Create continuous build integration using Oracle Developer Cloud Service and Oracle Application Container Cloud Service](springboot-sample/devcs.accs.ci.md)
+ [Using Eclipse IDE (Oracle Enterprise Pack for Eclipse) with Oracle Developer Cloud Service](oepe/setup.oepe.md)

#### Container based application development lifecycle using Wercker and Container Cloud Service ####

+ [Build Spring Boot container packaged application using Wercker and deploy to Oracle Container Cloud Service](springboot-sample/create.wercker.ci.md)
	+ [Use Wercker step to restart Oracle Container Cloud Service in Wercker Continuous Delivery workflow](springboot-sample/wercker.step.occs.md)
+ [Build Spring Boot application using Wercker and deploy to Oracle Application Container Cloud Service using custom Wercker Step](springboot-sample/wercker.step.accs.md)
+ [Build Node.js-MongoDB container packaged application using Wercker and deploy to Oracle Container Cloud Service as the Stack of services](containers/nodejs-mongodb-stack/README.md)
+ [Build Node.js-Cassandra DB container packaged application using Wercker and deploy to Oracle Container Cloud Service as the Stack of services](containers/node-cassandra-stack/README.md)

#### DevOps and Cloud Native Microservices ###
+ [Walk you through the Software Development Lifecycle (SDLC) for a Cloud Native project, create and use several Microservices](microservices/README.md) 

#### Clean up the environment ####

+ [Delete Application Cloud Container Service using PaaS Service Manager (PSM) Command Line Interface (CLI)](cleanup/cleanup-psm.md)

## [License](../../LICENSE.md)
