### Create the below service linked role before creating EKS 
aws iam create-service-linked-role --aws-service-name autoscaling.amazonaws.com --custom-suffix suffix
