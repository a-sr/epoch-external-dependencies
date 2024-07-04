# Epoch External Dependencies

This repository wraps prebuilt jars of maven dependencies that are not available (at the time) on p2 updatesites into Eclipse plugins for use in the Epoch IDE.
The artifacts are pulled from maven central and redistributed via an Eclipse p2 repository acting as a mirror.

## Content

The main directories of the repository are the following:

- *org.lflang.epoch.mirror.kotlin* The plugin containing the jars of Kotlin
- *org.lflang.epoch.mirror.json* The plugin containing the jars of org.json
- *org.lflang.epoch.mirror.jcip* The plugin containing the annotations of org.jcip
- *org.lflang.epoch.mirror.json* The plugin containing the jars of com.hubspot.jinjava
- *org.lflang.epoch.external.dependencies* A legacy alias of *org.lflang.epoch.mirror.kotlin*
- *org.lflang.epoch.external.dependencies.repository* The p2 repository

## Kotlin

You can find the Kotlin source code at: https://github.com/JetBrains/kotlin
The code is made available under the Apache License, Version 2.0, which can be read in the LICENSE file.

Maven central source: https://mvnrepository.com/artifact/org.jetbrains.kotlin

## Json

Maven central source: https://mvnrepository.com/artifact/org.json/json

## JCIP

Maven central source: https://mvnrepository.com/artifact/net.jcip/jcip-annotations

## Jinja

Maven central source: https://mvnrepository.com/artifact/com.hubspot.jinjava/jinjava

