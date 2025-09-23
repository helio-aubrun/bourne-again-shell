# Introduction au monde de la ligne de commande

Quand on utilise un ordinateur, on pense souvent aux **icônes**,
**fenêtres** et **menus** que l'on clique avec la souris. Mais derrière
cette interface, il existe une autre manière d'interagir avec
l'ordinateur : **la ligne de commande**. C'est une façon de dialoguer
directement avec la machine en tapant des instructions sous forme de
texte.

Pour comprendre ce monde, explorons étape par étape les notions
essentielles.

------------------------------------------------------------------------

## 1. Qu'est-ce qu'une **ligne de commande** ?

Une **ligne de commande**, c'est une instruction que l'on écrit pour
dire à l'ordinateur ce qu'il doit faire.
👉 Exemple :
- Si vous tapez `ls` (sous Linux ou macOS), l'ordinateur vous renvoie la
liste des fichiers présents dans un dossier.
- C'est comme **donner un ordre écrit** à l'ordinateur, au lieu de
cliquer sur une icône.

**Métaphore** : Imaginez que vous êtes dans un restaurant rapide.
- Cliquer sur une icône, c'est comme pointer du doigt un plat au menu.
- Taper une ligne de commande, c'est comme écrire précisément : *"Un
sandwich jambon-fromage, sans tomate, avec boisson gazeuse."*
C'est plus précis, mais demande d'apprendre la bonne manière de formuler
la demande.

------------------------------------------------------------------------

## 2. Qu'est-ce qu'un **terminal** ?

Le **terminal** est une **fenêtre spéciale** qui vous permet de taper
ces fameuses lignes de commande.

👉 Exemple concret :
- Sous Windows, on parle de **Invite de commandes** ou **PowerShell**.
- Sous macOS et Linux, l'application s'appelle simplement **Terminal**.

**Métaphore** : Le terminal est **le comptoir du restaurant**.
- C'est là que vous vous placez pour passer vos commandes.
- Sans comptoir, impossible de donner vos ordres au serveur.

------------------------------------------------------------------------

## 3. Qu'est-ce que le **Shell** ?

Le **Shell** est le **programme qui reçoit vos commandes** dans le
terminal et les traduit pour l'ordinateur.

👉 Exemple :
- Si vous tapez `ls`, le shell comprend que vous voulez la liste des
fichiers et demande au système de vous répondre.

**Métaphore** : Le shell, c'est **le serveur derrière le comptoir**.
- Vous lui dites votre commande.
- Il la comprend, la transmet en cuisine (le système), puis vous ramène
le résultat.

------------------------------------------------------------------------

## 4. Qu'est-ce que **Bash** ? Quelle différence avec le Shell ?

-   **Shell** est un terme **générique** : il existe plusieurs types de
    shell (sh, zsh, fish, csh, etc.).
-   **Bash** est **l'un de ces shells**, et c'est le plus populaire sur
    Linux et macOS.

### Petite histoire de Bash

-   **Origine** : Bash a été créé en 1989 par **Brian Fox**, pour
    remplacer un shell plus ancien appelé **sh**.
-   **Nom** : "Bash" veut dire **Bourne Again Shell** (un jeu de mots,
    car il remplace le **Bourne Shell**).
-   **Caractéristiques clés** :
    -   Permet d'exécuter des commandes classiques (`ls`, `cd`, etc.).
    -   Possède un langage de programmation intégré (pour créer des
        scripts).
    -   Supporte l'autocomplétion (taper une partie d'une commande et
        appuyer sur `Tab`).
    -   Largement répandu : sur presque toutes les distributions Linux,
        Bash est installé par défaut.

**Métaphore** :
- "Shell" = un type de serveur.
- "Bash" = **le serveur le plus populaire**, formé dans beaucoup de
restaurants, qui connaît le plus de recettes.

------------------------------------------------------------------------

## 5. Différence entre **Terminal** et **Shell**

-   Le **terminal** = la **fenêtre** (le comptoir).
-   Le **shell** = le **programme** (le serveur) qui prend vos
    commandes.
-   La **ligne de commande** = ce que **vous tapez** (la commande au
    serveur).

👉 Exemple :
- Vous ouvrez un terminal → une fenêtre s'ouvre.
- Le shell (souvent Bash) s'exécute dans cette fenêtre.
- Vous tapez `ls` → Bash comprend, demande au système, et vous affiche
la liste des fichiers.

------------------------------------------------------------------------

# Lexique simple

-   **Ligne de commande** : une phrase que vous écrivez pour donner un
    ordre à l'ordinateur.
-   **Terminal** : une fenêtre où vous pouvez écrire vos ordres.
-   **Shell** : le programme qui lit vos ordres et les exécute.
-   **Bash** : un type de shell très répandu, populaire pour sa
    puissance et sa simplicité.
-   **Commande** : l'ordre concret que vous tapez (`ls`, `cd`, etc.).
-   **Script** : une suite de commandes enregistrées dans un fichier
    pour être réutilisées.

------------------------------------------------------------------------

👉 Avec ces métaphores (restaurant, comptoir, serveur, commandes), même
une personne qui n'a jamais vu un terminal peut comprendre la logique
derrière la ligne de commande.
