# **Pycurl-Docker-default**

Python:3.9-Alpine latest with pycurl - default ( **not support TLS1.3 and Http3** )

## **Repository**

**Github :** [https://github.com/qiandao-today/pycurl-docker-default](https://github.com/qiandao-today/pycurl-docker-default)

**DockerHub :** [https://hub.docker.com/r/a76yyyy/pycurl](https://hub.docker.com/r/a76yyyy/pycurl)

```bash
docker pull a76yyyy/pycurl:default-latest
```

## **VERSION**

- PYTHON_VERSION == 3.9
- CURL_VERSION == 7.80.0
- OPENSSL_VERSION == 1.1.1l-r8
- PYCURL_VERSION == 7.44.1

```bash
./configure \
    --with-ssl \
    --with-nghttp2=/usr \
    --prefix=/usr \
    --enable-ipv6 \
    --enable-unix-sockets \
    --without-libidn \
    --disable-static \
    --disable-ldap \
    --with-pic
```
