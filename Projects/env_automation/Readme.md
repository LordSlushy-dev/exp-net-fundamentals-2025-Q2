## How to Deploy

### Check your AWS Account

```sh
aws sts get-caller-identity
```

```sh
cd Projects/env_automation
chmod u+x ./bin/deploy
./bin/deploy
```


> you only have to chmod the file once to make it executable.