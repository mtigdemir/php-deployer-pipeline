## How To Deploy PHP Application with Deployer via Bitbucket CI/CD

Please have a look at this article to find out how to use Deployer with self-build docker image and benefits of using your own image.

https://medium.com/@mtigdemir/php-deployment-with-deployer-to-aws-via-bitbucket-pipeline-a605763c63bf


## How to use Deployer Image with Bitbucket Pipeline 

### Available Versions

- PHP 7.1 (`mtigdemir\php-deployer-pipeline:7.1`)
- PHP 7.3 (`mtigdemir\php-deployer-pipeline:7.3.25`)

{% gist 1bb599d7fa5caad3ab647aad87fadc18 %}


Please note that, only PHP 7.1 tag uses Composer v1 and all the builds after that compatible with Composer v2