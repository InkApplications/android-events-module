Android Events Module
=====================

A Module for including Android livecycle events using Otto Event Bus.

Installation
------------

You can include this into your project using gradle:

```groovy
    compile 'com.inkapplications:android-events-module:{VERSION}'
```

or maven:
```
    <dependency>
      <groupId>com.inkapplications</groupId>
      <artifactId>android-events-module</artifactId>
      <version>{VERSION}</version>
    </dependency>
```

And then include it in your application module:
```java
    @Module(
        includes = {
            AndroidEventsModule.class
        },
        // ...
    }
    // ...
```
