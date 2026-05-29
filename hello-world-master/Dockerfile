'''
# Pull base image 
From tomcat:8-jre8 

# Maintainer 
MAINTAINER "valaxytech@gmail.com" 
COPY ./webapp.war /usr/local/tomcat/webapps
'''


FROM tomcat:8-jre8

MAINTAINER "[valaxytech@gmail.com](mailto:valaxytech@gmail.com)"

COPY target/*.war /usr/local/tomcat/webapps/webapp.war
