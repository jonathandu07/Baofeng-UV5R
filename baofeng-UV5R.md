# Guide complet de la radio Baofeng-UV5R
Le Baofeng UV-5R est une radio portative bi-bande (VHF/UHF) très répandue dans le monde militaire et civil, offrant :
- Large gamme de fréquences (136–174 MHz VHF, 400–520 MHz UHF)
- Programmation manuelle ou via câble USB et logiciel
- Sous-canaux CTCSS/DCS pour limiter l'écoute non-autorisée

> ⚠️ **Attention** : Le Baofeng n’est pas crypté. Il permet de rendre l’écoute difficile, pas impossible.


## Tableau PMR446 : Canaux + Fréquences proches ("Sous-canaux")

| Canal | Fréquence principale | Sous-canal 1 (+6.25 kHz) | Sous-canal 2 (–6.25 kHz) | Utilisation officielle             | Remarque                      |
|-------|---------------------|--------------------------|--------------------------|------------------------------------|-------------------------------|
| 1     | 446.00625           | 446.01250                | 446.00000                | Phonie                             |                               |
| 2     | 446.01875           | 446.02500                | 446.01250                | Phonie                             |                               |
| 3     | 446.03125           | 446.03750                | 446.02500                | Phonie                             | Survivaliste/Preppers         |
| 4     | 446.04375           | 446.05000                | 446.03750                | Phonie                             |                               |
| 5     | 446.05625           | 446.06250                | 446.05000                | Phonie (Scout/Rando)               | Radiocoutisme                 |
| 6     | 446.06875           | 446.07500                | 446.06250                | Répéteurs                          | CTCSS Recommandé              |
| 7     | 446.08125           | 446.08750                | 446.07500                | Balises/Urgence Montagne           | URG. Montagne Ch 7 tone 7     |
| 8     | 446.09375           | 446.10000                | 446.08750                | Canal d'appel (Local & DX)         | Aucun CTCSS sur 8             |
| 9     | 446.10625           | 446.11250                | 446.10000                | Analogique/DMR (TS1/CC1/TG99)      |                               |
| 10    | 446.11875           | 446.12500                | 446.11250                | Analogique/DMR (TS1/CC1/TG99)      |                               |
| 11    | 446.13125           | 446.13750                | 446.12500                | Analogique/DMR (TS1/CC1/TG99)      | Survivaliste/Preppers         |
| 12    | 446.14375           | 446.15000                | 446.13750                | Analogique/DMR (TS1/CC1/TG99)      |                               |
| 13    | 446.15625           | 446.16250                | 446.15000                | Analogique/DMR (TS1/CC1/TG99)      |                               |
| 14    | 446.16875           | 446.17500                | 446.16250                | Analogique/DMR (TS1/CC1/TG99)      |                               |
| 15    | 446.18125           | 446.18750                | 446.17500                | Analogique/DMR (TS1/CC1/TG99)      |                               |
| 16    | 446.19375           | 446.20000                | 446.18750                | Analogique/DMR (TS1/CC1/TG99)      | Appel DMR (Local et DX)       |

---

### Explications

- **Fréquence principale** : La fréquence standard du canal PMR446.
- **Sous-canal 1 (+6.25 kHz)** : Fréquence "proche", utilisable sur Baofeng UV-5R mais non autorisée officiellement (risque d’interférer d’autres canaux). Sert à brouiller la recherche.
- **Sous-canal 2 (–6.25 kHz)** : Même logique, de l’autre côté.
- **Utilisation officielle** : Telles que listées dans ton tableau d’origine.
- **Remarque** : Indications terrain ou recommandations pratiques.

---

> **Attention**  
> Utiliser des "sous-canaux" (fréquences décalées) peut gêner d’autres utilisateurs et n’est pas autorisé par l’ARCEP en France, mais cette pratique existe en survie ou pour des missions discrètes.  
> En combinant ça à des codes CTCSS/DCS, tu rends la détection quasi impossible par un simple scan.

---

### Utilisation en plan radio

