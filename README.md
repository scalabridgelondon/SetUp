# SetUp
Tools and steps to install them for the ScalaBridge course.

## Software

You will need to install 1) Java Virtual Machine (JVM) and 2) a text editor or integrated development environment (IDE) to write Scala code.

To install the JVM visit [Corretto][corretto] and grab the appropriate package for your operating system. Version 8 or above is fine. (Your computer may already have a JVM installed. You can find out by running the `java` command from a terminal. If you don't know what this means it doesn't matter. It won't hurt to install Corretto if you have another JVM already. If you use a package manager you probably have a range of JVMs available. Any JVM that supports Java 8 or above is fine.)

There are two routes to installing the text editor or IDE you need to develop Scala:

- *If you already have tools you are comfortable with* then you can continue to use them. You will need the example project below and [SBT][sbt]. If you go this route it is your responsibility to maintain your setup, though the mentors are likely to have experience with common tools like Emacs and Vim.

- *If you haven't programmed before or don't have a strong preference* we recommend you install the [IntelliJ Scala Bundle][intellij-scala]. Follow the link and scroll down the page a bit until you see the "Downloads" heading. Download the appropriate package from there.

## Base Project

The base project provides some basic configuration for the work we'll do at ScalaBridge. Depending on your group you will have a different base project:

- *If you don't have programming experience* get the [Creative Scala template][creative-scala-template]. Click the green "Clone or download" button and choose "Download ZIP". (If you know how to use Git you can clone or fork the repository instead.)

- *If you have programming experience, but not with Scala* TBC

- *If you have Scala experience* setup yourself up a project.

[corretto]: https://aws.amazon.com/corretto/
[sbt]: https://www.scala-sbt.org/
[intellij-scala]: https://github.com/JetBrains/intellij-scala-bundle
[creative-scala-template]: https://github.com/creativescala/creative-scala-template
