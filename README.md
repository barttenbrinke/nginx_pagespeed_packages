Based on https://sysadminblog.net/2014/05/nginx-google-pagespeed-debian-package/

Uploaded to Github, because nobody should really try to compile Google pagespeed with Passenger into NGINX for Ubuntu 14.04 LTS Trusty...

Install With Passenger Opensource (4.0.45):

  dpkg -i nginx-full_1.6.0-1+trusty0ubuntu2_amd64.deb nginx-common_1.6.0-1+trusty0ubuntu2_all.deb nginx-doc_1.6.0-1+trusty0ubuntu2_all.deb

Install With Passenger Enterprise (4.0.48):

  dpkg -i nginx-full_1.6.0-1+trusty0ubuntu3_amd64.deb nginx-common_1.6.0-1+trusty0ubuntu3_all.deb nginx-doc_1.6.0-1+trusty0ubuntu3_all.deb
