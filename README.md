# AWSLogs Docker image

[![](https://badge.imagelayers.io/konjak/awslogs:latest.svg)](https://imagelayers.io/?images=konjak/awslogs:latest)

This image comes with the latest awslogs tool from https://github.com/jorgebastida/awslogs. I'm using it in a container so I don't need to install python on my host.

## Usage

```bash
docker run \
  -v ~/.aws:/root/.aws
  -e AWS_DEFAULT_PROFILE=your-profile-name-if-not-default
  konjak/awslogs
```

## Status

Production stable.

