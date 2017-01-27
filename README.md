# docker-write-mime-multipart
Dockerized [write-mime-multipart](http://manpages.ubuntu.com/manpages/trusty/man1/write-mime-multipart.1.html)

## Usage

```
$ docker pull tsub/write-mime-multipart
$ mkdir $HOME/.bin
$ curl -L https://raw.githubusercontent.com/tsub/docker-write-mime-multipart/master/bin/write-mime-multipart -o $HOME/.bin/write-mime-multipart
$ chmod +x $HOME/.bin/write-mime-multipart
$ export PATH=$HOME/.bin:$PATH
$ write-mime-multipart userdata.sh:text/x-shellscript cloud_boothook.sh:text/cloud-boothook
```

### Install with [Whalebrew](https://github.com/bfirsh/whalebrew)

```
$ whalebrew install tsub/write-mime-multipart
```
