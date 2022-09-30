This repository wraps prebuilt jars of the Kotlin project into an Eclipse plugin for use in the Epoch IDE.

You can find the Kotlin source code at: https://github.com/JetBrains/kotlin
The code is made available under the Apache License, Version 2.0, which can be read in the LICENSE file.

The artifacts are pulled from maven central (https://mvnrepository.com/artifact/org.jetbrains.kotlin) and redistributed via an Eclipse p2 repository.


The main directories of the repository are the following:

- *org.lflang.epoch.external.dependencies* The plugin containing the jars of Kotlin to be avaible as Eclipse plugin
- *org.lflang.epoch.external.dependencies.repository* The p2 repository
