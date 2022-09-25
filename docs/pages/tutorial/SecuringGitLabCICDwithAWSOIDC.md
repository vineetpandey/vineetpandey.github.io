# Securing GitLab CI/CD with AWS OIDC

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Problem Statement -

* With Gitlab CI/CD, key rotation is a major challenge for any organisation since there is not about just one repository to handle but could be many
* CIS benchmark for AWS recommends to rotate the credentials every 90 days to safeguard the secrets
* Tracking and rotating the keys - since there could be multiple repositories and chances of missing out on credentials rotation would be pretty high
* Also, there could be multiple repercussions & use-cases that can have differing views with different needs. So, this list can potentially be huge in the real world

## Solution Concept -
* To get rid of this key rotation headache, let's move to OIDC supported by AWS
* OIDC (OpenID Connect) is an authentication layer on top of the OAuth 2.0 framework.

    * It is used to authenticate identities with an external identity provider
    * No involvement of keys therefore no such pain of key management
    * AWS provides support to create and manage an OIDC provider such as facebook, google, etc.

## How to Configure
1. ***Configuring AWS***
    1. *Search for IAM in AWS services and open the IAM console. Click on the “Identity providers” section at left*
1. Hi-tech
    1. d
## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
