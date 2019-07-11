Deployed to https://hub.docker.com/r/jzheaux/cloudfoundry-uaa

You can run the sample Docker with:

```
docker run -e UAA_CONFIG_FILE=/etc/uaa/uaa.config -v `pwd`:/etc/uaa -p 8080 jzheaux/cloudfoundry-uaa
```
