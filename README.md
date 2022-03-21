# clusterReplicationTemplate

This is an example of replication an EKS cluster from one environment to another.  

# Overview  
- The parameter list details networking and naming details.  
- Resources are run by default in parallel. The 'Depends-On' flag and 'Ref' are used for control flow.  

# Output  
- IAM User  
- Secret in Secrets Manager  
- ECR Respository  
- Node + Cluster role and policy
- Builds two node groups (one for spot and one for reserved types)
- EKS Cluster
