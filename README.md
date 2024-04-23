# UpperDeck server images

This is the source repository for building UpperDeck server images. It was forked from [Snikket service](https://snikket.org/service/)
Docker images.

UpperDeck is an open-source self-hosted personal messaging service. It aims to
provide an alternative to proprietary and centralized messaging platforms
while supporting all the expected features and being easy to use.


### Requirements

 - GNU make
 - docker (tested on 19.03.5)
 - ansible (tested on 2.7 (debian buster))

### Building

Run `make`

### Running

The easiest way is to use docker-compose. Copy the file `snikket.conf.example` to
`snikket.conf` and edit the values in it. Then run:

```console
docker-compose up -d
```
### Todo

Replace snikket brand with UDC branding.
