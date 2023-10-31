# create stack
aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network-infra.yaml --parameters file://dev-parameter-file.jason


# destroy stack
aws cloudformation delete-stack     --stack-name dev-network-infra-pf



