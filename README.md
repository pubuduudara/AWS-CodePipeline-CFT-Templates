# Codepipelines

## To create and deploy the Cloudformation Stack run below command

aws cloudformation create-stack --stack-name xxxx-codepipeline \
--template-body file://xxxx-PIPELINE-CFT.yaml \
--parameters file://xxxx-params.json \
--capabilities CAPABILITY_NAMED_IAM \
--region us-east-1

https://medium.com/@pubuduudara7/aws-codepipeline-to-deploy-frontend-web-apps-using-aws-static-web-hosting-a14036f7acfc
