# cloudformation-s3-website-with-cloudfront-boilerplate

A [CloudFormation](https://aws.amazon.com/cloudformation/) template that deploys [CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html) distribution with a [S3](https://aws.amazon.com/s3/) bucket as the origin to host files for a static website. Also comes with a [lambda edge](https://aws.amazon.com/lambda/edge/) function to handle [HTTP security headers](https://www.keycdn.com/blog/http-security-headers).

## Notes
This assumes you have an [AWS account](https://aws.amazon.com/account/). Since this uses lambda edge, this needs to be deployed into us-east-1.

## Support

Please open an [issue](https://github.com/ndchristian/cloudformation-s3-website-cloudfront-boilerplate/issues) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and open a pull request.