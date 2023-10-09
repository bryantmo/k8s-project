FROM mirrors.tencent.com/code/tomcat:11.7.23
MAINTAINER lekkoli lekkoli@tencent.com
WORKDIR /data/www/code-business-plugins-cr/latest/codeapp/
RUN rm -fr /data/www/code-business-plugins-cr/latest/codeapp/*&&rm -f /start
COPY code-business-plugins-cr/ /data/www/code-business-plugins-cr/latest/codeapp
COPY Dockerstart /start
RUN chmod +x /start
ENTRYPOINT ["/start"]
