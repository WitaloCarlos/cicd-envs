# Gitlab Community Edition
## Docker Compose file

### Environment

a) Windows 10 with WSL2/Ubuntu 20 LTS (at home)
b) Ubuntu 20 LTS (at lab)

### Setup

- Create folder under /srv/ directory to host the containers volumes;
- Change the owner of directories: `sudo chown -R $USER /`

### References

- [Gitlab Docker Images - Official Docs](https://docs.gitlab.com/omnibus/docker/README.html)
- [Gitlab Environment Variables](https://docs.gitlab.com/ee/administration/environment_variables.html)