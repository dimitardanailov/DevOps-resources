# AWS CloudFormation

### AWS CloudFormation VPC

Command:

```bash
aws cloudformation create-stack --stack-name myfirsttest --region us-west-2 --template-body file://testcfn.json
```

Output: 

```bash
{
    "StackId": "arn:aws:cloudformation:us-west-2:497430998518:stack/myfirsttest/..."
}
```

Resources:
- [AWS CloudFormation VPC Template](https://docs.aws.amazon.com/codebuild/latest/userguide/cloudformation-vpc-template.html)