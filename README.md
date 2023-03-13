# Caviar Productions website

Based on Freelancer theme

### Run local webserver for website development
Pre-requisites:
* Docker

```
docker run --rm --name httpd -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ httpd
```

And then open browser http://localhost:8080