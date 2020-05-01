# Binbash - Ansible Role: Jenkins Github OAuth

Ansible role for installing and configuring Github OAuth on Jenkins

## Requirements
* Jenkins with Github OAuth plugin installed => https://plugins.jenkins.io/github-oauth/

## Examples
```
  - role: binbash_inc.jenkins-github-oauth
    jenkins_github_oauth_client_id: "your-github-oauth-client-id"
    jenkins_github_oauth_client_secret: "your-github-oauth-client-secret"

```
