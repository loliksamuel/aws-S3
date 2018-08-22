AWS S3 Service 
--------------
This app help u connect to s3 through code.


- first step go to aws > iam > your user > security credentials > add access key
then set the security credentials in application.properties
```sh
jsa.aws.access_key_id=XX
jsa.aws.secret_access_key=YY
```
- to download and upload files set application.properties
```sh
shouldUpload=true
shouldDownload=true
```

aws-cli
-------
u also can use aws-cli
- go to aws > iam > your user > security credentials > add access key
- install aws-cli
- aws configure
- put access key, secret, region, type
- aws s3 ls 
- aws s3 ls s3://YOUR_BUCKET
- aws help
- aws s3 mb s3://NEW_BUCKET_NAME --region eu-west-1