- Prévois une **table de correspondance** pour chaque mission (ex : Canal "B7" = 446.08750, DCS D047N).
- Change régulièrement la fréquence et le code (ex : rotation horaire ou selon événement).
- Ne pas rester sur les canaux d’appel longtemps.
- Sur Baofeng : régler la fréquence exacte au lieu de simplement utiliser le mode "channel".

---

**Tu veux le même tableau avec une colonne “CTCSS” ou “DCS” à remplir pour chaque sous-canal ?**
Ou un générateur aléatoire de plan de fréquence et code ?  
Dis-moi le format qui te va !

## Différence entre VHF et UHF sur Baofeng UV-5R

### Définitions rapides

- **VHF** = Very High Frequency = **136 à 174 MHz** sur le Baofeng UV-5R
- **UHF** = Ultra High Frequency = **400 à 520 MHz** sur le Baofeng UV-5R

Le Baofeng UV-5R fonctionne sur les deux bandes.  
Les canaux **PMR446** sont situés en **UHF**.

---

### Comparatif terrain

|               | **VHF (136–174 MHz)**           | **UHF (400–520 MHz)**            |
|---------------|----------------------------------|----------------------------------|
| **Pénétration obstacles** | Faible (murs, forêts, bâtiments) | Forte (passe mieux à travers)   |
| **Portée à découvert**    | Portée longue (terrain ouvert)   | Portée moindre mais plus stable |
| **Propagation**           | Rebonds sur reliefs              | Réflexion/diffraction, capte même sans visibilité directe |
| **Interférences**         | Sensible (éclairs, moteurs)      | Moins sensible (sauf autres radios UHF) |
| **Utilisation courante**  | Militaire, secours, aviation, rural | PMR446, police, sécurité, urbain, airsoft |
| **Antenne**               | Plus longue                      | Plus courte                     |

---

### Utilisation pratique sur le Baofeng UV-5R

- **PMR446 = UHF** (446 MHz)
    - Pour communiquer avec talkies “civils”, toujours UHF.
- **VHF** :
    - Pour fréquences militaires/sécuritaires (si autorisées)
    - Pour grandes distances en terrain ouvert
    - Moins de brouillage en zone rurale

**En zone urbaine ou boisée** :  
> **UHF** est le meilleur choix (meilleure pénétration).

**En plaine ou montagne** :  
> **VHF** offre la portée maximale.

---

### Résumé opérationnel

- **Communiquer avec PMR446 : UHF obligatoire (446 MHz)**
- **Liaisons longues distances en terrain dégagé : VHF recommandé**
- **Opérations urbaines/infiltration : UHF plus fiable**

Astuce :  
Utiliser **VHF** pour liaisons entre groupes (commandement, relais)  
et **UHF** pour communications internes au groupe (patrouille, appui).

---

**En résumé**  
- **UHF** = ville, forêt, bâtiments  
- **VHF** = terrain ouvert, montagne

---


## Menus du Baofeng UV-5R — Guide rapide

Le menu du Baofeng UV-5R permet de régler tous les paramètres importants de la radio.  
Pour entrer dans le menu, appuie sur la touche `MENU`, navigue avec les flèches ▲▼, puis valide à nouveau avec `MENU` pour modifier un réglage.  
Appuie sur `EXIT` pour quitter.

---

### Tableau récapitulatif des menus principaux

