# Gradle for Visual Studio Code
Gradle is a build system for Java.<br/>There were times during which Gradle was more optimized and flexible than Maven.<br/>Maven is however seen as more intuitive, while Gradle is seen as way more in-depth.<br/>Although Maven is generally preferred for basic management, Gradle will be preferred for more intricate projects.<br/><br/>Visual Studio Code is an IDE which has the second-best compatibility with Gradle; the best belongs to both Eclipse and IntelliJ, in a tie.<br/>Setup requires :<br/>- OpenJDK 21<br/>- Java (JVM) 64 bits<br/>- Visual Studio Code

1. Open Visual Studio Code.
2. From the "Extensions" (or "Plug-ins") tab (1), search and click the "Extension Pack for Java" extension (2), then click "Install" (3).
![image](https://github.com/user-attachments/assets/82d679d8-8360-41eb-8f2e-e3ffb2f9b469)
The installation may take some time, since 7 extensions are actually being installed at the same time. 
This pack contains what will be needed to easily code in a Java environment on Visual Studio Code, and will also let us use Gradle.
3. Open the project on Visual Studio Code (File -> Open Folder -> Select Folder)
Some automatic configurations must happen, which may take time.

![image](https://github.com/user-attachments/assets/15b30238-a0aa-4d1b-9317-34edf6442d20)

If Java stays at 0%, you might need to confirm the presence of OpenJDK on the displayed Visual Studio Code page, by confirming in the drop-down list.
If the list does not appear, then you need to wait for about 5 minutes.

Now, Java environment, including Gradle, has been installed Visual Studio Code.

*Note*: It is recommended to call Gradle often in order to re-evaluate the project after a change regarding Gradle has occurred.
To do so, you may find useful to enter "gradlew" in the terminal.
