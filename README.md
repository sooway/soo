#soo
Hello World!
My first repository on Github


这个应该是会导致Unable to load client key -8178
你的系统应该是centos或fedora，他们上的好像是nss，debian/ubuntu上是openssl的
wget http://soft.vpser.net/lib/curl/curl-7.42.1.tar.gz
tar zxf curl-7.42.1.tar.gz && cd curl-7.42.1
./configure --prefix=/usr --without-nss --with-ssl
make &&make install

这样就能替换到原来的curl