| N° | Nom       | Fonction principale                                | Valeurs/réglages possibles |
|----|-----------|----------------------------------------------------|----------------------------|
| 0  | SQL       | Squelch (niveau de seuil du bruit)                 | 0–9                        |
| 1  | STEP      | Pas de fréquence                                   | 2.5/5/6.25/10/12.5/25 kHz  |
| 2  | TXP       | Puissance d’émission                               | HIGH / LOW                 |
| 3  | SAVE      | Économie batterie                                  | OFF/1/2/3/4                |
| 4  | VOX       | Transmission vocale (VOX)                          | OFF / 1–10                 |
| 5  | WN        | Largeur de bande                                   | WIDE (large) / NARR (étroite) |
| 6  | ABR       | Durée éclairage écran                              | OFF/1–5                    |
| 7  | TDR       | Double veille/réception                            | OFF/ON                     |
| 8  | BEEP      | Bip clavier                                        | OFF/ON                     |
| 9  | TOT       | Limite temps de transmission                       | 15–600s                    |
| 10 | R-DCS     | Réception DCS (code numérique)                     | OFF/D023N–D754N            |
| 11 | R-CTCS    | Réception CTCSS (code analogique)                  | OFF/67.0–254.1 Hz          |
| 12 | T-DCS     | Emission DCS (code numérique)                      | OFF/D023N–D754N            |
| 13 | T-CTCS    | Emission CTCSS (code analogique)                   | OFF/67.0–254.1 Hz          |
| 14 | VOICE     | Aide vocale                                        | OFF/ON                     |
| 15 | ANI       | ID radio automatique (réglable PC)                 | Logiciel uniquement        |
| 16 | DTMFST    | Tonalité DTMF                                      | OFF/DT-ST/ANI-ST/DT+ANI    |
| 17 | S-CODE    | Code de signal (logiciel PC)                       | Logiciel uniquement        |
| 18 | SC-REV    | Type de scan                                       | TO/CO/SE                   |
| 19 | PTT-ID    | Transmission de l’ID                               | OFF/BOT/EOT/BOTH           |
| 20 | PTT-LT    | Délai envoi ID                                     | 0–30 ms                    |
| 21 | MDF-A     | Affichage VFO A (logiciel PC)                      | FREQ/CH/NAME               |
| 22 | MDF-B     | Affichage VFO B (logiciel PC)                      | FREQ/CH/NAME               |
| 23 | BCL       | Blocage canal occupé                               | OFF/ON                     |
| 24 | AUTOLK    | Verrouillage automatique du clavier                | OFF/ON                     |
| 25 | SFT-D     | Décalage répéteur (+/-/OFF)                        | OFF/+/-                    |
| 26 | OFFSET    | Valeur de décalage                                 | 00.000–69.990 MHz          |
| 27 | MEMCH     | Enregistrer canal mémoire                          | 000–127                    |
| 28 | DELCH     | Supprimer canal mémoire                            | 000–127                    |
| 29 | WT-LED    | Couleur écran veille                               | OFF/BLEU/ORANGE/VIOLET     |
| 30 | RX-LED    | Couleur écran réception                            | OFF/BLEU/ORANGE/VIOLET     |
| 31 | TX-LED    | Couleur écran émission                             | OFF/BLEU/ORANGE/VIOLET     |
| 32 | AL-MOD    | Type d’alarme                                      | SITE/TONE/CODE             |
| 33 | BAND      | Choix bande (VHF/UHF) en VFO                       | VHF/UHF                    |
| 34 | TX-AB     | Transmission A/B en double veille                  | OFF/A/B                    |
| 35 | STE       | Tonalité fin de transmission                       | OFF/ON                     |
| 36 | RP-STE    | Fin de transmission sur répéteur                   | OFF/1–10                   |
| 37 | RPT-RL    | Délai de fin de transmission répéteur              | OFF/1–10                   |
| 38 | PONMGS    | Message d’accueil                                  | FULL/MGS                   |
| 39 | ROGER     | Son de fin de transmission ("roger beep")          | OFF/ON                     |
| 40 | RESET     | Restaure valeurs par défaut                        | VFO/ALL                    |

---

### **Utilisation basique du menu**

1. Appuie sur `MENU` pour entrer dans le menu.
2. Navigue avec les flèches ▲▼ pour sélectionner l’option voulue (numéro ou nom).
3. Appuie à nouveau sur `MENU` pour éditer.
4. Change la valeur avec ▲▼ puis valide avec `MENU`.
5. Sors avec `EXIT`.

---

### **Menus essentiels pour la sécurité/mission**

- **SQL (0) :** Ajuste pour ne pas capter le bruit de fond (5 conseillé).
- **TXP (2) :** LOW (1W) pour la discrétion, HIGH (5W) pour la portée.
- **T-CTCS (13)/T-DCS (12) :** Ajoute un code pour sécuriser la comm.
- **R-CTCS (11)/R-DCS (10) :** Ajoute un code en réception.
- **MEMCH (27) :** Sauvegarde une fréquence en mémoire.
- **DELCH (28) :** Efface un canal.
- **BCL (23) :** Empêche d’émettre si le canal est occupé.

---

