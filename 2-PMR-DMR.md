## 1. PMR (ici : PMR446 analogique) vs DMR

### 1.1. PMR (PMR446 analogique)

Quand on dit “PMR” dans le grand public, on parle presque toujours de **PMR446** :

* **Bande** : autour de **446 MHz** (en UHF).
* **Modulation** : **FM analogique** (narrow FM, NFM).
* **Largeur de canal** : typiquement 12,5 kHz.
* **Fonctionnement** :

  * Tu choisis un **canal** (1, 2, 3…) → correspond à une fréquence précise.
  * Tu peux ajouter un **sous-ton CTCSS** ou un **code DCS** pour filtrer ce que tu entends (mais ça ne chiffre rien, ça ne fait que couper le squelch si le bon code est reçu).
* **Puissance limitée** (pour PMR446) → portée typique de quelques centaines de mètres à quelques km selon le terrain.

Usage typique :
talkies grand public, petites équipes, clubs, airsoft, rando, etc.

Caractéristiques clés :

* Simple : je tourne le bouton sur le même canal que toi, on parle.
* Audio continu : tu entends le souffle, les parasites, les bruits de fond, etc.
* À la limite de portée, le son devient progressivement mauvais, mais on comprend parfois encore.

---

### 1.2. DMR (Digital Mobile Radio)

**DMR** est une **norme numérique** normalisée (ETSI) pour les radios pro.

Principes techniques importants :

* **Modulation numérique** (en gros une FM numérique avec codage binaire).
* **Canal 12,5 kHz**, mais découpé en **2 time slots (TDMA 2 créneaux)** :

  * Sur une seule fréquence, on a **2 “voies” de communication indépendantes** (Slot 1 et Slot 2).
* La voix est **numérisée et compressée** (codec type AMBE+2 ou équivalent).

Notions spécifiques DMR :

* **ID radio** : chaque poste a un identifiant numérique (comme un numéro).
* **Color Code** : équivalent numérique d’un CTCSS, nécessaire pour accéder au réseau.
* **Time Slot** : 1 ou 2 (deux “sous-canaux” sur la même fréquence).
* **Talkgroup** : groupe logique de conversation (ex : TG 1 “Commandement”, TG 2 “Équipe 1”, etc.).

Fonctionnalités supplémentaires :

* Appel individuel (une radio vers une seule radio).
* Appel de groupe (talkgroup).
* Envoi de **petits messages de données** (texte, télémétrie, GPS, etc.).
* Possibilité de **chiffrement** (selon matériel et configuration : basique ou plus avancé).

Comportement radio :

* Tant que le **signal est suffisant**, le son est très propre, presque “téléphonique”.
* À la limite de portée, on passe d’un coup de “clair” à “robotique” puis **plus rien du tout** (effet falaise du numérique).
* Le bruit de fond est quasi absent (le décodeur ne laisse rien passer en dehors de ce qui est compris).

---

### 1.3. Comparaison pratique PMR (analogique) vs DMR

**Simplicité d’emploi**

* PMR analogique :

  * On règle le canal (et éventuellement un CTCSS/DCS), et c’est parti.
  * Très intuitif pour des débutants.
* DMR :

  * Nécessite une **programmation** (codeplug) : fréquences, color code, time slot, talkgroups.
  * Plus complexe à mettre en place, mais très puissant pour un réseau structuré.

**Qualité audio**

* PMR analogique :

  * Audio naturel, mais bruit, souffle, crachotements.
  * On entend “quelque chose” même si la liaison n’est pas bonne.
* DMR :

  * Audio propre tant que le signal est bon.
  * Si le signal est trop faible → coupure nette.

**Capacité du réseau**

* PMR analogique :

  * Un canal = **une seule conversation à la fois**.
* DMR :

  * Un canal (une fréquence) = **deux conversations simultanées** (slots).
  * Gestion de nombreux talkgroups sur les mêmes fréquences via relais → gros réseaux possibles.

**Fonctionnalités**

* PMR analogique :

  * Simple voix, éventuellement CTCSS/DCS.
* DMR :

  * Talkgroups, appels individuels, télémétrie, GPS, messagerie, chiffrement, etc.

**Matériel**

* PMR analogique :

  * Radios simples, peu chères, faciles à utiliser.
* DMR :

  * Radios plus chères, qu’il faut programmer (PC + logiciel).

---

## 2. VHF vs UHF

Maintenant, axe “fréquences” indépendamment d’analogique/numérique.

