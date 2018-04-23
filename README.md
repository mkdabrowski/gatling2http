# Gatling2Http
Script works on data from standard input
# Options
  * -e or blank makes script send http request
  * -c produce curl on output
  * --host allows to change host of the request. When using localhost make sure to use http://localhost because script assumes https when not specified
# Installation
```
git clone https://github.com/worekleszczy/gatling2http
cd gatling2http
stow bin -t /usr/bin
or
ln -s `pwd`/bin/g2h --target /usr/local/bin/g2h
```
