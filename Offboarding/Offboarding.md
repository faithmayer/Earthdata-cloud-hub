# Moving out of the Earthdata Cloud Playground
Once you have gotten comfortable working in the cloud environment, you may find you have use cases that aren't supported in the Playground or you are ready to set up a more permanent cloud workflow.


## What are my options?
There are numerous options available for creating a similar cloud setup. Below are some of the main ones.


### Personal AWS account
You can create your own AWS account and "DIY" a setup similar to that of the Playground. Below are some initial steps for getting started.


1. Create an AWS account
AWS has detailed documentation that walks through setting up a new account. To do so, follow the steps in [Module 1: Create Your AWS Account](https://aws.amazon.com/getting-started/guides/setup-environment/module-one/).
2. Monitoring cost
Understanding and monitoring the various service costs is a crucial aspect of working within a cloud environment. AWS allows you to set up cost budgets that notify you when you exceed your budgeted threshold. AWS provides an [overview](https://aws.amazon.com/getting-started/hands-on/control-your-costs-free-tier-budgets/) on introductory cost information, including which services fall under the AWS Free Tier and how to create a cost budget.
3. Create necessary resources
To create an EC2 instance in AWS for compute, follow their [tutorial](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html#ec2-launch-instance).


### Managed solutions


#### Coiled
[Coiled](https://www.coiled.io/) reduces the overhead required to set up infrastructure when working directly in AWS. It offers cloud compute via a script run on a local machine or in a Hub and includes features like spending caps, cost and computation observability, and responsive support. More information on using Coiled can be found in [Coiled's Getting Started](https://docs.coiled.io/user_guide/setup/index.html) documentation.


#### Nebari
[Nebari](https://www.nebari.dev/) is an open source platform that provides a way to set up and manage resources for a custom cloud deployment. Nebari offers features like full-fledged Jupyterhub deployments with Kubernetes (container orchestration) integration. It is managed by the person or organization who deploys it. For more information on implementation, visit [Nebari's Getting Started](https://www.nebari.dev/docs/category/get-started) documentation.


#### 2i2c
[2i2c](https://2i2c.org/) is a managed JupyterHub service. It handles the design, development, and operation of JupyterHubs in the cloud for communities of practice in research & education. To learn more about using a Hub through 2i2c, before requesting a Hub, visit their [Hub Service Guide](https://docs.2i2c.org/).


## Environment setup
### Corn
**TODO:** Will this section be filled out inline, or do I just reference the existing documentation? https://nasa-openscapes.github.io/earthdata-cloud-cookbook/environment-setup/


## More information
For more detailed information on setup and cost management in the AWS environment, see the [Earthdata Cloud Primer](https://www.earthdata.nasa.gov/learn/user-resources/webinars-and-tutorials/cloud-primer).



