# Deploy a high-availability web app using CloudFormation

Application URL: http://serve-webap-xn3cmnrgdcbd-1351043148.us-west-2.elb.amazonaws.com/

<br>

To deploy your stack use this snippet after signing in to your AWS account in AWS CLI tool use this:
```bash
~$ ./deploy.sh INFRA_STACK_NAME SERVERS_STACK_NAME
```

For Executing each script on it's own use this script
```bash
~$ ./create.sh STACK_NAME STACK_TEMPLATE.yaml STACK_PARAMETERS.json
```

To Update a stack use this:

```bash
~$ ./update.sh STACK_NAME STACK_TEMPLATE.yaml STACK_PARAMETERS.json
```
Notes:
* I'm using us-west-2 Region