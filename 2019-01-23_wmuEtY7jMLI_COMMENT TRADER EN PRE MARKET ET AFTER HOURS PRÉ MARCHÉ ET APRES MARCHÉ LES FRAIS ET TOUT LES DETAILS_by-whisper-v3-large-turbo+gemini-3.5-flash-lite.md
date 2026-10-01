# 🎬 COMMENT TRADER EN PRE MARKET ET AFTER HOURS PRÉ MARCHÉ ET APRES MARCHÉ LES FRAIS ET TOUT LES DETAILS

> **Chaîne** : [Dany Murray Trader](https://www.youtube.com/@danymurraytrader6032)  
> **Lien YouTube** : [https://www.youtube.com/watch?v=wmuEtY7jMLI](https://www.youtube.com/watch?v=wmuEtY7jMLI)  
> **Date de publication** : 2019-01-23  
> **Durée** : 10m 51s (`651s`)  
> **Identifiant vidéo** : `wmuEtY7jMLI`  
> **Modèles utilisés** : Audio: `large-v3-turbo` (Faster-Whisper int8 VPS) | Vision: `gemini-3.5-flash-lite` (Google AI Studio API)  

---

## 📌 Synthèse Exécutive & Outils

### 💡 Résumé
Cette vidéo de Dany Murray aborde les subtilités opérationnelles, les règles techniques et les pièges financiers liés au trading en pré-marché (*pre-market*) et en après-marché (*after-hours*). Contrairement aux heures d'ouverture traditionnelles (9h30 - 16h00), ces périodes hors-séance permettent de se positionner en amont ou en aval des grandes annonces, mais exigent une rigueur absolue dans le paramétrage des ordres pour éviter des pertes financières colossales. Murray y détaille le fonctionnement des courtiers (comme Questrade), l'accès aux différentes plages horaires et la mécanique incontournable du paramètre de durée pour valider ces transactions.

Au cœur de la méthode présentée se trouve la gestion des frais transactionnels, souvent sous-estimés par les traders débutants. En effet, transiger en dehors des heures normales active des frais dits ECN (frais de routage électronique) qui s'ajoutent aux commissions fixes du courtier. Pour les actions classiques ou les *penny stocks*, ces frais, calculés par tranche d'actions, peuvent s'envoler de manière exponentielle lors de transactions sur de gros volumes, transformant un gain potentiel en gouffre financier. L'analyse met également en lumière l'absence de liquidité sur certains marchés (comme les OTC) et l'interdiction de fait des ordres *stop-loss* classiques.

La leçon principale de ce cours de bourse réside dans la protection du capital face à la volatilité et aux pièges techniques. Murray insiste sur l'obligation absolue d'utiliser des **ordres limites** pour contrer le *spread* (l'écart entre acheteurs et vendeurs) souvent extrême en pré/post-marché, évitant ainsi un "bad fill" destructeur. Enfin, il rappelle la nécessité absolue de réinitialiser les paramètres de durée dès la cloche d'ouverture de 9h30 pour ne pas continuer à accumuler bêtement des frais ECN superflus tout au long de la journée.

---

### 🛠️ Outils, Plateformes & Logiciels Présentés
* **Questrade** : Courtier en ligne (utilisé par Dany Murray, donnant accès au pré-marché dès 7h30).
* **Ordres Limites (*Limit Orders*)** : Outil de passage d'ordre obligatoire en pré-marché et *after-hours* pour se protéger de la volatilité et des *spreads* larges.
* **Paramètre de durée GTM (*Good Till Market / Extended Hours*)** : Code de paramétrage obligatoire à renseigner dans la plateforme pour autoriser un ordre à s'exécuter en dehors des heures normales de bourse.
* **Penny stocks / Micro penny stocks** : Actifs spéculatifs à très bas prix (ex. sous 1 $, 25 sous, ou quelques centimes) particulièrement ciblés par la mise en garde sur les frais.
* **Marchés OTC (*Over-The-Counter*)** : Marchés de gré à gré exclus de toute séance de pré-marché ou d'après-marché.
* **Formule Form T** : Documentation réglementaire liée aux transactions hors cote/hors heures (mentionnée en description).

---

### 🔑 Points Clés & Enseignements Stratégiques
* **Disponibilité des courtiers :** Tous les courtiers ne se valent pas ; l'accès au pré-marché et à l'after-hour varie selon les plateformes (par exemple, 7h30 chez Questrade).
* **Paramétrez le GTM :** Pour qu'un ordre soit exécuté en dehors des heures de bureau, il est impératif de modifier la durée de l'ordre de "Journée" (D) vers le code **GTM**.
* **L'explosion des frais ECN :** Le trading hors-séance déclenche des surcoûts par action (ex: 3 $ par tranche de 1000 actions) qui s'ajoutent aux frais de base du courtier.
* **Attention aux gros volumes sur *penny stocks* :** Acheter des dizaines de milliers ou des millions d'actions à bas prix en pré-marché peut générer des centaines de dollars de frais de transaction, annulant la rentabilité du trade.
* **Obligation de l'ordre limite :** Ne jamais utiliser d'ordre au marché (*market order*) en pré ou post-marché sous peine d'être exécuté à un prix catastrophique en raison d'un manque temporaire de liquidité.
* **La volatilité des *spreads* :** En l'absence de la majorité des acteurs de marché, l'écart entre le *bid* (acheteur) et le *ask* (vendeur) peut exploser, passant de quelques centimes à plusieurs dizaines de centimes.
* **Absence de *stop-loss* :** Les ordres de protection automatiques (*stops*) ne fonctionnent pas correctement ou sont inexistants en dehors des heures d'ouverture officielles.
* **Le piège de l'ouverture (9h30) :** N'oubliez jamais de repasser la durée de vos ordres en mode "Journée" (D) dès l'ouverture officielle pour stopper net l'application des frais ECN.
* **Inéligibilité des actions OTC :** Il est totalement impossible de trader des actions OTC en pré-marché ou en after-hour ; quand c'est fermé, c'est définitivement fermé.
* **Gestion du risque vs Coût :** Parfois, accepter de payer des frais élevés en pré-marché est un "mal pour un bien" pour couper une position d'urgence, mais cela doit rester un calcul mûrement réfléchi.
* **La psychologie du trader piégé :** Le trading hors-séance demande une vigilance de chaque instant pour ne pas découvrir des frais aberrants en fin de journée à cause d'un oubli de paramétrage.

---

## ⏱️ Chronologie & Transcription Complète Audio & Visuelle (Mot pour Mot)

### ⏱️ `[00:00:01 - 00:00:23]` | Segment #01

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Alors bonjour tout le monde, ici Dan Murray pour un autre superbe cours de bourse. Aujourd'hui nous allons regarder comment trader en pre-market et en after-hour et combien ça peut bien coûter tout ça parce que des frais ajoutés. Donc c'est de tout ça qu'on va regarder dans cette vidéo, comment faire et les frais.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Diapositive de présentation affichée sous forme de document textuel ou tableur (fond blanc, fenêtres Windows avec ruban Fichiers/Accueil/Affichage).

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE ?", suivi de deux points clés encadrés ("1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE"). Deux tableaux distincts en bas : à gauche "FRAIS ECN" détaillant des tarifs par action (ex: Canadian securities $0.003$/share, U.S Securities FREE ou $0.003/share), et à droite "ACTION / FRAIS" listant des volumes et leurs coûts associés (ex: 1000 = 8.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Aucune manipulation de curseur visible ; la diapositive est fixe à l'écran pour introduire le cours.

---

### ⏱️ `[00:00:23 - 00:00:51]` | Segment #02

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc on fait un petit tour de tout ça en l'instant mes chers amis. Donc comme je vous ai parlé dans une précédente vidéo que je vais mettre un petit peu plus loin dans la vidéo, vous irez voir ça si vous n'êtes pas au courant des fameuses horaires de travail. Donc aujourd'hui comment trader un pre-market et tout dépendant de votre broker vous allez pouvoir trader plus tôt ou plus tard dans le pre-market.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Document visuel ou diapositive affichée à l'écran, structurée en texte centré et tableaux encadrés.

**Contenu textuel & Code** : Texte principal : "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE ?". Points clés : "1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE". Deux tableaux distincts : "FRAIS ECN" détaillant des tarifs par action (ex: $0.0035/share) et "ACTION / FRAIS" listant des volumes par paliers et leurs coûts associés (ex: 1000 = 8.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Le présentateur affiche une infographie récapitulative pour expliquer les règles et les coûts liés au trading hors heures d'ouverture.

---

### ⏱️ `[00:00:51 - 00:01:27]` | Segment #03

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc à faire attention tout dépendant de votre broker ça se pourrait qu'il va vous dire oui on a le pre-marché, le pre-market et l'after-hour, l'après-marché. oui on l'a mais c'est facile de dire ça mais votre broker peut-être qu'il va vous donner accès juste à partir de par exemple 9h le pre-market ou à partir de 8h moi chez Questrate c'est 7h30 donc à partir de 7h30 je peux transiger sur le pre-marché de la bourse et sachez que les paramètres

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Diapositive de présentation pédagogique sur fond blanc affichée via un logiciel de visionnage ou de traitement d'images.

**Contenu textuel & Code** : Titre principal : "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?". Deux points encadrés : "1- DURÉE / DURATION : GTEM" et "2- ORDRE LIMITE OBLIGATOIRE". Deux tableaux : à gauche, "FRAIS ECN" détaillant des tarifs en $/action pour des titres canadiens et américains (ex: $0.0035/share, FREE) ; à droite, "ACTION / FRAIS" listant des paliers de volumes et leurs coûts totaux (ex: 1000 = 8.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Le curseur de la souris est visible au centre de l'écran, au-dessus du texte encadré du premier point.

---

### ⏱️ `[00:01:27 - 00:01:50]` | Segment #04

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> de pre-marché et les paramètres d'after hour sont les mêmes Donc, pas à vous casser la tête. Un coup, vous savez comment le faire. Vous le faites soit en pré-marché ou en après-marché. Ça va donner les mêmes résultats. Donc, qu'est-ce qui se passe quand on regarde tout ça? Vous voyez ici, on a deux choses à faire pour être capable de transiger.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Diapositive de présentation pédagogique affichée en plein écran sur fond blanc.

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", suivi de deux points encadrés ("1- DURÉE / DURATION : GTEM" et "2- ORDRE LIMITE OBLIGATOIRE"). En bas, deux tableaux : à gauche "FRAIS ECN" détaillant les tarifs par action pour les titres canadiens et américains (ex: $0.0035/share, MNGD/LAMP gratuit), et à droite "ACTION / FRAIS" listant les commissions par volume d'actions (ex: 1000 = 8.95$, 250 000 = 1004.95$). Le curseur de la souris est visible au centre de l'écran.

**Action / Démonstration** : Le présentateur expose de manière statique le récapitulatif théorique des paramètres et des frais de courtage applicables au pré-marché et à l'after-hours.

---

### ⏱️ `[00:01:50 - 00:02:12]` | Segment #05

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> c'est changer certains paramètres dans votre ordre. Quand vous allez passer votre ordre à la bourse, ça ne sera pas plus compliqué que changer la duration, qui est la durée en français. Tout dépendant, habituellement, cette duration, on met D.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation au format texte illustré (diapositive/document explicatif sur fond blanc).

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", deux points clés encadrés en rouge ("1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE"), ainsi que deux tableaux encadrés détaillant les "FRAIS ECN" et la grille "ACTION / FRAIS" (ex: 1000 = 8.95$, 2000 = 12.95$).

**Action / Démonstration** : Affichage fixe de la diapositive pédagogique résumant les paramètres et les coûts liés au trading hors heures d'ouverture.

---

### ⏱️ `[00:02:12 - 00:02:41]` | Segment #06

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc, D pour journée. On met une transaction ouverte pour la journée. Pour la journée, ça veut dire de 9h30 jusqu'à 16h. Donc, c'est une transaction normale qui ne nous ajoute pas des frais de transaction ni rien. On est par exemple chez Quesstoy à 4,95$ la transaction et à partir de là, ça reste là que vous achetiez une action ou 100 000 actions, c'est encore 4,95$.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation PowerPoint affichée en mode édition, sur fond blanc.

**Contenu textuel & Code** : Titre : "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE ?". Points clés : "1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE". Deux tableaux : à gauche "FRAIS ECN" détaillant les tarifs selon les types de titres canadiens et américains ; à droite "ACTION / FRAIS" listant des volumes d'actions associés à leurs frais (ex: 1000 = 8.95$, 250 000 = 1004.95$). Les points 1 et 2 sont entourés de rectangles rouges.

**Action / Démonstration** : Capture fixe d'une diapositive explicative textuelle sans manipulation en cours à l'écran.

---

### ⏱️ `[00:02:41 - 00:03:04]` | Segment #07

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Sauf que le problème, c'est quand on arrive dans le prix marché et l'après-marché, on a, par exemple, des frais ECN qui s'ajoutent à nos frais de transaction normaux. Donc, ça peut revenir très cher si vous êtes sur des petites actions. Certains marchés le permettent, d'autres marchés ne le permettent pas.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Document de présentation statique (PDF ou visionneuse d'images) sur fond blanc avec encadrés et texte.

**Contenu textuel & Code** : Titre : "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE ?". Points clés : "1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE". Tableaux : "FRAIS ECN" détaillant les tarifs par action (ex: Canadian securities $1.00 and above : $0.0035/share, U.S. Securities - INET : $0.003/share) et "ACTION / FRAIS" montrant des exemples de tarification par volume d'actions (ex: 1000 = 8.95$, 50 000 = 204.95$).

**Action / Démonstration** : Affichage fixe d'un support pédagogique récapitulant les règles et les frais ECN liés au trading hors heures d'ouverture.

---

### ⏱️ `[00:03:04 - 00:03:26]` | Segment #08

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Oubliez ça si vous pensez que les OTC, il y a du prix marché ou de l'après-marché. Il n'y en a tout simplement pas. Quand c'est fermé, c'est fermé, ça finit là. Sinon, il va y avoir des histoires de form T que je vais vous mettre dans la description ici. Vous pourrez aller voir en haut. Sinon, comme je disais, c'est des paramètres à changer dans votre tableau d'ordre.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Document texte ou présentation affichant un récapitulatif structuré sur fond blanc.

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", suivi de deux points encadrés ("1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE"), ainsi que deux tableaux : "FRAIS ECN" détaillant les tarifs par action (canadiennes et US selon les réseaux) et "ACTION / FRAIS" listant des exemples de commissions par volume (de 1000 à 250 000 actions, allant de 8,95$ à 1004,95$).

**Action / Démonstration** : Présentation statique d'un support visuel explicatif par le présentateur.

---

### ⏱️ `[00:03:27 - 00:03:53]` | Segment #09

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc, on a la duration qu'au lieu d'avoir une transaction pour la journée, on va avoir une transaction qu'on va mettre GTM. Fouillez-moi pourquoi, j'en ai aucune idée pourquoi GTM. Ça ne m'intéresse pas de le savoir et ce n'est pas important. Ce qui est important, c'est que si vous voulez faire une transaction sur le marché hors des heures normales de la bourse, il faut mettre GTM.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Document texte ou présentation affichant un tableau récapitulatif sur le trading pré-market et after-hours.

**Contenu textuel & Code** : Titre : "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE ?". Points clés : "1- DURÉE / DURATION : GTEM" et "2- ORDRE LIMITE OBLIGATOIRE". Deux tableaux de bas de page : "FRAIS ECN" détaillant les tarifs par action (ex: Canadian securities $1.00 and above : $0.0035/share, U.S Securities - MNGD, LAMP : FREE) et "ACTION / FRAIS" listant des commissions par volume d'actions (ex: 1000 = 8.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Le curseur de la souris est positionné au-dessus du premier point encadré en rouge ("1- DURÉE / DURATION : GTEM").

---

### ⏱️ `[00:03:53 - 00:04:18]` | Segment #10

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Et ça, je suis pas mal certain que c'est dans la majorité des BlueWalkers que c'est le même code GTM qu'il faut mettre. Donc, toujours mettre ça. Mais ça, dès que vous embarquez ça, ça veut dire que vous embarquez les frais additionnels. Donc les frais additionnels, regardez c'est tout ça pour les tout dépendant des bourses et tout ça. Donc 4 sous ou 3 sous, t'es dépendant où vous tradez, par où vous passez, blablabla.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Présentation textuelle explicative sur fond blanc avec encadrés et tableaux.

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", points "1- DURÉE / DURATION : GTEM" et "2- ORDRE LIMITE OBLIGATOIRE" encadrés en rouge, tableau des "FRAIS ECN" (tarifs par action selon les marchés canadiens et américains) et tableau "ACTION / FRAIS" (exemples de tarification par volume de 1 000 à 250 000 actions).

**Action / Démonstration** : Le curseur de la souris est visible au-dessus du texte central, pointant vers les éléments de la liste des règles de trading.

---

### ⏱️ `[00:04:18 - 00:04:39]` | Segment #11

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc il y a d'autres places que c'est gratuit, mais stop après ça. Donc quand vous arrivez et que par exemple vous placez des transactions, là les frais vont embarquer et regardez sur une action que vous avez, le prix marché peut être utile pour se dire on va acheter une action à 2, 3, 5, 10, 50 $.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de présentation ou visionneuse d'image avec une diapositive informative sur fond blanc.

**Contenu textuel & Code** : Titre principal "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", deux points clés ("1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE"), ainsi que deux tableaux encadrés : "FRAIS ECN" détaillant les tarifs par action selon les marchés canadiens et américains, et "ACTION / FRAIS" affichant des exemples de commissions par volume d'actions (ex: 1000 = 8.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Le curseur de la souris est visible et immobile au centre du tableau de gauche, sur la ligne "Canadian securities $0.99 and below - CSE".

---

### ⏱️ `[00:04:40 - 00:05:00]` | Segment #12

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Puisqu'on n'achètera pas nécessairement des grosses quantités comme quand on est dans les penny stock ou les micro penny stock, des 2 sous ou 3 sous, ça va coûter extrêmement cher et je vais vous montrer pourquoi. Donc vous avez ça ici, 1000 actions incluant le 4,95 $, donc c'est 8,95 $.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Document visuel explicatif ou diapositive présentant des tableaux de frais boursiers.

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", règles (1- DURÉE / DURATION : GTEM, 2- ORDRE LIMITE OBLIGATOIRE), tableau "FRAIS ECN" avec tarifs par action (ex: Canadian securities $1.00 and above: $0.0035/share) et tableau "ACTION / FRAIS" détaillant le coût total selon le volume (1000 = 8.95$, 2000 = 12.95$, 5000 = 24.95$, 10 000 = 44.95$, 50 000 = 204.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Un curseur de souris est positionné précisément sur la ligne "1000 = 8.95$" dans le tableau de droite.

---

### ⏱️ `[00:05:00 - 00:05:24]` | Segment #13

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc à chaque 1000 actions sur cette bourse-là ici, on rajoute 3$ à chaque fois. Donc si on achète 2000 actions, on va rajouter 6$. 5000 actions, on va en rajouter 15$ de plus. Mais là quand on commence à être dans les grosses quantités, puisque par exemple votre action ne coûte pas cher, elle coûte environ 25 sous.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Document textuel ou présentation (format image/PDF) affichant des informations sur les frais de courtage et le trading en pré-market/after-hours.

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", deux points clés ("1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE"), un tableau de "FRAIS ECN" (tarifs par action selon les bourses canadiennes et américaines) et un tableau "ACTION / FRAIS" détaillant des coûts totaux par volume d'actions (ex: 1000 = 8.95$, 2000 = 12.95$, 5000 = 24.95$, 10 000 = 44.95$, 50 000 = 204.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Le curseur de la souris (flèche) est positionné sur la ligne "1000 = 8.95$" dans le tableau de droite.

---

### ⏱️ `[00:05:24 - 00:05:44]` | Segment #14

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> vous voulez en acheter 10 000 ou 20 000 ou 30 000, ben là ça commence à être cher. 10 000, on est déjà à 44,95$, donc on rajoute 40$ de frais de transaction sur cette bourse-là, tout dépendant de la bourse que vous allez prendre.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Diapositive ou document de présentation synthétique sur fond blanc avec encadrés bleus.

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", 1- DURÉE / DURATION : GTEM, 2- ORDRE LIMITE OBLIGATOIRE, tableau "FRAIS ECN" et tableau "ACTION / FRAIS" détaillant les tarifs par volume d'actions (ex: 10 000 = 44,95$).

**Action / Démonstration** : Le curseur de la souris survole la ligne "10 000 = 44,95$" dans le tableau des frais de transaction.

---

### ⏱️ `[00:05:45 - 00:06:10]` | Segment #15

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc vous voyez que ça peut monter extrêmement vite et vous me le voyez souvent, Moi-même, transiger des quantités de 100 000, 200 000, 500 000 actions, même 1 million d'actions, c'est impensable tout simplement de faire des transactions. Donc, en prix marché, soyez conscient de ça. Quand le prix a du bon sens, quand ce n'est pas en bas de 1$ et que vous n'achetez pas nécessairement des grosses quantités, c'est un mal pour un bien.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Document visuel textuel affiché dans une visionneuse de type logiciel de bureautique ou PDF (fond blanc, barres d'outils Windows/logiciel en haut et en bas).

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", règles "1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE", tableau "FRAIS ECN" détaillant les tarifs par action (ex: $0.0035/share, $0.0008/share, FREE), et tableau "ACTION / FRAIS" montrant la progression des coûts (1000 = 8.95$, 2000 = 12.95$, 5000 = 24.95$, 10 000 = 44.95$, 50 000 = 204.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Le curseur de la souris est visible en bas de l'écran, positionné sous le chiffre "250 000 = 1004.95$".

---

### ⏱️ `[00:06:10 - 00:06:46]` | Segment #16

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Mais si vous allez trop haut, ça va coûter extrêmement cher. Oubliez ça en partant. Je me suis déjà fait prendre dans des transactions obligatoires en pre-market avec des 150 000 actions et des choses comme ça. Ça m'est arrivé. et laissez-moi vous dire et j'ai bien fait, c'est ça qui est le pire mais je perdais du 3, 4, 5 600$ de frais de transaction pour en sauver 1000, 2000, 3000 au bout de la ligne donc c'était un mal pour un bien mais on ne veut pas que ça arrive donc faites attention avec les grosses quantités ça peut être très dangereux

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de présentation ou traitement de texte affichant une diapositive informative sur fond blanc avec encadrés rectangulaires bleus.

**Contenu textuel & Code** : Titre principal "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN ÇA COUTE ?", suivi de deux points clés encadrés ("1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE"). En bas à gauche, tableau des "FRAIS ECN" détaillant les tarifs par action (ex: Canadian securities $1.00 and above = $0.0035/share, U.S. Securities - INET = $0.003/share). En bas à droite, tableau "ACTION / FRAIS" montrant le coût total selon le volume d'actions (ex: 1000 = 8.95$, 2000 = 12.95$, 5000 = 24.95$, 10 000 = 44.95$, 50 000 = 204.95$, 250 000 = 1004.95$). Curseur de souris visible au bas du tableau de droite.

**Action / Démonstration** : Présentation statique d'un tableau explicatif récapitulant les frais de courtage et commissions ECN en fonction du volume d'actions transigées.

---

### ⏱️ `[00:06:46 - 00:07:07]` | Segment #17

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> de ce côté là, autre petit danger à faire attention c'est quand le marché va ouvrir à l'ouverture, ne pas oublier de remettre la duration à une transaction qui va durer pour la journée. Parce que même si on est pendant la journée et que vous mettez GTM, les frais vont être là quand même.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Diapositive explicative de présentation sur fond blanc avec encadrés et tableaux bleus.

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", points clés "1- DURÉE / DURATION : GTEM" et "2- ORDRE LIMITE OBLIGATOIRE", tableaux détaillant les frais ECN et la grille "ACTION / FRAIS" (ex: 1000 = 8.95$, 2000 = 12.95$, etc.).

**Action / Démonstration** : Le curseur de la souris (flèche) est positionné au centre de l'écran, au-dessus du premier point clé encadré en rouge.

---

### ⏱️ `[00:07:08 - 00:07:46]` | Segment #18

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc même si on est pendant la journée, vous pouvez vous mettre à trader et à trader et à trader avant de vous rendre compte « Oh merde, j'étais sur le GTM et tous les frais de transaction embarquent et ça peut être l'enfer. » Donc vous voyez un peu le genre, quand il arrive 9h30 à l'ouverture du marché, changer absolument ça, c'est une erreur à ne pas faire. Deuxième chose qui est très important, quand on va passer un ordre en pré-marché ou en après-marché, il faut mettre un ordre limite obligatoire. Pourquoi un ordre limite obligatoire? Eux, ils ont mis ça et je les comprends très bien que s'il n'y aurait pas de limite, souvent en pré-marché,

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de visualisation d'images ou document PDF affichant une diapositive de présentation éducative sur fond blanc avec des encadrés rouges et des tableaux bleus.

**Contenu textuel & Code** : Texte centré "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", points "1- DURÉE / DURATION : GTEM" et "2- ORDRE LIMITE OBLIGATOIRE", tableau "FRAIS ECN" détaillant des tarifs par action (ex: 0,0035$/share, FREE) et tableau "ACTION / FRAIS" listant des volumes et commissions associés (ex: 1000 = 8.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Le présentateur affiche une diapositive explicative synthétisant les règles de durée (GTEM) et les structures de frais ECN et de commissions applicables.

---

### ⏱️ `[00:07:46 - 00:08:12]` | Segment #19

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> le gap entre les acheteurs et les vendeurs est extrême parce que le marché n'est pas là encore parce que 95% des traders ne sont pas encore sur le marché ce qui fait qu'une action qui généralement aurait par exemple 1 sou de différence entre les acheteurs et les vendeurs peut en avoir 10, 20, 50 sous.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de visionnage d'image ou document PDF affichant une diapositive de présentation pédagogique.

**Contenu textuel & Code** : Texte centré "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", deux points encadrés en rouge ("1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE"), un tableau des "FRAIS ECN" (ex: $0.0035/share) et un tableau "ACTION / FRAIS" détaillant les commissions par volume d'actions (ex: 1000 = 8.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Le curseur de la souris est visible et positionné au centre de la première ligne encadrée en rouge.

---

### ⏱️ `[00:08:12 - 00:08:48]` | Segment #20

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> donc les ordres limites sont obligatoires parce que si on fait marcher parce que ton stop débarque et juste quelqu'un a voulu faire débarquer ton stop et l'a vendu pendant qu'il n'y avait absolument personne sur le marché un sou plus bas et il vous fait débarquer en tout cas vous voyez un peu le genre donc en pré-marché et en after-hour il n'y a aucun stop possible et il faut absolument mettre la limite parce que si vous ne mettez pas de limite l'action peut être à 1,60 mais à cette fraction de seconde là ou pendant ce temps là il n'y a juste personne sur le marché

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Document visuel explicatif (type présentation ou PDF) affiché à l'écran sur fond blanc.

**Contenu textuel & Code** : Texte centré "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE ?", suivi de deux points encadrés : "1- DURÉE / DURATION : GTEM" et "2- ORDRE LIMITE OBLIGATOIRE". Deux tableaux en bas : à gauche "FRAIS ECN" détaillant les tarifs selon les bourses (canadiennes et américaines de 0,0008$/share à 0,004$/share, ou FREE), et à droite "ACTION / FRAIS" listant des volumes d'actions avec leurs commissions associées (ex: 1000 = 8.95$, 250 000 = 1004.95$). Le curseur de la souris est visible près du texte "GTEM".

**Action / Démonstration** : Le présentateur illustre les règles de base du trading hors-séance, en pointant du curseur la durée GTEM et l'obligation d'utiliser des ordres limites.

---

### ⏱️ `[00:08:48 - 00:09:14]` | Segment #21

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> donc les bids vont être à 1$ et vous, vous allez faire hors de limite hors de limite au marché vous allez être filé à 1$ ça n'a aucun sens donc les hors de limite c'est pour vous protéger d'une certaine manière de ne pas faire ce genre d'erreur là et ça oblige un minimum en pré-marché et en after hour donc vous voyez un petit peu le genre qu'il faut faire Attention quand même quand on va trader.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de visionnage d'image ou traitement de texte affichant une diapositive explicative synthétique.

**Contenu textuel & Code** : Titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE?", points clés encadrés en rouge ("1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE"), et deux tableaux comparatifs : "FRAIS ECN" détaillant les tarifs par action selon les marchés (canadiens et américains) et "ACTION / FRAIS" listant les commissions par volume d'actions (de 1000 à 250 000 actions).

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné près du texte "GTEM" à l'écran.

---

### ⏱️ `[00:09:15 - 00:09:36]` | Segment #22

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> C'est vraiment un bon moment pour trader. Le marché quand il est là le matin, si par exemple il y a une action qui est montée de 25, 30 ou 50%, c'est certain que le marché va être presque tous focus au même endroit. Le gap va être minime et vous allez pouvoir transiger comme une action ouverte en plein milieu de la journée.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Document texte ou présentation affiché en plein écran avec un fond blanc.

**Contenu textuel & Code** : Titre en majuscules bleues : "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE ?". Deux points clés encadrés de rouge : "1- DURÉE / DURATION : GTEM" et "2- ORDRE LIMITE OBLIGATOIRE". Deux tableaux : à gauche, "FRAIS ECN" détaillant les tarifs par action pour les titres canadiens et américains (ex: $0.0035/share, FREE) ; à droite, "ACTION / FRAIS" listant les coûts totaux selon le volume (ex: 1000 = 8.95$, 5000 = 24.95$, jusqu'à 250 000 = 1004.95$).

**Action / Démonstration** : Présentation statique de la diapositive explicative sur les règles et les frais de courtage en dehors des heures de cotation normales.

---

### ⏱️ `[00:09:36 - 00:10:12]` | Segment #23

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc c'est à ne pas négliger. le pré-marché peut être très intéressant mais il faut absolument savoir ce qu'on fait c'est sûr quand on s'en va de ce côté là en mettant la duration à GTM en mettant notre ordre limite à chaque coup et en n'oubliant surtout pas de remettre tout ça quand l'ouverture du marché arrive à duration journée donc à ne pas oublier erreur à ne pas faire, ce qui m'est déjà arrivé apprenez de mes erreurs et j'ai payé

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Diapositive de présentation pédagogique affichée sur fond blanc.

**Contenu textuel & Code** : Texte explicatif sur le trading en pré-marché/after-hours avec deux encadrés rouges : "1- DURÉE / DURATION : GTEM" et "2- ORDRE LIMITE OBLIGATOIRE". Deux tableaux de bas de page détaillent les frais ECN et la grille tarifaire par nombre d'actions (de 1 000 à 250 000 actions, de 8,95$ à 1004,95$).

**Action / Démonstration** : Le curseur de la souris est positionné au centre de l'écran, sous le deuxième encadré rouge.

---

### ⏱️ `[00:10:12 - 00:10:42]` | Segment #24

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> assez cher pour le savoir donc oubliez pas tous ces détails là alors c'est à peu près ça pour cette vidéo mes chers amis, j'espère que vous allez avoir apprécié tous les détails tout est là alors si oui vous pouvez m'exploser les bons pouces bleus, vous pouvez aussi continuer votre formation avec moi en regardant justement les vidéos qui vont suivre ici et je vous remercie aussi si vous voulez d'aller visiter mon site d'animerytrader.com pour plus d'informations sur ce que je fais en général.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Visionneuse de document ou logiciel de présentation affichant un support visuel explicatif sur fond blanc.

**Contenu textuel & Code** : Texte récapitulatif centré : titre "COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE ?", points "1- DURÉE / DURATION : GTEM", "2- ORDRE LIMITE OBLIGATOIRE", ainsi que deux tableaux encadrés détaillant les "FRAIS ECN" et la grille tarifaire "ACTION / FRAIS" (ex: 1000 = 8.95$, 250 000 = 1004.95$).

**Action / Démonstration** : Le curseur de la souris est visible au centre, positionné au niveau du premier point sur la durée (GTEM), illustrant la conclusion de la vidéo.

---

### ⏱️ `[00:10:43 - 00:10:50]` | Segment #25

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc, merci à tous. Je vous remercie encore une fois d'avoir été là. Et on se reparle. Très bientôt. Ciao tout le monde.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Diapositive de présentation textuelle affichée sur fond blanc.

**Contenu textuel & Code** : Texte centré intitulé « COMMENT TRADER EN PRÉ-MARKET ET AFTER HOURS ET COMBIEN CA COUTE? » avec deux points clés encadrés : « 1- DURÉE / DURATION : GTEM » et « 2- ORDRE LIMITE OBLIGATOIRE ». Deux tableaux explicatifs : à gauche « FRAIS ECN » détaillant les tarifs par action selon les marchés canadiens et américains, et à droite « ACTION / FRAIS » montrant le coût total par volume d'actions (ex: 1000 = 8.95$, 5000 = 24.95$, jusqu'à 250 000 = 1004.95$).

**Action / Démonstration** : Le curseur de la souris est visible au centre de l'écran, au-dessus du titre principal.

---
