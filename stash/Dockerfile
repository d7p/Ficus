FROM java:7

RUN apt-get update

RUN apt-get clean

ADD http://www.atlassian.com/software/stash/downloads/binary/atlassian-stash-3.5.0-x64.bin /opt/atlassian/

CMD atlassian-stash-3.5.0.bin -q -varfile response.varfile
