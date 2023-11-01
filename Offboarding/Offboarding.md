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
Below are some links that introduce options for commercial providers of managed solutions.

#### Commercial Dask Deployment Options
https://docs.dask.org/en/latest/ecosystem.html

#### Openscapes Suggestions
https://openscapes.org/blog/2023-10-13-nasa-jupyterhub-coiled/

## Environment setup
### Corn
Corn is a base image that allows the provisioning of a multi-kernel Docker base image for JupyterHub deployments. Visit the [Cloud Environment Setup instructions](https://nasa-openscapes.github.io/earthdata-cloud-cookbook/environment-setup/) for further information.

## More information
For more detailed information on setup and cost management in the AWS environment, see the [Earthdata Cloud Primer](https://www.earthdata.nasa.gov/learn/user-resources/webinars-and-tutorials/cloud-primer).



