# Lambda Layer for Python Libraries
When your Lambda need to import libraries, packaing all libraries along with your business logic is not recommended.  Instead you can upload libraries as Lambda Layers, so that multiple Lambda functions can access same layer.  This module will create an AWS Lambda Layer with ANY Python library you like.   

## Links
- [Documentation](https://cloudpedia.ai/terraform-module/aws-lambdalayer-python/)
- [Terraform module](https://registry.terraform.io/modules/cloudpediaai/lambdalayer-python/aws/latest)
- [GitHub Repo](https://github.com/CloudPediaAI/terraform-aws-lambdalayer-python)

## Related Terraform Modules from CloudPedia.AI

### Scheduled Job for AWS
- [Documentation](https://cloudpedia.ai/terraform-module/aws-scheduled-job/)
- [Terraform module](https://registry.terraform.io/modules/cloudpediaai/scheduled-job/aws/latest)
- [GitHub Repo](https://github.com/CloudPediaAI/terraform-aws-scheduled-job)

### Lambda Layer for Node.js Libraries
- [Documentation](https://cloudpedia.ai/terraform-module/aws-lambdalayer-nodejs/)
- [Terraform module](https://registry.terraform.io/modules/cloudpediaai/lambdalayer-nodejs/aws/latest)
- [GitHub Repo](https://github.com/CloudPediaAI/terraform-aws-lambdalayer-nodejs)
