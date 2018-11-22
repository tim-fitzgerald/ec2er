## AWS Instance Describer (ec2er) 

Another excuse to play with golang. This command queries running EC2 instances in an account and returns the `project` tag value, `instance id`, and the `Public DNS` of the instance. 
Its intended to allow the user to quickly retrieve the SSH address of an instance.
 
 #### Usage 
```bash
find-instances -region ca-central-1 -profile my_aws_profile
```
