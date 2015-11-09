# xlrstats-docker
A docker file for xlrstats

## How to use:
`docker run -d -p 80:80 -e ALLOW_OVERRIDE=true that0n3guy/xlrstats-docker`

## Config (optional)
If you want your configs to be stored on a volume, do something like:

`docker run -d -p 80:80 -e ALLOW_OVERRIDE=true -v /path/on/host:/app/Config that0n3guy/xlrstats-docker`
