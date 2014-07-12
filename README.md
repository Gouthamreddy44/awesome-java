# Awesome Java

A curated list of awesome Java frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome Java](#awesome-java)
    - [Build Tool](#build-tool)
    - [Code Analysis](#code-analysis)
    - [Compiler-compiler](#compiler-compiler)
    - [Continuous Integration](#continuous-integration)
    - [Database](#database)
    - [Date and Time](#date-and-time)
    - [Dependency Injection](#dependency-injection)
    - [Development](#development)
    - [Distributed Applications](#distributed-applications)
    - [GUI](#gui)
    - [Game Development](#game-development)
    - [High Performance](#high-performance)
    - [IDE](#ide)
    - [JVM and JDK](#jvm-and-jdk)
    - [JSON](#json)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [ORM](#orm)
    - [PDF](#pdf)
    - [Security](#security)
    - [Science](#science)
    - [Server](#server)
    - [Template Engine](#template-engine)
    - [Testing](#testing)
    - [Utility](#utility)
    - [Web Crawling](#web-crawling)
    - [Web Frameworks](#web-frameworks)
    - [XML](#xml)
    - [REST Frameworks](#rest-frameworks)
- [Resources](#resources)
    - [Twitter](#twitter)
    - [Websites](#websites)
    - [Communities](#communities)
    - [Influental Books](#influental-books)
- [Contributing](#contributing)

## Build Tool

*Tools which handle the buildcycle of an application*

* [Apache Maven](http://maven.apache.org/) - Declarative lifecycle and dependency managment which favors convention over configuration. It's regarded as spiritual successor to [Apache Ant](http://ant.apache.org/).
* [Gradle](http://www.gradle.org/) - Incremental builds which are programmed via Groovy.

## Code Analysis

*Tools that provide metrics and quality measurements of static code*

* [SonarQube](http://www.sonarqube.org/) - Inspection tool for code quality.
* [FindBugs](http://findbugs.sourceforge.net/) - Static analysis to find potential bugs.
* [Metrics](http://metrics.codahale.com/) - Measures the behavior of critical components.

## Compiler-compiler

*Tools that create parsers, interpreters or compilers*

* [ANTLR](http://www.antlr.org/) - Complex full-featured framework.
* [JavaCC](https://javacc.java.net/) - More specific and slightly easier to learn.

## Continuous Integration

*Tools which support continuously building, testing and releasing applications*

* [Jenkins](http://jenkins-ci.org/) - Provides server-based CI services, often seen as the successor to [Hudson](http://hudson-ci.org/).

## Database

*Everything which simplifies interactions with the database*

* [jOOQ](http://www.jooq.org/) - Generates typesafe code based on SQL schema.
* [Liquibase](http://www.liquibase.org/) - Source control for your database which can be embedded.
* [MapDB](http://www.mapdb.org/) - Database engine with optimized datastructures.

## Date and Time

*Libraries related to date and time.*

* [Java 8 SE: Date and Time API](http://www.oracle.com/technetwork/articles/java/jf14-date-time-2125367.html) - Incorporates Joda-Time.
* [Joda-Time](http://joda-time.sourceforge.net/) - De facto standard date/time-library before Java 8.

## Dependency Injection

*Libraries that help to realize the [Inversion Of Control](http://en.wikipedia.org/wiki/Inversion_of_control) paradigm*

* [Dagger](http://square.github.io/dagger/) - Compile-time injection framework without reflection, mainly for Android.
* [Google Guice](http://de.wikipedia.org/wiki/Google_Guice) - Lightweight DI framework.
* [Spring](http://spring.io/) - The Spring Context module provides DI.
* [Weld](http://docs.jboss.org/weld/reference/latest/en-US/html_single/) - CDI reference implementation.

## Development

*Tools with augment the process of development at a fundamental level*

* [DCEVM](http://ssw.jku.at/dcevm/) - Modification of the JVM that allows unlimited redefinition of loaded classes at runtime.
* [JRebel](http://zeroturnaround.com/software/jrebel/) - Instantly reloads code and configuration changes without redeploys.

## Distributed Applications
*Libraries and frameworks used to ease writing distributed and fault-tolerant applications*

* [Akka](http://akka.io) - Toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on the JVM.
* [JGroups](http://www.jgroups.org/) - Toolkit for reliable messaging and creating clusters whose nodes can send messages to each other.
* [Apache ZooKeeper](http://zookeeper.apache.org/) - Coordination service with distributed configuration, synchronization, and naming registry for large distributed systems.

## GUI

*Libraries to create modern graphical user interfaces*

* [JavaFX](http://www.oracle.com/technetwork/java/javase/overview/javafx-overview-2158620.html) - Considered the successor of [Swing](http://www.oracle.com/technetwork/java/architecture-142923.html).
* [Scene Builder](http://www.oracle.com/technetwork/java/javase/downloads/javafxscenebuilder-info-2157684.html) - Visual Layout Tool for JavaFX Applications.

## Game Development

*Frameworks that support the development of games*

* [LWJGL](http://lwjgl.org/) - Robust framework that abstracts libraries like OpenGL/CL/AL.
* [libGDX](http://libgdx.badlogicgames.com/) - Allround cross-plattform, high-level framework.

## High Performance

*Everything about high performance computation, from collections to specific libraries*

* [Trove](http://trove.starlight-systems.com/) - Primitive collections.
* [HPPC](http://labs.carrotsearch.com/hppc.html) - Primitive collections.
* [Disruptor](http://lmax-exchange.github.io/disruptor/) - Inter-thread messaging library.
* [Javalution](http://javolution.org/) - Library for real-time and embedded systems.

## IDE

*Integrated development environments that try to simplify several aspects of development*

* [NetBeans](https://netbeans.org/) - Integrates a lot of features and provides tools ranging from Java SE to EE starting with database access and servers to HTML5 and AngularJS.
* [Eclipse](http://www.eclipse.org/) - Does a lot of things in the background. Noteworthy are its large amount of plugins.
* [IntelliJ IDEA](http://www.jetbrains.com/idea/) - Supports a lot of JVM languages and provides good options for Android development. The commercial edition targets the enterprise sector.

## JVM and JDK

*Various implementations of the JVM/JDK*

* [HotSpot](http://openjdk.java.net/groups/hotspot/) - Official JVM.
* [JDK 9](https://jdk9.java.net/) - Early access releases of JDK 9.
* [OpenJDK](http://openjdk.java.net/) - Open source implementation.

## JSON

*Libraries that simplify JSON processing*

* [Google Gson](https://code.google.com/p/google-gson/) - Serializes Java objects to JSON and vice versa. Good performance with on-the-fly usage. 
* [Jackson](http://wiki.fasterxml.com/JacksonHome) - Similar to GSON but has performance gains if you need to instantiate the library more often.

## Logging

*Libraries that log the behavior of an application*

* [Apache Log4j 2](http://logging.apache.org/log4j/) - Complete rewrite of the previous software. Now has a powerful plugin and configuration architecture.
* [Logback](http://logback.qos.ch/) - Founded by the same developer as Log4j and proves to be a robust logging library with interesting configuration options via Groovy.
* [SLF4J](http://www.slf4j.org/) - Abstraction layer which is to be used with an implementation.

## Machine Learning

*Tools that allow to learn from data via a set of specific algorithms*

* [Apache Hadoop](http://hadoop.apache.org/) - Open-source software framework for storage and large-scale processing of data-sets on clusters of commodity hardware.
* [Apache Mahout](https://mahout.apache.org/) - Scalable algorithms focused on collaborative filtering, clustering and classification.
* [Apache Spark](http://spark.apache.org/) - Open-source data analytics cluster computing framework.
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Collection of algorithms for data mining tasks ranging from pre-processing to visualization.

## Messaging

*Tools that help sending messages between clients to ensure protocol independency*

* [Apache ActiveMQ](http://activemq.apache.org/) - Open-source message broker that implements JMS and converts synchronous to asynchronous communication
* [JBoss HornetQ](http://hornetq.jboss.org/) - Clear, concise, modular and made to be embedded.

## Miscellaneous

*Everything else*

* [Jimfs](https://github.com/google/jimfs) - In-memory file system.
* [Lombok](http://projectlombok.org/) - Code-generator which aims to reduce the verbosity of Java.

## Natural Language Processing

*Libraries that are specialized on processing text*

* [Apache OpenNLP](https://opennlp.apache.org/) - Toolkit for common tasks like tokenization.
* [LingPipe](http://alias-i.com/lingpipe/) - Toolkit for a variety of tasks ranging from POS tagging to sentiment analysis.
* [Mallet](http://mallet.cs.umass.edu/) - Statistical natural language processing, document classification, clustering, topic modeling, etc.

## ORM

*APIs which handle the persistence of objects*

* [EclipseLink](https://www.eclipse.org/eclipselink/) - Supports a number of persistence standards: JPA, JAXB, JCA and SDO
* [Hibernate](http://hibernate.org/orm/) - Robust and widely used with an active community.

## PDF

*Everything that helps with the creation of PDF files*

* [Apache FOP](http://xmlgraphics.apache.org/fop/) - Creates PDF from XSL-FO.
* [Apache PDFBox](http://pdfbox.apache.org/) - Toolbox for creating and manipulating PDF.
* [JasperReports](http://community.jaspersoft.com/project/jasperreports-library) - Complex reporting engine.
* [DynamicReports](http://dynamicreports.org/) - Simplifies JasperReports.
* [iText](http://itextpdf.com/) - Easy to use PDF library which creates PDF files programmatically but requires a license for commercial purposes.

## Security

*Libraries that handle security, authentication, authorization or session management*

* [Apache Shiro](http://shiro.apache.org/) - Performs authentication, authorization, cryptography and session management.
* [Keycloak](http://keycloak.jboss.org/) - Integrated SSO and IDM for browser apps and RESTful web services. Currently in beta but looks very promising.
* [PicketLink](http://picketlink.org/) - PicketLink is an umbrella project for security and identity management for Java Applications.
* [Spring Security](http://projects.spring.io/spring-security/) - Focuses on authentication and authorization and protects against several attack vectors.

## Science

*Libraries for scientific computing and analysis*

* [JScience](http://www.jscience.org/) - Comprehensive framework of science related libraries.
* [JTransforms](https://sites.google.com/site/piotrwendykier/software/jtransforms) - Multithread FFT library.
* [Parallel Colt](https://sites.google.com/site/piotrwendykier/software/parallelcolt) - Multithread high performance scientific and technical computing.
* [SCaVis](http://jwork.org/scavis/) - Environment for scientific computation, data analysis and data visualization.

## Server

*Servers which are specifically used to deploy applications*

* [GlassFish](https://glassfish.java.net/) - Open source reference implementation for Java EE sponsored by Oracle.
* [WildFly](http://www.wildfly.org/) - Formerly known as JBoss and developed by Red Hat with extensive Java EE support.
* [Jetty](http://www.eclipse.org/jetty/) - Lightweight, small server often embedded in projects. Part of the Eclipse Foundation.
* [Apache Tomcat](http://tomcat.apache.org/) - Robust allround server for Servlet and JSP.
* [Apache TomEE](http://tomee.apache.org/) - Tomcat plus Java EE.

## Template Engine

*Tools which substitute expressions in a template*

* [Apache Velocity](http://velocity.apache.org/)
* [FreeMarker](http://freemarker.org/)
* [JavaServer Pages](https://jsp.java.net/)
* [Thymeleaf](http://www.thymeleaf.org/)

## Testing

*Tools that test from object to interface level including performance and other benchmarks*

* [AssertJ](http://joel-costigliola.github.io/assertj/) - Fluent assertions.
* [Apache JMeter](http://jmeter.apache.org/) - Functional testing and performance measurements.
* [Arquillian](http://arquillian.org/) - Integration and functional testing platform with integration of Java EE containers.
* [Calipher](https://code.google.com/p/caliper/) - Microbenchmarking framework.
* [FEST](https://code.google.com/p/fest/) - Collection of testing libraries.
* [Hamcrest](http://hamcrest.org/JavaHamcrest/) - Framework for writing declarative assertion matchers.
* [JMH](http://openjdk.java.net/projects/code-tools/jmh/) - Microbenchmarking.
* [JUnit](http://junit.org/) - Testing framework.
* [Mockito](http://code.google.com/p/mockito/) - Creation of test double objects in automated unit tests for the purpose of TDD or BDD.
* [Selenium](http://docs.seleniumhq.org/) - Portable software testing framework for web applications.
* [TestNG](http://testng.org/) - Testing framework.
* [VisualVM](http://visualvm.java.net/) - Visual interface for viewing detailed information about Java applications while they are running on a JVM

## Utility

*Libraries which provide unspecific functionality, e.g. optimized datastructures*

* [Apache Commons](http://commons.apache.org/)
* [Google Guava](http://code.google.com/p/guava-libraries/)

## Web Crawling

*Libraries that analyze the content of websites*

* [Apache Nutch](http://nutch.apache.org/)
* [Crawler4j](https://code.google.com/p/crawler4j/)

## Web Frameworks

*Frameworks that handle the communication between the layers of an web application*

* [Apache Tapestry](http://tapestry.apache.org/)
* [Spring](http://projects.spring.io/spring-framework/)
* [Grails](https://grails.org/)
* [Vaadin](https://vaadin.com/)
* [GWT](http://www.gwtproject.org/)
* [Apache Wicket](http://wicket.apache.org/)
* [Play](http://www.playframework.com/)
* [PrimeFaces](http://primefaces.org/)
* [Spark](http://www.sparkjava.com/why.html)

## XML

*Libraries that simplify XML processing*

* [JAXB](https://jaxb.java.net/) - Reference Implementation of JAXB, the Java Architecture for XML Binding.
* [XStream](http://xstream.codehaus.org/) - Simple library to serialize objects to XML and back again.
* [Apache XMLBeans](http://xmlbeans.apache.org/)
* [Woodstox](http://woodstox.codehaus.org/) - High-performance StAX XML processor.

## REST Frameworks

*Frameworks specifically for creating RESTful services*

* [Dropwizard](https://dropwizard.github.io/dropwizard/) - Opinionated framework for setting up modern web applications, includes Jetty, Jackson, Jersey and Metrics.
* [Jersey](https://jersey.java.net/) - JAX-RS reference implementation.
* [RESTEasy](http://resteasy.jboss.org/) - Fully certified and portable implementation of the JAX-RS specification.

# Resources

## Twitter

*People to follow*

* [Adam Bien](https://twitter.com/AdamBien/)
* [Antonio Goncalves](https://twitter.com/agoncal/)
* [Arun Gupta](https://twitter.com/arungupta/)
* [Ed Burns](https://twitter.com/edburns)
* [Java](https://twitter.com/java/)
* [Java EE](https://twitter.com/Java_EE/)
* [Java.net](https://twitter.com/javanetbuzz/)
* [Java Magazine](https://twitter.com/Oraclejavamag)
* [Mark Reinhold](https://twitter.com/mreinhold)
* [OpenJDK](https://twitter.com/OpenJDK)
* [Pete Muir](https://twitter.com/plmuir/)
* [Reza Rahman](https://twitter.com/reza_rahman)
* [Simon Maple](https://twitter.com/sjmaple)
* [Tim Boudreau](https://twitter.com/kablosna)

## Websites

*Sites to read*

* [Java.net](http://java.net/)
* [JavaWorld](http://www.javaworld.com/)
* [Javalobby](http://java.dzone.com/)

## Communities

*Active discussions*

* [r/java](http://www.reddit.com/r/java) - Subreddit for the Java community.
* [stackoverflow](http://stackoverflow.com/questions/tagged/java)

## Influental Books

*Books about Java that had a high impact and are still worth reading*

* [Effective Java (2nd Edition)](http://www.amazon.com/Effective-Java-Edition-Joshua-Bloch/dp/0321356683)
* [Java Concurrency in Practice](http://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)
* [Thinking in Java](http://www.amazon.com/Thinking-Java-Edition-Bruce-Eckel/dp/0131872486)

# Contributing

Contributions are very welcome!

Please have a look at [CONTRIBUTING](https://github.com/akullpp/awesome-java/blob/master/CONTRIBUTING.md) for guidelines. 

Topics which have no libraries as of yet are located in [TOPICS](https://github.com/akullpp/awesome-java/blob/master/TOPICS.md).
