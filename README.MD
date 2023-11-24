# Forge Yourself

Allows you use vanilla registry in forge mod that be like fabric work.

Enjoy!

# Source?

This mod is close-source. This is only for uploading mod files and reporting issues.

# How to use?

Add to your build.gradle:

```gradle
repositories {
    maven {
        name = "Modrinth"
        url = "https://api.modrinth.com/maven"
    }
}

dependencies {
    // Don't forget set property in your gradle.properties!
    modImplementation "maven.modrinth:fys:${fys_version}"
}
```
