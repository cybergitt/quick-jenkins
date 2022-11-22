# Quick Jenkins
This is the Dockerized Jenkins Automation Server powered by Docker In Docker (dind) & Docker Compose

# Usage
```bash
docker compose up -d
```

after installing Your Jenkins service will host at [https://localhost:8080](http://localhost:8080/) (Default port).

go to [/jenkins-data/secrets/initialAdminPassword](/jenkins-data/secrets/initialAdminPassword) and use key inside that file to login.
or use 
```
bash ./scripts/getPW.bash
```