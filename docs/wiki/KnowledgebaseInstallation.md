[[_TOC_]]

# Installation documentation

>I.S. 20211018 - I know we have several customers that take care of the infrastructure for Cloud Inform and we only have to push the code... Maybe this is the right time to make the possible installation path transparent!

## Customer is in charge of the infrastructure

The customer is end responsible for deploying and maintaining the Infrastructure necessary for running Cloud Inform. This will make troubleshooting/upgrading Cloud Inform cumbersome.

## Insight deploys the infrastructure

Having Insight take care of the infrastructure has it's advantages:

- Deployments can be centralized from AzDevOps with a proper Service Connection
- Insight is end-responsible for maintenance/upgrade

## TBD Containerized Cloud Inform solution

The containerized implementation will help centralizing maintenance/upgrade. Rather than deploying upgrades to multiple customers the container will be upgraded and tagged accordingly, making image distribution  the main activity for upgrading/hotfixes etc.

>I.S. 20211018 - Again feel free to update!
