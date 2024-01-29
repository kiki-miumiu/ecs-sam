#

## Prerequisites

### Setup CLI environment

```bash
export AWS_ACCESS_KEY_ID=""
export AWS_SECRET_ACCESS_KEY=""
export AWS_SESSION_TOKEN=""
aws sts get-caller-identity
```

## Deploy

### Local

```bash
aws cloudformation deploy --stack-name hello-world-ecs --template-file main.yml --capabilities CAPABILITY_IAM
```