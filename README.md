# Branchlock Java Obfuscator

Start obfuscating [here](https://branchlock.net/login).

For more information, read the [documentation](https://branchlock.net/docs).

<img src="https://branchlock.net/img/logo-xl.svg" width=20% height=20%>


Branchlock is a sophisticated SaaS-technology designed to enhance the security of your Java and Android projects. It operates by encrypting the compiled code of your projects, rendering it virtually impossible to restore to its original form. This is a significant upgrade from conventional obfuscators, which typically only rename methods, fields, and class names, leaving constants like API keys and private URLs unchanged. These can be easily viewed by decompilers or scanned by automated bots, posing a security risk.

Branchlock takes this a step further by encrypting class pool constants such as strings, numbers, and even references. This provides robust protection for your Java projects, ensuring that the original code structure cannot be recovered at all. Furthermore, Branchlock offers different encryption modes, each with varying effects on the security and performance of your application.

# Introduction To Branchlock

Branchlock offers obfuscation for binary files of Java desktop applications, Android applications, and Java Virtual Machine languages like Kotlin and Groovy. 
The demo version of Branchlock provides a small overview of the service, but it doesn't offer the full range of features. 
Obfuscation can be performed on different projects:

## Supported Project Types

We provide support for a wide range of projects, including:

- Java Standalone Applications
- Java Libraries
- Java Applets
- J2ME and Jakarta EE Applications
- Android SDK Applications (Java & Kotlin only, no cross-platform app tools)
- Compose Desktop / Android Applications
- Spring Boot Applications
- Java Virtual Machine Languages (Kotlin, Groovy, Scala, etc.)
- JavaFX and Swing Applications (GUI)
- Java Web Applications (Servlets, JSP, JSF, etc.)
- and more.

Branchlock supports all Java versions from Java 5 to the latest version. 
For Android, we support all projects with AGP 7 and above. 
If a new version of Java or Android is released, we will add support for it as soon as possible.
Note that some project types require some configuration work to be obfuscated correctly.

## Obfuscating Java Archives, Desktop Apps, Server Apps, Class Files

To obfuscate Java archives (JAR files), open the web app and create a new project. Upload the Java binary you wish to obfuscate. 
Our service will perform obfuscation on your application and return an obfuscated output JAR file.
Branchlock supports most JVM languages like Kotlin and Groovy.

## Obfuscating Android Applications

Obfuscation in Android operates similarly to its counterpart in Java, though there are distinctions in the tasks available. 
Certain tasks are exclusive to Android projects, whereas others are unique to Java. 
To initiate obfuscation for an Android project, begin by creating a new project and choose the "Android" option. 
Branchlock provides an Android Gradle plugin for application obfuscation. 
Detailed setup instructions for the Gradle plugin can be found within the input section of each Android project.
Also take a look at the "Branchlock Gradle Plugin" section for more information.
