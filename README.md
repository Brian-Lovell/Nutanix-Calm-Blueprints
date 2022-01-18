# Nutanix-Calm-Blueprints

## Udacity - Hybrid Cloud SaaS: Three-Tier Web Application
Project description
I created a Three-Tier Web Application Nutanix Calm blueprint that has a load balancer, two web tiers, and a database on Nutanix AHV, and Amazon Web Services.

I learned how to use Nutanix Calm blueprints to create a web server tier on private and public cloud. Both are scalable with Calm Variables, and Macros and orchestrates updating the load balancer.

I also learned how to create different application profiles for different resource requirements. Small and medium application profiles for more demanding loads.

Created a database back up and restore action that uses end user runtime specified password for the database root account. Database actions also orchestrate the stop and restart of the web server tier.

## Udacity - Private Cloud SaaS: Three-Tier Web Application
Project description
I created a Nutanix Calm Blueprint that automates the creation of a three-tier web application.
The blueprint creates a load-balancer and a scalable web-tier that's connected with a database on a private cloud Nutanix AHV.

I learned about how to create a scalable web service tier, that allows you to add or remove additional web servers with the push of a button. I created a Calm Variable that allows you to select the number of servers. I also learned how to orchestrate updating the load balancer when the web servers scale up and down.

I also created an action that allows the user to backup the database and orchestrate the stop and restart of the web tier.
