# deploy-nodejs-app-to-EKS-using-GitHub-Actions
# Date: 10/06/2024
#
1. Create AWS ECR name = demoecr
2. Create AWS EKS Cluster

	eksctl create cluster --name devops-cluster --region us-east-1 --nodegroup-name linux-nodes --node-type t2.micro --nodes 2
