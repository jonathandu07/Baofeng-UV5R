Voici l’essentiel à connaître sur le fonctionnement d’une onde radio, en allant du plus fondamental au plus pratique.

---

## 1. Nature d’une onde radio

* Une onde radio est une **onde électromagnétique** :
  un champ électrique et un champ magnétique qui **oscillent** et se propagent dans l’espace.
* Elle se propage à environ

  * **c ≈ 300 000 km/s** dans le vide,
  * presque la même vitesse dans l’air.
* Elle **n’a pas besoin de support matériel** (contrairement au son qui a besoin d’air, d’eau, etc.).

Conséquence pratique :
une onde radio peut traverser le vide (espace), l’air, certains matériaux (murs, végétation) mais avec plus ou moins de pertes.

---

## 2. Paramètres fondamentaux : fréquence, longueur d’onde, période

Une onde radio est caractérisée par trois grandeurs liées entre elles :

1. **Fréquence (f)**

   * Nombre d’oscillations par seconde.
   * Unité : **hertz (Hz)**.
   * 1 kHz = 1 000 Hz, 1 MHz = 1 000 000 Hz, 1 GHz = 1 000 000 000 Hz.

2. **Longueur d’onde (λ)**

   * Distance entre deux “crêtes” successives de l’onde.
   * Unité : **mètre (m)**.

3. **Période (T)**

   * Durée d’une oscillation complète.
   * T = 1 / f.

Relation fondamentale :

[
c = \lambda \times f
]

où c ≈ 3 × 10⁸ m/s (vitesse de la lumière).

Exemples utiles :

* **PMR446** : f ≈ 446 MHz

  * 446 MHz = 446 × 10⁶ Hz
  * λ ≈ (3 × 10⁸) / (446 × 10⁶) ≈ 0,67 m
    ≈ 67 cm de longueur d’onde.
* **FM radio** autour de 100 MHz :

  * λ ≈ (3 × 10⁸) / (100 × 10⁶) = 3 m.

Conséquence pratique :
la longueur d’onde donne un **ordre de grandeur de la taille d’antenne idéale** et influe sur la manière dont l’onde interagit avec les obstacles.

---

## 3. Spectre radio et bandes de fréquences

Les ondes radio font partie du **spectre électromagnétique** (avec infrarouge, lumière visible, etc.).

Quelques bandes classiques (approximation) :

* **HF** (3–30 MHz) : grandes distances possibles (réflexion ionosphère).
* **VHF** (30–300 MHz) : radios aviation, marine, PMR pro, etc.
* **UHF** (300–3000 MHz) : PMR446, talkies grand public, beaucoup de liaisons modernes.

Plus la fréquence est **élevée** :

* plus la longueur d’onde est **courte**,
* plus la propagation est **ligne de vue**,
* plus l’onde est sensible aux obstacles (bâtiments, relief).

---

## 4. Propagation d’une onde radio

Une onde radio ne se propage pas “en ligne parfaite”, elle interagit avec l’environnement.

### 4.1. Modes de propagation

* **Onde de sol** (suit la surface de la Terre) : surtout pour les fréquences plus basses (LF / MF / HF).
* **Propagation troposphérique** (dans la couche basse de l’atmosphère) : VHF / UHF, portée dépend de la courbure de la Terre, du relief, de la météo.
* **Réflexion ionosphérique** : pour certaines fréquences HF, permet d’atteindre des grandes distances (rebonds entre ionosphère et sol).
* **Ligne de vue (LOS)** : surtout VHF / UHF (ce qui t’intéresse pour les Baofeng, PMR, etc.) :
  en pratique : si tu ne “vois” pas (au sens géométrique) l’antenne adverse, la liaison se dégrade rapidement.

### 4.2. Interactions avec les obstacles

* **Réflexion** : rebond sur bâtiments, falaises, etc.
* **Diffraction** : contournement partiel d’un obstacle, surtout si l’obstacle est de taille proche de la longueur d’onde.
* **Réfraction** : changement de direction en traversant des couches d’air de densité différente.
* **Absorption** : une partie de l’énergie est perdue (forêt dense, mur épais, corps humain, etc.).

Conséquences pratiques :

