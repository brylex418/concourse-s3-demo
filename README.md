You will need the following:

S3 or S3 comptabile storage that supports versioning 

aws cli

Ensure that versioning is set ont the bucket and if not set it

aws s3api --endpoint-url https://<s3 location>:9021 get-bucket-versioning --bucket <bucket-name>

aws s3api --endpoint-url https://<s3 location>:9021 put-bucket-versioning --bucket <bucket-name> --versioning-configuration Status=Enabled
