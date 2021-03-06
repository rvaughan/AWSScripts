# AWS Scripts
Various AWS Automation Scripts

A collection of shell scripts for automating various security tasks with Amazon Web Services.<br>
You will need the [AWS-CLI](https://aws.amazon.com/cli/) installed and configured to make this work correctly.

## Scripts

**_WAF/WAF.SH_**: Creates a WAF using cloud formation and a rules template.<br>
Usage:  ./waf.sh policy-name.

**_ACM/acmdigicert.sh_**: Creates Digicert TLS certificates using their API and uploads them to ACM.<br>
Usage:  ./acmdigicert.sh FQDN.<br>
More Details [Here](https://jerrygamblin.com/2017/11/04/automating-digicert-certificates-into-aws-acm/)

**_EC2/noingress.sh_**: Lists all in-use security groups that allow 0.0.0.0/0 for your inspection.

**_EC2/notused.sh_**: Lists all unused security groups that can likely be removed.

## Important Notice
*I likely dont know what I am doing and this could be done faster, better and simpler some other way. These scripts could also break your cloud and make you cry.*
