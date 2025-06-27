## How to deploy

### Check your AWS Account

```
aws sts get-caller-identity
```
This command will let you know your AWS CLI is configured under which account.

If you have not configured you AWS account in the CLI, first do that by running below command, and passing on the respective access key values that is generated for the user account in IAM.

```
aws configure
```

### Deploying the cloud formation template

```
cd project/env_automation
chmod u+x ./bin/deploy
./bin/deploy
```

The file permission for ```deploy``` needs to be changed only once, to set it to executable.

