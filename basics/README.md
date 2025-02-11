<div align="center">
  <img src="https://github.com/ksyv/holbertonschool-web_front_end/blob/main/baniere_holberton.png" alt="Banner">
</div>

# Shell, Basics

Ce projet couvre les bases du Shell, la navigation dans le système de fichiers, la manipulation des fichiers et répertoires, ainsi que l'utilisation des commandes essentielles en ligne de commande.

---

## Table des Matières

- [Resources](#resources)
- [Learning Objectives](#learning-objectives)
- [Requirements](#requirements)
- [Tasks](#tasks)

---

## Resources

### Read or Watch
- [What Is “The Shell”?](https://www.linuxjournal.com/article/2807)
- [Navigation](https://tldp.org/LDP/intro-linux/html/sect_03_01.html)
- [Looking Around](https://tldp.org/LDP/intro-linux/html/sect_03_02.html)
- [A Guided Tour](https://tldp.org/LDP/intro-linux/html/sect_03_03.html)
- [Manipulating Files](https://tldp.org/LDP/intro-linux/html/sect_03_04.html)
- [Working With Commands](https://tldp.org/LDP/intro-linux/html/sect_03_05.html)
- [Reading Man pages](https://www.man7.org/linux/man-pages/man1/man.1.html)
- [Keyboard shortcuts for Bash](https://www.gnu.org/software/bash/manual/html_node/Command-Line-Editing.html)
- [LTS](https://ubuntu.com/about/release-cycle)
- [Shebang](https://en.wikipedia.org/wiki/Shebang_(Unix))

### Man or Help
- `cd`
- `ls`
- `pwd`
- `less`
- `file`
- `ln`
- `cp`
- `mv`
- `rm`
- `mkdir`
- `type`
- `which`
- `help`
- `man`

---

## Learning Objectives

À la fin de ce projet, vous serez capable d’expliquer à n’importe qui, sans l’aide de Google :

### Général
- Que signifie **RTFM** ?
- Qu’est-ce qu’un **Shebang** ?
- Différence entre un **terminal** et un **shell**
- Utilisation de l’historique des commandes

### Navigation
- Commandes `cd`, `pwd`, `ls`
- Navigation dans le système de fichiers
- Différences entre **.**, **..**, et **/** (répertoires)
- Affichage et gestion des fichiers cachés

### Exploration et Manipulation de Fichiers
- Commandes `ls`, `less`, `file`
- Utilisation des liens symboliques (`ln`)
- Copies, déplacements et suppressions de fichiers (`cp`, `mv`, `rm`, `mkdir`)
- Compréhension et usage des **wildcards** (`*`, `?`, etc.)

### Utilisation des Commandes
- Différences entre `type`, `which`, `help`, `man`
- Alias et commandes personnalisées

---

## Requirements

### Général
- Éditeurs autorisés : `vi`, `vim`, `emacs`
- Tous les scripts seront testés sur **Ubuntu 22.04 LTS**
- Chaque script doit être **exactement de deux lignes** (`$ wc -l <file>` doit afficher 2)
- Tous les fichiers doivent se terminer par une **nouvelle ligne**
- La **première ligne** de chaque fichier doit être : `#!/bin/bash`
- Un fichier `README.md` décrivant chaque script
- **Interdictions** : `&&`, `||`, `;`, `sed`, `awk`
- Tous les scripts doivent être **exécutables** (`chmod u+x script_name.sh`)

---

## Tasks

### 0. Where am I?
Afficher le chemin absolu du répertoire de travail actuel.  
**Fichier :** `0-current_working_directory`

---

### 1. What’s in there?
Afficher le contenu du répertoire courant.  
**Fichier :** `1-listit`

---

### 2. There is no place like home
Changer le répertoire de travail vers le **home** de l’utilisateur.  
**Fichier :** `2-bring_me_home`

---

### 3. The long format
Afficher le contenu du répertoire courant en **format long**.  
**Fichier :** `3-listfiles`

---

### 4. Hidden files
Afficher tous les fichiers (y compris les cachés `.`), en format long.  
**Fichier :** `4-listmorefiles`

---

### 5. I love numbers
Afficher le contenu en format long avec **ID utilisateur et groupe affichés numériquement**.  
**Fichier :** `5-listfilesdigitonly`

---

### 6. Welcome
Créer un répertoire `my_first_directory` dans `/tmp/`.  
**Fichier :** `6-firstdirectory`

---

### 7. Betty in my first directory
Déplacer le fichier `betty` dans `/tmp/my_first_directory/`.  
**Fichier :** `7-movethatfile`

---

### 8. Bye bye Betty
Supprimer le fichier `betty` situé dans `/tmp/my_first_directory/`.  
**Fichier :** `8-firstdelete`

---

### 9. Bye bye My first directory
Supprimer le répertoire `/tmp/my_first_directory`.  
**Fichier :** `9-firstdirdeletion`

---

### 10. Back to the future
Revenir au répertoire précédent.  
**Fichier :** `10-back`

---

### 11. Lists
Lister les fichiers du **répertoire courant**, du **répertoire parent**, et de **/boot**, en format long.  
**Fichier :** `11-lists`

---

### 12. File type
Afficher le type du fichier `/tmp/iamafile`.  
**Fichier :** `12-file_type`

---

### 13. We are symbols, and inhabit symbols
Créer un **lien symbolique** vers `/bin/ls`, nommé `__ls__`.  
**Fichier :** `13-symbolic_link`

---

### 14. Copy HTML files
Copier les fichiers `.html` du répertoire courant vers son parent **(uniquement s’ils sont nouveaux ou plus récents)**.  
**Fichier :** `14-copy_html`

---

### 15. Let’s move
Déplacer tous les fichiers commençant par une **majuscule** vers `/tmp/u`.  
**Fichier :** `15-lets_move`

---

### 16. Clean Emacs
Supprimer tous les fichiers terminant par `~` dans le répertoire courant.  
**Fichier :** `16-clean_emacs`

---

### 17. Tree
Créer la structure de répertoires suivante en **deux lignes seulement** :  

### 17. Tree
Create directories `welcome/`, `welcome/to/`, and `welcome/to/school` in the current directory, using only **two** lines.

**File:** `17-tree`
