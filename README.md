# java-cli-gradle-jacoco-junit-test-hello-world

## Description
A POC for gradle app using JUnit.
Uses test task to dump html and xml
to shared folder. Also dumps jacoco reports
to the same folder.

## Tech stack
- java
- gradle
  - junit
  - jacoco

## Docker stack
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept] (https://github.com/eugenp/tutorials/tree/master/maven-modules/maven-integration-test)
[Path to reports] (https://igorski.co/generating-junit-test-coverage-using-gradle-and-jacoco/)
