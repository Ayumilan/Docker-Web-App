# Docker Web App

## Overview

A web app that uses RHEL8 system and perfom the docker opreations.

Stack:

- HTML,python
- Python CGI

## Develop locally

- Clone this repo by running `git clone https://github.com/Ayumilan/box-office.git`
- install docker and Apache HTTP Server(httpd) on your RHEL8 sytem (using required config files)
- Open `dockerweb.html` and edit line 141 from `xhr.open("GET","http://192.168.43.247/cgi-bin/docker.py?x="+i,true);` to
   `xhr.open("GET","http://IP_ADDRESS/cgi-bin/docker.py?x="+i,true);`
- Check the status of httpd server(i.e. running) and surf on localhost with port number.
