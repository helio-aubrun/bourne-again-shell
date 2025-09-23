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

# 📑 Tableau récapitulatif des commandes

| **Commande** | **Explication** | **Cas pratique** |
|--------------|-----------------|------------------|
| `ls` | Liste les fichiers et répertoires | `ls -l` → affiche les fichiers avec détails (taille, droits, date) |
| `cat fichier.txt` | Affiche le contenu d’un fichier | `cat premiertexte` → montre le contenu du fichier |
| `less fichier.txt` | Affiche le contenu page par page (sans éditer) | `less premiertexte` |
| `nano fichier.txt` | Éditeur de texte simple en ligne de commande | `nano premiertexte` |
| `vim fichier.txt` | Éditeur avancé en ligne de commande | `vim premiertexte` |
| `rm fichier.txt` | Supprime un fichier | `rm premiertexte` |
| `rmdir dossier/` | Supprime un dossier **vide** | `rmdir essai/` |
| `rm -r dossier/` | Supprime un dossier et tout son contenu | `rm -r essai/` |
| `cp source dest` | Copie un fichier | `cp premiertexte double` |
| `mv source dest` | Déplace ou renomme un fichier/dossier | `mv double introduction` |
| `mkdir dossier/` | Crée un répertoire | `mkdir essai/` |
| `grep "mot" fichier` | Recherche un mot ou motif dans un fichier | `grep "pomme" exemple.txt` |
| `sort fichier.txt` | Trie les lignes d’un fichier par ordre alphabétique | `sort exemple.txt` |
| `head -n 5 fichier.txt` | Affiche les 5 premières lignes d’un fichier | `sort exemple.txt \| head -n 5` |
| `tail -n 5 fichier.txt` | Affiche les 5 dernières lignes d’un fichier | `sort exemple.txt \| tail -n 5` |
| `echo "texte"` | Affiche un texte dans le terminal | `echo "Bonjour"` |
| `echo "texte" > fichier.txt` | Écrit du texte dans un fichier (remplace le contenu) | `echo "Hello" > output.txt` |
| `echo "texte" >> fichier.txt` | Ajoute du texte à la fin du fichier | `echo "Encore une ligne" >> output.txt` |
| `find chemin -name "*.txt"` | Recherche des fichiers selon critères | `find projet/ -type f -name "*.txt"` |
| `file fichier.txt` | Indique le type de fichier | `file secret.txt` |
| `chmod o=r fichier.txt` | Modifie les permissions (lecture seule pour "autres") | `chmod o=r secret.txt` |
| `awk -F, '{print $1, $2*$3}' fichier.txt` | Permet de parcourir un fichier et faire des calculs | Calculer montant total d’une facture |
| `sed 's/ancienne/nouvelle/' fichier.txt` | Remplace du texte dans un fichier | Modifier quantité d’un livre |
| `read variable` | Récupère une saisie utilisateur dans un script | `read titre` puis `grep "$titre" facture.txt` |
