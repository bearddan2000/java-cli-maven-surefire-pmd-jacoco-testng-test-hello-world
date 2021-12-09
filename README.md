# java-cli-maven-surefire-pmd-jacoco-testng-test-hello-world

## Description
A POC for maven app using testNg
framework with jacoco, pmd, and surefire
plugins.

## Tech stack
- java
- maven
  - testNg
  - jacoco
  - surefire
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- pmd report found at bin/target/site

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
- [Jacoco config](https://www.baeldung.com/jacoco)
