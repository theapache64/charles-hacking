Hacking Charles Web Debugging Proxy

<http://www.gfzj.us/tech/2015/06/24/charles-hacking.html>

# Quick Setup

(Tested with `Ubuntu 16.04`)

## Installation

Install official version first

```
sudo apt-key adv --keyserver pgp.mit.edu --recv-keys 1AD28806 &&
sudo sh -c 'echo deb https://www.charlesproxy.com/packages/apt/ charles-proxy main > /etc/apt/sources.list.d/charles.list' &&
sudo apt-get update &&
sudo apt-get install charles-proxy
```

## Cracking

Then, download and replace original `charles.jar` with cracked `charles.jar`

```
wget https://github.com/HeIp/charles-hacking/raw/master/4.2.8/charles.jar &&
sudo rm /usr/lib/charles-proxy/charles.jar && 
sudo mv charles.jar /usr/lib/charles-proxy/
```
