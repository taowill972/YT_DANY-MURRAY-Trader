# 🎬 SCREENER DU MARCHÉ DES STOCKS US / CAD ET OTC POUR TRADER AVEC  PETIT OU GROS CAPITAL DE DÉPART...

> **Chaîne** : [Dany Murray Trader](https://www.youtube.com/@danymurraytrader6032)  
> **Lien YouTube** : [https://www.youtube.com/watch?v=9FgV1cdthno](https://www.youtube.com/watch?v=9FgV1cdthno)  
> **Date de publication** : 2020-08-08  
> **Durée** : 30m 13s (`1813s`)  
> **Identifiant vidéo** : `9FgV1cdthno`  
> **Modèles utilisés** : Audio: `large-v3-turbo` (Faster-Whisper int8 VPS) | Vision: `gemini-3.5-flash-lite` (Google AI Studio API)  

---

## 📌 Synthèse Exécutive & Outils

### 💡 Résumé

Cette vidéo de Dany Murray aborde l'un des aspects les plus critiques du trading de *penny stocks*, d'actions à faible capitalisation et de titres OTC : la mise en place d'un *screener* performant et en temps réel sur la plateforme Questrade. Contrairement aux tableaux de bord classiques de type « Top Gainers » (souvent mis en cache ou rafraîchis avec un décalage préjudiciable de plusieurs minutes), le *screener* personnalisé offre aux traders une maîtrise totale sur les flux de marché et permet d'isoler les véritables opportunités du jour parmi des millions d'actions cotées.

La méthode de Dany Murray repose sur une rigueur implacable en matière de filtrage pour éliminer le « bruit de marché ». En compartimentant les écrans de recherche selon les bourses (Marché US, Marché Canadien, et Marchés OTC / Pink Sheets), le trader évite les erreurs opérationnelles et adapte ses critères de prix et de liquidité à chaque niche. Le cœur de sa stratégie consiste à cibler en priorité les actions à fort pourcentage de variation tout en appliquant des barrières strictes, notamment sur le volume minimum de transactions pour écarter les faux signaux et les pièges de liquidité.

À travers cette démonstration pratique, la leçon principale est que le succès en trading de momentum ne dépend pas seulement de la détection des hausses, mais de la capacité à structurer un environnement de travail propre, rapide et sécurisé. En automatisant le tri des actions sous un certain seuil de prix (par exemple, en dessous de 1 $) et en exigeant un volume plancher (comme 250 000 actions), le trader protège son capital contre les manipulations et se concentre exclusivement sur des configurations hautement probables.

---

### 🛠️ Outils, Plateformes & Logiciels Présentés

*   **Questrade :** Courtier en ligne et plateforme de courtage principale utilisée pour le passage d'ordres et l'accès au *screener*.
*   **Stock Screener (Questrade) :** Outil de filtrage avancé intégré à la plateforme, indispensable pour configurer des listes de surveillance personnalisées (*Custom Screens*).
*   **Marchés et bourses ciblés :** 
    *   Marché US (NASDAQ, NYSE, ARCA / New York).
    *   Marché Canadien (TSX, CNSX, NEO).
    *   Marchés OTC et Pink Sheets (pour les micro-capitalisations et les petits budgets).
*   **Filtres et indicateurs clés :**
    *   *Percentage Change* (% de variation) pour classer les actifs par ordre de momentum.
    *   *Last Price* (Prix de dernier échange) pour cibler les actions à bas prix (sous 1 $ ou sous 10 $).
    *   *Volume* (Volume de transactions journalier) pour filtrer les actions illiquides.
*   **Top Gainers / Market Movers :** Tableaux de bord alternatifs (mentionnés pour leurs limites, notamment leur manque de rafraîchissement en temps réel).

---

### 🔑 Points Clés & Enseignements Stratégiques

1.  **Privilégier le *Screener* au détriment des *Top Gainers* :** Les tableaux de bord généralistes manquent souvent de réactivité (rafraîchissement lent de type 5 minutes) ; un *screener* personnalisé permet d'obtenir des données en temps réel indispensables sur les actions à fort mouvement.
2.  **Segmenter les marchés par listes dédiées :** Créer des tables distinctes pour le marché US, le marché canadien et les OTC évite les erreurs de manipulation et d'exécution lors du passage d'ordres.
3.  **Filtrer impérativement le bruit de marché :** Le nombre total d'actions cotées étant immense, le rôle premier du *screener* n'est pas de trouver des idées, mais d'éliminer agressivement tout ce qui ne correspond pas à sa stratégie.
4.  **Maîtriser sa niche de prix :** Concentrer ses recherches sur des gammes de prix précises (par exemple, les actions sous 1 $ ou sous 10 $) en fonction de sa tolérance au risque et de la taille de son capital de départ.
5.  **Exiger un volume plancher strict :** Imposer un filtre de volume minimal (comme 250 000 actions échangées) permet d'éliminer les "fonds de tiroir" et les valeurs mortes qui affichent de faux pourcentages de hausse sur de microscopiques transactions.
6.  **Éviter les pièges de liquidité :** Un faible volume combiné à une forte variation en pourcentage est souvent le piège classique d'un titre illiquide impossible à revendre au prix affiché.
7.  **Optimiser la gestion du petit capital :** Les segments OTC et Pink Sheets, accessibles via un filtrage rigoureux, offrent des opportunités asymétriques pour les traders disposant d'un capital de départ restreint.
8.  **Personnaliser l'affichage des colonnes :** Ne garder à l'écran que les informations réellement utiles à la prise de décision (variation en %, dernier prix, volume) pour garder l'esprit clair et réactif.
9.  **Automatiser l'exclusion des erreurs :** En séparant les marchés réglementés des OTC dans des fenêtres de screener différentes, le trader s'interdit d'exécuter par inadvertance des ordres non conformes à sa structure de compte.
10. **La discipline de configuration :** Un bon trader passe du temps à paramétrer ses outils en amont pour que, pendant les heures d'ouverture des marchés, la prise de décision devienne instantanée et mécanique.

---

## ⏱️ Chronologie & Transcription Complète Audio & Visuelle (Mot pour Mot)

### ⏱️ `[00:00:01 - 00:00:23]` | Segment #01

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Alors bonjour tout le monde ici Anivery pour un Muraylicious cours de bourse pour vous aujourd'hui. Aujourd'hui on va parler enfin du fameux Screener. Donc le Screener de Questrade. Et non ça ne sera pas le Top Gainer comme on discute habituellement. Mais là ça va être bel et bien le Screener.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading Questrade IQ Edge (onglet Screener actif).

**Contenu textuel & Code** : Tableau de filtrage "Most volatile stocks" affichant des tickers boursiers (TRVN à 2.80$, MCRB à 4.20$, MARA à 3.31$, MVIS à 2.54$, KODK à 14.40$, etc.) avec leurs variations en dollars et en pourcentage, volumes et volatilité implicite (IV).

**Action / Démonstration** : Affichage fixe du screener par défaut du logiciel sans manipulation de curseur visible.

---

### ⏱️ `[00:00:23 - 00:00:47]` | Segment #02

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Comment le set-upper, comment arranger tout ça, où le trouver. Donc on vous parle de tout ça. En restant dans cette superbe vidéo. Et n'oubliez pas que cette vidéo est d'autant plus importante pour ceux qui ont un petit capital pour chercher les fameux OTC. Là, on a parlé beaucoup des OTC, mais les gens se demandent où trouve-t-on les OTC.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading Questrade IQ Edge affichant une liste de sélection de type screener/scanner de marché filtrée sur les actions les plus volatiles ("Most volatile stocks"). Barre d'outils supérieure visible avec accès aux modules Account, Level 1, Level 2, Chart, Screener, StockTwits et Watch list.

**Contenu textuel & Code** : Tableau de données boursières listant des tickers américains : TRVN (2,80 $, -4,76 %), MCRB (4,20 $, +2,69 %), CRBP (6,86 $, +1,03 %), MARA (3,31 $, -13,58 %), IBIO (4,39 $, -2,88 %), MVIS (2,54 $, +27,00 %), KODK (14,40 $, -3,61 %), HMHC (3,16 $, +8,22 %), CEMI (5,90 $, +0,51 %), LEJU (3,39 $, -7,38 %), CAPR (8,07 $, +5,08 %), PGEN (4,62 $, +3,59 %), BCRX (4,23 $, -3,86 %), MBIO (3,26 $, -5,22 %), XSPA (4,13 $, -8,63 %), ODT (36,90 $, -0,03 %), RIOT (3,40 $, -2,86 %), XERS (3,20 $, +3,90 %), XNET (3,82 $, -10,96 %), ALBO (24,75 $, -5,61 %). Colonnes affichées : Symbol, Description, Last, Chg $, Chg %, Day price rank, High low spd %, Vol, Vol 20d rel, IV.

**Action / Démonstration** : Présentation statique du screener de volatilité par le trader, affichant les actions à forte volatilité implicite (IV) triées dans l'interface, servant de base pour identifier les opportunités de trading sur petits capitaux.

---

### ⏱️ `[00:00:47 - 00:01:13]` | Segment #03

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc, on va regarder tout ça. C'est ici que ça se passe. C'est dans ce tableau-là. Pourtant, rien n'est visible. Mais comment on va s'etoper tout ça? On va se faire un screener pour le marché normal et on va se faire un screener pour les OTC. Donc vous allez être équipé pour faire les deux, trouver les meilleurs stocks du jour et régler le problème tout simplement avec le fameux screener.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading Questrade IQ Edge affichant un tableau de screener de marché sous forme de grille de données.

**Contenu textuel & Code** : Tableau des actions les plus volatiles ("Most volatile stocks") listant les tickers (TRVN, MCRB, MARA, KODK, MVIS, etc.), descriptions d'entreprises, prix actuels (Last), variations en dollars et en pourcentages (Chg $, Chg %), rangs de prix du jour (Day price rank), volumes (Vol) et volatilité implicite (IV-).

**Action / Démonstration** : Le présentateur affiche le tableau récapitulatif des actions volatiles pour préparer la configuration du screener de marché.

---

### ⏱️ `[00:01:13 - 00:01:49]` | Segment #04

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc on commence tout ça. Comme je disais précédemment, ce n'est pas le fameux tableau des market movers. les market movers l'avantage, désavantage bon c'est un petit tableau facile à regarder facile à analyser à mettre les filtres et tout ça mais pour le reste habituellement il n'est pas live donc c'est un désavantage de ne pas l'avoir live, il le refresh peut-être aux 5 minutes, donc là 5 minutes plus tard, oh on est rendu 20% plus haut donc c'est un petit peu plus tannant pour ça, donc c'est pas ce tableau là qu'on va jaser aujourd'hui, c'est vraiment le screener

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Dany Murray face caméra ou présentation générale de trading.

**Contenu textuel & Code** : Explications orales des concepts de bourse et psychologie de marché.

**Action / Démonstration** : Démonstration pédagogique et partages d'expériences de trading.

---

### ⏱️ `[00:01:49 - 00:02:23]` | Segment #05

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> donc où trouve-t-on le screener mes chers amis on va aller voir ça à l'instant on enlève ça le screener vous avez votre petite barre de tâche ici que vous avez habituellement dans le haut de votre logiciel Questrade donc chez Questrade je ne peux pas parler pour les autres plateformes parce que je ne sais même pas s'ils ont un screener ou quelle sorte de screener et tout ça mais pour Questrade vous allez aller tout simplement ici le screener Donc, vous cliquez sur l'option ici et ça va vous amener ce beau tableau-là que vous voyez ici.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading Questrade IQ Edge affichant la barre d'outils supérieure et un tableau de type screener/market scanner ("Most volatile stocks").

**Contenu textuel & Code** : Tableau listant des tickers d'actions (TRVN, MCRB, CRBP, MARA, IBIO, MVIS, KODK, HMHC, CEMI, LEJU, CAPR, PGEN, BCRX, MBIO, XSPA, ODT, RIOT, XERS, XNET, ALBO) avec les colonnes Last, Chg $, Chg %, Day price rank, High low spd %, Vol, Vol 20d rel, IV.

**Action / Démonstration** : Le curseur de la souris est positionné au niveau de l'icône "Event calendar" dans la barre d'outils horizontale supérieure.

---

### ⏱️ `[00:02:24 - 00:02:45]` | Segment #06

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc, c'est le tableau à regarder et vous allez voir avec le temps, vous allez vous habituer peut-être à travailler avec ça qui va être encore mieux que tout le reste. Donc, on va quand même commencer à setupper tous ces petits détails-là. On y va en instant. Donc, ça c'est le premier tableau qui vous envoie la première fois que vous voyez.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading Questrade IQ Edge affichant un tableau de cotations (Market View / Watch list).

**Contenu textuel & Code** : Tableau listant des tickers d'actions (TRVN, MCRB, CRBP, MARA, MVIS, KODK, etc.) avec leurs colonnes respectives : "Last", "Chg $", "Chg %", "Day price rank", "High low spd %", "Vol", "Vol 20d rel", "IV". On y lit notamment MVIS à 2.54 avec une variation de +27,00% et un volume de 25.54M.

**Action / Démonstration** : Aucune manipulation active visible (pas de curseur de souris distinct ou de tracé), affichage statique de la liste de sélection des titres.

---

### ⏱️ `[00:02:45 - 00:03:20]` | Segment #07

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> vous cliquez sur Stock Screener et vous voyez ça donc là, une tonne de colonnes plus ou moins utiles, plus ou moins utiles pour ce que moi je vais faire mais on s'entend tous les gens peuvent trouver une utilité à des certains détails il y en a qui vont regarder les volumes relatifs, donc des volumes peu importe, il y a multiples façons de faire mais en général, je vous dirais, c'est souvent des façons de faire pour éliminer ce qu'on ne veut pas voir, parce que des stocks à voir, il n'y en a pas tant que ça à tous les jours.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Plateforme de courtage Questrade IQ Edge (outil Stock Screener / "Most volatile stocks").

**Contenu textuel & Code** : Tableau de筛选 d'actions affichant divers tickers (TRVN, MCRB, CRBP, MARA, IBIO, MVIS, KODK, HMHC, CEMI, LEJU, CAPR, PGEN, BCRX, MBIO, XSPA, ODT, RIOT, XERS, XNET, ALBO), avec leurs descriptions, prix (Last), variations en $ et %, rang de prix (Day price range), volatilité (High low spd %), volumes (vol) et volatilité implicite (IV %).

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné au centre du tableau, entre les lignes HMHC et CEMI, illustrant la revue des colonnes du scanner.

---

### ⏱️ `[00:03:21 - 00:03:57]` | Segment #08

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Oui, nous, on nage dans toutes ces actions-là, dans les actions avec des super gains d'enfer et tout ça, comme vous voyez par exemple aujourd'hui, 126, 72, 70, donc ça, c'était la journée d'aujourd'hui. Nous, on nage dans ces actions-là, mais en général, des stocks, il y en a des milliers, sinon des millions, donc on va oublier ça et on va essayer de trouver les meilleurs donc on va commencer tout de suite en partant, quand on va arriver ici on a Most Volestile Stock on s'en fout on va s'en créer un nouveau en espérant que ça ne gèle pas trop

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading Questrade IQ Edge (tableaux de sélection et de suivi des marchés boursiers américains).

**Contenu textuel & Code** : Tableau des "Top gainers" affichant des tickers US avec prix, variations en pourcentage et volumes : ATHE (3,06 $ ; +126,67 %), WLL (1,33 $ ; +72,73 %), ARPO (2,20 $ ; +70,54 %), AGE, VRAY, UUU, ALRN, SINT, MVIS, CVEO, HNRG, PRPO, IMAC, PPSI, TCON, OCX, ZSAN, ASM, OSN, OSS. Colonnes additionnelles affichant les volumes relatifs et la volatilité implicite (IV) à droite.

**Action / Démonstration** : Affichage fixe d'un scanner de marché montrant les meilleures performances journalières (top hausses) des actions américaines.

---

### ⏱️ `[00:03:57 - 00:04:35]` | Segment #09

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> donc on ajoute ici ça va à New Custom Screen et on clique dessus on va lui donner un nom on va marquer par exemple US Market donc le US Market va être créé on va changer le nom juste pour l'exemple, il dit qu'il y en a déjà un mais je reproduis ce que j'ai déjà donc le US Market donc on arrive avec ça on va fermer ce qu'il nous donne préalablement on s'en fout pas mal donc on ferme ça, là on a US Market

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage / plateforme de screening boursier (interface sombre avec tableau de données).

**Contenu textuel & Code** : Tableau de screener affichant des tickers boursiers US et leurs métriques : TRVN (2,80$, -4,76%), MCRB (4,20$, +2,69%), CRBP (6,86$, +1,03%), MARA (3,31$, -13,58%), IBIO (4,39$, -2,88%), MVIS (2,54$, +27,00%), KODK (14,40$, -3,61%), HMHC (3,16$, +8,22%), ainsi que des colonnes Last, Chg $, Chg %, Day price rank, High low spd %, Vol, Vol 20d rel, IV et IV chg %.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné au centre du tableau de cotations, sur la ligne du titre XNET.

---

### ⏱️ `[00:04:35 - 00:05:11]` | Segment #10

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> et vous allez pouvoir faire aussi ajouter des nouvelles tables, les tables principales que vous allez avoir besoin faire ça va être US market, Canadian market et OTC et Pinksheet. Donc c'est trois tables, trois screeners différents qui vont demander des options différentes. C'est certain qu'on pourrait tout mettre dans le même tableau mais pour que ce soit plus clair à savoir où on trade évidemment quand on trade des OTC on peut pas les trader par exemple dans des contre ER des choses comme ça donc ça nous évite de piser sur le bouton puis là il y a une erreur on se

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage (interface de screener/tableau de données boursières sur fond sombre).

**Contenu textuel & Code** : Tableau de données "US MARKET" affichant des tickers boursiers américains (ZEUS, YORW, WIRE, VEC, USPH, UNL, UNF, UFCS, THFF, TBNK, SAFT, REXR, QADA, PTVCB, OCSL, MTD, MGIC, LN, IOSP, IIIN), avec les colonnes Symbol, Description, Last, Chg %, Mkt cap, EPS, P/E, etc., et les bourses sélectionnées (NYSE, NASDAQ, NYSEAM, ARCA, PINK/OTCBB, TSX, TSXV, CNSX, NEO, BATS).

**Action / Démonstration** : Le curseur de la souris survole le bouton "+" situé à côté de l'onglet "US MARKET" pour ajouter un nouveau screener ou une nouvelle table.

---

### ⏱️ `[00:05:11 - 00:05:51]` | Segment #11

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> demande qu'est ce qui se passe on va être obligé d'aller lire et peu importe donc ça évite ce genre d'erreur. Mais on va commencer avec un donc le US market. Qu'est ce qu'on a besoin dans les US market optionnables donc on n'est pas dans les options vous allez aller dans tous les stocks, All Stock. Donc un coup que All Stock est fait on clique sur le stock, ça c'est beau et il nous demande comment le ranker donc le mettre en ordre de quoi donc on va aller lui mettre en pourcentage change donc des pourcentages de gains des plus gros pourcentages ou de pertes vont être set up

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de screening de marché boursier (US Market) avec un tableau de données, des menus déroulants de filtrage en haut (Stocks / Options, bourses NYSE, NASDAQ, etc.) et des onglets de configuration de filtres fondamentaux.

**Contenu textuel & Code** : Tableau de cotations listant divers tickers d'actions américaines (ZEUS, YORW, WIRE, VEC, USPH, UNL, UNF, UFCS, THFF, TBNK, SAFT, REXR, QADA, PTVCB, OCS1, MTD, MGIC, LNN, IOSP, IIIN) avec leurs descriptions complètes, prix actuels (Last), variations en pourcentage (Chg %), capitalisation boursière (Mkt cap), ratios financiers (EPS, P/E, etc.).

**Action / Démonstration** : Le curseur de la souris survole et clique sur l'onglet "Stocks" du menu supérieur pour filtrer l'affichage des marchés américains sur les actions simples plutôt que sur les options.

---

### ⏱️ `[00:05:51 - 00:06:29]` | Segment #12

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> et donc on va faire appliquer tout de suite en partant mais là on n'a rien set up et encore donc faut pas oublier le vu qu'on est dans tous les marchés ok on va avoir besoin de sélectionner bien des petites choses donc le new york ici le nasdaq le new york sim donc arca et l'on s'arrête là parce qu'après ça c'est le pink donc quand vous ferez votre prochaine table vous allez cliquer seulement pink et si vous faites le canadien vous allez mettre tsx tsx cnsx bon et un nio bats on va

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage Questrade IQ Edge (Market Screener / Scanner de marché boursier).

**Contenu textuel & Code** : Tableau de sélection d'actions américaines affichant les colonnes Symbol, Description, Last, Chg %, Chg % 1y, Mkt cap, EPS, P/E avec des tickers comme ZEUS, YORW, WIRE, VEC, USPH. En haut, cases à cocher des bourses : NYSE, NASDAQ, NYSEAM, ARCA, PINK/OTCBBM, TSX, TSXV, CNSX, NEO, BATS.

**Action / Démonstration** : Le curseur de la souris survole la case à cocher "ARCA" dans le menu de filtrage des marchés boursiers.

---

### ⏱️ `[00:06:29 - 00:07:04]` | Segment #13

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> les mettre pour New York aussi donc on fait appliquer et là nous voilà avec les top gainers ça c'est à peu près la même liste des top gains que l'on a sur le tableau des top gainers qu'on a habituellement sauf que là on va évidemment changer, ajouter quelques filtres parce que on veut pas se ramasser avec, on a un range bien à nous on a notre niche bien à nous on sait où on est confortable, est-ce que c'est dans les plus petites actions, dans les plus grosses actions,

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Plateforme de market screening boursier (interface sombre de type screener d'actions).

**Contenu textuel & Code** : Tableau des "top gainers" US avec colonnes Symbol, Description, Last, Chg %, Mkt cap, etc. Tickers visibles : ATHE (3,43 $, +154,07 %), SSNT (5,40 $, +98,53 %), SINT, WLL, UUU, IRTC, SRNE, VRAY, MVIS, PRPO.

**Action / Démonstration** : Le curseur de la souris survole le tableau des résultats de recherche configuré par les filtres.

---

### ⏱️ `[00:07:05 - 00:07:27]` | Segment #14

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> avec plus de float, moins de float et tout ça. Donc, on va ajouter des stock filters. Donc là, ici, c'est ajouter des options. On n'est pas dans les options, on n'est pas dans les fondamentales. C'est add stock filter. Donc, qu'est-ce qu'il y aurait comme stock filter à vérifier? Il ne faut pas mettre ça plus compliqué que ce que ça l'est en général.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de screener de marché boursier (interface sombre avec tableau de scan de type US Market).

**Contenu textuel & Code** : Tableau de données de scanner boursier affichant des colonnes : Symbol, Description, Last, Chg %, Chg % 1d, Mkt cap, EPS, EPS growth, P/E, Forward P/E. Premiers tickers listés : ATHE (3.43 $, +154.07 %), SSNT (5.40 $, +98.53 %), NBACW, SINT, WLL, UUU, AGE, BRLIW, IRTRC, SRNE, TCCO, OSN, ETHC.TO, VRAY, MVIS, DAC, LIVKW, AHT.PRI, AHT.PRF, PRPO. En-tête avec boutons de filtrage : "Add fundamental filter", "Add stock filter", "Add option filter".

**Action / Démonstration** : Le curseur de la souris (flèche) pointe précisément sur le bouton vert "Add stock filter".

---

### ⏱️ `[00:07:27 - 00:08:02]` | Segment #15

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> donc on va y aller avec les limites de prix donc le prix on va dire price range quelque part 2 secondes on va y aller par last price donc last price c'est correct un minimum donc le minimum c'est 0.5 par exemple 0.05 on s'en fout, il n'y aura pas pareil parce qu'on est à New York mais pour les pink sheets ça peut être intéressant. On va en reparler un petit peu plus loin aussi pour les pink sheets.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Plateforme de courtage US Market (scanner de marché / screener boursier).

**Contenu textuel & Code** : Tableau de筛选 (screener) affichant des tickers US (ATHE à 3.43$, SSNT, NBACW, SINT, WLL, UUU, AGE, BRLIW, IRTC, SRNE, TCCO, OSN, ETHC.TO, VRAY, MVIS, DAC, LIVKW, AHT.PRI, AHT.PRF, PRPO), variations en pourcentage (Chg % de +154.07% à +25.24%), capitalisations boursières et filtres actifs configurés sur "Last price".

**Action / Démonstration** : Dany Murray configure les filtres du scanner, sélectionnant le critère de prix "Last price" dans les options de recherche de range.

---

### ⏱️ `[00:08:02 - 00:08:36]` | Segment #16

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Maximum donc là c'est votre maximum. Est-ce que vous vous traitez des actions à maximum 1$? Est-ce que vous traitez des actions maximum à 5$ ou à 10$? C'est ici vous allez l'indiquer. Donc par exemple moi je vais y aller à 10$ par exemple. Donc appliquer. Donc premier setup de fait, vous voyez le last, tout est pris en bas de 10$, mais on va y aller pour la bonne cause et on va y aller en bas de 1$ parce que je crée presque juste des actions en bas de 1$.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de screener boursier (Interface US MARKET) avec panneaux de filtres avancés et tableau de cotation.

**Contenu textuel & Code** : Tableau de scanner affichant des tickers (ATHE, SSNT, SINT, WLL, etc.), prix de clôture ("Last"), variations en pourcentage ("Chg %"), capitalisation boursière ("Mkt cap") et filtres de prix configurés avec une fourchette maximale ("Range") fixée à 10$.

**Action / Démonstration** : Le curseur de la souris survole et clique sur le bouton vert "Apply" pour valider le filtre de prix maximum.

---

### ⏱️ `[00:08:36 - 00:09:12]` | Segment #17

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Une fois de temps en temps qu'il n'y a rien en bas de 1$, je me sens un peu condamné à aller au-dessus de 1$, mais on va y aller avec 1$. Donc premier filtre, c'est ça. donc deuxième filtre on va en ajouter un autre parce que c'est un filtre très important ça va être un filtre de volume parce qu'on veut éliminer les stocks qui donnent rien les stocks qui ne se transigent presque pas il va y avoir quelques transactions ils vont nous faire croire qu'on a eu un 15 ou un 30 ou un 50% de hausse avec pratiquement pas d'action vendue ou achetée donc c'est des stocks à éliminer

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage Questrade IQ Edge (outil de scanneur/filtrage de marché "US MARKET").

**Contenu textuel & Code** : Tableau de résultats de filtrage boursier affichant des tickers (NBACW à 0.18$ / +80.00%, BRLIW à 0.16$ / +33.33%, ETHC.TO à 0.60$ / +29.03%, INFI à 1.01$ / +10.03%), colonnes Last, Chg %, Mkt cap, EPS, P/E, ainsi qu'un filtre de prix configuré sur une plage Min (0.0050$) et Max (1.0000$).

**Action / Démonstration** : Dany Murray positionne le curseur de la souris sur le panneau de configuration des filtres pour ajuster les critères de prix des actions.

---

### ⏱️ `[00:09:12 - 00:09:50]` | Segment #18

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> donc le volume on peut mettre facilement un 250 000 actions minimum donc maximum, pas de maximum appliqué donc là on va avoir on le voit le volume, on le voit pas on va le voir un petit peu plus loin on va régler ça tout de suite les fameuses colonnes, on a plein de colonnes inutiles qui nous servent à rien donc on va cliquer sur le deuxième bouton de la souris et là on va aller faire edit colonne Donc vous allez voir dans le petit menu, je ne sais pas si vous voulez le voir, mais en tout cas on va dans le petit menu, edit colonne.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage Questrade IQ Edge (outil de scanneur/market scanner US Market).

**Contenu textuel & Code** : Tableau de screener affichant les tickers (ETHC.TO, HNRG, CVEO, ALJJ, ZN, SCON, HSDT, TRXX, GPL, INFI, CDEV, CBL, GEVO, RGLS, TAT, TGB, NFINW, GSV, BIOX.WS, SYN), les prix (ex: 0.60, 0.8265), les variations en pourcentage (Chg %) et les filtres de volume configurés à un minimum de 250 000 actions.

**Action / Démonstration** : Le curseur de la souris survole l'en-tête de colonne "Chg %" du tableau de recherche boursière.

---

### ⏱️ `[00:09:50 - 00:10:10]` | Segment #19

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc la description, on s'en fout de la description, je ne veux pas vous autres savoir c'est quoi. On trade des symboles, ça n'a pas d'importance pour moi en tout cas, selon mes méthodes, mes façons de faire. Je ne suis pas en train de me demander, ah c'est quoi cette compagnie là, fait quoi, whatever. On va avoir des petites indications générales, vous allez le voir un peu plus loin, mais ça on élimine ça.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage Questrade IQ Edge (outil de scanneur/market screener "US Market").

**Contenu textuel & Code** : Tableau de filtrage d'actions affichant les colonnes Symbol, Description, Last, Chg %, Chg % 1y, Mkt cap, EPS, EPS growth, P/E, Forward P/E, P/B. Parmi les tickers visibles : HNRG (0,8265 $ ; +22,77 %), CDEV (0,905 $ ; +9,71 %), CBL (0,1851 $ ; +9,66 %), GEVO (0,6078 $ ; +9,02 %), HSDT, TRXC, TAT, ALJJ, CVEO, SCON, INFI, GSV, GPL, RGLS, ETHC.TO, SYN, BIOX.WS, ZN, TGB, NFINW. Plage de prix filtrée entre 0,0050 $ et 1,0000 $, volume minimum 250 000.

**Action / Démonstration** : Le curseur de la souris est immobile au centre du tableau (sur la ligne SCON, colonne Chg %).

---

### ⏱️ `[00:10:10 - 00:10:49]` | Segment #20

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> le dernier c'est d'une évidence qu'on a besoin du prix de la dernière transaction et le pourcentage de gains après ça il n'y a plus grand chose de vraiment important pourcentage en un an c'est pas aucune importance donc vous allez descendre et descendre le petit tableau de petites secondes on va y arriver oui donc on voyait pas le tableau mais ce sont les options qui sont un peu plus haut donc on descend on descend et on enlève tout ce qu'il y a plus ou moins d'importants il ya le volume qui est important donc lui il sera à cocher donc

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Plateforme de courtage Questrade IQ Edge (outil de sélection et de scan de marché "Stock Finder" / "US Market").

**Contenu textuel & Code** : Tableau de筛选 boursier affichant divers tickers américains (HNRG, CDEV, CBL, GEVO, HSDT, TRXC, etc.), avec les colonnes "Last" (prix de la dernière transaction), "Chg %" (variation en pourcentage), "Chg % 1y" (variation sur un an), "Mkt cap", "EPS", "EPS growth", "Forward P/E". Plage de prix configurée de 0.0050 à 1.0000 et volume minimum de 250 000.

**Action / Démonstration** : Dany Murray présente l'interface de scan boursier et pointe du doigt l'importance des colonnes "Last" (dernière transaction) et "Chg %" par rapport à la colonne "Chg % 1y" (variation sur un an) qu'il juge superflue.

---

### ⏱️ `[00:10:49 - 00:11:24]` | Segment #21

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> ça très important ensuite de cela qu'est ce qu'on va enlever les ivs ou à laver bon ok le market cap certains vont trouver ça intéressant moi je m'en sers pas donc j'élimine ça un intercher on s'en fout totalement pour moi ça aussi, ça aussi, ça aussi mais ce qui est important le nombre de share donc le nombre de share est important yield, on s'en fout même si on ne sait pas ce que ça veut dire justement, on l'enlève, on s'en fout on enlève toutes ces colonnes là, on va y arriver, on va y arriver

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Fenêtre de paramétrage de screener boursier (Screener: Edit columns) superposée à une interface de marché US (US MARKET).

**Contenu textuel & Code** : Onglets visibles : Overview, Stock volatility, Option volatility, Open interest, Valuation. Liste de colonnes à cocher sous l'onglet Valuation : Mkt cap, Shares, EPS, EPS growth, P/E, Forward P/E, PEG.

**Action / Démonstration** : Le curseur de la souris survole et décoche les cases des options de valorisation du screener (comme Forward P/E et PEG) pour les retirer de l'affichage.

---

### ⏱️ `[00:11:24 - 00:11:44]` | Segment #22

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> on peut laisser le secteur donc on se ramasse qu'on n'a plus beaucoup de colonnes donc on peut enfin rapetir notre graphique, nos tableaux et tout ça mais vous avez vu quand même que pour s'étoffer ça, deux petites secondes, on va enlever ça. On y est.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading professionnel (type StocksToTrade ou similaire) affichant une interface sombre avec une liste de symboles à gauche et une grille dense de graphiques et de carnets d'ordres imbriqués au centre.

**Contenu textuel & Code** : Liste de tickers visible à gauche : HNRG, CDEV, CBL, GEVO, HSDT, TRXC, TAT, ALI, CVEO, SCON, INFI, GSV, GPL, RGLS, ETHC.TO, SYN, BIOX.WS, ZN, TGB, NFINW. Au centre, multiples fenêtres de graphiques en chandeliers et tableaux de cotations/ordres colorés (vert, jaune, rouge).

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné sur le côté droit de la zone de travail noire, l'interface montrant une multitude de fenêtres de graphiques réduites et empilées que le trader manipule ou s'apprête à réagencer.

---

### ⏱️ `[00:11:44 - 00:12:08]` | Segment #23

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> On y est. On va y aller. Donc, déjà là, on a les pourcentages de changement. On peut cliquer, double-cliquer dessus. Vous allez voir que ça donne à la hausse ou à la baisse. Vous pouvez y aller par volume. On double-clique dessus. Ça va trier par colonne, par volume et tout ça. Autre chose importante, le nombre qui vont vous indiquer les top gainers.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Plateforme de trading ou screener boursier (interface sombre USMARKET), affichant des filtres de recherche en haut et un tableau de cotations boursières au centre.

**Contenu textuel & Code** : Tableau de filtrage d'actions américaines/canadiennes avec les colonnes Symbol, Last, Chg %, Vol, Shares, Sector. Tickers visibles : ETHC.TO (0,60$, +29,03%, 443,26K), HNRG (0,8265$, +22,77%, 1,15M), CVEO, ALJJ, ZN, SCON, HSDT, TRXC, GPL, INFI, CDEV, CBL, GEVO, RGLS, TAT, TGB, NFINW, GSV, BIOX.WS, SYN. Filtres de prix configurés entre 0,0050$ et 1,0000$ et de volume minimum à 250000.

**Action / Démonstration** : Le curseur de la souris (pointeur) est positionné sur l'en-tête de la colonne "Chg %" pour illustrer le tri des valeurs par pourcentage de changement.

---

### ⏱️ `[00:12:09 - 00:12:31]` | Segment #24

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Ils nous mettent 20 de base, mais il faut en mettre beaucoup plus que ça. Parce que justement, éventuellement, on va trier par volume. Et vous allez voir ce que ça va donner. Donc, vous pouvez y aller par exemple à 100. 100 ou 200, peut-être que ça va surcharger un peu plus le logiciel, mais on va y aller avec 100 pour commencer. Donc là, on a une grande liste de stocks.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage / plateforme de scan de marché boursier (fenêtre USMARKET) avec des filtres de recherche configurables et un tableau de résultats.

**Contenu textuel & Code** : Tableau de screening affichant des tickers boursiers (ZIN, CDEV, CBL, GEVO, etc.), leurs prix (Last), pourcentages de variation (Chg %), volumes (Vol), nombres d'actions et secteurs. Paramètre "Show" réglé sur 20 en haut à droite.

**Action / Démonstration** : Le curseur de la souris est positionné dans l'interface près du champ de configuration du nombre de résultats affichés ("Show 20"), illustrant la modification future de ce paramètre.

---

### ⏱️ `[00:12:31 - 00:13:09]` | Segment #25

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Mais là, évidemment, moi j'ai mis ça très très court. Donc, c'est jusqu'à 1$, si on mettrait par exemple jusqu'à 10$, on en aurait beaucoup plus, 10 voilà, j'ai mis 10 millions je pense en tout cas, sont tous là donc là, c'est tous les top gains du jour et il y en a beaucoup, beaucoup d'opportunités et tout ça, lequel choisir là-dedans habituellement, on va aller voir ceux qui ont encore le plus de volume donc les plus gros volumes fut aujourd'hui ATHE, avec 154% de hausse et SRNE

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage / plateforme de screening boursier (US Market Scanner) avec interface en mode sombre.

**Contenu textuel & Code** : Tableau de筛选 (scanner) affichant la liste des "top gains" (hausses du jour) avec les colonnes : Symbol, Last (prix), Chg % (variation), Vol, Shares et Sector. Exemples de tickers visibles : ZVO (6.09$, +20.36%), KOSS (2.33$, +20.10%), BXC, IMAC, OSS, OCX, ZCMD, STRL, PTI, TUSK, CLIR, ASM, TLRY, DBD, ALLJ, PSNL, CLSN, WIMI, JOB, ZSAN, MTSC, TCON, GAIA, GPOR, MXC, TOUR, SYKE, WOW, EXPI, AGQ, ALVR. En haut, les filtres de prix affichent des bornes configurées (Price de 0.0050$ à 100000.0000$ et Volume minimum 250000).

**Action / Démonstration** : Dany Murray présente un tableau de scan des plus fortes hausses du marché boursier américain, en illustrant les critères de filtrage configurés (prix et volumes).

---

### ⏱️ `[00:13:09 - 00:13:38]` | Segment #26

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> à 12,84 sûrement très low float donc 200 millions de shares 172 millions de shares tradés donc c'était beaucoup beaucoup donc on sait habituellement que les actions qui ont un vrai mouvement un vrai mouvement intéressant c'est ceux qui ont des gros volumes parce que même si on aurait on va aller voir un peu plus bas un 20% sur 300 000 actions ça ne veut pas dire grand chose.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Plateforme de market screening (US MARKET) avec filtres configurés par volume et variation en pourcentage (Chg %).

**Contenu textuel & Code** : Tableau de scanners d'actions affichant en tête de liste le ticker SRNE (Last: 12,84, Chg %: +31,42 %, Vol: 172,11M, Shares: 202,12M, Sector: Health care), suivi d'autres tickers (ATHE, SINT, SSNT, WLL, etc.) avec leurs prix, variations, volumes et capitalisations respectifs.

**Action / Démonstration** : Le curseur de la souris (pointeur fléché) est positionné au milieu de l'écran, au niveau de la ligne du ticker ATHE, servant de repère visuel pendant l'analyse.

---

### ⏱️ `[00:13:39 - 00:14:04]` | Segment #27

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Même si ça serait sur 500 000 ou 600 000, ça prend des millions, plusieurs millions. Et là, quand on arrive bizarrement en haut, on a plusieurs millions et on a des grosses hausses qui me semblent fair, qui ont l'air à des vraies hausses. Donc, c'est la partie qui est importante, les gros volumes et le pourcentage de changement.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading type screener de marché (US Market Scanner), affichant un tableau de données boursières avec des filtres avancés (prix, volume, bourses US).

**Contenu textuel & Code** : Tableau de screener affichant des tickers US (SRNE à 12.84 $ / +31.42 %, ATHE, SINT, SSNT, WLL, MVIS, WIMI, TLRY, ZCMD, etc.), colonnes "Last", "Chg %", "Vol" (en millions), "Shares" et "Sector" (Health care, Technology, Energy, etc.).

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné sur la ligne du ticker TLRY à 8.70 $ (+17.09 %).

---

### ⏱️ `[00:14:04 - 00:14:53]` | Segment #28

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> donc à partir de là vous avez votre filtre et vos top gains du jour pour tout ça qu'est ce que je vous dirais là dedans habituellement moi quand je trade je vais rajouter un autre filtre parce que je ne veux pas voir vraiment ce qu'il y a en dessous vous allez voir ici qu'on va aller voir price ok puis on va remettre price change je ne veux pas avoir de changement en bas de 5% et maximum par exemple 1000% parce que 1000% souvent c'est des fakes ou peu importe donc entre 5% et 1000% donc là je l'ai fait de pas correct ça a l'air d'avoir tout enlevé

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de scan de marché boursier (Screener) avec des filtres avancés en haut et un tableau de résultats détaillé en bas.

**Contenu textuel & Code** : Tableau des actions classées par variation (Chg %) avec les tickers (SRNE, ATHE, SINT, etc.), les prix actuels (ex : SRNE à 12.84), les pourcentages de variation (ex : +31.42%, +154.07%), les volumes et les secteurs d'activité (Health care, Technology, Energy). En haut, le panneau de configuration affiche des critères de filtrage basés sur le prix, le volume et la plage de valeurs.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné sur les options de configuration des filtres du screener dans la partie supérieure de l'écran.

---

### ⏱️ `[00:14:53 - 00:15:31]` | Segment #29

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> vous voyez que ici moi habituellement je rajoute un pourcentage c'est price change pourcentage pour ça que ça marche pas donc 1000% apply bon nous revoilà donc je n'ai pas de hausse en haut ou en bas de 5% donc c'est ça élimine encore une fois des stocks que je ne veux pas voir parce que moi ma

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de scan de marché boursier (US Market) avec panneaux de filtres avancés et tableau de résultats tabulaire.

**Contenu textuel & Code** : Filtres actifs : Last price (0.0050 à 100000.0000), Volume (25000 à Max), Price change % (réglé à 5.0000). Tableau affichant des tickers US (IRTC, CRNC, AGQ, SEDG, AMD, etc.) avec colonnes Last, Chg %, Vol, Shares et Sector.

**Action / Démonstration** : Le curseur de la souris est positionné au centre du tableau de résultats pour illustrer le tri des actions selon les filtres de variation de prix.

---

### ⏱️ `[00:15:31 - 00:16:06]` | Segment #30

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> méthode c'est quoi ça fait partie de je tuer des actions qui bougent beaucoup à la hausse je ne suis pas en train d'essayer de trouver le fond sur une action qui a crash et tout ça c'est pas ma méthode ma méthode on s'en va dans des gros gains et les gros gains donnent d'autres gros gains et donne des hausses éventuelle dans le compte. Donc c'est un peu le principe de la chose. Donc ça c'est tout mon setup que j'ai pour les top gainers. Et là l'avantage justement avec notre tableau des top gainers qui

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading ou plateforme de courtage (interface de screener de marché de type tableur boursier avec filtres supérieurs).

**Contenu textuel & Code** : Tableau de listes d'actions américaines triées par variation en pourcentage ("Chg %") avec les tickers suivants visibles : ATHE (3.43 $, +154.07%), SSNT (5.40 $, +98.53%), SINT (3.26 $, +53.05%), WLL, UUU, AGE, IRTC, SRNE, TCCO, OSN, ETHC.TO, VRAY (3.23 $, +27.67%), MVIS, DAC, PRPO, PPSI, HLIT, HNRG, FUV, CVEO, CRNC, ALRN, ICON, ZVO, KOSS, BXC, IMAC, OSS, OCX, ZCMD, avec colonnes Last, Chg %, Vol, Shares, et Secteur.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné sur la ligne du ticker VRAY.

---

### ⏱️ `[00:16:06 - 00:16:38]` | Segment #31

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> est rafraîchée à peu près à tous les cinq minutes, c'est la petite option ici. Donc on a l'option refresh de information. Donc on rafraîchit l'information et dès qu'on pèse on a les vrais chiffre. Donc éventuellement, on finit par savoir que, gars, il y a ces trois actions-là qui sont autour du 27%, puis là, on fait refresh, puis il y en a une qui est rendue à 29%, on va aller cliquer dessus, et on va la regarder parce que c'est probablement la prochaine. Mais vous allez le voir, vous allez comprendre ça éventuellement.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Scanner de marché boursier (interface de type USMARKET) avec des filtres supérieurs (bourses NYSE, NASDAQ, etc.), des champs de critères numériques et un tableau de classement par pourcentage de variation.

**Contenu textuel & Code** : Tableau affichant des tickers d'actions américaines triés par variation en pourcentage (Chg %) avec leurs prix (Last), volumes (Vol), parts et secteurs : ATHE (3.43 $, +154.07%), SSNT (5.40 $, +98.53%), SINT (3.26 $, +53.05%), WLL, UUU, AGE, IRTC, SRNE, TCCO, OSN, ETHC.TO, VRAY, MVIS, DAC, PRPO, PPSI, HLIT, HNRG, FUV, CVEO, CRNC, ALRN, ICON, ZVO, KOSS, BXC, IMAC, OSS, OCX, ZCMD.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné sur la ligne de l'action WLL (1.08 $, +40.76%).

---

### ⏱️ `[00:16:39 - 00:17:17]` | Segment #32

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Souvent aussi, vous allez vous remarquer que ça va aller par secteur. Certains m'ont demandé, ah, tu n'as pas de formation pour les OTC et tout ça. J'ai une très bonne formation pour les OTC qui est celle du cannabis. La formation, c'est sur mon site internet de numerytrader.com pour ceux qui voudront aller voir. La formation sur le cannabis est basée premièrement sur les OTC et basée d'une deuxième façon sur le secteur cannabis. Mais le secteur cannabis pourrait être le secteur de la santé, des technologies ou des industries ou d'énergie

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de screening de marché boursier avec un thème sombre, comportant un panneau de filtres en haut et un tableau de données classées par pourcentage de variation (Chg %). Les places boursières cochées incluent NYSE, NASDAQ, NYSEAM, ARCA, PINK/OTCBB, TSX, TSKV, CNSX, NEO, BATS.

**Contenu textuel & Code** : Tableau de scanner affichant une liste de tickers boursiers avec leurs colonnes respectives (Symbol, Last, Chg %, Vol, Shares, Sector). Exemples de tickers visibles : ATHE (Last: 3.43, +154.07%, Vol: 110.12M, Secteur: Health care), SSNT (5.40, +98.53%), SINT (3.26, +53.05%), WLL (1.08, +40.26%), SRNE, MVIS, HNRG.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné au centre du tableau, pointant sur la ligne du ticker WLL (Energy).

---

### ⏱️ `[00:17:17 - 00:17:49]` | Segment #33

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> ou peu importe, ça peut être n'importe quel secteur. Donc cette formation-là est aussi bonne pour tous les secteurs que vous allez voir et je la recommande encore une fois pour ceux qui débutent parce que moi c'était une de mes formations que j'ai commencé quand moi je redébutais une deuxième fois, quand j'ai redébuté dans les OTC, quand j'ai re-recommensé à trader beaucoup d'OTC et tout ça et tout est basé sur les OTC, donc vous pouvez reproduire ça dans plusieurs secteurs et surtout que ces temps-ci, on a eu un crash massif de la bourse.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de scan de marché boursier (Screener) avec filtres avancés (prix, volume, variation) et tableau de classement des actions américaines par secteur.

**Contenu textuel & Code** : Tableau listant divers tickers (ATHE, SSNT, SINT, WLL, UUU, AGE, IRTC, SRNE, etc.) avec leurs colonnes respectives : "Last" (prix), "Chg %" (variation en pourcentage de +154.07% à +18.75%), "Vol", "Shares" et "Sector" (Health care, Technology, Energy, Industrials, Materials).

**Action / Démonstration** : Le curseur de la souris pointe vers la ligne du ticker SINT (prix 3.26, +53.05%, secteur Health care).

---

### ⏱️ `[00:17:49 - 00:18:12]` | Segment #34

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Certaines choses ne sont pas remontées encore, donc ça sera à voir, mais si on est déjà installé par secteur, ça peut être très bon. Donc, on va devoir la deuxième petite option. Deuxième option, l'option pour ceux qui ont moins de capital et qui ont besoin d'avoir les OTC. Donc, on va s'en faire un OTC Market.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage / scanner de marché actions (interface sombre type TradeZero, Sterling Trader Pro ou plateforme similaire) affichant un tableau de screener boursier avec filtres supérieurs.

**Contenu textuel & Code** : Tableau de cotations (tickers, derniers prix, variations en %, volumes, actions en circulation et secteurs) : ATHE (3.43 $ / +154.07% / Health care), SSNT (5.40 $ / +98.53% / Technology), SINT (3.26 $ / +53.05%), WLL (1.08 $ / +40.26%), UUU, AGE, IRTC, SRNE, TCCO, OSN, ETHC.TO, VRAY, MVIS, DAC, PRPO, PPSI, HLIT, HNRG, FUV, CVEO, CRNC, ALRN, ICON, ZVO, KOSS, BXC, IMAC, OSS, OCX, ZCMD. Filtres actifs : marchés (NYSE, NASDAQ, etc.), plage de prix (8.00 à 100000.00), volume (25000 min) et variation de prix (5.00 min).

**Action / Démonstration** : Le curseur de la souris survole le bouton "+" situé en haut à gauche de l'onglet "USMARKET".

---

### ⏱️ `[00:18:13 - 00:18:33]` | Segment #35

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> On va le marquer comme ça tout de suite et voilà. OTC Market. On revient un peu à l'accord avec le même tableau. On n'a plus rien de fait. Donc, on revient ici. On remet le pourcentage de gain. On ne cochera pas tout le marché US, ni le marché canadien.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de screening boursier de type tableur (plateforme de courtage ou screener de marché), affichant des onglets de sélection "US MARKET" et "OTCMARKET", ainsi que des filtres par marchés (NYSE, NASDAQ, NYSEAM, ARCA, PINK/OTCBB, TSX, TSXV, CNSX, NEO, BATS).

**Contenu textuel & Code** : Tableau de données financières contenant des tickers (ZEUS, YORW, WIRE, VEC, USPH, UNL, UNF, UFCS, THFF, TBNK, SAFT, REXR, QADA, PTVCB, OCSJ, MTD, MGIC, LIN, IOSP, IIIN), des descriptions d'entreprises, des prix de dernière transaction ("Last"), des variations en pourcentage ("Chg %", "Chg % 1y"), des capitalisations boursières ("Mkt cap"), des ratios EPS, P/E et Forward P/E.

**Action / Démonstration** : Le curseur de la souris survole le menu déroulant du classement ("Rank by: Ask") dans la barre de filtres supérieure.

---

### ⏱️ `[00:18:34 - 00:19:10]` | Segment #36

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> On va cocher seulement Pink et OTC. Donc, ça ne sera pas côté options. Ça va être tous les stocks. ici ça va être le market que j'ai indiqué donc pas trop de problèmes de ce côté là et là on va voir qu'est ce que ça donne pour les OTC on voit une belle grande ligne de scrap comme on les aime donc on continue d'avancer notre setup mais avant toute chose j'aimerais quand même vous

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage / plateforme de screening boursier (Interface de type TradeZero ou scanner de marché), affichant un tableau de filtrage de données financières sous forme de liste.

**Contenu textuel & Code** : Tableau de screener affichant les colonnes Symbol, Description, Last, Chg %, Chg % 1yr, Mkt cap, EPS, EPS growth, P/E, Forward P/E, PEG. Tickers visibles : ZEUS, YORW, WIRE, VEC, USPH, UNL, UNF, UFCS, THFF, TBNK, SAFT, REXR, QADA, PTVCB, OCSI, MTD, MGIC, IIN, IOSP, LN. Prix affichés (Last) de 6.42 à 928.59. Filtres activés : "Stocks", "All markets", et cases des bourses (NYSE, NASDAQ, NYSEAM, ARCA, PINK/OTCBB, TSX, TSXV, CNSX, NEO, BATS).

**Action / Démonstration** : Dany Murray configure les filtres du screener de marché en sélectionnant les options de stocks et les segments de marché boursier correspondants.

---

### ⏱️ `[00:19:10 - 00:19:30]` | Segment #37

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Vous invitez cordialement sur le chatroom qui est gratuit comme d'habitude. Pour venir trader avec nous les guerriers traders. Plus de 200 guerriers traders en permanence en train de trader avec vous. Ou d'apprendre ou peu importe. Mais on est plus de 200 sur le chatroom. Un vrai succès.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Scanner de marché boursier avec onglets USMARKET et OTCMARKET, configuré sur l'onglet des actions de gré à gré (OTCMARKET).

**Contenu textuel & Code** : Tableau de cotation de penny stocks (WHEN, WDHR, VGID, TSNP, SPRV, SPQS, SANP, OPMZ, etc.) affichant des prix à 0.0001, des variations Chg % à +9,900.00%, et des capitalisations boursières (Mkt cap) très faibles (ex: 89.79K, 4.67K).

**Action / Démonstration** : Affichage fixe du screener montrant une liste de micro-capitalisations de type penny stocks sans manipulation active de curseur.

---

### ⏱️ `[00:19:31 - 00:20:08]` | Segment #38

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Les gens sont vraiment super gentils. On est là pour travailler. Mais autant pour avoir du fun. Répondre aux questions des nouveaux. faire un petit peu de tout donc n'oubliez pas sur twitch tv donc twi tch point tv donc aller dans la description tout est là dans la description de cette vidéo et vous pouvez vous abonner gratuitement comme ça vous abonner à n'importe quel autre site ça coûte rien et tu t'abonnes à moi Danny Murray Trader sur twitch et tu viendras nous rejoindre tu pourras jaser sur le chatroom voir mon écran live avec tous mes transactions

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de screening de marché boursier (tableaux de cotations de type scanner/screener OTC Markets).

**Contenu textuel & Code** : Liste de tickers d'actions (WHEN, WDHR, VGID, TSNP, SPRV, SPQS, SANP, OPMZ, INOH, HYII, GRLT, FTWS, ESPHQ, ELCR, EESO, ECOS, CNXS, BNGI, BEHL, AZFL) affichant tous un prix de dernier échange (Last) à 0.0001 avec des variations (Chg %) affichées à 9,900.00% et diverses capitalisations boursières (Mkt cap).

**Action / Démonstration** : Affichage fixe d'un tableau de tri des actions du marché OTC (OTCMARKET) classées par pourcentage de variation.

---

### ⏱️ `[00:20:08 - 00:20:44]` | Segment #39

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> que je fais, où j'en suis pour la journée et tout ça donc ne manquez pas ça parce que c'est un bel endroit pour apprendre et habituellement tout le monde va vous charger assez cher pour être sur les chat rooms et moi je ne charge absolument rien, pourquoi encore une fois pour pouvoir démontrer aux gens et ne pas avoir de haters qui vont dire que ah Danny c'est un fake ou peu importe toutes mes transactions sont le live personne ne peut rien cacher en continuant dans la set à pas dans notre screener bienvenue vous sur twitch.tv

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading Questrade IQ Edge affichant un scanner de marché centré sur les actions OTC (OTCMARKET).

**Contenu textuel & Code** : Tableau de cotations (tickers : WHEN, WDHR, VGID, TSNP, etc.) avec des prix à 0.0001, des variations affichées à +9,900.00 %, ainsi que des colonnes Mkt cap, EPS et Forward P/E.

**Action / Démonstration** : Affichage fixe d'un screener listant des penny stocks ultra-spéculatifs à très faible capitalisation sur les marchés de gré à gré.

---

### ⏱️ `[00:20:44 - 00:21:11]` | Segment #40

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> excusez moi si j'ai dit .com avant mais c'est .tv donc là on a tous les marchés encore une fois on en a pas assez donc on va aller ici, on va en mettre par exemple 200 pourquoi pas 200, applique donc 200, on a beaucoup de merde à éliminer donc comment éliminer cette merde là donc c'est en allant dans les filtres Donc, on va ajouter un stock filter.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de screening de marché boursier avec onglets US MARKET et OTCMARKET, filtres avancés (sélection des bourses NYSE, NASDAQ, etc.) et menu déroulant pour le nombre de résultats.

**Contenu textuel & Code** : Tableau vide de screener avec les en-têtes : Symbol, Description, Last, Chg %, Chg % 1y, Mkt cap, EPS, EPS growth, P/E, Forward P/E. Paramètre de résultats configuré à 200 (Show: 200).

**Action / Démonstration** : Le curseur de la souris est positionné dans le coin supérieur droit au niveau du bouton d'application des paramètres (Apply).

---

### ⏱️ `[00:21:12 - 00:21:32]` | Segment #41

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Donc, ça va être un stock filter de prix. Le dernier prix que je vais vouloir. Donc, le dernier prix sur les OTC. OK. Sur les OTC, on va aller à 0.0005. OK. 3-0. Mais, il n'est pas à 0.0001. Là, vous allez perdre votre temps.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de market screener / plateforme de courtage affichant un tableau de filtrage d'actions (onglets "USMARKET" et "OTCMARKET", options de filtres par prix et marchés).

**Contenu textuel & Code** : Tableau de listes d'actions OTC (Pink/OTCBB) avec les colonnes Symbol, Description, Last (prix à 0.0001 pour la plupart), Chg % (variations extrêmes affichées à 9,900.00%), Mkt cap, EPS, etc. Le panneau de filtre supérieur montre "Stock", "Last price", et les champs de plage "Min" et "Max".

**Action / Démonstration** : Le curseur de la souris est positionné au niveau des paramètres de filtrage de prix pour configurer les seuils de recherche sur les actions OTC.

---

### ⏱️ `[00:21:33 - 00:22:09]` | Segment #42

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Et c'est comme si achetez un billet de luto. Si vous achetez à 1, vous pouvez vendre à 0. donc le donner, donc si vous achetez pour 100$ ou 500$ vous savez que si vous l'achetez à 1 millième de sous c'est de l'argent mis dans le feu donc on commence à 5 gros minimum, ça c'est pour les OTC mais on peut aller par exemple jusqu'à 10$ dans cette partie là, on va appliquer, on va voir de quoi ça a l'air bon on vient d'éliminer tous les 10 000% ici, il ne faut pas oublier les colonnes, donc on va retourner aussi dans les colonnes après donc on va faire stock filter

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de screening de marché boursier (probablement Questrade IQ Edge), onglets "USMARKET" et "OTCMARKET", avec filtres de recherche par type d'actions (Stocks/Options), unité de temps 1D, et filtres de prix configurés (plage de 0.0005 max).

**Contenu textuel & Code** : Tableau de listes d'actions OTC (penny stocks) affichant les colonnes Symbol, Description, Last, Chg %, Chg % 1y, Mkt cap, EPS, EPS growth, P/E, Forward P/E. Tous les premiers tickers affichent un prix ("Last") de 0.0001 avec des variations aberrantes ("Chg %") à +9,900.00% (ex: WHEN, WDHR, VGID, TSNP, SPQV, SPQS, SANP, OPMZ, INOH, HYII, GRLT, FTWS, ESPHQ, ELOR, EESO, ECOS, CNXS, BNGI, BEHL, AZFL, APTY).

**Action / Démonstration** : Dany Murray présente et illustre l'écran de sélection des actions à un dixième de centime (0.0001) sur le marché OTC, illustrant le concept de "billet de loterie" mentionné dans l'audio.

---

### ⏱️ `[00:22:09 - 00:22:44]` | Segment #43

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> deuxième stock de prix et ça va être le price change donc c'est quoi mon price change en pourcentage que je veux avoir je veux avoir un minimum minimum de peut-être 10% donc 10% on va appliquer là on vient d'enlever tout ce qu'il y a en bas en bas et qui est trop petit de toute façon on les voyait probablement même pas et ensuite de ça on va ajouter un filtre de volume

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage Questrade IQ Edge (onglet OTCMARKET sélectionné), avec un panneau de filtres (stock screener) et un tableau de données tabulaire sur fond noir.

**Contenu textuel & Code** : Tableau de screener affichant des tickers OTC (PGNE, BMWLF, TIDE, SVMMF, PSIQ, etc.), colonnes "Last" (prix), "Chg %", "Chg % 1yr", "Mkt cap", "EPS", "EPS growth", "P/E", "Forward P/E". Dans les filtres de plage supérieure : "Price change %" configuré avec un champ de saisie actif (en cours de modification), et bouton vert "Apply" visible en haut à droite des filtres.

**Action / Démonstration** : Dany Murray configure et applique un filtre sur le pourcentage de variation de prix ("Price change %") dans le screener pour filtrer et afficher les actions selon un seuil minimal de performance.

---

### ⏱️ `[00:22:44 - 00:23:21]` | Segment #44

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> donc le volume qui est là on va faire un volume minimum donc volume minimum de pour moi les OTC c'est clairement 500 000 puis même encore là donc peut-être le matin à l'ouverture c'est un petit peu différent mais on y va à 500 000 on ne se pose pas de questions on ne veut pas avoir de vidange et tout ça, donc on est fait pour les filtres après ça, là c'est encore un peu bordélique donc on va aller faire enlever ces petites

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage (interface de type scanner boursier / screener) avec onglets "USMARKET" et "OTCMARKET".

**Contenu textuel & Code** : Tableau de filtrage des actions OTC affichant les colonnes Symbol, Description, Last, Chg %, Chg % 1yr, Mkt cap, EPS, EPS growth, P/E, Forward P/E. Paramètres de filtrage actifs en haut avec un champ de volume configuré à "500000" et le bouton vert "Apply". Tickers visibles : WSHE, UPLCQ, MCCHF, SOACF, SHRG, etc.

**Action / Démonstration** : Le curseur de la souris survole et clique sur le bouton vert "Apply" pour appliquer le filtre de volume minimum de 500 000 sur le marché OTC.

---

### ⏱️ `[00:23:21 - 00:23:58]` | Segment #45

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> colonnes là deux petites secondes, donc ça ici vous cliquez sur le deuxième bouton de la souris sur la colonne et vous allez faire edit colonne donc je vous mets ça à l'instant on résume tout cela donc la description, on s'en fout on a besoin de symboles, on recommence la même chose que tantôt, donc le dernier est important, le pourcentage de changement, au delà de ça pourcentage de changement dans l'année on s'en fout, on est là pour 5 minutes ça a besoin de bouger aujourd'hui, ensuite de ça on va enlever toutes les market caps

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Plateforme de trading de type scanner de marché (onglets "US MARKET", "OTCMARKET"), affichant une fenêtre modale de configuration des colonnes par-dessus un tableau de données boursières.

**Contenu textuel & Code** : Fenêtre de sélection des colonnes affichant une liste de paramètres ("Symbol", "Description", "Exch", "Venues", "Security type", "Currency", "Ask") avec des cases à cocher, ainsi que des boutons de gestion ("Move up", "Move down", "Show", "Hide", "Restore defaults", "OK", "Cancel"). En arrière-plan, tickers visibles : STRH, EVUS, XTRM, GLKIF, CCTL, PGAS, ECPLA, EXCLA, SRUTF, MLFB, VMNT, IALS, BWXMF, VSYM, SWHI, BLGI, MEEC, TXSO, SMME, UPLCQ, SHRG, MLB, GMER, WTII, UNDR, CNNA, VMSI, OPTI, GBBFF.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné sur la case à cocher de l'option "Description" dans la fenêtre de configuration des colonnes.

---

### ⏱️ `[00:23:58 - 00:24:22]` | Segment #46

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> comme je vous dis, il y en a certains qui vont aimer le market cap mais j'ai besoin du nombre de shares donc on va mettre share learning per share, ça c'est pas intéressant pas pour moi en tout cas donc on enlève tout le reste s'il n'y avait pas grand chose qui nous intéressait à part de ça. Il y en a qui nous parlent de volume relatif par rapport à la journée.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de trading ou plateforme de courtage (type Questrade IQ Edge) affichant un scanner de marché de type "US Market / OTC Market" avec une fenêtre pop-up de configuration des colonnes de valorisation.

**Contenu textuel & Code** : Fenêtre de sélection des colonnes "Valuation" affichant des critères fondamentaux tels que "EPS growth", "P/E", "Forward P/E", "PEG", "Div", "Yield", "Ex-date". En arrière-plan, liste de tickers boursiers (STRH, EVUS, XTRM, GLKIF, CNNA, VMSI, OPTI, GBBFF) avec cours, variations en pourcentage et volumes.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné sur la case à cocher "Yield" de la liste des colonnes de valorisation dans la fenêtre contextuelle.

---

### ⏱️ `[00:24:23 - 00:25:02]` | Segment #47

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Oui, c'est une option qui sera envisageable éventuellement, mais pour l'instant, on laisse ça à la base et simple. Donc, OK, on a tout ce qu'il faut. Donc, ça c'est le float, le nombre de shares, donc le nombre de floats d'actions qu'il y a sur le marché. on a besoin du pourcentage du dernier et ensuite de ça les symboles donc là à partir de là on a tout ce qu'il faut et il nous manque par exemple le volume donc on va retourner, attendez une petite seconde pour que ça prenne deux jours je vais vous éviter ça on va juste rajouter le volume. Donc nous voilà avec le volume

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de courtage / plateforme de trading de type scanner de marché boursier avec listes de watchlists à gauche et affichage multifenêtré de graphiques et carnets d'ordres au centre.

**Contenu textuel & Code** : Watchlist à gauche affichant des tickers OTC/US (STRH, EVUS, WTII, UNDR, CNNA, VMS1, OPTI, GBBFF, ENKS) avec des prix fractionnaires, des variations en pourcentage (+33,33%) et des volumes en millions ou milliards (17.54M, 479.40M, 8.98B). Au centre, une grille dense de graphiques en chandeliers et de carnets d'ordres (Level 2).

**Action / Démonstration** : Le curseur de la souris est positionné au centre de l'écran sur la ligne du ticker WTII, pointant les données chiffrées du tableau.

---

### ⏱️ `[00:25:02 - 00:25:27]` | Segment #48

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> c'est pas vraiment plus compliqué que ça comment trouver les bons stocks on est Et là, on a le screener, on a le stock des OTC, les marchés US. Vous pouvez faire aussi le marché canadien. Vous allez changer les options ici que vous allez cocher. Vous allez mettre les options canadiennes, TSX, etc. Donc, tout est là. Vous voyez aujourd'hui sur les OTC, c'était les gros mouvements qu'il y a eu.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de screener boursier (style Questrade) avec des onglets "USMARKET" et "OTCMARKET" et divers filtres de marché.

**Contenu textuel & Code** : Tableau de筛选 (screener) affichant des tickers OTC américains (STRH à 0.003 avec +172.73%, EVUS à 0.0016 avec +166.67%, XTRM, GLKIF, CCTL, etc.) avec colonnes Symbol, Last, Chg %, Vol et Shares.

**Action / Démonstration** : Le curseur de la souris survole la case de sélection "PINK/OTCM" pour filtrer les actions de gré à gré.

---

### ⏱️ `[00:25:29 - 00:26:04]` | Segment #49

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Après ça, on va analyser les volumes. 823 000, ce n'est pas beaucoup. Mais ici, on regarde 105 millions, 158 millions. ça a déjà plus d'allure mais il y a toujours une corrélation aussi oubliez pas entre la valeur de l'action parce que là on a beaucoup de zéros donc quand on arrive à 0.0008 c'est certain que moi tout seul 2.600.000 c'est je crois 2600$ donc c'est pas un volume significatif pour une action de ce prix là mais 158 millions

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage Questrade IQ Edge (tableau de screener de marché US/OTC).

**Contenu textuel & Code** : Tableau de listes d'actions avec filtres avancés en haut (prix, volume, variations). Colonnes visibles : Symbol, Last, Chg %, Vol, Shares. Tickers listés avec leurs données (ex: STRH à 0.003 avec un volume de 823.64K, EVUS à 0.0016 avec un volume de 105.26M, XTRM à 0.0317 avec un volume de 158.57M).

**Action / Démonstration** : Le curseur de la souris survole la ligne du ticker XTRM dans le tableau.

---

### ⏱️ `[00:26:04 - 00:26:40]` | Segment #50

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> sur une action à 3 sous déjà là c'est plus intéressant, donc souvent on va aller éliminer le reste par les volumes donc qu'est-ce qui reste dans les OTC aujourd'hui à trader qu'il y a des volumes intéressants vous regardez tout ça, peut-être jusqu'à 40 millions vous enlevez le 8 ici donc là on pourrait peut-être même changer ça à 5 qu'on aille à appliquer, ça va éviter de mettre plein de merde donc là c'est ce qui se tradait aujourd'hui c'est dans ces sections

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Scanner de marché boursier avec onglets USMARKET et OTCMARKET, filtres de recherche avancés par prix, variation en pourcentage et volume, et tableau de tri des actions.

**Contenu textuel & Code** : Tableau listant des actions OTC avec colonnes Symbol, Last, Chg %, Vol et Shares. Exemples de tickers visibles : CCTL (0.0007, +75.00%, 661.73M), BBRW (0.0046, +13.58%, 255.39M), XTRM (0.0317, +131.39%), et CBDL (0.0008, +14.29%). Filtre de prix configuré entre 0.0000 et 10.0000 et volume minimal à 500000.

**Action / Démonstration** : Le curseur de la souris survole la ligne du ticker CBDL (0.0008) dans le tableau de sélection des valeurs.

---

### ⏱️ `[00:26:40 - 00:27:10]` | Segment #51

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> là que c'était intéressant sur les OTC ça ne va pas plus loin que ça des volumes, il y en a un peu partout mais quand les décimales sont trop loin, ça ne vaut pas cher la tonne, donc CVSI toujours un classique et tout ça mais tout ça pour dire que les gros mouvements vont se passer dans les gros volumes et les gros volumes vont confirmer que le gros mouvement semble officiel ou semble qu'il y en aurait peut-être éventuellement d'autres.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de scan de marché actions/OTC avec onglets "USMARKET" et "OTCMARKET" (sélectionné), filtres de recherche avancés et tableau de cotation.

**Contenu textuel & Code** : Tableau de screener affichant les colonnes Symbol, Last, Chg %, Vol et Shares pour des actions OTC (ex: UPLCQ à 0.0282 (+41.00%), SHRG, MILB, GMER, OPTI avec un volume de 190.74M). Plage de prix filtrée de 0.0010 à 10.0000 et volume minimum de 500000.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné sur la ligne du ticker PRVCF (0.0575, +24.73%, 3.76M Vol).

---

### ⏱️ `[00:27:10 - 00:27:35]` | Segment #52

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> Peut-être que ça va juste redescendre à partir de là, personne ne sait. Mais c'est l'endroit pour savoir justement toutes ces choses-là, à savoir où trouver les stocks, où trouver les OTC. Les gens qui ont plus de sous, qui sont commencés à être habitués, je vous conseille les actions en bas de 1$. Et les gens qui vont avoir un très petit capital, je vous recommande fortement d'aller trader que des OTC.

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de screening de marché boursier (mode sombre) avec onglets "USMARKET" et "OTCMARKET", comportant des filtres avancés par prix, variation et volume.

**Contenu textuel & Code** : Tableau de cotation affichant des tickers de penny stocks et valeurs OTC (STRH à 0.003$ / +172.73%, EVUS, XTRM, PGAS, ECPLA, EXLA, SRUTF, MLFB, VMNT, IALS, BWXMF à 1.70$ / +54.55%, VSYM, BLGI, MEEC, TXSO, SMME, UPLCQ, SHRG, MULB, GMER, WTII, CNNA, VMSI, OPTI, GBBFF, ENKS, DSGT, SNDO, SRCO, SFIO) avec leurs prix de dernière transaction (Last), pourcentages de variation (Chg %), volumes (Vol) et nombre d'actions (Shares).

**Action / Démonstration** : Le curseur de la souris (pointeur blanc) est positionné sur la ligne du ticker MULB (0.0025$) au milieu du tableau de screening.

---

### ⏱️ `[00:27:35 - 00:28:15]` | Segment #53

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> c'est très long mais on va en reparler dans une prochaine vidéo je vous faire une petite série de comment trader les OTC pour vous aider vous enlignez parce que malheureusement je ne suis plus vraiment beaucoup dans les OTC parce que plus on a de capital plus on veut faire de l'argent et à quelque part les OTC ont leurs limites mais ont leurs limites à peut-être 50 000 c'est pas une limite à 14 millions ou une limite à 1000 dollars c'est on est capable d'en mettre beaucoup d'argent je mettais facilement du 15 20 milles dans une action otc avant aujourd'hui malheureusement j'aime mieux mettre un 10 20 milles ou un 30 milles

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage / plateforme de screening avec un panneau de filtres avancé en haut et un tableau de listes de titres (scanner de marché en mode sombre). L'onglet "OTCMARKET" est sélectionné.

**Contenu textuel & Code** : Tableau de tri des actions OTC classées par variation en pourcentage ("Chg %") décroissante. Colonnes visibles : Symbol (STRH, EVUS, XTRM, PGAS, etc.), Last (prix de 0.0013 à 1.70), Chg % (variations positives de +172.73% à +25.00%), Vol, et Shares.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est visible au milieu du tableau sur la ligne du ticker "GMER" (prix à 0.0068, variation de +36.00%).

---

### ⏱️ `[00:28:15 - 00:28:58]` | Segment #54

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> sur d'autres choses mais peu importe ça pour dire vous avez peu de capital votre départ en trading commence là commence sur les otc et vous allez évoluer éventuellement vous transférez sur le marché us et éventuellement vous transférer sur des actions plus grosses seront peut-être éventuellement des dos flotte ou des choses comme ça donc j'espère que cette petite vidéo vous avoir aidé dans tous ces histoires de screener donc comme je vous dis c'est pas le top gamer c'est le screener screen il faut faire refresh à chaque fois qu'on veut avoir les nouvelles cotes et on est capable

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de screening de marché avec onglets "USMARKET" et "OTCMARKET", comportant des filtres de recherche avancés par prix, variation en pourcentage et volume.

**Contenu textuel & Code** : Tableau de scanner affichant une liste de tickers penny stocks/OTC (STRH à 0.003 avec +172.73%, EVUS à 0.0016 avec +166.67%, XTRM, PGAS, ECPLA, EXLA, SRUTF, MLFB, VMNT, IALS, BWXMF, VSYM, BLGI, MEEC, TXSO, SMME, UPLCQ, SHRG, MULB, GMER, WTII, CNNA, VMSJ, OPTI, GBBFF, ENKS, DSGT, SNDO, SRCO, SFIO) avec leurs colonnes Last, Chg %, Vol et Shares.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné sur la ligne du ticker MULB (0.0025, +38.89%).

---

### ⏱️ `[00:28:58 - 00:29:35]` | Segment #55

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> capable de l'avoir à l'instant, c'est le fun pour le matin à l'ouverture, quand on n'a pas de chiffres, quand l'autre tableau, lui, va nous indiquer, bon, à 9h30, c'était temps, mais on ne les voit pas flasher ou monter ou des choses comme ça, il faut les voir une par une, donc à partir de là, quand on a ça ici, on va les voir monter, ça va être plus facile d'avoir un focus, de trouver les bonnes actions dans notre range de prix et avoir les derniers détails justement des actions qui montent donc si vous avez apprécié cette bonne vidéo vous faites m'exploser les bons pouces bleus

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage ou plateforme de screening (fond noir), onglets "USMARKET" et "OTCMARKET", section de filtrage avancée par prix, volume et variation (Chg %).

**Contenu textuel & Code** : Tableau de scanner affichant plusieurs tickers penny stocks / OTC (STRH, EVUS, XTRM, PGAS, etc.) avec leurs colonnes respectives : Symbol, Last (prix), Chg % (variation), Vol (volume) et Shares. Par exemple, le ticker STRH affiche 0.003 avec +172.73% de variation.

**Action / Démonstration** : Le curseur de la souris (flèche blanche) est positionné dans le coin supérieur droit de la fenêtre, au niveau des indicateurs de résultats (Results: 83).

---

### ⏱️ `[00:29:35 - 00:30:11]` | Segment #56

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> parce que moi je suis un youtubeur et vous savez moi les capotes moi quand je vois des pouces bleus je suis en train de virer fou raide donc n'oubliez pas les pouces bleus n'oubliez pas de partager si vous voulez supporter la chaîne mettez moi un petit commentaire en bas que ce soit un petit point d'exclamation et tout ça Youtube aime bien ça et merci beaucoup de me supporter depuis le début je suis rendu un point que je ne croyais jamais possible de me rendre donc merci à tous d'avoir été là et on se repart la semaine prochaine dans une nouvelle vidéo ciao tout le monde bon week-end

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Logiciel de courtage Questrade IQ Edge (scanner de marché / filtre de cotations actions), onglets "USMARKET" et "OTCMARKET".

**Contenu textuel & Code** : Tableau de筛选 de penny stocks américaines et OTC affichant les tickers (Symbol), derniers prix (Last), pourcentages de variation (Chg %), volumes (Vol) et nombre total d'actions (Shares) avec des filtres configurés (ex: STRH à 0.003$ / +172.73%, EVUS à 0.0016$ / +166.67%, XTRM, PGAS, ECPLA, etc.).

**Action / Démonstration** : Aucune manipulation active visible, affichage statique du scanner de marché filtré par variation en pourcentage (Chg %).

---

### ⏱️ `[00:30:11 - 00:30:12]` | Segment #57

**🔊 Audio (Transcription Intégrale Mot pour Mot en Français) :**
> à bientôt

**👁️ Analyse Visuelle d'Écran (gemini-3.5-flash-lite) :**
**Interface & Outils** : Interface de filtrage et de scan de marché boursier (Screener) avec onglets USMARKET et OTCMARKET sur fond sombre.

**Contenu textuel & Code** : Tableau de筛选 des actions avec les tickers : STRH (0.003, +172.73%), EVUS (0.0016, +166.67%), XTRM (0.0317, +131.39%), PGAS, ECPLA, EXLA, SRUTF, MLFB, VMNT, IALS, BWXMF, VSYM, BLGI, MEEC, TXSO, SMME, UPLCQ, SHRG, MULB, GMER, WTII, CNNA, VMSI, OPTI, GBBFF, ENKS, DSGT, SNDO, SRCO, SFIO, affichant les colonnes Symbol, Last, Chg %, Vol et Shares avec des filtres de prix configurés de 0.0010 à 10.0000.

**Action / Démonstration** : Affichage fixe du screener de fin de session ou de revue de marché sans manipulation active visible du curseur.

---
