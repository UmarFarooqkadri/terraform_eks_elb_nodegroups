# Terraform EKS Cluster Creation
##Intro##
##Create IAM Role for EKS Cluster
Attach AmazonEKSClusterPolicy to EKS Role
Create AWS EKS Cluster
Create IAM Role for EKS Node Group
Attach AmazonEKSWorkerNodePolicy, AmazonEKS_CNI_Policy, and AmazonEC2ContainerRegistryReadOnly to EKS Node Group IAM Role
Create AWS EKS Node Group
Run Terraform Commands to Create AWS EKS Cluster
Connect to EKS Cluster
Deploy Sample Application to EKS Cluster
Expose Kubernetes Service with Private Load Balancer
Expose Kubernetes Service with Public Load Balancer
