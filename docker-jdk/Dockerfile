FROM wangenzhi/alpine:alpine-glibc
MAINTAINER <WangEnZhi W_enzhi@163.com>

ENV JAVA_HOME="/usr/local/jdk"
ENV CLASSPATH=".:${JAVA_HOME}/jre/lib/rt.jar:${JAVA_HOME}/lib/tools.jar"
ENV PATH="${JAVA_HOME}/bin:${PATH}"

ADD jdk-8u121-linux-x64.tar.gz /usr/local/
RUN ln -s /usr/local/jdk1.8.0_121/ /usr/local/jdk
