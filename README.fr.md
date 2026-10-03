# KCleaner

**Un nettoyeur de PC gratuit pour Windows : en un clic, il ferme tous les programmes inutiles pour ne garder que ce dont Windows a vraiment besoin, et range au même endroit les éléments de lancement automatique, les fichiers résiduels et les programmes de sécurité installés de force.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · Français

> Ce document est une traduction. En cas de différence, la [version coréenne](README.ko.md) fait foi.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-4.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kcleaner?lang=fr)

![Écran de KCleaner](images/kcleaner-en.webp)

## Présentation

Laissez votre PC allumé un moment et une foule de programmes finit par tourner en arrière-plan : messageries, assistants de mise à jour, programmes utilisés puis jamais fermés, et même des programmes de sécurité que des sites bancaires vous ont fait installer. Les retrouver et les fermer un par un est fastidieux.

Un seul clic sur **Nettoyer** dans l'onglet **Accueil** suffit : KCleaner ferme tout sauf les programmes dont Windows a besoin pour fonctionner, puis libère la mémoire restante. Les pilotes essentiels, comme ceux de la carte graphique et du son, et les antivirus de confiance ne sont pas fermés ; les programmes qui se déguisent sous le nom d'un programme système de Windows le sont. Les programmes sont seulement fermés, jamais désinstallés.

Trois outils de nettoyage l'accompagnent sous forme d'onglets :

- **Démarrage** — désactive, sans les supprimer, les programmes, tâches planifiées et services lancés avec Windows.
- **Nettoyage** — choisit et supprime les résidus, comme les caches et fichiers temporaires, laissés par les applications installées.
- **Groupé** — trouve et retire les programmes de sécurité que des sites bancaires ou administratifs vous ont demandé d'installer.

## Fonctionnalités

- **Tout fermer d'un coup** — Un bouton ferme tous les programmes sauf les essentiels.
- **Des règles sûres** — Les programmes essentiels de Windows, les pilotes graphiques et audio et les antivirus de confiance sont conservés. Les faux programmes système qui ne font qu'imiter des noms de Windows sont fermés.
- **Nettoyage de la mémoire** — Une fois les programmes fermés, la mémoire restante est libérée.
- **Liste d'exceptions** — Vous pouvez indiquer vous-même les programmes qui doivent rester ouverts pour qu'ils ne soient pas fermés.
- **Résultats** — À la fin du nettoyage, une page de résultats s'ouvre avec les programmes fermés et l'évolution de la mémoire.
- **Gestion du démarrage** — Activez ou désactivez depuis une seule liste les éléments de lancement automatique répartis entre dossiers de démarrage, registre, Planificateur de tâches et services.
- **Nettoyage des fichiers résiduels** — Analyse et supprime caches, fichiers temporaires et journaux, uniquement pour les applications installées sur ce PC. Les données personnelles comme les favoris, mots de passe et historique de navigation ne sont pas cochées par défaut.
- **Retrait des programmes installés de force** — Affiche la liste des programmes de sécurité bancaires et administratifs et lance leur programme de désinstallation d'un clic.
- **Icône de la barre d'état** — La version installée attend dans la zone de notification après l'ouverture de session et s'ouvre d'un clic.
- **Mode sombre** — Les couleurs suivent le mode d'application de Windows (clair · sombre).
- **9 langues** — Coréen · anglais · japonais · chinois · russe · italien · français · espagnol · arabe.

## Téléchargement / Installation

