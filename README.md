# Server-conf
#Server Details:
 IP: 52.88.24.229
 DNS: http://www.ahmedserag.tk/
 password for grader: grader
#SSH connect:
 ssh -i "linxCourse.pem" grader@ec2-50-112-217-158.us-west-2.compute.amazonaws.com  -p 2200
#firewall:
 deny incoming
 allow ports 2200 / 80 / 123/
#installation
apachy 
mod-wsgi
python
pip
flask 
sqlalchemy 
PostgreSQL 
requests
#resources:
https://github.com/jaikathuria/FullStack-Project--8

