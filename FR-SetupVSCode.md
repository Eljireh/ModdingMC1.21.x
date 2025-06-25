# Gradle pour Visual Studio Code
Gradle est un outil de construction de projets pour Java.
Il y eut des périodes durant lesquelles Gradle était plus optimisé et flexible que Maven.
Maven est cependant considéré comme plus intuitif, tandis que Gradle est considéré comme bien plus approfondi.
Bien que l'on préfère généralement Maven pour de la gestion simple, les projets en profondeur préféreront Gradle. 

Visual Studio Code est un éditeur de code dont la compatibilité avec Gradle est la deuxième meilleure ; la meilleure revient, ex æquo, à Eclipse et à IntelliJ.

La mise en place nécessite :
- OpenJDK 21
- Java (JVM) 64 bits
- Visual Studio Code

1. Ouvrir Visual Studio Code.
2. Depuis la fenêtre "Extensions" (1), chercher et cliquer sur l'extension "Extension Pack for Java" (2), puis cliquer sur "Installer" ou "Install" (3).
![image](https://github.com/user-attachments/assets/82d679d8-8360-41eb-8f2e-e3ffb2f9b469)
L'installation peut prendre un peu de temps car 7 extensions à la fois sont en réalité installées. 
Ce pack contient ce qu'il faudra afin de développer aisément dans un environnement Java sur Visual Studio Code et permettra également d'utiliser Gradle.
3. Ouvrir le projet Visual Studio Code (Fichier -> Ouvrir Dossier -> Choisir le dossier)
Des configurations automatiques doivent avoir lieu, prenant un peu de temps.

![image](https://github.com/user-attachments/assets/15b30238-a0aa-4d1b-9317-34edf6442d20)

Si Java reste sur 0%, il faut possiblement confirmer la présence d'OpenJDK sur la page Visual Studio Code affichée, en validant dans la liste déroulante.
Si cette liste n'apparaît pas, il faut donc attendre près de 5 minutes.

À présent, l'environnement Java, incluant Gradle, est installé sur Visual Studio Code.

*Petit point* : Il est recommandé de souvent appeler Gradle afin de réévaluer le projet après un changement concernant Gradle.
Pour cela, il est utile d'entrer "gradlew" dans le terminal.
