Contributing to logstash by providing a debian/ directory to easily build a .deb package.

= Howto =

  * get logstash source

  * unpack logstash source (ex. logstash-5.1.1)

  * git clone https://github.com/unki/logstash-debian-package.git

  * cd logstash-debian-package

  * mv .\* ../logstash-5.1.1/

  * cd ../logstash-5.1.1/

  * dch -i

  * dpkg-buildpackage
