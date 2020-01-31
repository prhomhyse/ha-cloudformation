# Udagram - Demonstration of a high availability infrastructure using AWS CloudFormation

## Description

This project gives actual experience needed to talk about Infrastructure as Code.
**Udagram** can be any applicatio of choice. I chose it to be a simple HTML page for proof of concept. This is a case scenario where the application will be deployed in Apache and its existing static content pulled from S3 storage.

This project is made of two parts:

- A developed High Availability diagram (drawn from LucidChart)
- Creating the CloudFormation script that intepretes the above diagram

## Create the stack

```sh
./create.sh myStackName infra.yml infra-params.json
```

Note: `myStackName` can be anything you want.

## Update the stack
```sh
./update.sh myStackName infra.yml infra-params.json
```