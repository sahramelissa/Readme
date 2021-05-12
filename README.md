# Readme

https://github.com/goharbor/harbor/issues/13465
If you look at prepare script you will see
docker run ... -v /:/hostfs
change it to docker run ... -v /pathOfYourCert/certs:/hostfs
That will fix the problem :)

https://github.com/goharbor/harbor/issues/13461
same fix like https://github.com/goharbor/harbor/issues/13465