| Type | Lien |
|---|---|
| Programme d'installation | [Télécharger](https://down.kilho.net/kcleaner?lang=fr) |
| Portable (ZIP) | [Télécharger](https://down.kilho.net/kcleaner?lang=fr&nosetup) |

Le programme d'installation lance KCleaner dès la fin de l'installation et place une icône dans la zone de notification. Pour la version portable, décompressez le ZIP et lancez `KCleaner.exe`. Les deux versions nettoient de la même façon ; seule la version installée a l'icône de la barre d'état.

Fermer des programmes et modifier les éléments de lancement automatique nécessite des droits d'administrateur ; Windows affiche donc une demande d'autorisation d'administrateur au lancement. Cliquez sur **Oui**.

## Utilisation

### Premiers pas

1. Si vous avez des documents ouverts ou un travail en cours, enregistrez-les d'abord. Tous les programmes non essentiels, navigateurs et messageries compris, seront fermés.
2. Lancez KCleaner et cliquez sur **Oui** dans la demande d'autorisation d'administrateur.
3. Dans l'onglet **Accueil**, cliquez sur **Nettoyer**.
4. Un indicateur de progression tourne à la place du bouton pendant que les programmes inutiles sont fermés et la mémoire nettoyée.
5. Une fois terminé, la page de résultats s'ouvre dans votre navigateur et la fenêtre de KCleaner se ferme d'elle-même.

### Organisation de l'écran

| Élément | Rôle |
|---|---|
| **Accueil** | Le premier écran, avec le bouton **Nettoyer** |
| **Démarrage** | Activer et désactiver les éléments lancés avec Windows |
| **Nettoyage** | Analyser et supprimer les fichiers résiduels des applications installées |
| **Groupé** | Retirer les programmes de sécurité bancaires et administratifs |
| Logo KILHO.net | Ouvre la page de KCleaner |

Chaque onglet charge sa liste la première fois que vous l'ouvrez. Si vous n'utilisez que **Nettoyer** dans **Accueil**, vous n'avez pas besoin d'ouvrir les autres onglets.

**Démarrage**

| Élément | Rôle |
|---|---|
| Colonne **Programme** | Icône et nom du programme (le nom du produit, s'il existe) |
| Colonne **Source** | L'endroit où l'élément est enregistré — **Démarrage** (dossier de démarrage) · **Registre** · **Tâche** · **Service** |
| Ligne grisée | Un élément désactivé |
| **Tous les programmes** | Cochée, affiche tout, y compris les éléments désactivés |
| **Désactiver** / **Activer** | Désactive ou active l'élément sélectionné |
| Menu du clic droit | **Supprimer** (éléments désactivés uniquement) · **Liste de sauvegarde** |

**Nettoyage**

| Élément | Rôle |
|---|---|
| Ligne de catégorie | **Windows** · noms de navigateurs · **Internet** · **Multimédia** · **Utilitaires** · **Applications** · **Jeux** · **Autres**. Cliquez pour développer ou réduire |
| Ligne d'élément | Un type de résidu qu'on peut supprimer. Seuls les éléments cochés sont analysés et nettoyés |
| Point d'exclamation | Un élément qui demande de la prudence avant suppression. Survolez-le pour voir une note (en anglais) |
| Colonne **Taille** | Ce qui peut être supprimé, après **Analyser** |
| Texte en bas | Nombre d'applications installées, progression, résultats de l'analyse ou du nettoyage |
| **Analyser** / **Nettoyer** | Trouve ce qui peut être supprimé et en affiche la taille / supprime ce qui a été analysé |
| Menu du clic droit | **Tout sélectionner** · **Tout désélectionner** · **Valeurs par défaut** |

**Groupé**

| Élément | Rôle |
|---|---|
| Colonne **Programme** | Les programmes de sécurité bancaires et administratifs installés sur ce PC |
| Colonne **Source** | L'éditeur (**Inconnu** en l'absence d'information) |
| **Désinstaller** | Lance le programme de désinstallation du programme sélectionné |

### Que faire quand…

**Le PC est devenu lent et vous voulez tout nettoyer d'un coup**
Cliquez simplement sur **Nettoyer** dans l'onglet **Accueil**. Les programmes qui tournaient en arrière-plan sont fermés ensemble et la mémoire est libérée. Les programmes sont seulement fermés, pas supprimés : relancez ceux dont vous avez besoin et utilisez-les comme d'habitude.

**Avant de cliquer sur Nettoyer**
Les programmes non essentiels — navigateurs, messageries, éditeurs de documents, etc. — sont fermés même s'ils sont ouverts. Enregistrez d'abord tout travail non enregistré. L'Explorateur Windows et le bureau, les pilotes graphiques et audio et les antivirus de confiance restent actifs.

**Certains programmes doivent rester ouverts (liste d'exceptions)**
Avec la version installée, faites un clic droit sur l'icône de KCleaner dans la zone de notification → **Liste d'exceptions**. Le Bloc-notes s'ouvre : écrivez les programmes à ne pas fermer, un par ligne, puis enregistrez.

- `programme.exe*` — le programme dont le nom de fichier exécutable correspond exactement (ex. : `editplus.exe*`)
- Sans `*` — tous les programmes dont le chemin contient ce texte (ex. : `\EditPlus\` couvre tous les programmes de ce dossier)

À partir du prochain clic sur **Nettoyer**, les programmes de la liste ne sont plus fermés. Avec la version portable, créez `NoClean.txt` à côté de `KCleaner.exe` et remplissez-le de la même façon.

**Consulter les résultats**
À la fin du nettoyage, une page de résultats s'ouvre dans votre navigateur avec les programmes fermés et la mémoire avant et après. La fenêtre de KCleaner se ferme d'elle-même une fois son travail terminé.

**L'ouvrir directement depuis l'icône de la barre d'état**
Avec la version installée, l'icône de KCleaner apparaît dans la zone de notification peu après l'ouverture de session. Un clic gauche ouvre KCleaner ; s'il est déjà ouvert, sa fenêtre passe au premier plan. Le menu du clic droit propose **KCleaner** · **Liste d'exceptions** · **À propos** · **Quitter**. **Quitter** retire l'icône jusqu'à la prochaine ouverture de session.

**Désactiver les programmes lancés avec Windows**
Dans l'onglet **Démarrage**, cliquez sur le programme puis sur **Désactiver**. L'élément n'est pas supprimé, seulement désactivé : il ne se lance plus à partir du prochain démarrage, et le programme lui-même fonctionne comme avant. La ligne reste en place, grisée, pour que vous puissiez la réactiver aussitôt avec **Activer**.

**Réactiver un élément désactivé**
Dans l'onglet **Démarrage**, cochez **Tous les programmes** et les éléments désactivés auparavant apparaissent en lignes grisées. Cliquez sur la ligne puis sur **Activer** : il se relance à partir du prochain démarrage.

**Désactiver les tâches de mise à jour et les services**
Les lignes dont la **Source** est **Tâche** s'exécutent automatiquement à heures fixes ; les lignes **Service** sont des services d'arrière-plan lancés avec Windows. **Désactiver** empêche une tâche de s'exécuter même quand son heure arrive, et empêche un service de démarrer avec Windows ou quand un autre programme l'appelle. Mieux vaut vérifier à quel programme appartient un service avant de le désactiver.

**Vous ne savez pas ce qu'est un élément de démarrage**
Double-cliquez sur la ligne : votre navigateur s'ouvre avec des informations sur cet élément.

**Des entrées de démarrage d'un programme désinstallé sont restées**
Passez d'abord la ligne sur **Désactiver**, puis clic droit → **Supprimer** et cliquez sur **Oui** pour confirmer. Les éléments supprimés ne peuvent pas être restaurés : ne supprimez que ce dont vous êtes sûr de ne pas avoir besoin. La suppression d'un service affiche l'avis « Un service en cours d'exécution est entièrement supprimé après un redémarrage » : redémarrez le PC une fois et il disparaît définitivement.

**Garder une copie de la liste de démarrage**
Dans l'onglet **Démarrage**, clic droit → **Liste de sauvegarde** enregistre dans un fichier texte tous les éléments de lancement automatique, y compris les éléments essentiels de Windows masqués dans la liste. Les services et tâches dont Windows a besoin sont masqués dès le départ pour que vous ne les désactiviez pas par erreur, et restent masqués même avec **Tous les programmes** cochée.

**Récupérer de l'espace disque en supprimant les fichiers résiduels**
La première fois que vous ouvrez l'onglet **Nettoyage**, KCleaner recherche les applications installées sur ce PC, l'indique sous la forme **N applications installées** et n'affiche, par catégorie, que les éléments de nettoyage de ces applications. Gardez les cases cochées par défaut et cliquez sur **Analyser** pour voir quels fichiers seraient supprimés et leur taille ; cliquez sur **Nettoyer** pour supprimer ce qui a été analysé. **Analyser** ne supprime rien : vous pouvez vous en servir uniquement pour voir combien d'espace vous pourriez libérer.

**Choisir vous-même ce qu'il faut supprimer**
Cliquez sur une ligne de catégorie pour la développer et voir ses éléments ; cliquez sur une ligne d'élément pour inverser sa case. La case d'une ligne de catégorie coche ou décoche toute la catégorie d'un coup, et devient grise quand seuls certains éléments sont cochés. Vos changements sont mémorisés et repris à la prochaine ouverture de l'onglet. Pour revenir à l'état d'origine, clic droit dans la liste → **Valeurs par défaut**.

**Vous voulez aussi effacer l'historique de navigation ou les listes de fichiers récents**
Les données que vous avez créées — marque-pages, favoris, mots de passe, historique de navigation, historique des conversations — ne sont pas cochées par défaut pour éviter de les effacer par erreur. Pour les applications qui mélangent caches et listes de fichiers récents, un élément distinct **… · Historique d'utilisation** est prévu. Si vous voulez aussi effacer ces données, cochez-le vous-même.

**Impossible de cliquer sur Nettoyer**
**Nettoyer** ne s'active que lorsque tous les éléments cochés ont été analysés avec **Analyser** et qu'il y a quelque chose à supprimer. Si vous avez coché de nouveaux éléments après l'analyse, ou si vous venez de terminer un nettoyage, cliquez de nouveau sur **Analyser**.

**Éléments marqués d'un point d'exclamation**
Ce sont des éléments pour lesquels il y a quelque chose à savoir avant suppression. Survolez le signe pour lire la note (en anglais) ; si un tel élément est coché, une confirmation vous est demandée en cliquant sur **Nettoyer**.

**Votre navigateur est ouvert**
Les fichiers en cours d'utilisation ne sont pas touchés et sont ignorés. Pour vider davantage le cache du navigateur, fermez-le avant de nettoyer, ou cliquez d'abord sur **Nettoyer** dans l'onglet **Accueil** puis lancez le nettoyage.

**Mes fichiers sont-ils en sécurité ?**
Les dossiers Documents, Bureau, Images, Vidéos, Musique et Téléchargements, ainsi que les fichiers cachés et système, ne sont jamais analysés ni nettoyés. Lorsque vous êtes connecté, la liste de nettoyage est automatiquement remplacée par la dernière version vérifiée.

**Retirer les programmes de sécurité installés par un site bancaire**
Ouvrez l'onglet **Groupé** pour ne voir que les programmes de sécurité bancaires et administratifs installés sur ce PC : sécurité du clavier, certificats numériques, pare-feu, etc. Sélectionnez-en un et cliquez sur **Désinstaller**, ou double-cliquez sur sa ligne : le programme de désinstallation s'ouvre, comme avec « Désinstaller un programme » dans le Panneau de configuration. Une fois la désinstallation terminée, il disparaît de lui-même de la liste. S'il n'y a rien à retirer, l'onglet affiche **Aucun programme à désinstaller**. Vous pourrez toujours le réinstaller depuis le site au besoin.

**Parcourir les listes au clavier**
Dans les onglets **Démarrage** et **Groupé**, utilisez **↑** · **↓** pour passer d'une ligne à l'autre ; **F5** recharge la liste. Si des noms sont coupés, faites glisser la limite entre les en-têtes de colonnes pour ajuster la largeur.

**Le relancer alors qu'il est déjà ouvert**
Un seul KCleaner tourne à la fois. Le relancer alors que la fenêtre est ouverte n'ouvre pas de nouvelle copie ; la fenêtre déjà ouverte passe au premier plan.

## Configuration

Il n'y a rien à configurer. Les programmes à garder ouverts se déclarent dans la **Liste d'exceptions** ci-dessus, et les cases de l'onglet Nettoyage sont mémorisées dès que vous les modifiez à l'écran. KCleaner suit de lui-même ce qui suit :

| Élément | Suit |
|---|---|
| Langue | Les paramètres régionaux de Windows (anglais si la langue n'est pas prise en charge) |
| Couleurs | Le mode d'application de Windows (clair · sombre) — les changements s'appliquent aussitôt, même quand KCleaner est ouvert |

## Configuration requise

- Windows 10 · Windows 11 (64 bits)
- Droits d'administrateur — nécessaires pour fermer des programmes et modifier les éléments de lancement automatique. Une demande de confirmation s'affiche au lancement.
- Aucun autre composant à installer.
- La connexion Internet sert aux avis de nouvelle version, à la mise à jour des listes et à la page de résultats. Sans connexion, le nettoyage fonctionne normalement avec les listes intégrées.

## Mises à jour

KCleaner ne se met **pas** à jour tout seul. Au lancement, il vérifie s'il existe une nouvelle version et affiche un avis ; cliquer sur **[Oui]** ouvre la page de téléchargement et ferme le programme. Les nouvelles versions sont publiées manuellement après vérification interne et annoncées sur la [page de KCleaner](https://kilho.net/kcleaner). Consultez l'[avis sur la politique de mise à jour](https://en.kilho.net/archives/notice/2940).

## Licence

KCleaner est un **freeware**. Utilisez-le gratuitement et sans restriction partout — au bureau, à la maison, dans l'administration ou à l'école — et redistribuez-le librement.

La liste de Nettoyage s'appuie sur [Winapp2](https://github.com/MoscaDotTo/Winapp2) (CC BY-SA 4.0). Les licences des composants utilisés figurent dans `THIRD-PARTY-NOTICES.txt`, dans le dossier d'installation.

## Liens

- Site web : <https://kilho.net/kcleaner>
- Forum : <https://kilho.top/forum/qna>
- X (Twitter) : <https://www.twitter.com/kilhonet>

© KILHO.NET
