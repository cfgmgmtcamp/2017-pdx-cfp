## Reproducible Infrastructure With Terraform and Puppet


## Abstract

Whether you manage a single application with thousands of identical nodes or a collection of unique, single-purpose servers, reproducibility of your infrastructure is critical to testing, reliability, and disaster recovery. Every DevOps tool purports to solve this problem, but too often, it feels like your "automation" involves more checklists than code, and this struggle only gets worse when you try to combine multiple tools. Turns out, though, you actually can make the dream of reproducible infrastructure a reality.

In this talk, we'll take a look at how to combine Terraform and Puppet to construct fully automated, reproducible infrastructure on AWS. We'll cover:

* building Terraform configurations to deploy EC2 instances, security groups, EBS volumes, Elastic Load Balancers, and more.
* setting up user data and cloud-init in AWS to prepare a new EC2 instance and run Puppet.
* using autosign with JWT to securely connect nodes to Puppet without manual intervention.
* configuring an application node from scratch with Puppet.
* leveraging AWS Lambda and Terraform to destroy infrastructure, clean up PuppetDB, and reprovision.
* designing everything to allow deploying multiple separate clusters.




## Ryan Whitehurst
