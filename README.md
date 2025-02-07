# cloudformation_templates
Repository of CloudFormation templates and useful scripts to automate setup etc

<!-- Use variable for template file -->

<!-- Get parameters working -->
aws cloudformation create-stack
    --stack-name testing-stack
    --template-body file://bucket.yaml

<!-- Delete stack command -->
aws cloudformation delete-stack \
    --stack-name testing-stack
