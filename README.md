# TelinkBleMeshLib library for android device

## Installation

Add it in your root build.gradle at the end of repositories:

- Groovy DSL

```groovy
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

- Kotlin DSL

```kotlin
allprojects {
    repositories {
        ...
        maven(url = "https://jitpack.io")
    }
}
```

Add the dependency

- Groovy DSL

```groovy
dependencies {
    implementation 'com.github.nghi-nv:TelinkBleMeshLib:1.0.0'
}
```

- Kotlin DSL

```kotlin
dependencies {
    implementation("com.github.nghi-nv:TelinkBleMeshLib:1.0.0")
}
```

