The contents of this directory are made public at https://modernization-workshop-bucket.s3-us-west-2.amazonaws.com/cfn/ for inclusion into nested stacks.  

Example: vpc.yaml is made public at https://modernization-workshop-bucket.s3-us-west-2.amazonaws.com/cfn/vpc.yaml

> Note that the files in root directory are here for backward compatibility and should not be used for 
> newer solutions.

Here is an example for a link to create an EKS cluster.

https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=ModernizationWorkshop&templateURL=https://modernization-workshop-bucket.s3-us-west-2.amazonaws.com/cfn/master-stacks/vpc-eks-QS-based-pipeline-user.yaml

To pass parameters use the following on the end of the URL: (This is just an example and won't work with the above link)
&param_DBName=mywpblog or &param_InstanceType=t2.medium or &param_KeyName=MyKeyPair

