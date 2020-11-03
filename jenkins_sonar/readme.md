# Jenkins & Sonar
## Docker Compose file to setup both services

### Environment

a) Windows 10 with WSL2/Ubuntu 20 LTS (at home)
b) Ubuntu 20 LTS (at lab)

### Setup

- Create folder under /srv/ directory to host the containers volumes;
- Change the owner of directories: `sudo chown -R $USER /`
- Increase Virtual Memory for Elastisearch instance from Sonarcube container: `sudo sysctl -w vm.max_map_count=262144`

### References

- [Install Jenkins using Docker - Official Docs](https://www.jenkins.io/doc/book/installing/docker/)
- [Install a SonarQube server - Official Docs](https://docs.sonarqube.org/latest/setup/install-server/)

