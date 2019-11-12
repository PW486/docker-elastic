<h1 align="center">🐳 Docker Elastic Stack</h1>
<p align="center">
  <a href="https://travis-ci.com/PW486/docker-elastic">
    <img alt="Travis (.com)" src="https://img.shields.io/travis/com/PW486/docker-elastic.svg?style=flat-square">
  </a>
  <a href="https://github.com/PW486/docker-elastic/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/PW486/docker-elastic?style=flat-square&color=yellow">
  </a>
  <a href="https://github.com/PW486/docker-elastic/network">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/PW486/docker-elastic?style=flat-square">
  </a>
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/PW486/docker-elastic.svg?style=flat-square&color=red">
  <a href="https://github.com/PW486/docker-elastic/blob/master/LICENSE">
    <img alt="GitHub license" src="https://img.shields.io/github/license/PW486/docker-elastic?style=flat-square">
  </a>
</p>

> NGINX log visualization provided by Elastic Stack

<p align="center">
  <img alt="NGINX + Elastic Stack" src="https://user-images.githubusercontent.com/14247340/68681377-a5a53880-05a6-11ea-80e1-b1844093ae4b.png">
</p>

## Requirements

- [Docker Engine](https://docs.docker.com/install)
- [Docker Compose](https://docs.docker.com/compose/install)

## Usage

```
$ docker-compose build
$ docker-compose up -d
```

### Generate NGINX log

```
$ curl http://localhost:8080
$ tail -f nginx/access.log
```

### Dashboard

![Kibana Dashboard](https://user-images.githubusercontent.com/14247340/68677923-447a6680-05a0-11ea-8f63-96e37b063a74.png)

> Enter Kibana Dashboard at http://localhost:5601

## Reference

- [stack-docker](https://github.com/elastic/stack-docker)
- [docker-elk](https://github.com/deviantony/docker-elk)
- [advanced-pipeline](https://www.elastic.co/guide/en/logstash/current/advanced-pipeline.html)

## License

Copyright © 2019 [DONGGEON LIM](https://github.com/PW486).<br />
This project is [MIT](https://github.com/PW486/docker-elastic/blob/master/LICENSE) licensed.