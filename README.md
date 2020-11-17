# cisummarizer

Generates a report summarizing the results from PMD, Checkstyle, and JUnit 5 runs.

Uses Gradle.

Has an important plugin (https://github.com/johnrengelman/shadow) to handle the making of "fat jars" like  `cisummarizer-all.jar`.

If you want to build a new jar, you'll need to run the `shadow > shadowjar` Gradle task. The jar will go to `build/libs`.

