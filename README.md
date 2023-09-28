# groovy-cli-maven-postgresql-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

A groovy maven build, that connects to postgresql database.

## Tech stack
- groovy
- maven
  - log4j
  - postgresql drivers

## Docker stack
- postgresql:alpine
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
