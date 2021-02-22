# stu-docker-proxy
Docker Proxy Environment for Web services with LetsEnrypt Certificate implementation

## Usage
- Install Docker and Docker-Compose on Development or Production System
- run *'docker-compose -d up proxy'*&nbsp; or *'proxy_up.sh'*&nbsp; to spin up proxy serving on ports 80 and 443
- run other containers with VIRTUAL_HOST and LETSENCRYPT env-Vars as templated in *'sample.yml'* file
- Take down with *'docker-compose down'*&nbsp; or *'proxy_down.sh'*&nbsp;