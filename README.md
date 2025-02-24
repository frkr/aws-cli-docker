# Docker AWS Cli updated every thursday

```shell
docker run --rm \
--env AWS_ACCESS_KEY_ID=a \
--env AWS_SECRET_ACCESS_KEY=z \
--env AWS_DEFAULT_REGION=us-east-1 \
frkr/aws-cli \
aws $@
```

```shell
./awscli.sh --version
```
