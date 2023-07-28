# Kubernetes (K8) Notes

## What is K8?

- K8 (Kubernetes) is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.
- Originally designed by Google, it is now maintained by the Cloud Native Computing Foundation (CNCF).
- It allows users to abstract the underlying infrastructure and focus on deploying and managing applications efficiently.
![k8 diagram](https://github.com/Zain-Ashfaq/tech241-K8/assets/110741952/34cb9bac-a4aa-4647-8948-a7ed3d3139f3)


## Why should we learn and use K8?

- K8 simplifies the process of deploying and scaling applications, making it easier to manage complex containerized environments.
- It provides automated load balancing and self-healing capabilities, reducing manual intervention and enhancing application reliability.
- K8 enables the efficient utilization of resources, ensuring optimal performance and cost-effectiveness.

## Who is using K8?

- K8 is widely adopted by a broad range of organizations, from startups to large enterprises.
- Many tech giants like Google, Microsoft, and Amazon use K8 in their cloud services to offer container orchestration capabilities.
- Various companies across industries, including finance, e-commerce, and healthcare, rely on K8 to deploy and manage their applications.

## Benefits to Business

- K8 increases development velocity by enabling faster and more frequent application deployments.
- It enhances application reliability and availability, reducing downtime and improving customer satisfaction.
- K8 helps in efficient resource utilization, leading to cost savings on infrastructure and operational expenses.

## K8 Objects:

### Pods:

- Smallest deployable units in K8, representing one or more containers.
- Containers within a Pod share the same network namespace and can communicate with each other via localhost.

### Deployments:

- Used to manage the deployment and updating of Pods, ensuring the desired number of replicas are always running.
- Provides declarative updates and rollbacks, making it easier to manage application versions.

### Services:

- Enables a stable network endpoint to access one or more Pods, allowing load balancing and discovery of running Pods.
- Different types of services include ClusterIP, NodePort, and LoadBalancer.

### Replica Sets:

- Ensures a specified number of replicas of a Pod are running at all times.
- Often used by Deployments to maintain the desired state of Pods.

## Concept of Labels and Selectors in K8:

- Labels are key-value pairs attached to K8 objects like Pods, allowing flexible categorization and identification.
- Selectors are used to identify a set of objects based on their labels, enabling grouping and easy management of related resources.

