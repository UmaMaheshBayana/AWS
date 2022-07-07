# Create and COnfigure IAM Role  

Login to aws account and create a IAM user in IAM service

Give S3 bucket full access policy to the user 

Download the Access key and Secret key form there.

Create IAM role with EC2 policy and attach to the particular instance

# Install awscli on the EC2 machine.

```sudo apt-get install awscli -y```

```aws configure```

It will ask for Access key ,Secret key, Region(optional) and language : json

To see the configuration list 

```aws configure list```

To copy files from your machine to S3

```sudo aws s3 cp filename s3FolderURL```

To remove aws IAM accesskey and secret key

```cd ~/.aws/```

Next remove config directory and credentials directory 
