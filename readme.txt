## Helm Chart: Flask DynamoDB

This Helm chart facilitates the deployment of the Flask DynamoDB application onto a Kubernetes cluster.

### Prerequisites

Before deploying this Helm chart, ensure the following prerequisites are met:

- **Proper Subnet Tags**: Ensure that the subnets associated with your EKS cluster have appropriate tags configured.
- **OIDC Identity Provider**: Set up an OIDC identity provider for your EKS cluster.
- **Ingress Role**: Create an IAM role for the Ingress controller with the required policies attached.
- **Git and Helm**: Make sure Git and Helm are installed on your local machine or deployment environment.

### Installation Instructions

To deploy the Flask DynamoDB application using this Helm chart, follow these steps:

Clone this repository to your local machine:
   git clone <repository-url>

