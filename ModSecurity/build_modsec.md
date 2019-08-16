# Ubuntu 
```
$ sudo apt-get install g++ flex bison curl doxygen libyajl-dev libgeoip-dev libtool dh-autoreconf libcurl4-gnutls-dev libxml2 libpcre++-dev libxml2-dev
$ cd /opt/
$ git clone https://github.com/SpiderLabs/ModSecurity
$ cd ModSecurity/
$ git checkout -b v3/master origin/v3/master
$ sh build.sh
$ git submodule init
$ git submodule update #[for bindings/python, others/libinjection, test/test-cases/secrules-language-tests]
$ ./configure
$ make
$ make install
```

Done build mod security lib

Get nginx source :

```
wget http://nginx.org/download/nginx-1.16.1.tar.gz
tar -xzvf nginx-1.16.1.tar.gz
```


Install dependencies:

```

```
