Portfolio Website



![Portfolio](https://github.com/user-attachments/assets/4ac45885-8046-474e-8c00-d60dc3f132ef)



Portfolio website on Amazon Lightsail
=====================================

* This Portfolio website was built on Amazon Lightsail.
* For this project , I created an Independent Amazon RDS (MariaDB) instance for the database and used an EC2 instance to a Apache Webserver on Ubuntu 22.
* A simple yet efficient setup to host my porfolio website which showcases my skills and experience including other DevOps and AWS projects.
* Route53 was used to host my domain records.
* Amazon CloudFront is used to serve HTTPS content to users viewing my portfolio site.
* A static IP is attached to my EC2 instance.
* The Certificate for my website was obtained from Amazon Certificate Manager (ACM) and attached to Amazon CloudFront.
* This architecture is hosted the canadian region making it easier for canadian users to access my website.


Tools:
-------

EC2 instance
Route53
VPC (default)
CloudFront
Amazon Certificate Manager (ACM)
Amazon RDS (MariaDB)
Security Group
