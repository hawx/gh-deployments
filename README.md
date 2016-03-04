# gh-deployments

A shell script for creating GitHub deployments.

```sh
$ curl -o gh-deployments https://raw.githubusercontent.com/hawx/gh-deployments/master/gh-deployments
$ chmod +x gh-deployments
$ export GH_DEPLOYMENTS_USERNAME='my_username'
$ export GH_DEPLOYMENTS_TOKEN='personal_access_token'
$ ./gh-deployments pending example/repo my-branch 'http://example.com/deploymentoutput' staging-01
$ ./gh-deployments success example/repo my-branch 'http://example.com/testoutput' staging-01
# $ ./gh-deployments failure example/repo my-branch 'http://example.com/failureoutput' staging-01
```