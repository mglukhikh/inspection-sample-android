# Inspection plugin example for Android project

To run inspection plugin for `:app` module, execute: `gradlew :app:inspections`.

The important configuration part is `task inspections` inside `app/build.gradle`.

Note: this project use experimental inspection plugin version `0.3.0.20181009` which fixes some Android-related bugs.
 