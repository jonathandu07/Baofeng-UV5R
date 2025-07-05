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