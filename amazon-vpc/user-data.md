#!/bin/bash
yum update -y
yum install -y httpd
systemctl start httpd
systemctl enable httpd

## This is a testing purpose for the course code to
## ensure it is the correct one
