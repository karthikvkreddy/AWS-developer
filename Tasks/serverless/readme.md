## 1. Serverless website:
Create Lambda function
- upload /script/app.py
- add trigger 
    - API Gateway
    - select Create a new API
    - security: Open

Execute stack 
```
aws cloudformation create-stack \
  --stack-name <STACK-NAME>\
  --template-body file://<FILE_LOC> \
  --parameters ParameterKey=<PARAMETER-NAME>,ParameterValue=<PARAMETER-VALUE>
```

Upload files to S3 bucket
```
aws s3 cp scrips/ s3://my-static-website-bucket-123455/ --recursive --acl public-read
```

## 2: Version control with lambda:
- Create a function and upload version1 .zip file
- click actions-> public new version and add version 1
- click create new allias -> give name = prod
- now again add files and upload version2 . zip files
- click actions-> public new version and add version 2
- click create new allias -> give name = val
