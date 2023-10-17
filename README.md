# Openproject with Gitlab Integration Plugin

## How to run

Pull the image from github registry:
```
docker pull ghcr.io/ferisetiyawan/openproject-gitlab-docker
```

then, run by using this command below:
```
docker run -d -p 8080:80 \
  -e OPENPROJECT_HTTPS=false \
  ghcr.io/ferisetiyawan/openproject-gitlab-docker
```