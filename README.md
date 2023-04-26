
### PHP quiz application
****Abstract : In this project, we have deployed a PHP application on the cloud. We have used the following AWS services:

-Elastic Beanstalk (EBS)
-Relational Database Service (RDS)
-Elastic Cloud Compute (EC2)

The application displays a quiz about the technical aspect of the PHP language itself. Users get their score at the end of the quiz.

### Project Members
PATIL UDAYRAJE JITENDRA [ Team Leader ]
MITHANI MOHSIN MAHMOOD
PUJARI DHRUV MANOJ
MANJREKAR RUPESH GURUNATH


### Project Guides
No guides assigned.


### Deployment Steps
Please follow the below steps to run this project.

1.Download the file as zip and then extract it
2.After creating EBS environment and RDS instance open the connection.php file and make changes in the file by adding the endpoint of your instance,your password entered while creating the RDS instance and your username enter in the db instance
3.Now make changes in the security groups of both rds and ebs by going through the ec2 dashboard and click on the connect and write the sql commands in the generated CLI
4.Use this command mysql -h (endpoint of your rds instance) -u (username of the rds instance) -p (password entered while creating ypur rds instance)
And finally go on to the ebs dashboard and click on the link above and your application will be up and running.

### Subject Details
Class : TE (AI&DS) Div A - 2022-2023
Subject : Skill base Lab Course: Cloud Computing (SBLCC)
Project Type : Course Project

### Platform, Libraries and Frameworks used
PHP

### References
-GitHub
