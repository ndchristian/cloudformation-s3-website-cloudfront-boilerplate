# cloudformation-serverless-website-boilerplate

A [CloudFormation](https://aws.amazon.com/cloudformation/) template that deploys [CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html) distribution with a [S3](https://aws.amazon.com/s3/) bucket as the origin to host files for a static website. Also comes with a [lambda edge](https://aws.amazon.com/lambda/edge/) function to handle [HTTP security headers](https://www.keycdn.com/blog/http-security-headers).

## Notes
Since this uses lambda edge, this needs to be deployed into us-east-1.

Assumptions:
- Possession of an [AWS account](https://aws.amazon.com/account/)
- Hosted Zone in [Route53](https://aws.amazon.com/route53/) with desired domain name
- [ACM](https://aws.amazon.com/certificate-manager/) Certificate

Recommendations:
- Add logging to S3 bucket
- Add logging to CloudFront distribution
- Tailor security headers

## Support

Please open an [issue](https://github.com/ndchristian/cloudformation-serverless-website-boilerplate/issues) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and open a pull request.
