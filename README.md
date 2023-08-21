# HAProxy Docker Container for Proxying HTTPS Traffic

This repository provides a Dockerized HAProxy setup for proxying STEEM API  traffic to backend servers. You can use this setup to quickly set up a reverse proxy for your applications.

## Usage

1. **Clone this Repository**

   ```bash
   git clone https://github.com/your-username/your-haproxy-repo.git
   cd your-haproxy-repo
#Build Docker image 

docker build -t my-haproxy .

# Run HAProxy using Docker Compose
docker-compose up -d
```
