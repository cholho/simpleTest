# ORACLE Cloud Test Drive #
-----
## 101: Create Oracle Developer Cloud Service Loyalty Management application project using initial GitHub repository ##

### About this tutorial ###
**Oracle Developer Cloud Service** is a cloud-based software development Platform as a Service (PaaS) and a hosted environment for your application development infrastructure. It provides an open-source standards-based solution to manage the application development life cycle effectively through integration with Hudson, Git, Maven, issues, and wikis. Using Oracle Developer Cloud Service, you can commit your application source code to the Git repository on the Oracle Cloud, track assigned issues and defects online, share information using wiki pages, peer review the source code, and monitor project builds. After successful testing, you can deploy the project to Oracle Java Cloud Service - SaaS Extension, publicly available Oracle Java Cloud Service instances, Oracle Application Container Cloud Service instances, or to an on-premise production environment.
![](images/101/00.dcs.png)

The key features of Oracle Developer Cloud Service include:

Project creation, configuration, and user management

+ Version control and source code management with Git
+ Storage of application dependencies and libraries with Maven
+ Continuous build integration with Hudson
+ Wiki for document collaboration
+ Issue tracking system to track tasks, defects, and features
+ Repository branch merge after code review
+ Deployment to Oracle Java Cloud Service - SaaS Extension, Oracle Java Cloud Service, and Oracle Application Container Cloud Service

Oracle Developer Cloud Service is available as a web interface accessible from a web browser and from Integrated Development Environments (IDEs) such as Oracle Enterprise Pack for Eclipse (OEPE), Oracle JDeveloper, and NetBeans IDE.

This tutorial demonstrates how to:

- create Oracle Developer Cloud Service project using existing external Git repository

### Prerequisites ###

- Oracle Public Cloud Service account including Developer Cloud Service (Check with instructor if you don't have one)

----

#### Create Oracle Developer Cloud Service project ####

1. Sign in to [https://cloud.oracle.com/sign-in](https://cloud.oracle.com/sign-in) by provided **Developer Cloud Service \(DevCS\)** identity domain Id and credential. First select your datacenter then provide the identity domain and credentials. After a successful login you will see your Dashboard. Find the Developer Service tile and click the hamburger icon. In the dropdown menu click **Open Service Console**.

![](images/101/01.dashboard.png)

2. Log in to Oracle Developer Cloud Service and create a new project.

![alt text](images/101/02.new.project.png)

3. Enter the name of the project and set the desired properties.
	**Name:** `APAC Cloud Test Drive`
	**Description:** `APAC Cloud Test Drive project hub`

4. Click **Next** and select *Initial Repository* as template.

![](images/101/03.select.template.png)

5. Click **Next** and on the Properties page select *Import existing repository*.
Enter or copy the *https://github.com/APACTestDrive/LoyaltyManagement.git* repository address.

![](images/101/04.import.repository.png "Import external repository")

6. Now click **Finish** to create the project and to clone the specified repository. You have now created a new Git repository with source code stored within the Developer Cloud Service that is based on an existing repository.

You have finished this lab section.

[Procced to Next - 102: Define Continuous Integration 'Build' and 'Deploy' Configuration in Oracle Developer Cloud Service](102-JavaAppsLab.md)

or

[Back to JavaAppsLab Home](README.md)
