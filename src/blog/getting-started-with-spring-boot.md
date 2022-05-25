---
layout: layout.njk
title: Getting started with spring boot
tags: blog
---

# Getting started with Spring Boot

Welcome to getting started with Spring Boot.

The only thing you need to know is Java.

# Installations

1. Install the Java Development Kit (JDK).
2. Install maven (package manager)

**Linux**

```bash
$ sudo apt install maven
```

**Windows**

Download from [maven.apache.org](https://maven.apache.org)

3. Install Vscode extensions for developing with Spring

   a. Install Extension Pack for Java
   ![vscode](assets/java-ext-pack.png)

   b. Install Spring Boot Extension Pack
   ![spring](assets/spring-boot-ext-pack.png)

# Getting Started

You can visit [https://youtu.be/eApc_BxEYsU](https://youtu.be/eApc_BxEYsU) for a video tutorial.

1. Visit [start.spring.io](https://start.spring.io)
   ![start](assets/start-spring.png)

2. Configure your project. We will configure a minimum configuration.

|                  |                                                                             |
| ---------------- | --------------------------------------------------------------------------- |
| Project          | We will choose maven                                                        |
| Language         | We will choose Java                                                         |
| Spring Boot      | We will pick the default spring boot default                                |
| Project Metadata |                                                                             |
| Group            | reverse of domain. Example **google.com** will be written as **com.google** |
| Artifact         | Your project name                                                           |
| Description      | the description for your project                                            |
We will leave other configurations as default.

| ![start2](assets/start-p2.png) |
| :----------------------------: |
|        start.spring.io         |

**Add a dependency**: We will add a spring web dependency

| ![dependency](assets/dependency.png) |
| :----------------------------------: |
|          Adding dependency           |

And we are good to go. Click **Generate**.

3. A zip file will download. Extract the contents and open the folder in vscode.

4. Once in vscode, open new terminal. Then run the following commands.

```bash
$ mvn install
```

This command installs the required maven dependencies for your project.

```bash
$ mvn spring-boot:run
```

| ![spring-cli](assets/spring-cli.png) |
| :----------------------------------: |
|        Spring Boot is running        |

If you saw the above screen that means Spring Boot is running and by default it runs at [http://localhost:8080](http://localhost:8080)

5. Open your browser and head over to [http://localhost:8080](http://localhost:8080)

| ![white](assets/whitelabel.png) |
| :-----------------------------: |
|        Whitelabel error         |

If you see the whitelabel error that means Spring Boot is running.

You've reached the end. Can't wait to see what you will do with Spring Boot.