FROM java:7

RUN apt-get update

RUN apt-get clean

ADD http://www.atlassian.com/software/jira/downloads/binary/atlassian-jira-6.3.11-x64.bin /opt/atlassian/

CMD atlassian-jira-6.3.11.bin -q -varfile response.varfile
