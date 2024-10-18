# learn_kubernetes
learn_kubernetes

**understanding terminology**
1. Kubernetes has a master-worker architecture.
2. The master node (now often referred to as the control plane) manages the cluster, while worker nodes run the containerized applications. The control plane is responsible for orchestrating the worker nodes.
3. A Kubernetes cluster can consist of multiple nodes (VMs or physical machines).The nodes can be organized as a set of worker nodes that run the workloads and one or more control plane nodes that manage the cluster.
4. A cluster is not exactly divided into services, but it runs pods (the smallest deployable units), which can contain one or more containers.
5. Services in Kubernetes are abstractions that define a logical set of pods and a policy to access them. Services provide stable endpoints for accessing the pods.
6. Each service is assigned a stable IP address and DNS name, allowing other components in the cluster to communicate with it. These endpoints are automatically managed by Kubernetes.
7. Ingress is a collection of rules that allow external HTTP/S traffic to access services within the cluster. Ingress rules define how to route traffic based on hostnames or paths, enabling flexible access to your services.
8. workloads refer to the applications and services that run on the cluster. They are managed by Kubernetes to ensure that your applications are running as expected. Workloads are encapsulated in pods, which are the smallest deployable units. Here’s an overview of the main types of workloads in Kubernetes:
   


