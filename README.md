
<div align="center">
<h1 align="center"> awesome-docker-compose </h1>
<p align="center">
The awesome-compose repository was created to provide a quick and simple way for developers to experience Compose-based setups with different software stacks.
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Maintainer-cyril@liaosirui.com-blue.svg" alt="Maintainer">
  <img src="https://img.shields.io/badge/Language-DockerCompose-green.svg" alt="Language">
</p>
</div>

## Usage

Create docker network public

```bash
docker network create \
    --driver bridge \
    --subnet 172.28.1.0/24 \
    --gateway 172.28.1.254 public
```
