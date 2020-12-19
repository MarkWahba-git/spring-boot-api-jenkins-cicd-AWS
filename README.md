## Overview

A Jenkins Script Pipeline Example - Automation - CICD 
using Spring - boot API Image


## Pre-requisites

* JDK 11+
* Docker

## Building

### Testing

`./gradlew test`

### Building (no tests)

`./gradlew assemble`

### Building (with tests)

`./gradlew build`

### Running in Docker

`./gradlew assemble docker dockerRun`

### Stopping Docker container

`./gradlew dockerStop`

### Deleting AWS deployment

`./gradlew awsCfnDeleteStack awsCfnWaitStackComplete`

