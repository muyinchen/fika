# Fika
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.speedment.fika/fika/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.speedment.fika/fika)
[![Hex.pm](https://img.shields.io/hexpm/l/plug.svg?maxAge=2592000)]()

"Fika" is a Swedish word that means "Coffee with something to it", and that is exactly what this project is about - a collection of general purpose modules for various Java projects.

## Included modules
Each module in this project is designed to work as an independant component. Below is a list of the included modules with links to their individual project pages:

### [CodeGen](https://github.com/speedment/fika/wiki/CodeGen)
An object-oriented code generator for Java that is built using the Model-View-Controller (MVC) design philosophy.
```xml
<dependency>
    <groupId>com.speedment.fika</groupId>
    <artifactId>codegen</artifactId>
    <version>2.4.0</version>
</dependency>
```

### [Lazy](https://github.com/speedment/fika/wiki/Lazy)
An utility used in [Speedment](https://github.com/speedment/speedment) that can be used for lazy initialization. It contains a generic ```Lazy<T>``` class, specialized Lazy classes for some primitive classes (```LazyInt```, ```LazyLong``` and ```LazyDouble```) and a number of specialized Lazy classes including ```LazyString```, ```LazyBooelan```, ```LazyByte```, ```LazyShort``` and many more. 
```xml
<dependency>
    <groupId>com.speedment.fika</groupId>
    <artifactId>lazy</artifactId>
    <version>1.0.0</version>
</dependency>
```

### [Logger](https://github.com/speedment/fika/wiki/Logger)
An lightweight logging framework inspired by Tengil.
```xml
<dependency>
    <groupId>com.speedment.fika</groupId>
    <artifactId>logger</artifactId>
    <version>1.0.0</version>
</dependency>
```

### [MapStream](https://github.com/speedment/fika/wiki/MapStream)
An utility class that expands the Java 8 Stream API to work with native Key-Value pair collections like `Map`. 
```xml
<dependency>
    <groupId>com.speedment.fika</groupId>
    <artifactId>mapstream</artifactId>
    <version>2.3.2</version>
</dependency>
```

### [RestUp](https://github.com/speedment/fika/wiki/RestUp)
A simple API for connecting to an existing REST API:s from Java.
```xml
<dependency>
    <groupId>com.speedment.fika</groupId>
    <artifactId>restup</artifactId>
    <version>1.0.1</version>
</dependency>
```

### [Reactor](https://github.com/speedment/fika/wiki/Reactor)
An extension to [Speedment](https://github.com/speedment/speedment) that polls the database at a regular interval to produce a materialized object view (MOV) of a particular table.
```xml
<dependency>
    <groupId>com.speedment.fika</groupId>
    <artifactId>reactor</artifactId>
    <version>1.0.1</version>
</dependency>
```

## License
All the modules in this project are available under [the Apache 2 license](http://www.apache.org/licenses/LICENSE-2.0). 
Attribution should be done to Speedment, Inc.