### **Astuces**

- Les menus CTCSS/DCS sont indispensables pour éviter l’écoute de base.
- Changer régulièrement le code et/ou la fréquence.
- Programmer tes canaux à l’avance, puis verrouille le clavier (`#` long).
- Le menu RESET (40) efface tout : à éviter sauf urgence !

---

## Tableau des sous-canaux CTCSS et DCS pour Baofeng UV-5R

### CTCSS (Continuous Tone Coded Squelch System) — Codes analogiques

| N° | Code (Hz) | N° | Code (Hz) | N° | Code (Hz) | N° | Code (Hz) | N° | Code (Hz) |
|----|-----------|----|-----------|----|-----------|----|-----------|----|-----------|
| 1  | 67.0      | 11 | 94.8      | 21 | 131.8     | 31 | 171.3     | 41 | 203.5     |
| 2  | 69.3      | 12 | 97.4      | 22 | 136.5     | 32 | 173.8     | 42 | 206.5     |
| 3  | 71.9      | 13 | 100.0     | 23 | 141.3     | 33 | 177.3     | 43 | 210.7     |
| 4  | 74.4      | 14 | 103.5     | 24 | 146.2     | 34 | 179.9     | 44 | 218.1     |
| 5  | 77.0      | 15 | 107.2     | 25 | 151.4     | 35 | 183.5     | 45 | 225.7     |
| 6  | 79.7      | 16 | 110.9     | 26 | 156.7     | 36 | 186.2     | 46 | 229.1     |
| 7  | 82.5      | 17 | 114.8     | 27 | 159.8     | 37 | 189.9     | 47 | 233.6     |
| 8  | 85.4      | 18 | 118.8     | 28 | 162.2     | 38 | 192.8     | 48 | 241.8     |
| 9  | 88.5      | 19 | 123.0     | 29 | 165.5     | 39 | 196.6     | 49 | 250.3     |
| 10 | 91.5      | 20 | 127.3     | 30 | 167.9     | 40 | 199.5     | 50 | 254.1     |

---

### DCS (Digital Coded Squelch) — Codes numériques

| N°  | Code   | N°  | Code   | N°  | Code   | N°  | Code   | N°  | Code   |
|-----|--------|-----|--------|-----|--------|-----|--------|-----|--------|
| 1   | D023N  | 22  | D131N  | 43  | D251N  | 64  | D371N  | 85  | D532N  |
| 2   | D025N  | 23  | D132N  | 44  | D252N  | 65  | D411N  | 86  | D546N  |
| 3   | D026N  | 24  | D134N  | 45  | D255N  | 66  | D412N  | 87  | D565N  |
| 4   | D031N  | 25  | D143N  | 46  | D261N  | 67  | D413N  | 88  | D606N  |
| 5   | D032N  | 26  | D145N  | 47  | D263N  | 68  | D423N  | 89  | D612N  |
| 6   | D036N  | 27  | D152N  | 48  | D265N  | 69  | D431N  | 90  | D624N  |
| 7   | D043N  | 28  | D155N  | 49  | D266N  | 70  | D432N  | 91  | D627N  |
| 8   | D047N  | 29  | D156N  | 50  | D271N  | 71  | D445N  | 92  | D631N  |
| 9   | D051N  | 30  | D162N  | 51  | D274N  | 72  | D446N  | 93  | D632N  |
| 10  | D053N  | 31  | D165N  | 52  | D306N  | 73  | D452N  | 94  | D645N  |
| 11  | D054N  | 32  | D172N  | 53  | D311N  | 74  | D454N  | 95  | D654N  |
| 12  | D065N  | 33  | D174N  | 54  | D315N  | 75  | D455N  | 96  | D662N  |
| 13  | D071N  | 34  | D205N  | 55  | D325N  | 76  | D462N  | 97  | D664N  |
| 14  | D072N  | 35  | D212N  | 56  | D331N  | 77  | D464N  | 98  | D703N  |
| 15  | D073N  | 36  | D223N  | 57  | D332N  | 78  | D465N  | 99  | D712N  |
| 16  | D074N  | 37  | D225N  | 58  | D343N  | 79  | D466N  | 100 | D723N  |
| 17  | D114N  | 38  | D226N  | 59  | D346N  | 80  | D503N  | 101 | D731N  |
| 18  | D115N  | 39  | D243N  | 60  | D351N  | 81  | D506N  | 102 | D732N  |
| 19  | D116N  | 40  | D244N  | 61  | D356N  | 82  | D516N  | 103 | D734N  |
| 20  | D122N  | 41  | D245N  | 62  | D364N  | 83  | D523N  | 104 | D743N  |
| 21  | D125N  | 42  | D246N  | 63  | D365N  | 84  | D526N  | 105 | D754N  |