Pour les portatifs type Baofeng / DMR classiques, on parle surtout de :

* **VHF** : environ **136–174 MHz**
* **UHF** : environ **400–470 MHz**

### 2.1. VHF (Very High Frequency)

* Fréquences plus **basses** → longueurs d’onde plus **grandes** (≈ 2 m à 150 MHz).
* Antennes adaptées : plus **longues** (¼ d’onde ≈ 50 cm à 150 MHz).

Comportement de propagation :

* Se propage bien en **terrain dégagé** : campagne, plaine, montagne.
* Pénètre mieux la **végétation** (forêt) que l’UHF.
* Suit un peu mieux le relief (léger contournement des obstacles).

Conséquences :

* Très intéressant pour :

  * **Rando, montagne, milieu rural**, liaisons à moyennes distances.
  * Communications sur terrain “ouvert” avec peu de bâtiments.

Limites :

* Moins bon dans les **bâtiments** ou les environnements très urbains.
* Antennes plus grandes (moins discrètes).

---

### 2.2. UHF (Ultra High Frequency)

* Fréquences plus **hautes** → longueurs d’onde plus **courtes** (≈ 70 cm à 430–450 MHz).
* Antennes plus **courtes** (¼ d’onde ≈ 17 cm à 430 MHz).

Comportement :

* Plus sensible aux **obstacles** physiques (murs, relief), mais en contrepartie :

  * Meilleure **pénétration dans les bâtiments** (béton armé, structures).
  * Plus de **réflexions** sur les surfaces (murs, structures métalliques), ce qui peut aider en ville (rebonds dans les rues).
* Propagation très “ligne de vue” : si une colline bloque, c’est souvent très net.

Conséquences :

* Très adapté pour :

  * Milieu **urbain**, zones industrielles.
  * Liaisons à courte/moyenne distance dans des environnements construits.
  * Applications où on veut des **antennes courtes et discrètes** (talkies compacts, antenne sur gilet, etc.).

Limites :

* En terrain ouvert et vallonné, l’UHF se fait vite couper par les obstacles.
* Un creux de terrain peut suffire à perdre la liaison.

---

## 3. Croisement des deux axes

Pour résumer :

### 3.1. PMR / DMR vs UHF / VHF

* **PMR446 analogique** :

  * Toujours en **UHF** (autour de 446 MHz).
  * Analogique FM.

* **DMR** :

  * Existe en **VHF** (136–174 MHz) et en **UHF** (400–470 MHz).
  * C’est un **mode numérique**, pas une bande de fréquence.

* **Baofeng UV-5R** :

  * Radio **analogique** FM.
  * Bi-bande **VHF + UHF** (selon la version).

* **Talkies DMR type Retevis RT3S** (par ex.) :

  * Radio **numérique DMR + analogique FM**, souvent UHF ou bi-bande.

### 3.2. Choix de bande et de technologie

En caricaturant pour ton cours :

* Si tu veux un système :

  * **Très simple, très intuitif, peu de réglages** → PMR analogique.
  * **Structuré, avec plusieurs groupes, des fonctions avancées** → DMR.

* Si ton terrain est :

  * **Rural / montagne / forêt** → VHF est souvent plus efficace (meilleure portée, moins affectée par la végétation).
  * **Urbain / bâtiments / CQB / zones industrielles** → UHF est généralement plus adaptée (effet de réflexion, meilleure pénétration dans les structures, antennes compactes).

Beaucoup de réseaux pros font :

* DMR **UHF** pour les sites urbains / industriels.
* DMR **VHF** pour des réseaux plus étendus en rase campagne.

---

## 4. À retenir pour ton cours

Tu peux donner à tes stagiaires les idées forces suivantes :

1. **PMR** (dans le langage courant) = talkies analogiques simples, souvent en UHF (PMR446), une conversation par canal.
2. **DMR** = radio **numérique**, 2 conversations simultanées par fréquence (2 slots), gestion de groupes, possibilités de chiffrement et de données.
3. **VHF** = mieux pour terrain ouvert et végétation, antennes plus longues, meilleur comportement en environnement rural.
4. **UHF** = mieux pour zones bâties, antennes courtes et discrètes, bon compromis pour talkies modernes, mais plus sensible aux masques de relief.

Si tu veux, je peux te rédiger une double-page de cours prête à projeter / imprimer :

* Page 1 : tableau comparatif PMR vs DMR.
* Page 2 : tableau comparatif VHF vs UHF + schéma simple de propagation.
