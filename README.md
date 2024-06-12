# Codepipelines

## To create and deploy the Cloudformation Stack run below command

aws cloudformation create-stack --stack-name xxxx-codepipeline \
--template-body file://xxxx-PIPELINE-CFT.yaml \
--parameters file://xxxx-params.json \
--capabilities CAPABILITY_NAMED_IAM \
--region us-east-1
