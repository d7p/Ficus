FROM java:7

RUN apt-get update

RUN apt-get clean

ADD http://www.atlassian.com/software/jira/downloads/binary/atlassian-jira-6.3.11-x64.bin /opt/atlassian/

ADD ./responce.varfile /opt/atlassian/

VOLUME ./jira-home:/var/atlassian/application-data

# in prod use -q not -fg
CMD /opt/atlassian/atlassian-jira-6.3.11.bin -fg -varfile response.varfile
