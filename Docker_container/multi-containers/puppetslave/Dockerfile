FROM centos:7

MAINTAINER thijs.schnitger@container-solutions.com


RUN rpm -ivh http://yum.puppetlabs.com/puppetlabs-release-el-7.noarch.rpm
RUN yum -y install puppet hostname git unzip epel-release
RUN yum clean all

CMD ["/sbin/init"]
