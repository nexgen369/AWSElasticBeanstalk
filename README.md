# AWSElasticBeanstalk


Ec2, Loadbalancer, autoscaling, security groups, monitoring etc in manually.

Elastic beanstalk does all of these automatically

Real time scenario:

You have Restaurant opened:

Without beanstalk:

You build your kitchen,

Hire Staff,

Arrange Tables,

Manage utilities Intercom, Electricity, Water etc.


with beanstalk:

AWS gives you a ready restaurant set up

you only provide the food (application)

EC2 runs app, Load balancing distributes the traffic, cloud watch is the monitor, AWS S3 Stores the App with dependencies and packaging.

Auto scaling groups adds and removes the servers, Security Groups, 
IAM Roles.


Application, Environment, App version, platform (ex: Python, Java,node.js, docker, .NET etc) 
 

Workflow ---> User Browser - DNS - Loadbalancer -EC2 - Application


app.zip for Python Demo and Dockerfile-eb.zip for Docker. platform selection

