Ensure that versioning is set ont the bucket

aws s3api --endpoint-url https://<s3 location>:9021 get-bucket-versioning --bucket <bucket-name>
