### Nextcloud + OnlyOffice + Redis


### 1. Setup

Run the docker-compose.yml:

```
sudo docker-compose up -d
```


### 2. After setup

Check that the background jobs, in nextcloud configuration (webpage, not files) is checked to cron

### 3. What is installed

* Nextcloud
* Redis for Nextcloud
* OnlyOffice DocumentServer protected with jwt-secret password (environment variable)


