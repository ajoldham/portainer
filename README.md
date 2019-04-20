Portainer Docker Compose
========================

Portainer is a useful graphical utility to visualize a Docker environment.

To download the Docker Compose file:

```php
git clone https://github.com/ajoldham/portainer
```

Run with:
```php
cd portainer
docker-compose up -d
```

this will download a pre-built image from Docker Hub and also start Portainer automatically when Docker is loaded.

Connect with:
```php
http://127.0.0.1:9000
```

<br>
<br>

Update Portainer to the latest version any time with:  
```php
docker pull portainer/portainer
```
