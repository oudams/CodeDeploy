# Cloudformation excercise for ECS deployment using Codedeploy

## Deploy a new stack with a template
```shell script
aws cloudformation deploy --stack-name <stack-name> --template-file <yaml-file-location>
```

## Delete a deployed stack
```shell script
aws cloudformation delete-stack --stack-name <stack-name>
```


## Validate a local template
```shell script
aws cloudformation validate-template --template-body file:///<full-file-path>.yaml
```