---

- **CTCSS** : Utilise un signal audio continu (50 codes courants).
- **DCS** : Utilise un code numérique, plus de possibilités (105 codes sur Baofeng).

---

## Plan de communication Baofeng UV-5R — MHz, 6.25kHz, CTCSS, DCS

| Canal | Fréquence (MHz) | Sécurité     | Code           | Remarque                   |
|-------|-----------------|--------------|----------------|----------------------------|
| 1     | 446.00625       | Aucune       | —              | Libre MHz                  |
| 2     | 446.01875       | Aucune       | —              | Libre MHz                  |
| 3     | 446.03125       | Aucune       | —              | Libre MHz                  |
| 4     | 446.04375       | Aucune       | —              | Libre MHz                  |
| 5     | 446.05625       | Aucune       | —              | Libre MHz                  |
| 6     | 446.06875       | Aucune       | —              | Libre MHz                  |
| 7     | 446.08125       | Aucune       | —              | Libre MHz                  |
| 8     | 446.09375       | Aucune       | —              | Libre MHz                  |
| 9     | 446.10625       | Aucune       | —              | Libre MHz                  |
| 10    | 446.11875       | Aucune       | —              | Libre MHz                  |
| 11    | 446.13125       | Aucune       | —              | Libre MHz                  |
| 12    | 446.14375       | Aucune       | —              | Libre MHz                  |
| 13    | 446.15625       | Aucune       | —              | Libre MHz                  |
| 14    | 446.16875       | Aucune       | —              | Libre MHz                  |
| 15    | 446.18125       | Aucune       | —              | Libre MHz                  |
| 16    | 446.19375       | Aucune       | —              | Libre MHz                  |
| 17    | 446.005         | Aucune       | —              | Libre (fréq. proche)       |
| 18    | 446.020         | Aucune       | —              | Libre (fréq. proche)       |
| 19    | 446.030         | Aucune       | —              | Libre (fréq. proche)       |
| 20    | 446.045         | Aucune       | —              | Libre (fréq. proche)       |
| 21    | 446.055         | Aucune       | —              | Libre (fréq. proche)       |
| 22    | 446.070         | Aucune       | —              | Libre (fréq. proche)       |
| 23    | 446.080         | Aucune       | —              | Libre (fréq. proche)       |
| 24    | 446.095         | Aucune       | —              | Libre (fréq. proche)       |
| 25    | 446.105         | Aucune       | —              | Libre (fréq. proche)       |
| 26    | 446.120         | Aucune       | —              | Libre (fréq. proche)       |
| 27    | 446.130         | Aucune       | —              | Libre (fréq. proche)       |
| 28    | 446.145         | Aucune       | —              | Libre (fréq. proche)       |
| 29    | 446.155         | Aucune       | —              | Libre (fréq. proche)       |
| 30    | 446.170         | Aucune       | —              | Libre (fréq. proche)       |
| 31    | 446.180         | Aucune       | —              | Libre (fréq. proche)       |
| 32    | 446.195         | Aucune       | —              | Libre (fréq. proche)       |
| 33    | 446.00625       | CTCSS        | 88.5 Hz        | Sécurisé MHz               |
| 34    | 446.01875       | CTCSS        | 94.8 Hz        | Sécurisé MHz               |
| 35    | 446.03125       | CTCSS        | 103.5 Hz       | Sécurisé MHz               |
| 36    | 446.04375       | CTCSS        | 110.9 Hz       | Sécurisé MHz               |
| 37    | 446.05625       | CTCSS        | 123.0 Hz       | Sécurisé MHz               |
| 38    | 446.06875       | CTCSS        | 127.3 Hz       | Sécurisé MHz               |
| 39    | 446.08125       | CTCSS        | 136.5 Hz       | Sécurisé MHz               |
| 40    | 446.09375       | CTCSS        | 141.3 Hz       | Sécurisé MHz               |
| 41    | 446.10625       | CTCSS        | 151.4 Hz       | Sécurisé MHz               |
| 42    | 446.11875       | CTCSS        | 162.2 Hz       | Sécurisé MHz               |
| 43    | 446.13125       | CTCSS        | 173.8 Hz       | Sécurisé MHz               |
| 44    | 446.14375       | CTCSS        | 192.8 Hz       | Sécurisé MHz               |
| 45    | 446.15625       | CTCSS        | 203.5 Hz       | Sécurisé MHz               |
| 46    | 446.16875       | CTCSS        | 210.7 Hz       | Sécurisé MHz               |
| 47    | 446.18125       | CTCSS        | 225.7 Hz       | Sécurisé MHz               |
| 48    | 446.19375       | CTCSS        | 250.3 Hz       | Sécurisé MHz               |
| 49    | 446.00625       | DCS          | D023N          | Sécurisé MHz               |
| 50    | 446.01875       | DCS          | D025N          | Sécurisé MHz               |
| 51    | 446.03125       | DCS          | D026N          | Sécurisé MHz               |
| 52    | 446.04375       | DCS          | D031N          | Sécurisé MHz               |
| 53    | 446.05625       | DCS          | D032N          | Sécurisé MHz               |
| 54    | 446.06875       | DCS          | D047N          | Sécurisé MHz               |
| 55    | 446.08125       | DCS          | D051N          | Sécurisé MHz               |
| 56    | 446.09375       | DCS          | D054N          | Sécurisé MHz               |
| 57    | 446.10625       | DCS          | D065N          | Sécurisé MHz               |
| 58    | 446.11875       | DCS          | D073N          | Sécurisé MHz               |
| 59    | 446.13125       | DCS          | D074N          | Sécurisé MHz               |
| 60    | 446.14375       | DCS          | D114N          | Sécurisé MHz               |
| 61    | 446.15625       | DCS          | D131N          | Sécurisé MHz               |
| 62    | 446.16875       | DCS          | D132N          | Sécurisé MHz               |
| 63    | 446.18125       | DCS          | D143N          | Sécurisé MHz               |
| 64    | 446.19375       | DCS          | D165N          | Sécurisé MHz               |
| 65    | 446.005         | CTCSS        | 88.5 Hz        | Sécurisé (fréq. proche)    |
| 66    | 446.020         | CTCSS        | 94.8 Hz        | Sécurisé (fréq. proche)    |
| 67    | 446.030         | CTCSS        | 103.5 Hz       | Sécurisé (fréq. proche)    |
| 68    | 446.045         | CTCSS        | 110.9 Hz       | Sécurisé (fréq. proche)    |
| 69    | 446.055         | DCS          | D023N          | Sécurisé (fréq. proche)    |
| 70    | 446.070         | DCS          | D025N          | Sécurisé (fréq. proche)    |
| 71    | 446.080         | CTCSS        | 136.5 Hz       | Sécurisé (fréq. proche)    |
| 72    | 446.095         | CTCSS        | 141.3 Hz       | Sécurisé (fréq. proche)    |
| 73    | 446.105         | DCS          | D051N          | Sécurisé (fréq. proche)    |
| 74    | 446.120         | DCS          | D054N          | Sécurisé (fréq. proche)    |
| 75    | 446.130         | CTCSS        | 151.4 Hz       | Sécurisé (fréq. proche)    |
| 76    | 446.145         | CTCSS        | 192.8 Hz       | Sécurisé (fréq. proche)    |
| 77    | 446.155         | DCS          | D131N          | Sécurisé (fréq. proche)    |
| 78    | 446.170         | DCS          | D132N          | Sécurisé (fréq. proche)    |
| 79    | 446.180         | CTCSS        | 225.7 Hz       | Sécurisé (fréq. proche)    |
| 80    | 446.195         | CTCSS        | 250.3 Hz       | Sécurisé (fréq. proche)    |

