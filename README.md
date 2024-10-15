# At-Bay Assignment Implementation - DEV

> This is the `Hello World!` "website" implementation for [At-Bay Assignment Implementation - OPS](https://github.com/mbstr/at-bay-assignment-ops)

The CI/CD pipeline is triggered by `push` events to this repository and is configured to take the contents of `HelloWorld.html` file and deploy them to AWS.
Go to [`https://d2huye70zjd203.cloudfront.net/`](https://d2huye70zjd203.cloudfront.net/) to access the "website".

__Note:__ After making changes to this repository, give it a minute or two for the site to update: the pipeline takes a few seconds and the CloudFront cahe has its TTL as well.
