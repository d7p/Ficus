FROM java:7

RUN apt-get update

RUN apt-get clean

ADD http://www.atlassian.com/software/confluence/downloads/binary/atlassian-confluence-5.6.5-x64.bin /opt/atlassian/

CMD atlassian-confluence-5.6.5.bin -q -varfile response.varfile
