# Redis Setup

## Installation
### clone repository
```shell
$ git clone https://github.com/mo-zza/redis-setup.git
```

### create environment file
|   variable name    |    description     | default value |
|:------------------:|:------------------:|:-------------:|
|     REDIS_PORT     |     redis port     |     6379      |
| REDIS_INSIGHT_PORT | redis insight port |     5540      |

```shell
$ cp .env.example .env
```

### start compose file
```shell
$ docker-compos up -d
```