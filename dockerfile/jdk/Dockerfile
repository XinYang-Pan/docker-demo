FROM centos
MAINTAINER seanpan2008@gmail.com

RUN wget https://blueo.oss-cn-beijing-internal.aliyuncs.com/jdk-8u181-linux-x64.rpm
RUN yum localinstall -y jdk-8u181-linux-x64.rpm
RUN echo "export JAVA_HOME=/usr/java/default" > /etc/profile.d/java.sh
