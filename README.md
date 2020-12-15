# postgres-tini

Use https://github.com/krallin/tini as PID 1

```
$ docker build -t mypg .

$ docker run --name pg -e POSTGRES_PASSWORD=abc@123 -d mypg
```
