# Overview
Simple ilspy docker image. Helpful bash function:

```bash
function ilspy { sudo docker run -it --rm -v $PWD:/ilspy bannsec/ilspy_docker /bin/sh -c "cd /ilspy && ilspycmd  $@";}
```

# Useage
Run the bash function definition above, then use the following to decompile the binary:

```bash
ilspy binary.exe > binary.cs
```
