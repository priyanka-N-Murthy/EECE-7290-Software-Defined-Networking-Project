## SDN for Secure Video Streaming: CORD Based Secure Video Streaming

### Students –
1)	Aman Maldar - Aman_Maldar@student.uml.edu
2)	Priyanka Murthy - Priyanka_Murthy@student.uml.edu

### List of Files - 
1) Project Report - Includes - Project details + Individual Contribution
2) CORD environement setup -  Instruction
3) Running and Changing HelloWorld Service - Instruction
4) Presentation Slides
-----------------------------------------------------------------------------------------------------------------------------------

The repository consist of the documents which includes detailed steps and screenshots indicating the work progress for the project.
Instructions to setup the project environment are explained in detail.

Read and follow the steps mentioned in the documents below to track the project progress.
1) CORD environement setup
2) Running and Changing HelloWorld Service

### Objectives Achieved - 
1) Setting up CORD Environment on CloudLab.
2) Running Hello World Service.
3) Making changes in HelloWorld service
4) Creating a new tenant service.

### What did not work? 
1) Running a python script as a service.
- We made a changes to the ansible script to run the python program as a service. The CORD-POD environment broke everytime we made the changes. So we basically could not deploy it.

2) Running Red5/Mist server
- CORD runs apache server to host/run the service. We tried to install red5 server in place of Apache server. Again, CORD-POD broke evrytime.

### Contribution-
The contribution part mainly involves understanding different concepts in the CORD architecture and discussing their role in implementation of the application.  We made efforts towards developing small parts in the application, we faces problems, we analyzed the issues to understand how things work.
Contributed together on
-	understanding advanced concepts like  XOS, ONOS, Service assembly 	
-	Implement the application as a whole.

Individual contribution goes like,
#### Aman Maldar
-	Read service assemble documentation and executed HelloWorld application.
-	Reused HelloWorld template to create tenant service.
-	Executed multiple services to display results
-	Created the documentation for example service demonstration.
-	Created documentation for CORD environment setup using CloudLab.
-	Made initial installation of red5 and mist server on the Linux for testing purpose.
-	Wrote a sample python application (uppercase program) to install as a service in CORD.
-	Made changes in the Ansible playbook to execute sample python application. 

#### Priyanka Murthy
-	Understood the installation process of CORD
-	Set up the environment for application development.
-	Managed the github repository to keep track of changes in different files/folders.
-	Worked on troubleshooting logs of container to understand execution of Ansible script.
-	Understood the role of docker container, VM in implementing the services.
-	Helped in creating final report by compiling the details. 
-	Worked on creating presentation slides.


-------------------------------------------------------------------------------------------------------------------------------
