# Humhub

Base on `adminrezo/docker-humhub` docker image

A social network without Big Brother

MariaDB is configured with default values (Go to variabes section)
## Howto

Just build it:

```docker build -t 13genius/humhub .```

run it:

```docker run --name humhub -d 13genius/humhub && docker inspect humhub |grep IPAddress```

enjoy it ! `https://your-container-ip/`

## Variables, and default values
```shell
GIT_MASTER_URL https://github.com/humhub/humhub/archive/master.zip
DB_DATABASE humhub
DB_USER humhub
DB_PASSWORD HuMhUb
```
