# HotColdDeploy
Containerized Application Deployment with Kubernetes and Helm

# Project Summary:
The Hot/Cold application is deployed using Kubernetes and Helm, demonstrating modern DevOps practices. This project showcases containerization, orchestration, and deployment strategies, along with integration with Helm for managing Kubernetes resources.

# Application Development:

A simple Hot/Cold application is developed in Python to randomly respond with "hot" or "cold".

# Kubernetes Deployment:

A local Kubernetes cluster is set up using kind.
Kubernetes deployment manifests are created for the application, including Deployment, Namespace, and Service resources.

# Containerization:

The application is containerized using a Dockerfile.
The Docker image is built and pushed to a container registry.

# Integration with Helm:

A Helm chart is initialized for the application.
Kubernetes YAML files are migrated to Helm templates, with detailed documentation for each configuration.
Deployment of the application is demonstrated using helm install, and scalability is showcased with helm upgrade to increase replicas.

# Harbor Integration (Bonus):

Harbor, a container registry and Helm chart repository, is deployed on the Kubernetes cluster using kind.
The Helm chart is configured to use images stored in Harbor, exemplifying a CI/CD pipeline component.

# Conclusion:

This project demonstrates proficiency in deploying applications with Kubernetes and Helm, highlighting best practices in containerization and orchestration. The integration with Harbor showcases real-world CI/CD pipeline components, providing a comprehensive example of modern DevOps practices in action.
