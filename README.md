# ModdingMC1.21.x
Modder en 1.21.x

Ressource : https://docs.minecraftforge.net/en/latest/gettingstarted/

Nécessite :
- Minecraft
- OpenJDK 21
- Java (JVM) 64 bits
- Un éditeur de code compatible avec Gradle. Ordre décroissant de facilité : Eclipse ou IntelliJ IDEA > Visual Studio Code > Autres éditeurs
NB : L'explication suivante détaillera la démarche pour **VISUAL STUDIO CODE**. 
- ZIP Forge **MDK** 1.21.x (Ici 1.21.6-56.0.7)
![image](https://github.com/user-attachments/assets/641a85b6-05dd-40b1-9af6-dd4053c2b05f)
- Logiciel de gestion d'archives comme 7-Zip ou WinRAR.

=== ÉTAPE 1 - Configuration de base ===
1. Créer un dossier dédié au mod
2. Extraire le ZIP Forge MDK 1.21.x dans le dossier mod.
Si un sous-dossier est créé à l'extraction, déplacer son contenu dans le dossier parent (le dossier dédié au mod).
3. Ouvrir Visual Studio Code.
4. Depuis la fenêtre "Extensions" (1), chercher et cliquer sur l'extension "Extension Pack for Java" (2), puis cliquer sur "Installer" ou "Install" (3).
![image](https://github.com/user-attachments/assets/82d679d8-8360-41eb-8f2e-e3ffb2f9b469)
L'installation peut prendre un peu de temps car 7 extensions à la fois sont en réalité installées. 
Ce pack contient ce qu'il faudra afin de développer aisément dans un environnement Java sur Visual Studio Code et permettra également d'utiliser Gradle, moteur de production de Java **indispensable** pour créer et gérer les mods (à moins d'être suffisamment patient.e pour créer sa propre méthode).
5. Ouvrir le dossier du mod dans Visual Studio Code (Fichier -> Ouvrir Dossier -> Choisir le dossier)
Des configurations automatiques doivent avoir lieu, prenant un peu de temps.

![image](https://github.com/user-attachments/assets/15b30238-a0aa-4d1b-9317-34edf6442d20)

Si Java reste sur 0%, il faut possiblement confirmer sur la page Visual Studio Code présentée la présence d'OpenJDK, en validant dans la liste déroulante.
Si cette liste n'apparaît pas, il faut donc attendre près de 5 minutes.

6. Dans le terminal, cliquer sur la flèche à droite du signe "+" (1) et lancer une tâche (2).
![image](https://github.com/user-attachments/assets/bfdca9c5-a203-4fec-9f7f-9eb20e5880a6)

Entrer "genVSCodeRuns". Si cela n'apparaît pas, cliquer sur "Afficher toutes les tâches" et sélectionner "gradle:genVSCodeRuns".
![image](https://github.com/user-attachments/assets/00e97f7e-1b5f-4bdc-a9cd-a7eaea0dc10d)

Si cela n'apparaît toujours pas, entrer à la place " gradle run* " (sans guillemets) dans le terminal intitulé cmd.

À présent :
- Le kit de modding Forge est installé dans un dossier dédié au mod.
- L'environnement Java, incluant Gradle, est installé sur Visual Studio Code.
- Les sources audio et les textures de Minecraft ont été obtenues via Gradle.

*Petit point* : Il est recommandé de souvent appeler Gradle afin de réévaluer le projet après un changement concernant Gradle.
Pour cela, il est utile d'entrer "gradlew" dans le terminal.
