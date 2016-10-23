# Base aarch64 Docker images for JBoss community projects with JDK

This repository contains images used as a base image for *all* JBoss community images that require Java Development Kit.

## Types of images

Currently this repository contains following images:

1. JDK 7 (in the `aarch64-jdk7` branch)
2. JDK 8 (in the `aarch64-jdk8` branch)

Both images **extend** the `project31/aarch64-jboss-base:latest` image and add latest OpenJDK distribution for selected version. Additionally a `JAVA_HOME` environment variable is set.

## Availability

Both images are built on Docker HUB and available for immediate pull from the public registry.

### OpenJDK 7

    docker pull project31/aarch64-jboss-base-jdk:7

### OpenJDK 8

    docker pull project31/aarch64-jboss-base-jdk:8
    
## Issues

All issues should be reported in the [GitHub issue tracker](https://github.com/JBoss-Dockerfiles/base-jdk/issues).
