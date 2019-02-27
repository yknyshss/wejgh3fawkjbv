# Whole Internet Provisioning Case Study
## Company overview
Whole Internet Provisioning provides SaaS platform for wide range of retailers across the globe. The platform is deployed to us-east and eu-west geographical locations. Company is highly cloud oriented. The 100% of their customer facing services are running in cloud. Also all their services are tied to a single Cloud Provider - Amazon AWS. Due to demand from some of their customers they are obligated to run their services in other Cloud Providers. Most of their data stacks are deployed to bare ec2 instances. However for the application stacks many engineering teams use Dockerized solutions on ECS along with custom ones. Utilization of Amazon managed solutions is minimal. Company is investing a lot of time and efforts into developing Kubernetes cluster, however GA is expected within 6-8 month.

## Solution Concept
Whole Internet Provisioning is building a customer to market connection service, which they expect to be very popular. Also as a data layer they plan to use highly scalable NoSQL database.

## Business Requirements
* Plan for a global footprint.
* Maximum uptime - downtime is loss of customers.
* Increase efficiency of the cloud resources we use.
* Reduce latency to all customers.

## Technical Requirements
### Requirements for Service Backend Platform (Application Layer)
* Dynamically scale up or down.
* Seamless Deployment.
* Rapid Releases.
* Effective Balancing.

### Requirements for Data Layer
* High availability and resiliency.
* Maintainability.
* Security (Data Layer should be accessible by Application Layer only).
