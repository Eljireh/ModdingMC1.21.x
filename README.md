# ModdingMC1.21.x
Modder en 1.21.x

Ressource : https://docs.minecraftforge.net/en/latest/gettingstarted/

Nécessite :
- Minecraft
- OpenJDK 21
- Java (JVM) 64 bits
- Un éditeur de code avec Gradle. Ordre décroissant de facilité : Eclipse ou IntelliJ IDEA > Visual Studio Code > Autres éditeurs
NB : L'explication suivante détaillera la démarche pour **VISUAL STUDIO CODE**. 
- ZIP Forge **MDK** 1.21.x (Ici 1.21.6-56.0.7)
![image](https://github.com/user-attachments/assets/641a85b6-05dd-40b1-9af6-dd4053c2b05f)

- Logiciel de gestion d'archives comme 7Zip ou WinRAR.

=== ÉTAPE 1 - Configuration de base ===
- Créer un dossier dédié au mod
- Extraire le ZIP Forge MDK 1.21.x dans le dossier mod.
Si un sous-dossier est créé à l'extraction, déplacer son contenu dans le dossier parent (le dossier dédié au mod).
- Ouvrir Visual Studio Code
- Ajouter l'extension "Extension Pack for Java".
L'installation peut prendre un peu de temps car 7 extensions à la fois sont en réalité installées. 
![image](https://github.com/user-attachments/assets/82d679d8-8360-41eb-8f2e-e3ffb2f9b469)
Ce pack contient ce qu'il faudra afin de développer aisément dans un environnement Java sur Visual Studio Code et permettra également d'utiliser Gradle, moteur de production de Java **indispensable** pour créer et gérer les mods (à moins d'être suffisament patient.e pour créer sa propre méthode).
 
