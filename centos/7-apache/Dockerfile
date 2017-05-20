FROM centos:7
RUN yum -y update && yum clean all
RUN yum install -y rpm-build redhat-rpm-config autoconf zlib-devel libselinux-devel libuuid-devel apr-devel apr-util-devel pcre-devel openldap-devel lua-devel libxml2-devel distcache-devel openssl-devel
RUN yum clean all
