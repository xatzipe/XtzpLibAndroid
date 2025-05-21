# XtzpLibAndroid

XtzpLibAndroid is an Android library project providing reusable Kotlin utilities and components. It is structured for easy integration and testing, following best practices for Android library development.

## Features
- Modular Kotlin codebase
- Unit and instrumentation tests
- Gradle-based build system

## Getting Started

### Prerequisites
- Android Studio (latest recommended)
- JDK 17 or later
- Gradle 8.x or later

### Installation
Add the library as a dependency in your `build.gradle`:

```groovy
dependencies {
    implementation 'io.github.xatzipe:xtzplib:1.0.0'
}
```

### Usage
Import and use the provided classes in your Android project:

```kotlin
import io.github.xatzipe.xtzplib.SimpleCalculator

val calc = SimpleCalculator()
val result = calc.add(2, 3)
```

## Testing
Run unit and instrumentation tests with:

```bash
./gradlew test
./gradlew connectedAndroidTest
```

## License
See [LICENSE](LICENSE) for details.
