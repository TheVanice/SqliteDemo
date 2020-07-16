# SqliteDemo
Demo App for using Sqlite with Intellij Java 

# How to use
1. Add the exernal library to your project
2. Copy the file **SqliteClient.java** into your project
3. Check **DemoApp.java** on how to use the Client

# How to add external libraries
In order to use Sqlite you need to add sqlite-jdbc as external library to your project.
In IntelliJ IDEA do the following steps:
1. FILE -> PROJECT STRUCTURE
2. Select LIBRARIES in the menu on the left
![Add lib from maven](/assets/frommaven.PNG)
3. In the following dialog search for **org.xerial:sqlite-jdbc** and select the latest version (at the time of writing this is **org.xerial:sqlite-jdbc:3.32.3.1**)
4. Click OK and select your project
