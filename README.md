Overview
- Defines an existing EKS cluster  
- Replicates the existing cluster into a staging environment  

Components
- Cloudformation  
- Breaks default parallel flow by using 'Depends-On' flags and 'Ref'  
- Secrets Manager  
- IAM  
- ECR  
- EKS 

Output
- IAM User  
- Secret in Secrets Manager  
- Two ECR Respositories  
- Node + Cluster role and policy  
- Builds one spot node group and one reserved node type group    
