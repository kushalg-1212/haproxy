# HAProxy Docker Container for Proxying HTTPS Traffic

This repository provides a Dockerized HAProxy setup for proxying HTTPS traffic to backend servers. You can use this setup to quickly set up a reverse proxy for your applications.

## Usage

```bash
# Clone this Repository
git clone https://github.com/kushalg-1212/haproxy.git
cd your-haproxy-repo

# Build the Docker Image
docker build -t my-haproxy .

# Validate Configuration Syntax
docker run -it --rm --name haproxy-syntax-check my-haproxy haproxy -c -f /usr/local/etc/haproxy/haproxy.cfg

# Run HAProxy using Docker Compose
docker-compose up -d


