# Whole Internet Provissioning Case Study
## Company overview
Whole Internet Provissioning provides SaaS platform for wide range of retailers across the globe. The platform is deployed to us-east and eu-west  geografical locations. Company is highly cloud oriented. The 100% of their customer facing services are running in cloud. Also all their services are tied to a single Cloud Provider - Amazon AWS. Due to demand from some of their customers they are obligated to run their services in other Cloud Providers. Most of thair data stack is deployed to bare ec2 instances. However for application stacks many engineering teams use Dockerized solutions on ECS along with custom ones. Utilization of Amazon managed solution is minimal. Company is investing a lot of time and efforts into developing Kubernetes cluster, however GA is expected within 6-8 month.

## Solution Concept
Whole Internet Provissioning is building a customer to market connection service, which they expet to be very popular. Also as a data layer they plan to use Apache Casandra as higly scalable database.

## Business Requirements
* Plan for a global footprint.
* maximum uptime - downtime is loss of customers.
* Increase efficiency of the cloud resources we use.
* Reduce latency to all customers.
* GDPR compilince.

## Technical Requirements
### Requirements for Service Backend Platform
* Dynamically scale up or down based on activity.
* Seamless Deployment.
* Rapid Releases.

### Requirements for Data Layer
* High availability and resiliency
* Maintenance
* Security
