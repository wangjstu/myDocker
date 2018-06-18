# myDocker

learn docker

## OpenResty

### openresty-1.13

#### build images

- `cd openresty-1.13`
- ` sudo docker build -t="wangjstu/openresty-1.13:v1" .`
- `docker images`
- `sudo docker run -d -p 80:80 --name test_openresty-1.13 wangjstu/openresty-1.13:v1`
