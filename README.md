# Graylog environment
## Environment variables
* `GRAYLOG_PASSWORD_SECRET`
* `GRAYLOG_ROOT_PASSWORD_SHA2`
* `GRAYLOG_HTTP_EXTERNAL_URI`

Password `admin` is SHA2 `8c6976e5b5410415bde908bd4dee15dfb167a9c873fc4bb8a81f6f2ab448a918`

## Run

`docker-compose -f docker-compose.yml up`

## Work

Login to graylog with opening http://127.0.0.1:9000/ in the browser
* Username: `admin`
* Password: `admin`