* Relief et bâtiments créent des **zones d’ombre radio**.
* Une antenne **en hauteur** améliore beaucoup la portée.
* Forêt dense + creux de terrain = grosse atténuation.

---

## 5. Polarisation

L’onde électromagnétique a une **polarisation** : direction du champ électrique.

* **Polarisation verticale** : antenne verticale (classique pour PMR, Baofeng).
* **Polarisation horizontale** : antenne horizontale.
* **Polarisation circulaire** : champ tournant (antennes particulières).

Règle pratique :
pour une liaison optimale, les antennes doivent avoir **la même polarisation**.
Verticale ↔ verticale = bon.
Verticale ↔ horizontale = pertes importantes (parfois > 20 dB).

---

## 6. Couplage onde radio / antenne

Une antenne sert à :

* **Convertir** un courant électrique oscillant en onde électromagnétique (émission).
* **Convertir** une onde électromagnétique reçue en courant électrique exploitable (réception).

Points importants :

* Une antenne fonctionne bien quand sa taille est **adaptée à la longueur d’onde** (par ex. antenne ¼ d’onde, ½ onde, etc.).
* Une antenne trop courte ou mal adaptée → moins de rendement, portée réduite.
* Le **plan de masse** (en gros, le “retour” de l’antenne) joue aussi un rôle (châssis véhicule, gilet, corps).

Conséquences pratiques :

* Une antenne RHD771 (plus longue) offre souvent une meilleure portée qu’une petite antenne d’origine, car plus adaptée à la longueur d’onde.
* Positionner l’antenne derrière une plaque balistique ou dans le dos diminue un peu les performances, mais permet la discrétion.

---

## 7. Atténuation, bruit et interférences

### 7.1. Atténuation

L’intensité de l’onde diminue avec la distance (loi en 1 / distance²) et avec les obstacles.

* Plus tu es loin, plus le signal est **faible**.
* Plus il y a d’obstacles (murs, forêt, relief), plus le signal est **atténué**.

### 7.2. Bruit

* Le **bruit** = perturbations aléatoires (thermiques, électriques, atmosphériques, bruit électronique de la radio elle-même).
* On parle de **rapport signal / bruit (S/N)** : si le bruit est trop fort par rapport au signal, tu entends du souffle, des crachotements, etc.

### 7.3. Interférences

* Deux signaux sur la même fréquence peuvent se **superposer** (stations différentes, autres équipes, parasites).
* Interférences → difficultés de compréhension, “doublons” (plusieurs personnes parlent en même temps), etc.

Conséquences pratiques :

* D’où l’usage du **squelch** : seuil au-dessous duquel la radio coupe le bruit.
* D’où l’importance de limiter les émissions inutiles et de gérer les canaux correctement.

---

## 8. Modulation : comment l’onde transporte l’information

L’onde radio de base (appelée **porteuse**) est une sinusoïde pure.
Pour transporter de l’information (voix, données), on la **modifie** :

* **AM (Amplitude Modulation)** : on fait varier l’**amplitude** de l’onde.
* **FM (Frequency Modulation)** : on fait varier la **fréquence instantanée** autour d’une fréquence centrale.
* **Modulations numériques** (FSK, PSK, QAM, etc.) : on fait varier amplitude / fréquence / phase selon un alphabet de symboles.

Pour un utilisateur de talkie-walkie :

* La voix est transformée en signal électrique par le micro.
* Ce signal module la porteuse (souvent en FM sur PMR/Baofeng).
* À la réception, la radio **démodule** : elle retransforme les variations de l’onde en signal électrique, puis en son.

---

## 9. Ce qu’il faut retenir opérationnellement

Pour un cours sur les transmissions, l’essentiel à retenir sur l’onde radio :

1. C’est une onde électromagnétique qui se propage à la vitesse de la lumière.
2. Elle est définie par sa fréquence, sa longueur d’onde et sa période, liées par c = λ × f.
3. Sa propagation dépend fortement de la fréquence, de la hauteur d’antenne et du relief.
4. La polarisation doit être cohérente entre antennes pour une bonne liaison.
5. L’antenne est l’interface clé : taille adaptée à la longueur d’onde et bon placement.
6. Atténuation, bruit et interférences limitent la portée et la qualité de la communication.
7. La modulation permet de “poser” la voix ou les données sur la porteuse.

