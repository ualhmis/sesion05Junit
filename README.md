# Sesion05 JUnit
[![Build Status](http://cnsa19jenkins.eastus2.cloudapp.azure.com/buildStatus/icon?job=sesion05JUnit)](http://cnsa19jenkins.eastus2.cloudapp.azure.com/view/HMIS/job/sesion05JUnit/)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ualhmis_sesion05Junit&metric=alert_status)](https://sonarcloud.io/dashboard?id=ualhmis_sesion05Junit)

Ejercicios de la sesion 05 con JUnit. Proyecto de ejemplo del Ejercicio 1 y Ejercicio 2, mavenizado. 

Resuelto con JUnit 5 y test parametrizados. 

Construido en Travis-ci.

SonarCloud.io (https://sonarcloud.io/project/configuration?analysisMode=GitHubAutoScanWaitCommits&id=ualhmis_sesion05Junit)

Para lanzar el análisis de Sonar con maven desde Eclipse:
1. Genera el login [token](https://docs.sonarqube.org/latest/user-guide/user-token/)
2. Ejecuta los goals de maven: clean verify sonar:sonar -Dsonar.login=$SONAR_LOGIN_TOKEN
