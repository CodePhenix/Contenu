# Linux et son utilisation
Ce tutorial pr�sente l'OS linux. Apr�s une introduction sur son histoire et son ffonctionnement, il traite de ce qui en fait sa force !
* La console et les lignes de commandes
* La gestion des process et des ecutions sur l'ordinateur
* Les scripts pour l'automatisation de tache

## Linux
### Mais bon sang, c'est QUOI Linux ?
On oppose souvent linux a windows, comme son alternative. Mais que fait r�ellement windows sur un ordinateur ? On peut voire que c'est l'un des premier nom qui s'affiche au d�marrage sur un ordinateur. C'est donc une �tape n�cessaire a toutes les autres utilisations de l'ordinateur (dans notre cas, le d�veloppement web) mais aussi les applications, les lectures de videos...

_Pourquoi y-a-t-il besoin de windows avant de pouvoir faire le reste ?_
Parce que� votre ordinateur a besoin d'une sorte de � superlogiciel � qui soit le chef d'orchestre. C'est lui qui doit g�rer la m�moire de votre ordinateur, la r�partir entre tous les programmes. Il fait le lien entre votre mat�riel (carte graphique, m�moire, imprimante) et vos logiciels. Et c'est un sacr� boulot !
Ce � superlogiciel � s'appelle le  **syst�me d'exploitation** (OS). Windows est donc un syst�me d'exploitation.
Et Linux en est un autre ! Il est r�put� entre autres pour sa s�curit� et pour ses mises � jour plus fr�quentes que Windows. On peut noter deux diff�rences majeures entre windows et Linux :
* Contrairement � Windows, Linux est un OS open-source, c'est � dire que les lignes de codes de ce "super logiciel" sont publique, et que l'utilisation de celui-ci est gratuite. De plus les diff�rentes mise a jour de celui-ci se font par une communaut�, tout le monde peut contribuer et ce sont ensuite les contributeurs les plus fr�quent qui valident les contributions.
* Linux se veut "plus proche de la machine". C'est � dire que le lien entre l'ordinateur (m�moire, process, ressources...) et les applications ayant r�ellement lieux (logiciel, browser, jeux, lecteurs videos) o� m�mes les actions li�es (installation,  d�placement de fichiers...) sont beaucoup plus encapsul� dans un OS comme windows. On dit parfois que Linux permet de reprendre le contr�le de son ordinateur.

### Un peu d'histoire

```mermaid
graph LR
G(MS DOS) --> H(Windows)
H --> J(Windows)
A(Unix)  --> B(Mac OS X)
B --> I(Mac OS X)
A --> C(GNU/Linux)
C --> D(Ubuntu)
C --> E(Archlinux)
C --> F(Fedora)
```

## La console et les command line
### La console
generalit�es
### Saisir une commande
man id�e de commande, le fonctionnement des options
### File system et manipulation
mv/cp/touch/ls/cd...
### Droit d'acces
Explication et comment les �diter
### Editeur texte de console
Nano et Vi
### Extraire et filtrer des donn�es
grep/wc/find/cut et les id�es qui vont avec
### Rediriger les flux
std et stdr et les chevrons

## Process programmes et executions
### L'activit� du system
top etc...
### Processus et PID
kill un process...

## Le bash et le scripting
### Les inputs et les variables
### Les conditions
### Les boucles
### Les fonctions

## Cheatsheet
Il faut toujours faire `man` pour en savoir plus sur les commandes, notamment les options utilisable et les arguments qui peuvent etre fournis.
Les commandes peuvent avoir diff�renteqs utilisations selon les options utilis�es et les arguments donn�s. La commande `man` d�taille les diff�rentes utilisations.
