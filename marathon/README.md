## Marathon docker-compose-examples
### Webports
- Marathon: 8085
- Mesos: 5050
### Test and Verify
a) Post Simple Docker App
- curl -X POST -H "Content-Type: application/json" localhost:8085/v2/apps -d@simple_docker.json
b) Check tasks in Mesos and Marathon
c) docker ps
