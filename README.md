# Redis Setup

## Installation
### clone repository
```shell
$ git clone https://github.com/mo-zza/redis-setup.git
```

### create environment file
| variable name  |  description   | default value |
|:--------------:|:--------------:|:-------------:|
|   REDIS_PORT   |   redis port   |     6379      |
| REDIS_PASSWORD | redis password |               |

```shell
$ cp .env.example .env
```

### start compose file
```shell
$ docker-compos up -d
```