## *GitHub* 

## 1. Présentation
### 1.1 GitHub

*Plateforme colleboratuve* Pour dev, plus grand espace de stockage de travaux collaboaratif dans le monde ! GitHub en lui-même n'est plus qu'un réseau social comme fb. Vous construisez un profil, vous y déposez des projets à partager et vous connectez avec d'autre utilisateurs en suivant leurs comptes. Meme si la pluârt des utilisateurs y deposent des projets de programmes ou de code, rien ne vous empeche d'y placer des textes ou tout type de fichier à présenter dans vos repertoires de projets.

### 1.2 Git
Git est un *logiciel de controle de version*, ce qui signfie qu'il gere les modifications f'un projets sans écarser n'importe quelle partie du projet.

## 2.Git et GitHub
###2.1  Vocabulaire

**ligne de commande**: En gros : le programme de l'ordinateur que nous utilisions pour entrer des sommandes Git. Dans le monde UNIX, on dit qu'on travaille en "ligne de commande" pour désigner le fait d'interagir avce un système informatique en entrant des lignes d'instrcutions textuelles dans un terminal, et non à l'aide d'une interface graphique.
Les commandes tapées dans le terminalJournal du Net => https://www.journaldunet.fr/web-tech/dictionnaire-du-webmastering/1445276-commande-informatique-definition-precise-et-exmples/

**Depot**: Un repertoire ou de l'espace de stockage ou vos projets peuevnt vivvre; les utilisateurs de GitHub raccourcissent en "repo" pour "repository". Il peut être un espace de stockage sur GitHub ou un autre hebergeur en ligne. A l'interieur d'un depot, vous pouvez conserver des fichiers de codes, des fichiers txt des images.

**Controle de version**: Fondamentalement, l'objectif pour lequel Gita été concu. Quand vous avez un fichier Word, vous l'écrasez à chaque fois que vous sauvegardez plusieurs versions. Avec Git, vous n'êtes plus obligé de faire ca. Git conserve des "intantanes" de chaque point dans l'historique d'un projet, de sortie que vous ne pouvez jamais le perdre ou l'ecraser.

**Commit**: C'est la commande qui donne à git toute la puissance. Quand vous committez, vous prenez un instant, une photo de cotre depot à ce stade vous donnant un point de contrôle que vous pouvez ensuite réévaluer ou tout simplement restaurer votre projet à cette version. Il est nécessaire de rappler que le nom de vos commits doivent-être parlant afin de savoir à quel stade du projet celui-ci a été fait.

**Branche**: Comment plusieurs personnes travaillent sur un projet en même temps sans que Git ne s'embrouille ? Habituellement, elles se debranchent du projet principal avec leurs propres version complètes, des modifications qu'elles on chacune produites de elur cote. Apres avoir temine, il est temps de fusionner cette branche pour la ramener vers la branche master, le repertoire principal du projet.

### 2.2 Commandes specifique Git

**Git init**: initialise un nouveau depot git jusqu'a ce que vous executiez les commandes Git qui suivent.

**git confid** Raccoruci de configuration, ceci est tout particulièrement utile quand vous paramétrez GIT pour la premiere fois identifiant et mot d'utilisateur

**git help**: Ouble une commande? pour afficher les 21 commades de git.

**git status**: Verifie le status de votre repo. Voir les fichiers et quelle sont les modification à commiter et sur quelle branche ou repo vous êtes en train de travaille.

**git add**: Ceci n'ajoute pas des fichiers dans votre repo,au lieu de cela porte de nouveaux fichiers à l'attestation de Git. Apres avoir ajouté des fichiers, ils sont inclus dans les instantanés du depot Git.

**git commit**: La commande la plus importante de Git. Apres avoir effectué toute sorte de modification vous entrez ca afin de prendre un instantané du depot. Le mettre en memeoire. On ecrit ca sous la forme de git commit -u 'votre message'. lr -m indique que la section suivante de la commande devrait etre lu comme un message.

**git branche**: Vous travaillez avec plusieurs collaborateurs et vous voulez produire des modofication de votre cote ? Cette commande vous permet de sonctruire une nouvelle branche, ou une chronologie de commits, des modifications et des ajouts de fichiers qui sont completement de votres. Votre titre va apres la commande. Si vous vouliez creer une nouvele branche appelle 'Yacine' vous saisiriez git branche Yacine.

**fit checkout**: C'est une commande de naviagation qui vous permet de vous deplacer vers le repertoire que vous voulez vérifier. Vous pouvez utiliser cette commande sous la forme de git checkout master pour regarder la branche master, ou git checkout  yacine pour regarder une autre branche.

**git marge**: Lorsque vous avez fini de travailler sur une branche, vous pouvez fusionner vos modifications vers la branche master, qui est visible pour tous les collaborateurs. Git marge yacine prendrait toutes les modifications que vous avez apportés à la branche yacine et les ajoutera à la barnche master.

**git push**: Si vous travaillez sur votre ordinateur en local et vous voulez que vos commits soient visible aussien ligne sur GitHub, vous pushez les modification vers GitHub avec cette commande.

**git pull**: Si vous travaillez en local et que vous voulez la version la plus à jour de votre repo pour travailler dessus, vous pullez les modifications provenant de GitHub avec cette commande

**git clone**: Permet de dupliquer, cloner un existant sur GutHub pour l'avoir en local. La commande git clone doit etre suivit