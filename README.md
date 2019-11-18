<p align="center">
  <img src="https://user-images.githubusercontent.com/3791941/31036931-072760fe-a534-11e7-8cd7-0565bdc2727c.png" width="100" height="60">

  <h3 align="center">Workshop: Continuous Delivery with GitHub Actions<br></h3>

  <p align="center">
    <a href="https://githubuniverse.com/">Universe Program</a>
  </p>
</p>

#### Prerequisites

1. [GitHub account](https://github.com/join) with a [verified email address](https://help.github.com/en/articles/verifying-your-email-address)
1. [Install GitHub Learning Lab](https://lab.github.com/docs/install) on your account
1. Sign up for the [GitHub Actions beta](https://github.com/features/actions/signup/?account=)
1. Sign up for the [GitHub Package Registry beta](https://github.com/features/package-registry)
1. Create a [GitHub Personal Access Token](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line) for your account.
1. [AWS Account](https://portal.aws.amazon.com/billing/signup?p=s3&cp=bn&ad=p#/start) 
    - The following permissions will be necessary for the second lab
    - Note: These are all `FullAccess`, which is not needed for production, but the permissions can be made more granular
      - AmazonEC2FullAccess
      - CloudFormationAllAccess
      - AmazonAPIGatewayAdministrator
      - AmazonS3FullAccess
      - AWSLambdaFullAccess
      - IAMFullAccess
1. Create an [AWS S3 bucket](https://aws.amazon.com/s3/getting-started/?nc=sn&loc=5)
    - Note: You will need to sign up for S3 in addition to your normal account, if you haven't already
1. Both [AWS Secret key and AWS Access Key](https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html#access-keys-and-secret-access-keys)

#### Optional (For the Full Experience)

1. Install [Docker](https://www.docker.com/) locally on your machine
    - [Windows](https://docs.docker.com/docker-for-windows/install/)
    - [Mac](https://docs.docker.com/docker-for-mac/install/)
    - [Linux](https://docs.docker.com/v17.12/install/#server)
1. [Configure](https://help.github.com/en/github/managing-packages-with-github-package-registry/configuring-docker-for-use-with-github-package-registry#authenticating-to-github-package-registry) Docker use the GitHub Package Registry

#### Getting Started

This workshop encompasses two Learning Lab courses
  - [Learning Lab: Using GitHub Actions for CD](https://lab.github.com/githubtraining/github-actions:-publish-to-github-package-registry)
  - [Learning Lab: Continuous Delivery with GitHub Actions](https://lab.github.com/githubtraining/github-actions:-continuous-delivery)
  
You can also follow [all of the workshops from Universe](https://lab.github.com/githubtraining/paths/github-universe-workshops)
