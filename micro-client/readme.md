# REST client plugin for Microserver

[micro-client example apps](https://github.com/aol/micro-server/tree/master/micro-client/src/test/java/app)

This plugin provides two REST Clients

1. NIORestClient - which is a non-blocking REST client using NIO
2. AsyncRestClient - which is asyncrhonous, but makes use of threads

The NIORestClient is available as  Spring bean. AsyncRestClient can simply be instantiated via the new keyword.

## To use

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.aol.microservices/micro-client/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.aol.microservices/micro-client)

Simply add to the classpath

Maven 

     <dependency>
        <groupId>com.aol.microservices</groupId>  
        <artifactId>micro-client</artifactId>
        <version>x.yz</version>
     </dependency>
     
Gradle

    compile 'com.aol.microservices:micro-client:x.yz'