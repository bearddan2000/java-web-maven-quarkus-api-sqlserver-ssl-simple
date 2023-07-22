# java-web-maven-quarkus-api-sqlserver-ssl-simple

## Description
A POC for quarkus web api
connecting to a sql server database.

Sql server uses self-signed ssl.

## Tech stack
- java
- maven
  - quarkus
  - hibernate
  - sql server connector
  - lombok
- ssl

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu
- maven:3-openjdk-17
- registry.access.redhat.com/ubi8/openjdk-11:1.11

## To run
`sudo ./install.sh -u`
curl -i localhost/dogs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
