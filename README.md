# This repo is used as a workspace in TF Cloud

It calls this [module](https://github.com/webpage-counter/terraform-aws-nomad_client) which is uploaded in TF Module registry 

It creates the Nomad client and starts the python application

You will need to configure the following variables in TF Cloud:

```
aws_access_key =

aws_secret_key = 

instance_type = "t2.small"

token = 

region = "us-east-1"

db_pass = 

```
