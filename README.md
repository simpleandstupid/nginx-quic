# nginx-quic
[![build nginx-quic](https://github.com/Funny-T/nginx-quic/actions/workflows/build.yml/badge.svg)](https://github.com/Funny-T/nginx-quic/actions/workflows/build.yml)
[![build nginx-opensslquic](https://github.com/Funny-T/nginx-quic/actions/workflows/openssl.yml/badge.svg)](https://github.com/Funny-T/nginx-quic/actions/workflows/openssl.yml)


使用GitHub Action编译nginx-quic，基于最新[源码](https://hg.nginx.org/nginx)

[测试你的浏览器对quic的支持](https://quic.nginx.org/quic.html)
[测试服务器对HTTP/3的支持](https://http3check.net)

#[官方介绍](https://quic.nginx.org/readme.html)


To enable GSO (Generic Segmentation Offloading):

    quic_gso on;

    #By default this Linux-specific optimization is disabled.
    Enable if your network interface is configured to support GSO.

