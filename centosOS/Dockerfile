FROM centos:latest
USER root

COPY result.txt /home/resultFolder/
COPY result.txt /home/resultFolderV2222/
# COPY resultV2.txt /home/resultFolder/
# RUN apt install stress
RUN yum update
RUN yum install stress

ENTRYPOINT ["tail", "-f", "/dev/null"]