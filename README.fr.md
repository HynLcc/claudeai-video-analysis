# Comment Anthropic réalise des vidéos à 78M de vues

Analyse systématique de 77 vidéos produit officielles de Claude (oct. 2025 – mai 2026). Méthodologie extraite, système de design, cadres narratifs et schémas d'engagement.

 **Languages:** [English](README.md) · [中文](README.zh.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [**Français**](README.fr.md) · [Português](README.pt.md)

---

<details>
<summary><b>Table of Contents</b></summary>

- [5 grands insights](#5-grands-insights)
- [Insights basés sur les données](#insights-basés-sur-les-données)
- [Formule de production (version TL;DR)](#formule-de-production-version-tldr)
- [Positionnement concurrentiel](#positionnement-concurrentiel)
- [Adaptez-le à votre produit](#adaptez-le-à-votre-produit)

- [1. Pipeline de Production](#1-pipeline-de-production)
- [2. Systeme de Design](#2-systeme-de-design)
- [3. Cadres Narratifs](#3-cadres-narratifs)
- [4. Transitions et Grammaire des Animations](#4-transitions-et-grammaire-des-animations)
- [5. Architecture Hook (les 3 premieres secondes decident de tout)](#5-architecture-hook-les-3-premieres-secondes-decident-de-tout)
- [6. Moteur de Rythme](#6-moteur-de-rythme)
- [7. Formules d'Engagement](#7-formules-dengagement)
- [8. Guide des Niveaux de Production](#8-guide-des-niveaux-de-production)
- [9. Liste des Anti-Patterns](#9-liste-des-anti-patterns)
- [10. Analyse d'Evolution Temporelle : Volume de vues multiplie par 18 en 8 mois](#10-analyse-devolution-temporelle-volume-de-vues-multiplie-par-18-en-8-mois)
- [11. Analyse de Viralite : Pourquoi le Top 10 explose](#11-analyse-de-viralite-pourquoi-le-top-10-explose)
- [12. Analyse Multi-Dimensionnelle Axee sur les Donnees](#12-analyse-multi-dimensionnelle-axee-sur-les-donnees)
- [13. Comparaison des Strategies Video des Concurrents](#13-comparaison-des-strategies-video-des-concurrents)
- [14. Psychologie de l'Engagement : Pourquoi ces modeles fonctionnent](#14-psychologie-de-lengagement-pourquoi-ces-modeles-fonctionnent)
- [15. Strategie Audio / Bande Sonore](#15-strategie-audio-bande-sonore)
- [16. Liste de Verification Pratique](#16-liste-de-verification-pratique)
- [17. Guide d'Adaptation : Comment l'appliquer a votre propre produit](#17-guide-dadaptation-comment-lappliquer-a-votre-propre-produit)
- [Annexe A : Reference rapide des types de videos](#annexe-a-reference-rapide-des-types-de-videos)
- [Annexe B : Template de video fonctionnalite 30 secondes](#annexe-b-template-de-video-fonctionnalite-30-secondes)
- [Annexe C : Template de video fonctionnalite 60 secondes](#annexe-c-template-de-video-fonctionnalite-60-secondes)

</details>


## 5 grands insights

### 1. Ils ne filment jamais de vrais écrans — ils reconstruisent des UI parfaits

Chaque "capture d'écran" dans une vidéo Claude est fabriquée. Des maquettes UI pixel-perfect composées sur des cadres de périphérique rendus en 3D (MacBooks, iPhones, moniteurs), flottant sur des fonds chauds. Pas de chrome navigateur, pas de barre de favoris, pas de badges de notification.

**Pourquoi ça marche :** Élimine le bruit visuel. Chaque image est brand-safe. Pas d'onglets accidentels, pas de favoris embarrassants, pas d'éléments UI obsolètes quand le produit sort une mise à jour la semaine suivante.

### 2. Le hook "moins c'est plus" est le pattern le plus performant

Les deux vidéos les plus vues (77.9M et 63.5M) ouvrent de la même façon : une petite icône sur un vaste fond chaud. Pas de texte. Pas d'animation. Juste de l'espace négatif et un point focal unique.

Cela crée un **écart cognitif** — le cerveau ne peut pas analyser l'image instantanément, alors il investit de l'attention pour la décoder. Quand le nom du produit apparaît à 0.8–1.2s, le spectateur est déjà accroché.

La vidéo de 10 secondes qui a fait 10M de vues ? Même principe. Minimalisme extrême. Un élément. Terminé.

### 3. Pas d'intro logo, pas de CTA de fin — jamais

Sur 77 vidéos :
- **0** commencent par une animation de logo
- **0** se terminent par "Inscrivez-vous !" ou un quelconque call-to-action

C'est du positionnement de marque délibéré. Un intro logo dit "nous devons nous présenter". Un CTA dit "nous avons besoin de vous". Claude ne fait ni l'un ni l'autre — le produit apparaît à la frame 1, et la vidéo fond vers un logo silencieux sur fond chaud.

Le message : *notre produit n'a pas besoin de se vendre.*

### 4. "Montrer la réflexion, pas seulement le résultat" stimule l'engagement

Les vidéos qui visualisent le processus de l'IA — listes de tâches qui se cochent en vert, commandes terminal qui défilent, graphes de nœuds qui s'étendent — surpassent systématiquement les vidéos qui montrent seulement le résultat final.

Ce n'est pas un simple truc de production. C'est de l'**architecture de confiance.** Montrer le processus rend l'IA moins opaque. Le spectateur peut vérifier : "oui, elle a vraiment effectué ces étapes".

L'exemple le plus extrême : Computer Use (77.9M) montre Claude qui navigue dans un vrai OS, application par application. Pas simulé. Pas trop accéléré. Vrai curseur, vrais clics, vraie hésitation.

### 5. Que des hard cuts — zéro transition fantaisiste

Sur 77 vidéos :
- ~60% de hard cuts entre scènes
- ~15% de fondus vers un fond chaud
- ~10% de glissements
- ~0% de dissolutions, morphs, flips 3D, effets de particules

Chaque transition dure moins de 2 secondes. Pas de dissolutions cinématiques. Pas de transitions motion graphics tape-à-l'œil. La philosophie : si chaque image vaut le coup d'œil, vous n'avez pas besoin de vous excuser de couper dessus.

---

## Insights basés sur les données

### "Introducing" vaut 5x plus que "now available"

Les vidéos annonçant quelque chose de nouveau ("Introducing Claude Cowork") atteignent en moyenne **23.6M de vues**. Les vidéos étendant quelque chose d'existant ("Claude is now available in Excel") atteignent en moyenne **4.6M**. Le mot "Introducing" n'est pas juste du copy — c'est un signal de "nouvelle espèce" vs "mise à jour de version".

### 60–90 secondes est le sweet spot — puis chute libre

| Durée | Vues moyennes |
|-------|--------------|
| <15s | 3.0M |
| 30–60s | 7.3M |
| **60–90s** | **15.6M** |
| >90s | 2.9M |

60–90s laisse assez de place pour un arc narratif complet (hook → démo → magie → résultat). Moins de 30s semble incomplet. Plus de 90s perd l'attention. Le sweet spot est étroit mais réel.

### Lancement en pulsation, pas au compte-gouttes

77 vidéos sur 222 jours = 1 toutes les 2.9 jours en moyenne. Mais 77% des jours ont zéro publication. Anthropic utilise des **campagnes en rafale** — fenêtres de 3–5 jours avec 2–3 vidéos par jour, puis des périodes de silence.

Le plus extrême : février 2026 a vu 23 vidéos en un mois (30% du total), concentrées autour des lancements Opus 4.6 et Cowork. Le jour le plus productif : 20 février — 7 vidéos en 24 heures.

**Pourquoi la pulsation fonctionne :** les algorithmes de plateforme récompensent la concentration thématique. Une rafale de vidéos liées crée une perception de "Claude est partout" qu'un débit constant ne peut pas égaler.

### Ampleur vs profondeur : deux jeux différents

- **Jeu d'ampleur** (exposition de marque) : Computer Use — 77.9M vues, 14,467 retweets. Des millions l'ont vu, peu l'ont sauvegardé.
- **Jeu de profondeur** (fidélité développeur) : Agent View — 2.3M vues, mais 0.32% de taux de bookmark et 686 replies. Moins de spectateurs, mais chacun profondément engagé.

Les deux comptent. L'ampleur construit la marque. La profondeur construit la communauté. Anthropic mène les deux voies en parallèle.

### Lundi est le jour de lancement

| Jour | Vues moyennes |
|------|--------------|
| **Lundi** | **12.6M** |
| Vendredi | 9.4M |
| Mar–Jeu | 4.7–5.5M |

Les posts du lundi surfent sur la vague d'attention week-end → semaine. Les posts du vendredi bénéficient de l'amplification du week-end.

---

## Formule de production (version TL;DR)

```
Canevas chaud (#FBFAF6) + UI sombre (#1A1A2E) + Accent terracotta (#D67C64)
+ UI parfaite reconstruite sur mockups périphériques 3D
+ Titres serif en sentence case avec point.
+ Hard cuts. Pas d'intro logo. Pas de CTA.
+ Task sequence pour les "magic moments"
+ Hook en 0–3s. Magic moment avant 15s.
= Vidéo Claude.
```

---

## Positionnement concurrentiel

| | Claude | ChatGPT | Gemini | Apple Intelligence |
|---|--------|---------|--------|-------------------|
| Couleur | Blanc chaud + terracotta | Bleu froid + dégradé noir | Blanc + multicolore | Noir pur + blanc pur |
| Ambiance | Académique, chaud, réfléchi | Tech, cool, avant-garde | Convivial, grand public | Minimal, premium |
| Typographie | Titres serif (éditorial) | Sans-serif (tech) | Google Sans (marque) | SF Pro (système) |
| Humains à l'écran | 1 sur 77 | Parfois | Souvent | Jamais |
| CTA de fin | Jamais | Parfois | Toujours | Carte de marque |

---

## Adaptez-le à votre produit

**Empruntez directement :** hard cuts, pas d'intro logo, pas de CTA, titres en sentence case avec points, poids de police 500/600/700, task sequences, scènes de 3–8s, liste d'anti-patterns, cadence de lancement en pulsation, sweet spot de 60–90s.

**Adaptez à votre marque :** système de couleurs (utilisez vos couleurs de marque mais gardez la hiérarchie canevas chaud + UI sombre), typographie (utilisez votre police de marque mais gardez la hiérarchie de tailles), mockups de périphérique (utilisez des captures avec ombres si vous ne pouvez pas faire de rendus 3D).

**Le principe sous-jacent :** chaque décision de production doit avoir une raison. Les choix de Claude ne sont pas une esthétique arbitraire — c'est une stratégie de marque exprimée par le mouvement. Copiez le raisonnement, pas les pixels.

---

# Methodology de Production Video pour Anthropic Claude

Analyse systematique basee sur 77 videos officielles @claudeai (2025-10 a 2026-05).
Couvre la pipeline de production, le systeme de design, les cadres narratifs, la grammaire des animations, le moteur de rythme et les formules d'engagement.

---

## 1. Pipeline de Production

### 1.1 Les 6 etapes du concept a la publication

```
Brief → Storyboard → UI Fabrication → Animation → Audio → Delivery
```

**Etape 1 : Brief (dossier creatif)**
- Determiner le type de video (voir Chapitre 3 — cadres narratifs)
- Fixer le budget de duree : 30s / 60s / 90s / 10s courte carte
- Confirmer le canal : X/Twitter (16:9 ou 1:1), YouTube (16:9), Instagram (4:5)
- Choisir la strategie d'ouverture (voir Chapitre 5 — architecture Hook)

**Etape 2 : Storyboard (storyboard)**
- Pas de storyboard dessine a la main — on directement dispose les scenes dans un outil de maquette UI
- Chaque scene est annotee : timecode, description du contenu, type d'animation, mode de transition
- L'approche de Claude : granularite fine des scenes (3-8s/scene), chaque scene ne fait qu'une seule chose

**Etape 3 : UI Fabrication (fabrication de l'interface)**
- **Principe central : ne pas enregistrer l'ecran reel, reconstruire une UI parfaite**
- Reconstruire les interfaces produit au pixel pres dans Figma/Sketch/After Effects
- Eliminer tout le bruit : onglets non pertinents, cadres de debug, barres de notification superflues, donnees sales des donnees reelles
- Les cadres de peripheriques sont des mockups 3D rendus (iPhone, MacBook, moniteur), avec des ombres subtils
- C'est le point de difference majeur entre les videos Anthropic et celles des concurrents : chaque image est parfaite

**Etape 4 : Animation (animation)**
- Tout le mouvement vient de l'animation de contenu, pas du mouvement de camera
- Les transitions entre scenes sont principalement des coupes dures, les transitions complexes (< 2s) sont occasionnelles
- Simulation du deplacement du curseur — definir le point de depart, opacity 0→1 en 0.46s, vol vers la cible, impulsion de clic
- Sequence de taches qui entre ligne par ligne, changement de couleur d'etat, coche

**Etape 5 : Audio (audio)**
- Videos d'animation rapide : musique electronique/percussion synchronisee au tempo
- Demonstration de produit : musique d'ambiance legere
- Videos terminal/developpeur : musique minimale ou absente
- Declaration de marque : silencieuse ou ton unique
- Conserver la version originale muette, puis exporter separement la version avec musique

**Etape 6 : Delivery (livraison)**
- Export multi-resolutions : 4K (3840x2160) pour les phares, 1080p pour le courant
- Multi-format : 16:9 paysage principalement, 4:5 portrait / 1:1 carre pour les reseaux sociaux
- Convention de nommage : `YYYY-MM-DD-slug-keyword.mp4`

### 1.2 Deux pistes de production

| Piste | Investissement | Caracteristiques | Usage typique |
|-------|---------------|-------------------|---------------|
| **Officiel raffine** | Eleve | 4K, UI simulee, mockups de peripheriques composites, motion graphics | Lancement de produit, fonctionnalites majeures |
| **Communaute/live** | Faible | Capture d'ecran brute, presence humaine, post-production minimale | Hackathon, evenements communaute, demonstrations reelles |

Les deux pistes fonctionnent en parallele. Le contenu live obtient parfois le plus haut engagement (demo live Cowork 14.6M), car le "realisme" est en soi une ressource rare.

---

## 2. Systeme de Design

### 2.1 Systeme de couleurs : "Intelligence chaleureuse"

```
Fond de canevas :  #FBFAF6 ~ #F5F0E8  Blanc chaud / creme (pas blanc pur)
Surface produit :  #1A1A2E ~ #2D2D3D  Charbon mode sombre
Accent principal :  #D67C64            Terracotta / orange brule
Accent secondaire :  #4ECDC4            Bleu-vert / cyan
Texte fonce :  #0F172A / #1A1A1A
Texte clair :  #FFFFFF / #E0E0E0
```

**Intention de design :**
- Blanc chaud != blanc pur. Le blanc chaud cree une texture "papier", plus premium et plus doux que le blanc pur
- La couleur terracotta est l'element visuel le plus immediatement reconnaissable — on reconnait Claude en une seconde
- L'UI en mode sombre = implication de "premium", "technique", "concentration"
- Eloignement global des degrades froids bleus/noirs des concurrents (OpenAI/Google) et du noir/blanc pur (Apple)
- Couleur chaude + intelligence = sentiment academique, pas corporatif

**Positionnement differentiel vs concurrents :**
- OpenAI : bleu froid + degrade noir → sens technologique / froid
- Google : blanc + multicolore → dynamique / grand public
- Apple : noir pur + blanc pur → minimaliste / haut de gamme
- Claude : blanc chaud + terracotta + UI sombre → academique / reflechi / chaleureux

### 2.2 Systeme typographique

| Usage | Style de police | Graisse | Caracteristiques |
|-------|----------------|---------|-------------------|
| Carte titre / marque | Serif a fort contraste (style Editorial New) | 700 | Casing de phrase avec point |
| Etiquettes UI / corps | Sans-serif geometrique (Inter/SF Pro) | 500-600 | Propre et lisible |
| Code / terminal | Monospace (JetBrains Mono) | 400-500 | Coloration syntaxique |
| Etiquettes majuscules | Sans-serif | 600 | "PROGRESS", "CONTEXT" |

**Details cles :**
- Titres en casing de phrase (sentence case), pas en Title Case
- Titres termines par un point — cree un sentiment de conversation et de confiance : "Claude now integrates."
- Graisses limitees a 500 / 600 / 700, gras synthetique interdit (`font-synthesis: none`)

### 2.3 Langage des mockups de peripheriques

Les mockups de peripheriques sont le dispositif visuel central, pas une decoration :

```
┌─────────────────────────┐
│                         │
│   ┌─────────────────┐   │
│   │  [UI Produit]    │   │  ← Cadre de peripherique rendu 3D
│   │  Interface sombre │   │     avec ombre subtile
│   │                 │   │     box-shadow: 0 8px 32px rgba(0,0,0,0.12)
│   └─────────────────┘   │
│                         │  ← Canevas blanc chaud / creme
└─────────────────────────┘
```

**Trois compositions pour afficher plusieurs ecrans simultanement :**

**A. Peripherique centre** — Focus unique, adapte aux annonces de fonctionnalites
**B. Disposition divisee** — Agent a gauche + application cible a droite, adapte aux presentations d'integration
**C. Narrative spatiale** — Telephone → griffonne → bureau, adapte aux flux multi-peripheriques

---

## 3. Cadres Narratifs

### 3.1 Quatre modes narratifs fondamentaux

#### Mode A : Annonce de fonctionnalite standard (30-60s) — Le plus courant

```
Hook    (0-3s)   Nom/icone de fonctionnalite revelee sur fond de couleur chaude
Context (3-8s)   Presentation du probleme ou du besoin utilisateur
Action  (8-15s)  L'utilisateur declenche une action (clic/saisie)
Demo    (15-45s) Demonstration de produit animee (contenu principal)
Magic   (30-50s) Le systeme complete automatiquement (sequence de taches / visualisation de progression)
Result  (45-55s) Affichage de l'etat final
Close   (55-60s) Logo + fond de couleur chaude en fermeture
```

Applicable : la plupart des lancements de fonctionnalites. Represente ~60% des 77 videos.

#### Mode B : Scan d'ecosysteme (30-50s)

```
Hook  (0-3s)   "[Produit] se connecte a [outil/workflow]"
Setup (3-8s)   Presentation de l'application cible (Slack/Excel/Figma)
Flow  (8-35s)  Alternance entre plusieurs applications, montrant le flux de donnees
Proof (35-45s) Etat final du resultat
Close (45-50s) Logo
```

Applicable : annonces d'integration, presentations de partenaires. Le dispositif visuel cles est l'ecran divise + declenchement par @mention.

#### Mode C : Carte sociale ultra-courte (8-15s)

```
Scene unique : fond de marque + animation de texte / revelation d'icone
Pas de demonstration de produit, pure information de marque / annonce
```

Applicable : promotion d'evenements, courtes annonces, declarations de marque. "Thank You" (8.2s, 12.7M de vues) correspond a ce mode.

#### Mode D : Demo approfondie developpeur (60-90s)

```
Hook        → Le terminal est deja en cours d'execution (narration inversee)
Setup       → L'utilisateur saisit des commandes avancees
Execution   → Sortie terminal + apercu divise
Magic       → Arbre de taches deploye, sous-taches multiples en parallele
Result      → Etat final + interface d'audit/suivi
Close       → Carte de marque
```

Applicable : fonctionnalites techniques orientees developpeurs. Esthetique terminal, polices monospace, coloration de diff de code.

### 3.2 Cinq variantes narratives speciales

| Variante | Video representante | Vues | Technique principale |
|----------|-------------------|------|----------------------|
| Commande et execution | Computer Use | 77.9M | Gauche a droite : telephone → flux de traitement → bureau |
| Revelation de galerie | Claude Design | 63.5M | Revelation progressive de l'abstrait au complexe |
| Narrative terminal | Managed Agents | 21.6M | Raconter une histoire via commandes CLI et sorties |
| Moment de gratitude | Thank You | 12.7M | 8.2s resonance emotionnelle minimaliste |
| Scan d'ecosysteme | Office GA | 27.7M | Presentation successive Excel → PowerPoint → Word |

### 3.3 Regles d'or pour les debuts et fins

**Debut :**
- Pas d'intro logo — le produit est presente dans les 2 premieres secondes
- Les 2 premieres secondes doivent avoir un attrait visuel
- 50% fond de marque + texte en fondu, 30% fenetre UI materialisee

**Fin :**
- Pas de coupe dure vers ecran noir
- Pas de carte CTA de fin traditionnelle (grande majorite)
- Fin avec le contenu ou fond de couleur chaude + logo en fondu sortant
- Renforcement du positionnement de marque "premium, confiant"

---

## 4. Transitions et Grammaire des Animations

### 4.1 Regles de transition

**Regle d'or : coupes dures en priorite, zero transition tape-a-l'oeil.**

| Type de transition | Frequence d'utilisation | Scene |
|-------------------|------------------------|-------|
| Coupe dure | ~60% | Methode principale de changement entre scenes |
| Fondu vers fond chaud | ~15% | Fermeture de marque, changement de rythme |
| Glissement (horizontal/vertical) | ~10% | Deploiement de panneau, barre laterale |
| Animation de dessin | ~5% | Revelation d'icone, connexion de traits |
| Zoom vers l'UI | ~5% | Vue d'ensemble vers detail |
| Dissolution / lent fondu entrant | ~0% | **Jamais utilise** |

Toutes les transitions sont controlees en moins de 2 secondes. Pas de retournement 3D, morphing ou effets de particules.

### 4.2 Vocabulaire d'animation fondamental

**Simulation de curseur (Cursor Simulation)**
```
Timeline :
  -0.46s : Point de depart defini, opacity: 0→1
  -0.38s : Vol vers la cible, ease: power3.out
   0.00s : Arrivee, animation clickPulse
  +0.12s : Leger zoom (yoyo)
  +0.82s : Fondu sortant du curseur
```
Cle : le curseur doit "arriver en avance", pas trainer.

**Sequence de taches (Task Sequence) — Le noyau du Magic Moment**
```
Entree  → Element glisse depuis le bas, opacity: 0→1, 0.28s
Changement de couleur  → Cercle d'etat passe du gris au vert, 0.16s
Coche  → La coche apparait, 0.10s
```
Chaque ligne de tache a son propre timing, peut etre decalée (stagger 0.05s).

**Entree de modale (Modal Entrance)**
```
Depart : y:34, scale:0.965, opacity:0
Animation : y→0, scale→1, opacity→1, 0.42s, ease: back.out(1.35)
```

**Revelation echelonnee (Staggered Reveal)**
```
y:16 → y:0, opacity: 0→1, 0.28s, stagger: 0.05s
```
Utilise pour les listes d'integrations, listes de fichiers, cartes d'outils.

**Animation de dessin (Draw-on)**
```
SVG stroke-dasharray :
  strokeDashoffset: 200 → 0, 0.8s, ease: power2.inOut
```
Usage : griffonne manuscrit reliant deux zones UI, icone de contour vers remplissage.

### 4.3 Regles de mouvement de camera

**Par defaut : image stable, pas de derive continue.**

Le mouvement de camera n'est utilise que pour un objectif narratif precis :
- Pan/zoom global pour se concentrer sur une zone produit, duree 0.3-0.6s
- Zoom sur l'ensemble de l'ecran ou de la zone produit, pas seulement sur un bouton
- Une fois la camera positionnee, elle reste stable pour que le texte UI et l'etat soient lisibles
- Les transitions entre scenes priviligient les coupes dures, changements de calques, animations de contenu entrantes

---

## 5. Architecture Hook (les 3 premieres secondes decident de tout)

### 5.1 Cinq strategies d'ouverture

| Strategie | Technique | Effet | Video representante |
|-----------|-----------|-------|---------------------|
| **Extreme minimalisme** | Espace negatif immense + tres petite icone | Curiosite maximale, taux de retention le plus eleve | Computer Use (77.9M), Design (63.5M) |
| **Revelation de marque** | Fond de couleur chaude + elements en fondu entrant | Retenu, premium, coherent | Majorite des videos de fonctionnalites standard |
| **Produit direct** | Capture UI ou mockup de peripherique direct | Sans detour, oriente efficacite | Cowork Windows, Chrome |
| **Question de douleur** | Le texte pose le probleme de l'utilisateur | Base sur la resonance | "Tired of tedious work?" |
| **Declaration audacieuse** | Declaration de marque ou prise de position | Propagation par la controverse | "Keep Thinking" (5.2M) |

### 5.2 Hooks "moins c'est plus" — Le modele le plus puissant

Les deux videos les plus vues (77.9M et 63.5M) utilisent la meme strategie :

1. Premiere image : un tres petit element sur fond de couleur chaude (icone de curseur / icone de contour)
2. Aucun texte — oblige le spectateur a s'arreter pour "decoder" ce que c'est
3. Deuxieme temps (apres 0.8-1.2s) : revelation du texte du nom de fonctionnalite

**Principe :** Extreme minimalisme → lacune cognitive → curiosite → retention → visionnage complet.

---

## 6. Moteur de Rythme

### 6.1 Regles de duree des scenes

| Type de video | Duree par scene | Sens du rythme |
|---------------|-----------------|----------------|
| Demo de fonctionnalite longue (60-96s) | 4-8s/scene | Mesure, style tutoriel |
| Demo de fonctionnalite moyenne (40-60s) | 3-5s/scene | Vitesse moyenne, style histoire |
| Courte annonce (<20s) | 2-3s/scene | Rapide, percutant |
| Carte sociale courte (<12s) | Scene unique | Minimal |

### 6.2 Relation entre duree et engagement

**Decouverte contre-intuitive : la duree en soi ne determine pas l'engagement.**

- Les videos les plus engageantes font 73s (Computer Use) et 81.5s (Design)
- Une video de 10 secondes a obtenu 10M de vues (Remote Control)
- Une video de 96 secondes n'a eu que 12.5M (Excel/PowerPoint)

**Ce qui determine reellement l'engagement :**
1. Qualite du hook d'ouverture (3 premieres secondes)
2. Universalite de la fonctionnalite (attraction interdisciplinaire)
3. Rythme narratif (pas de longueurs, chaque scene a une densite d'information)
4. Raffinement visuel (4K vs 1080p a une correlation mais pas de causalite)

### 6.3 Position du Magic Moment

**Le Magic Moment doit apparaitre dans les 15 premieres secondes.**

Le Magic Moment est le moment visuel ou "le systeme accomplit quelque chose pour l'utilisateur" — pas un spinner de chargement, mais :
- Taches accomplies ligne par ligne (coches vertes)
- Fichiers generes automatiquement
- Commandes terminal executees de maniere autonome
- Donnees circulant entre plusieurs applications

Si les 15 secondes ne donnent pas un moment "waouh" au spectateur, il scrolle plus loin.

---

## 7. Formules d'Engagement

### 7.1 5 caracteristiques communes des videos a fort engagement

Extrait des donnees de 77 videos :

1. **Resolution 4K** — 3840x2160 fortement correle aux hauts volumes de vues
2. **Ouverture extreme minimaliste** — curiosite qui declenche la retention
3. **Fonctionnalite universelle** — attraction interdisciplinaire, pas seulement pour les developpeurs
4. **Narration rythmee de 70-80 secondes** — les spectateurs regardent la demonstration complete
5. **Composition narrative spatiale/horizontale** — flux visuel de gauche a droite

### 7.2 Facteurs qui ne determinent PAS l'engagement

- La duree en soi (pas plus court = mieux)
- Le ratio d'aspect (paysage et portrait ont des hauts et des bas)
- L'orientation developpeur (Code Review 23.5M)
- Le cout de production (video live 14.6M vs video raffinee 2M)

### 7.3 Niveaux d'engagement

| Niveau | Vues | Proportion | Caracteristiques communes |
|--------|------|-----------|---------------------------|
| Super | 50M+ | ~3% | 4K, ouverture extreme minimaliste, fonctionnalite universelle, narrative spatiale |
| Eleve | 10-30M | ~15% | Production raffinee, demonstration de fonctionnalite claire, narrative forte |
| Moyen | 2-10M | ~40% | Production standard, narrative moyenne |
| Faible | <2M | ~42% | Densite d'information faible ou audience etroite |

---

## 8. Guide des Niveaux de Production

### Tier 1 : Lancement phare (4K, 60-90s)

- **Scene :** Lancement de fonctionnalite majeure, presentation de nouveau produit
- **Caracteristiques :** 3840x2160, mockups de peripheriques composites, animations complexes multi-scenes, musique synchronisee au tempo
- **Cycle de production :** 1-2 semaines
- **Equipe :** Motion designer + UI designer + audio

### Tier 2 : Demonstration de fonctionnalite (1080p, 30-60s)

- **Scene :** Presentation de fonctionnalite unique, annonce d'integration
- **Caracteristiques :** 1920x1080, disposition divisee, 3-5 scenes, musique legere
- **Cycle de production :** 3-5 jours
- **Equipe :** Motion designer

### Tier 3 : Carte sociale courte (1080p ou carree, 8-15s)

- **Scene :** Annonce, promotion d'evenement, information de marque
- **Caracteristiques :** Scene unique, animation de texte principale, pas de demonstration de produit
- **Cycle de production :** 1 jour
- **Equipe :** Motion designer (peut cumuler)

### Tier 4 : Communaute live (qualite brute, illimitee)

- **Scene :** Hackathon, evenement communautaire, demonstration de produit reelle
- **Caracteristiques :** Post-production minimale, presence humaine, capture d'ecran brute
- **Cycle de production :** Meme jour
- **Equipe :** Personnel produit/ingenierie enregistre lui-meme

---

## 9. Liste des Anti-Patterns

Extrait de l'analyse de 78 videos — ce que Claude n'a PAS fait et que vous ne devriez pas faire :

1. **Pas d'entree logo-only** — le produit ou la promesse de fonctionnalite doit apparaitre dans les 2 premieres secondes
2. **Pas de carte CTA de fin** — terminer avec le contenu/l'etat du produit ou un simple signe de marque
3. **Pas de transition tape-a-l'oeil** — coupes dures, changements de calques, animations de contenu entrantes en priorite
4. **Pas de fond degrade decoratif** — le canevas reste retenu, le produit est la vedette
5. **Pas de presence humaine sauf necessite** — 1 seule video sur 78 a un visage humain
6. **Pas d'enregistrement d'ecran reel** — reconstruire une UI parfaite, eliminer tout le bruit
7. **Pas de vide dans le processus de generation IA** — il faut visualiser task / progress / preview
8. **Pas de texte marketing vague** — utiliser de vrais noms de fonctionnalites et etiquettes de produit
9. **Pas de derive continue de camera** — seulement des pan/zoom courts et precis
10. **Pas de zoom sur un seul bouton** — zoomer sur l'ensemble de l'ecran ou de la zone produit

---

## 10. Analyse d'Evolution Temporelle : Volume de vues multiplie par 18 en 8 mois

### 10.1 Panorama des donnees

| Periode | Nombre de videos | Vues moyennes | Vues maximales | Total vues |
|---------|-----------------|---------------|----------------|------------|
| 2025 T4 | 21 | **0.7M** | 2.7M | 14M |
| 2026 T1 | 41 | **9.1M** | 77.9M | 373M |
| 2026 T2 | 15 | **12.6M** | 63.5M | 190M |

Le volume moyen de vues a ete multiplie par 18 en 8 mois. Ce n'est pas un coup de chance avec un hit — c'est une methodologie qui s'itere.

### 10.2 Trois phases de transformation qualitative

#### 2025 T4 — "Nous savons faire des videos"

Periode de demarrage. Production grossiere mais etablissement du langage de base :
- Fenetres d'applications flottantes sur fond de marque (comme des animations PPT)
- Couleur terracotta + mode sombre etablis comme standard
- Titres serif + casing de phrase avec point
- Presence humaine dans 1 seule video (ingenieur Opus 4.5)
- Vues maximales 2.7M (Claude Code on Web)

**Caracteristique : securite — toutes les videos se ressemblent, comme si elles etaient faites a partir d'un template.**

#### 2026 T1 — "Formule de hit trouvee"

Phase de transformation qualitative :
- Evolution des fenetres flottantes vers les **mockups de peripheriques 3D** (telephone/ordinateur portable/moniteur composites sur fond de couleur chaude)
- La philosophie de marque "Keep Thinking" emerge — vendre une attitude plutot qu'une fonctionnalite
- La serie Cowork definit la narration "flux de travail IA pour non-techniciens"
- **Deux hits d'envergure evenementielle :** Lancement Cowork (49.7M), Computer Use (77.9M)
- Video sur la securite 26.2M — le mot "securite" a un pouvoir de propagation intrinseque
- Videos live (demo Cowork, 14.6M) prouvent que le "realisme" est plus puissant que le "raffinement"

**Decouverte cle : ce n'est pas la production qui est plus raffinee, c'est la narrative qui est plus forte.**

#### 2026 T2 — "Moins c'est plus" est verifie

L'evolution de la derniere phase est une soustraction :
- L'ouverture extreme minimaliste devient le Hook le plus puissant (Computer Use avec seulement une icone de curseur + vaste espace vide)
- Claude Design (63.5M) s'ouvre avec une icone de palette de contour, ne dit pas ce que c'est tout de suite
- La narrative spatiale murit : flux visuel de gauche a droite (telephone → traitement → bureau)
- Les connecteurs griffonnes a la main deviennent un element signature
- Office GA (27.7M) presente la narration "scan d'ecosysteme"

**Comprehension centrale : moins on donne d'information dans les 2 premieres secondes, plus longtemps le spectateur reste.**

### 10.3 Evolution de la position narrative

```
T4 2025 : "Regardez, Claude peut faire X"           → Explicative
T1 2026 : "Imaginez, il suffit de dire une phrase"   → Demonstrative
T2 2026 : "(montre en silence, ne dit rien)"          → Implicative
```

De "explicative" a "demonstrative" a "implicative" — l'energie de marque augmente, les videos deviennent de plus en plus silencieuses.

### 10.4 Analyse du rythme de publication : strategie de publication en impulsions

**Donnees globales : 77 videos, 222 jours, en moyenne 1 tous les 2.9 jours.**

Mais la "moyenne" est trompeuse — les publications d'Anthropic ne sont pas uniformement distribuees, mais suivent un rythme d'impulsions denses + longs intervalles.

#### Distribution mensuelle

| Mois | Nombre de videos | Caracteristique |
|------|-----------------|-----------------|
| 2025-10 | 5 | Demarrage, 1 par semaine |
| 2025-11 | 5 | Stable, 1 par semaine |
| 2025-12 | 11 | Acceleration, sprint de fin d'annee |
| 2026-01 | 9 | Stable et legerement eleve |
| 2026-02 | **23** | **Mois d'explosion — 30% du total** |
| 2026-03 | 9 | Repli mais niveau eleve maintenu |
| 2026-04 | 10 | Stable |
| 2026-05 | 5 | Debut du mois (donnees jusqu'au 10 mai) |

**Fevrier 2026 est le point de rupture cles** — 23 videos en un mois, 30% des 77 au total. Ce n'est pas un hasard : lancement Opus 4.6, mise en ligne Sonnet 4.6, promotion intensive de la serie Cowork, evenements hackathon concentres dans ce mois.

#### Seulement 51 jours avec publication sur 222 jours

Cela signifie que **77% des jours sont des "jours vides"** — aucune video publiee. La densite de publication n'est pas lineaire, mais impulsionnelle.

#### Trois campagnes de publication intensive

| Campagne | Periode | Jours | Videos | Contenu cles |
|----------|---------|-------|--------|-------------|
| Semaine de lancement Opus 4.6 | 2-6 fevrier | 5 jours | 9 | Opus 4.6, Sonnet 4.6, matrice de fonctionnalites |
| Semaine promotion Cowork | 17-20 fevrier | 3 jours | 10 | Serie fonctionnalites Cowork, demos live, 7 videos le 20/02 |
| Semaine phare T1 | 23-25 mars | 3 jours | 3 | Computer Use (77.9M), Design (63.5M), total 93.1M |

**La troisieme campagne est la plus extreme** — 3 videos en 3 jours, mais 93.1M de vues au total. Verification parfaite de qualite > quantite.

#### Plus longs intervalles

| Intervalle | Duree | Periode |
|------------|-------|---------|
| Le plus long | 28 jours | 2025-10-28 → 2025-11-25 |
| Deuxieme | 19 jours | 2025-12-29 → 2026-01-17 |
| Troisieme | 14 jours | 2025-11-11 → 2025-11-25 |

Ces longs intervalles apparaissent en debut de periode (T4 2025), indiquant que l'equipe cherchait encore son rythme. En T1-T2 2026, le plus long intervalle se reduit a 7-10 jours.

#### Logique sous-jacente de la strategie impulsionnelle

```
Periode normale : 1-2 videos par semaine, maintien de la presence de marque
         ↓
Lancement de produit : 3-5 jours denses, 2-3 videos par jour, creation de densite informationnelle
         ↓
Periode de refroidissement : retour au rythme normal
```

**Pourquoi utiliser des impulsions plutot qu'une distribution uniforme ?**

1. **Effet d'algorithme** — les algorithmes des plateformes sociales recompensent la "concentration thematique", plusieurs videos en peu de temps = poussees dans plus de fils d'actualite
2. **Densite narrative** — une grande fonctionnalite presentee sous 3-5 angles differents couvre plus qu'une seule video
3. **Rythme d'equipe** — la production video est un travail par lots, faire un lot entier d'un coup est plus efficace qu'un peu chaque jour
4. **Perception utilisateur** — "Claude est partout recemment" a plus d'impact que "stablement un par semaine"

**Lecon pratique :** Ne cherchez pas a publier une video par jour. Accumulez un lot, publiez-le de maniere intensive sur 3-5 jours, puis revenez a un rythme calme. Impulsion > Uniforme.

#### Analyse du moment de publication (precision a l'heure, fuseau PST)

Extraction de l'heure precise a partir des snowflake IDs des 77 tweets, statistiques en heure normale du Pacifique (PST) :

**Distribution par tranche horaire (PST) :**

| Tranche (PST) | Videos | Vues moyennes | Signification |
|---------------|--------|---------------|---------------|
| 0h-6h du matin | 10 | **13.1M** | Publication programmee a l'avance |
| 6h-9h du matin | 33 | 6.3M | **Fenetre de publication principale** (43% des videos) |
| 9h-12h matin | 24 | 8.4M | Fenetre secondaire |
| 12h-15h apres-midi | 10 | 3.8M | Publications en queue |

**Les 77 videos sont toutes concentrees dans les 10 heures PST 04:00-14:00.** Apres 15h, zero publication.

**Distribution precise par heure :**

| Heure (PST) | Videos | Vues moyennes | Videos representantes |
|-------------|--------|---------------|----------------------|
| **05:00** | **9** | **12.9M** | Design 63.5M, Financial Services 13.5M |
| **08:00** | **18** | 7.2M | Office GA 27.7M, Cowork GA |
| 07:00 | 9 | 6.0M | Managed Agents 21.6M |
| 09:00 | 11 | 3.0M | Code Review 23.5M |
| 10:00 | 8 | 10.3M | Thank You 12.7M |
| **11:00** | **5** | **17.1M** | Computer Use 77.9M, Hackathon |
| 13:00 | 8 | 3.4M | Excel 23.4M |
| Autres | 9 | 5.1M | Reparties sur 04/06/12h |

**Trois pics de publication :**

| Pic | Heure PST | Videos | Vues moyennes | Caracteristique |
|-----|-----------|--------|---------------|-----------------|
| **Premiere vague matinale** | 05:00-06:00 | 15 | 10.0M | Vues moyennes les plus elevees, videos phares souvent publiees ici |
| **Pic de bureau** | 08:00-09:00 | 29 | 5.4M | Plus dense en quantite, mises a jour de fonctionnalites quotidiennes concentrees ici |
| **Queue de matinee** | 10:00-11:00 | 13 | 12.9M | Encore des videos a haut volume, possible "deuxieme choix" de creneau |

**Interpretation :**

1. **05:00 PST = heure de debut en Europe** — Publier a ce moment couvre les deux cotes de l'Atlantique : la cote ouest americaine est encore en pleine nuit, mais l'Europe (CET 14:00) est en plein apres-midi actif. Les 9 videos publiees a 05:00 atteignent 12.9M de moyenne, **incluant deux videos de 50M+**, ce qui montre que la programmation a l'avance laisse le contenu fermenter en Europe avant de refluer aux Etats-Unis.

2. **08:00 PST = heure de debut aux Etats-Unis** — Fenetre de publication la plus dense (18 videos), pile au debut de la journee de travail sur la cote est a 11h et la cote ouest a 8h. C'est le creneau de publication "standard".

3. **11:00 PST = avant dejeuner** — Vues moyennes les plus elevees (17.1M) mais seulement 5 videos. Ce creneau est peut-etre utilise comme "deuxieme fenetre" pour les lancements majeurs — si le lancement matinal est rate, la publication en fin de matinee reste efficace.

4. **Quasi-zero publication l'apres-midi** — Apres 13h, seulement quelques videos eparses, zero apres 14h. Cela indique que l'equipe video d'Anthropic travaille principalement le matin.

**Lecons pratiques :**
- **Lancement phare** : programmer a 05:00 PST (couverture marche europeen et americain)
- **Mises a jour quotidiennes** : PST 08:00-09:00 (pic de bureau americain)
- **Eviter la publication l'apres-midi** : apres 14h, quasi personne ne regarde
- **Si l'objectif est le marche asiatique** : 05:00 PST = 21h heure de Beijing, 22h Tokyo, pile dans la plage horaire doree du soir

---

## 11. Analyse de Viralite : Pourquoi le Top 10 explose

### 11.1 Vue d'ensemble du Top 10

| # | Video | Vues | Duree | En une phrase |
|---|-------|------|-------|---------------|
| 1 | Computer Use | 77.9M | 73s | "L'IA peut utiliser votre ordinateur" |
| 2 | Claude Design | 63.5M | 82s | "Parler pour faire du design" |
| 3 | Lancement Cowork | 49.7M | 69s | "Les non-programmeurs aussi peuvent utiliser l'IA" |
| 4 | Office GA | 27.7M | 87s | "IA dans Excel/Word/PPT" |
| 5 | Code Security | 26.2M | 50s | "L'IA trouve vos failles de securite" |
| 6 | Code Review | 23.5M | 45s | "Revue automatique de PR" |
| 7 | Lancement Excel | 23.4M | 44s | "Demandez directement a l'IA dans Excel" |
| 8 | Managed Agents | 21.6M | 59s | "L'IA gere l'IA" |
| 9 | Computer Use (Code) | 16.1M | 45s | "L'IA opere seule en CLI" |
| 10 | Mise a jour Cowork | 14.6M | 120s | "Collaboration equipe IA en entreprise" |

### 11.2 Cinq lois de viralite

#### Loi 1 : Contenu > Production

**Les mots cles des hits sont "nouvelles possibilites", pas "mise a jour de fonctionnalite".**

- Le Top 10 est entierement compose de "Introducing..." ou "You can now..." — **premiere annonce**
- Le Bottom 10 est entierement compose de "now available on...", "is now in beta" — **extension d'une fonctionnalite existante**

| Type de contenu | Vues moyennes | Exemples |
|----------------|---------------|----------|
| Premiere de nouveau produit/capacite | **30M+** | Computer Use, Design, Cowork |
| Mise a jour majeure de fonctionnalite | **5-15M** | Code Review, Security |
| Extension de plateforme / partenariat | **1-5M** | Excel on Pro, Chrome |
| Mise a jour incrementielle / petite fonctionnalite | **<1M** | Skills Dir, /stats, guest passes |

**Les gens paient pour une "nouvelle espece", pas pour une "mise a jour de version".**

#### Loi 2 : La taille de l'audience determine le plafond

Les fonctionnalites du Top 10 sont universelles et interdisciplinaires :
- Computer Use (77.9M) — tout le monde comprend "l'IA opere votre ordinateur"
- Cowork (49.7M) — l'audience est dix fois celle de Claude Code
- Office GA (27.7M) — les utilisateurs Office du monde entier

Le Bottom 10 concerne des fonctionnalites de niche :
- Skills Directory (77K) — seuls les utilisateurs existants s'y interessent
- Guest Passes (62K) — seuls les utilisateurs Max s'y interessent
- Commande /stats (70K) — seuls les utilisateurs CLI s'y interessent

**Un sujet qui n'a de sens que pour 1 million de personnes, meme avec une production superbe, ne peut pas rivaliser avec un sujet qui a du sens pour 100 millions de personnes.**

#### Loi 3 : 60-80 secondes est le point ideal

| Intervalle de duree | Proportion du Top 10 | Caracteristique |
|--------------------|---------------------|-----------------|
| 40-50s | 3/10 | Focus fonctionnalite, demo rapide |
| 60-80s | 4/10 | Narrative complete, avec Demo et Magic |
| 80-90s | 2/10 | Presentation d'ecosysteme, chaine multi-produits |

**Pas plus court = mieux.** Le Bottom 10 fait en moyenne 35 secondes, le Top 10 fait 67 secondes. Le probleme des videos courtes n'est pas qu'elles sont "trop courtes", mais que la "densite informationnelle est trop faible" — 35 secondes pour dire "now available on Android", sans demo valable.

#### Loi 4 : Emotion > Fonctionnalite (parfois)

**Le taux de likes le plus eleve (likes/vues) n'est pas dans le Top, mais dans le Bottom.**
- Taux de likes moyen du Top 10 : 0.22%
- Taux de likes moyen du Bottom 10 : 0.60%

Car les videos du Bottom touchent les utilisateurs cles — ils suivent deja @claudeai, donc naturellement likent. Le Top touche le grand public — en majorite des passants.

Mais il y a une exception : **"Thank You" (8.2s, 12.7M, taux de likes 0.38%)**. Le contenu est une seule phrase "les deux prochaines semaines, utilisation en heures de pointe doublee". Pas de nouvelle fonctionnalite, juste un merci.

**"Etre remercie" est une experience rare.** La plupart des entreprises publient des videos "regardez la nouvelle fonctionnalite", Anthropic a dit "merci".

#### Loi 5 : Live > Raffine (parfois)

La demo live Cowork (14.6M) est la video la plus grossierement produite — une vraie personne enregistre son ecran dans une chambre. Mais son volume de vues depasse beaucoup de videos 4K raffinees.

**Dans un fil d'actualite compose de mockups parfaits, quelque chose de "reel" est rare.** Il ne s'agit pas d'arreter de faire des videos raffinees — mais d'intercaler occasionnellement du contenu live pour creer une reaction chimique.

### 11.3 Priorite des facteurs de viralite

Classe par impact :
1. **Contenu "nouvelle espece"** — premiere annonce d'une capacite entierement nouvelle
2. **Taille de l'audience** — plus de gens peuvent comprendre, mieux c'est
3. **Ouverture extreme minimaliste** — moins d'information dans les 2 premieres secondes, mieux c'est
4. **Rythme de 60-80 secondes** — assez pour se deployer, sans trainer
5. **Declencheur emotionnel** — dire "merci" occasionnellement est plus puissant que dire "regardez la fonctionnalite"
6. **Intercale du realisme** — mettre une video live dans un flux de videos raffinees


## 12. Analyse Multi-Dimensionnelle Axee sur les Donnees

Avec les donnees structurees de 77 videos, analyse croisee sur 7 dimensions : taux d'engagement, resolution, duree, jour de publication, mots cles de contenu, viralite, utilite — pour extraire les regles des donnees du marketing video d'Anthropic.

### 12.1 Dimension taux d'engagement : qui participe vraiment

Taux d'engagement = nombre d'interactions / volume de vues. Plus revelateur que les valeurs absolues car il filtre le bruit du "l'algorithme pousse au grand public mais le grand public reste indifferent".

| Indicateur | Formule | Signification |
|-----------|---------|---------------|
| Taux de likes | likes / vues | Reconnaissance immediate |
| Taux de favoris | bookmarks / vues | "C'est utile, je veux le revoir plus tard" |
| Taux de retweets | retweets / vues | "Je veux que d'autres voient" |
| Taux de reponses | replies / vues | "Je veux en discuter" |

**Decouverte cle : Haut volume de vues != Haut taux d'engagement.**

- Le **taux de favoris le plus eleve** n'est pas dans les hits, mais dans le contenu developpeur : Built with Opus 4.6 (0.47%), Conference Code with Claude (0.35%), Hackathon (0.34%), Agent View (0.32%)
- Le **taux de reponses le plus eleve** est aussi oriente niche : Claude Code executable (0.045%), Claude for Public (0.041%)
- Le **taux de likes le plus eleve** est pour le contenu lie a Opus 4.6 (1.46%) et l'anniversaire de Claude Code (1.19%)

**Interpretation :** Le groupe des developpeurs, bien que moins nombreux, a une profondeur de participation bien superieure au grand public. Taux de favoris eleve = "c'est un outil, je vais l'utiliser". Cela montre que les videos de Claude servent simultanement deux groupes : le grand public pour le volume de vues, les utilisateurs cles pour la profondeur d'engagement.

### 12.2 Dimension resolution : 4K a une correlation mais pas de causalite

| Resolution | Videos | Vues moyennes | Vues maximales |
|-----------|--------|---------------|----------------|
| 3840x2160 (4K) | 16 | 9.2M | 77.9M |
| 1920x1080 (1080p) | 40 | 8.5M | 63.5M |
| Autres resolutions | 21 | 1.7M | 26.2M |

- L'ecart entre 4K et 1080p en vues moyennes est faible (9.2M vs 8.5M)
- **La deuxieme video la plus vue (Design, 63.5M) est en 1080p, pas en 4K**
- Les "autres resolutions" n'atteignent en moyenne que 1.7M — mais c'est parce qu'elles sont en majorite des videos anciennes ou des formats speciaux (portrait, carre)

**Pratique :** Privilegier le 4K, mais si les ressources sont limitees, le 1080p ne penalise pas significativement les performances. Ce qui compte vraiment est la qualite du contenu et de la narrative, pas le nombre de pixels.

### 12.3 Dimension duree : 60-90 secondes est le point ideal

| Intervalle de duree | Videos | Vues moyennes | Taux de likes | Taux de favoris |
|--------------------|--------|---------------|---------------|-----------------|
| <15s | 13 | 3.0M | 0.56% | 0.17% |
| 15-30s | 7 | 1.9M | 0.54% | 0.20% |
| 30-60s | 27 | 7.3M | 0.43% | 0.15% |
| **60-90s** | **19** | **15.6M** | **0.48%** | **0.13%** |
| >90s | 11 | 2.9M | 0.55% | 0.19% |

**Les vues moyennes de 60-90 secondes (15.6M) sont 2 a 8 fois superieures a tous les autres intervalles.**

Mais l'intervalle >90s chute a 2.9M. Cela signifie :
- Trop court (<30s) : densite informationnelle insuffisante, pas de Demo complete → vues faibles
- 60-90s : assez pour deployer une narrative complete (Hook → Demo → Magic → Result) → vues les plus elevees
- Trop long (>90s) : declin de l'attention, sauf si le contenu est particulierement dense → vues en baisse

**Le taux de favoris diminue avec la duree** : les videos courtes ont un taux de favoris plus eleve (<15s a 0.17%, 60-90s seulement 0.13%). Video courte = consommation rapide, video longue = on regarde et on part, pas de favori.

### 12.4 Dimension jour de publication : Lundi et Vendredi les plus forts

| Jour | Videos | Vues moyennes | Total vues |
|------|--------|---------------|------------|
| **Lundi** | **15** | **12.6M** | **189.5M** |
| Mardi | 17 | 5.5M | 93.6M |
| Mercredi | 16 | 4.7M | 74.8M |
| Jeudi | 13 | 5.1M | 65.9M |
| **Vendredi** | **15** | **9.4M** | **141.0M** |
| Samedi | 1 | 12.7M | 12.7M |

- **Lundi : vues moyennes les plus elevees (12.6M)** — premier jour ouvrable apres le weekend, activite utilisateur elevee
- **Vendredi : deuxieme (9.4M)** — possible correlation avec le mode de propagation "publication vendredi, fermentation le weekend"
- Samedi : seulement 1 video (Thank You, 12.7M), echantillon trop petit pour conclure
- Mardi a Jeudi : relativement plats

**Pratique :** Lancements majeurs le lundi ou vendredi. Mises a jour regulieres de mardi a jeudi pour maintenir la presence.

### 12.5 Dimension mots cles de contenu : quels sujets ont un pouvoir de propagation intrinseque

| Mot cle | Signification | Videos | Vues moyennes |
|---------|--------------|--------|---------------|
| **Introducing** | **Annonce de premiere** | **9** | **23.6M** |
| Design | Design | 5 | 19.7M |
| Cowork | Cowork/Entreprise | 10 | 17.7M |
| Excel | Excel/Office | 4 | 16.1M |
| Security | Securite | 2 | 15.5M |
| Claude Code | Outils developpeur | 26 | 9.9M |
| can now | Extension de capacite | 16 | 7.9M |
| Agent | Lie a Agent | 11 | 7.6M |
| now available | Fonctionnalite en ligne | 8 | 4.6M |

**"Introducing" est la garantie absolue de vues** — 23.6M en moyenne, 5 fois "now available" (4.6M).

Cela confirme la decouverte du Chapitre 11 : **Premiere annonce >> Extension de fonctionnalite**. "Introducing" implique "nouvelle espece", "now available" implique "ancien objet dans un nouvel endroit".

**Classement d'attraction des sujets :**
1. Design (19.7M) — interdisciplinaire, les utilisateurs non-techniques s'y interessent aussi
2. Cowork (17.7M) — "les non-programmeurs peuvent aussi utiliser l'IA", audience tres large
3. Excel (16.1M) — base d'utilisateurs Office mondiale
4. Securite (15.5M) — "securite" porte un sentiment d'anxiete et d'attention intrinseque
5. Claude Code (9.9M) — reserve aux developpeurs, audience etroite mais fidelite elevee

### 12.6 Viralite vs Utilite : deux signaux radicalement differents

**Taux de retweet eleve = "Je veux que d'autres voient" (viralite)**

| Rang | Contenu | Taux de RT | Vues |
|------|---------|-----------|------|
| 1 | Claude for Public | 0.098% | 0.1M |
| 2 | Conference Code with Claude | 0.094% | 1.1M |
| 3 | Anniversaire Claude Code | 0.078% | 0.8M |
| 4 | Built with Opus 4.6 | 0.077% | 1.0M |
| 5 | Ads are coming to AI | 0.076% | 5.2M |

**Taux de favoris eleve = "C'est utile, je vais l'utiliser plus tard" (utilite)**

| Rang | Contenu | Taux de favoris | Vues |
|------|---------|----------------|------|
| 1 | Built with Opus 4.6 | 0.47% | 1.0M |
| 2 | Conference Code with Claude | 0.35% | 1.1M |
| 3 | Hackathon | 0.34% | 1.6M |
| 4 | Oeuvre Crossbeam | 0.32% | 0.5M |
| 5 | Agent View | 0.32% | 2.3M |

**Decouverte :** Les taux de retweet et de favoris les plus eleves concernent presque exclusivement le contenu developpeur de niche, pas les hits grand public. Cela signifie :
- Les hits grand public (77.9M Computer Use) n'ont pas des taux de retweet et de favoris exceptionnels — les gens ont regarde, ete eblouis, puis sont passes
- Le contenu developpeur (0.1M-2M) a les taux de retweet et de favoris les plus eleves — les gens ont regarde, mis en favoris, retransmis a leurs collegues

**Deux mesures de succes :**
- **Exposition de marque** : regarder le volume de vues et le volume absolu de retweets → Computer Use (77.9M, 14 467 rt)
- **Impact profond** : regarder le taux de favoris et le taux de reponses → Agent View (0.32% bm, 686 reponses)

### 12.7 Score d'engagement composite : evaluation ponderee

Attribuer des poids differents aux comportements d'engagement (favoris = 3x, reponses = 5x, retweets = 2x, likes = 1x), calculer le score d'engagement composite :

```
Score composite = (likes + bookmarks×3 + retweets×2 + replies×5) / views × 100
```

**Top 5 engagement composite :**

| Rang | Contenu | Score composite | Vues | L | B | RT | R |
|------|---------|----------------|------|---|---|----|---|
| 1 | Built with Opus 4.6 | 2.70% | 1.0M | 9.9K | 4.9K | 800 | 370 |
| 2 | Conference Code with Claude | 2.39% | 1.1M | 10.8K | 3.9K | 1,057 | 460 |
| 3 | Agent View | 2.13% | 2.3M | 20.3K | 7.3K | 1,571 | 686 |
| 4 | Anniversaire Claude Code | 2.04% | 0.8M | 9.7K | 1.4K | 641 | 310 |
| 5 | Hackathon | 2.01% | 1.6M | 10.7K | 5.5K | 937 | 622 |

**Regle :** Le contenu au score composite le plus eleve partage un trait commun — oriente vers les developpeurs ou les evenements communautaires. Leur volume de vues n'est pas eleve (0.8M-2.3M), mais chaque personne qui les voit participe en profondeur.

**Cela offre deux voies a la strategie marketing :**
1. **Voie large** : faire des videos de fonctionnalites universelles, chercher le volume de vues et l'exposition de marque (Computer Use, Design, Cowork)
2. **Voie profonde** : faire du contenu developpeur/communaute, chercher le taux de favoris et le volume de discussion (Agent View, Hackathon, Built with Opus 4.6)

Les deux voies doivent coexister — la largeur attire les nouveaux, la profondeur retient.


## 13. Comparaison des Strategies Video des Concurrents

### 13.1 Differences de langage video entre les quatre grandes entreprises d'IA

| Dimension | Anthropic (Claude) | OpenAI (ChatGPT) | Google (Gemini) | Apple (Apple Intelligence) |
|-----------|-------------------|------------------|----------------|--------------------------|
| **Couleur principale** | Blanc chaud + terracotta | Bleu froid + degrade noir | Blanc + multicolore | Noir pur + blanc pur |
| **Ton** | Academique, chaleureux, reflechi | Technologique, cool, avant-gardiste | Dynamique, amical, grand public | Minimaliste, haut de gamme, retenu |
| **Strategie typographique** | Titres serif (sensation d'edition) | Sans-serif (sensation technologique) | Google Sans (sensation de marque) | SF Pro (sensation systeme) |
| **Presentation UI** | Mode sombre constant | Mixte clair/sombre | Principalement clair | Suit le systeme |
| **Presence humaine** | Tres rare (1/78) | Occasionnelle | Frequente | Jamais |
| **Style narratif** | Retenu, montrer > raconter | Explicatif, sensation de tutoriel | Vie quotidienne, pilote par les scenes | Le produit est la narrative |
| **Style de transition** | Coupes dures en priorite | Degrad + coupes dures | Animations dynamiques | Coupes dures precises |
| **Fin** | Pas de CTA, fondu sortant | Parfois avec CTA | Avec CTA | Carte de marque |

### 13.2 Interpretation de la strategie de differentiation de Claude

**Pourquoi choisir les couleurs chaudes ?**
Le langage visuel par defaut des produits d'IA est froid (bleu/noir) — transmettant une "sensation technologique" et une "intelligence". Anthropic fait le contraire : les couleurs chaudes transmettent la "reflexion", l'"academique", l'"humaniste". Ce n'est pas une preference esthetique, c'est l'expression visuelle du positionnement de marque : Claude est "l'IA qui reflechit", pas "la machine qui calcule".

**Pourquoi presque jamais de presence humaine ?**
1 seule video sur 78 a un visage humain. Raison :
- La presence humaine distrait — les spectateurs commencent a s'interesser a "cette personne" plutot qu'a "cette fonctionnalite"
- L'UI / le texte / l'animation peuvent porter la personnalite de la marque
- Pas de presence humaine = scalabilite illimitee — independant des changements de personnel
- Exception : quand il faut une "transfert de confiance" (ingenieur presentant Opus 4.5), on introduit une presence humaine

**Pourquoi pas de CTA de fin ?**
Le marketing video traditionnel utilise un CTA ("Inscrivez-vous maintenant !") pour creer un sentiment d'urgence. Claude ne l'utilise pas :
- Le CTA est un signal de "vous avez besoin du spectateur" — reduit l'energie de marque
- Le fondu vers le logo = "notre produit parle de lui-meme" — augmente l'energie de marque
- C'est un **signal de rarete** : moins on vous sollicite, plus vous voulez regarder

### 13.3 "Keep Thinking" comme philosophie de marque

"Keep Thinking" n'est pas qu'un slogan, c'est la logique sous-jacente de toute la strategie video :
- Pas d'intro logo → "Nous n'avons pas besoin de nous presenter"
- Pas de CTA de fin → "Nous n'avons pas besoin de vous convaincre"
- UI en mode sombre → "Nous travaillons dans un environnement serieux"
- Ouverture minimaliste → "Nous vous donnons l'espace pour reflechir"
- Animation retenue → "Nous n'interferons pas avec votre jugement"

Chaque decision de production remonte a cette philosophie de marque. C'est le niveau le plus eleve de la methodologie — pas le "comment faire", mais le "pourquoi faire ainsi".

---

## 14. Psychologie de l'Engagement : Pourquoi ces modeles fonctionnent

### 14.1 Principe de lacune cognitive du "moins c'est plus"

Les deux videos les plus vues (77.9M et 63.5M) utilisent une ouverture extreme minimaliste. Principe :

```
Image minimaliste → Information insuffisante → Lacune cognitive → Le comble automatiquement → Curiosite → Retention de visionnage
```

C'est l'application de la **theorie de la lacune informationnelle (Information Gap Theory)** :
- Le cerveau deteste les modeles incomplets
- Quand l'image n'a qu'une tres petite icone + vaste espace vide, le cerveau est force de travailler pour "comprendre" cette image
- Cet investissement cognitif cree une connexion emotionnelle — le spectateur a deja "investi" son attention, il ne veut pas abandonner

**Pratique :** Mettre un seul element dans la premiere image, pas de texte. Reveler le texte apres 0.8-1.2s.

### 14.2 Construction de confiance par la "visualisation du processus"

Pourquoi visualiser le processus (liste de taches, sortie terminal) obtient-il un engagement plus eleve que la simple presentation du resultat ?

- **Transparence = Confiance** : montrer ce que l'IA "est en train de penser" est plus convaincant que de simplement dire "j'ai fini"
- **Satisfaction retardee** : le spectateur voit la barre de progression avancer, creant un sentiment d'anticipation de "bientot termine"
- **Verifiabilite** : la sortie terminal, le diff de code donnent au spectateur le sentiment que "c'est reel, pas une demo"

**Pratique :** Ne pas sauter le processus de generation. Utiliser la Task Sequence, les indicateurs de progression, le defilement terminal pour visualiser.

### 14.3 Instinct de lecture de la "narrative spatiale"

Pourquoi le flux visuel de gauche a droite (telephone → traitement → bureau) fonctionne-t-il ?

- La direction de lecture du texte horizontal est de gauche a droite (anglais/chinois horizontal)
- Le cerveau interprete "gauche a droite" comme une "relation causale" ou un "ecoulement du temps"
- Cette ligne temporelle implicite reduit la charge cognitive — pas besoin d'expliquer supplementairement "quoi faire en premier, quoi faire ensuite"

**Pratique :** Quand il y a plusieurs etapes, utiliser une disposition spatiale de gauche a droite pour suggerer le flux, plutot que des numeros ou des fleches.

### 14.4 Effet psychologique des coupes dures

Pourquoi Claude utilise-t-il presque exclusivement des coupes dures, sans jamais de dissolution lente / degrad ?

- **Coupe dure = Confiance** : pas de trainage, implication que "chaque image merite de s'arreter"
- **Dissolution = Incertitude** : la dissolution implique que "cette image ne merite pas de s'arreter, passons vite"
- **Sens du rythme** : les coupes dures creent un sentiment de tempo, comme les coups de batterie dans la musique
- **Modernite** : la dissolution lente est une esthetique des annees 2000 — l'utiliser aujourd'hui semble daté

---

## 15. Strategie Audio / Bande Sonore

### 15.1 Solutions audio pour cinq types de videos

| Type de video | Style de bande sonore | Voix | Reference |
|---------------|----------------------|------|-----------|
| Animation rythmee | Electronique/percussion synchronisee au tempo | Non | Lancement Cowork (49.7M) |
| Demonstration de produit | Musique d'ambiance legere | Non ou voix off | Majorite des videos de fonctionnalites |
| Terminal/developpeur | Minimale ou silencieuse | Non | Agent View, Managed Agents |
| Declaration de marque | Ton unique ou silencieuse | Possible | "Keep Thinking" |
| Live/presence humaine | Narration vocale | Oui | Demo live Cowork |

### 15.2 Principes de production audio

1. **Conserver la version muette** — finaliser d'abord la version purement visuelle sans bande sonore, puis superposer la musique separement
2. **La musique ne doit pas eclipser l'image** — la bande sonore renforce le rythme, ne dirige pas la narrative
3. **Fondu entrant/sortant en debut et fin** — eviter que la musique ne commence/s'arrete brutalement
4. **Alignement au tempo** — les changements de scene des videos rythmees doivent tomber sur les temps de la musique
5. **Regardable en muet** — la majorite des lectures sur les plateformes sociales se font en silence, la video doit transmettre l'information meme sans son

---

## 16. Liste de Verification Pratique

### 16.1 Verification pre-production

- [ ] Type de video determine (Mode A/B/C/D)
- [ ] Budget de duree fixe
- [ ] Canal cible et ratio d'aspect confirmes
- [ ] Strategie d'ouverture choisie (extreme minimaliste / revelation de marque / produit direct / question de douleur)
- [ ] Formuler en une phrase "ce que le spectateur doit ressentir en regardant cette video"

### 16.2 Verification en production

- [ ] Toutes les UI sont des versions parfaites reconstruites, pas des captures d'ecran reelles
- [ ] UI non pertinente eliminee : cadres de debug, onglets supplementaires, barres de notification inutiles
- [ ] Les 2 premieres secondes ont un attrait visuel
- [ ] Le Magic Moment apparait dans les 15 premieres secondes
- [ ] Graisses limitees a 500/600/700, avec `font-synthesis: none`
- [ ] Titres en casing de phrase avec point
- [ ] Pas d'intro logo
- [ ] Deplacement du curseur naturel (arrive en avance)
- [ ] Pas de derive continue de camera
- [ ] Pas de zoom sur un seul bouton

### 16.3 Verification post-production

- [ ] Pas de carte CTA de fin
- [ ] Pas de coupe dure vers ecran noir
- [ ] Derniere image avec la marque visible
- [ ] L'information est transmissible en muet
- [ ] La version avec musique conserve la version muette originale
- [ ] Export multi-resolutions (4K + 1080p)
- [ ] Export multi-formats (16:9 + 4:5 ou 1:1)

### 16.4 Strategie de publication

- [ ] X/Twitter : 16:9 ou 1:1, les 3 premieres secondes decident de la retention
- [ ] YouTube : 16:9, le titre et la miniature sont tout aussi importants
- [ ] Instagram : 4:5 portrait, priorite visuelle
- [ ] Heure de publication : suivre la plage active de l'audience cible

---

## 17. Guide d'Adaptation : Comment l'appliquer a votre propre produit

### 17.1 Directement reutilisable

| Pratique de Claude | Principe universel | Directement applicable |
|-------------------|---------------------|----------------------|
| Coupes dures en priorite | Retenue des transitions | Oui |
| Pas d'intro logo | Presenter le produit dans les 2 premieres secondes | Oui |
| Pas de CTA de fin | Terminer avec le contenu | Oui |
| Titres en casing de phrase avec point | Texte conversationnel | Oui |
| Graisses 500/600/700 | Stabilite typographique | Oui |
| Task Sequence | Visualisation du processus | Oui |
| Scenes de 3-8 secondes | Rythme serre | Oui |
| Liste des anti-patterns | Eviter les erreurs courantes | Oui |

### 17.2 Necessite une adaptation

| Pratique de Claude | Pourquoi on ne peut pas copier directement | Comment adapter |
|-------------------|---------------------------------------------|-----------------|
| Systeme de couleurs blanc chaud + terracotta | Couleurs de marque Claude | Remplacer par votre couleur de marque principale, mais conserver la relation "canevas chaud + UI sombre" |
| Mode sombre constant | Votre produit est peut-etre en UI claire | Conserver la luminosite reelle de votre UI, utiliser le blanc chaud uniquement sur le canevas exterieur |
| Police serif pour les titres | Votre marque peut ne pas convenir au serif | Utiliser votre police de marque, mais conserver la hierarchie "titre grand + corps petit" |
| Mockups de peripheriques composites | Necessite des capacites de rendu 3D | Retrograder vers captures d'ecran + ombres, moins bien mais beaucoup plus accessible |
| Ouverture extreme minimaliste | Necessite la reconnaissance de marque pour soutenir l'effet | Si votre marque est peu connue, mettre d'abord le nom de fonctionnalite puis faire le minimalisme |

### 17.3 Philosophie fondamentale

N'imitez pas l'"apparence" de Claude, imitez la "logique de decision" de Claude :

- **Pourquoi utiliser des couleurs chaudes ?** → Parce que les concurrents utilisent des couleurs froides, se differencier
- **Votre version :** Trouvez un langage de couleurs que les concurrents n'utilisent pas

- **Pourquoi pas de presence humaine ?** → Parce que l'UI elle-meme peut raconter une histoire
- **Votre version :** Si votre UI n'est pas assez belle, corrigez d'abord l'UI avant de faire la video

- **Pourquoi pas de CTA ?** → Parce que l'energie de marque est suffisamment haute
- **Votre version :** Si votre marque est peu connue, un CTA modere est raisonnable

- **Pourquoi coupes dures en priorite ?** → Parce que chaque image a de la valeur
- **Votre version :** Si une scene ne tient pas 3 secondes, raccourcissez-la ou supprimez-la

**L'essence de la methodologie n'est pas une liste de regles, mais "chaque decision doit avoir une raison".**

## Annexe A : Reference rapide des types de videos

| Ce que vous devez faire | Quel cadre utiliser | Duree | Video de reference |
|------------------------|---------------------|-------|--------------------|
| Lancer une nouvelle fonctionnalite | Mode A : Annonce de fonctionnalite standard | 30-60s | Opus 4.6, Code Review |
| Annoncer une integration | Mode B : Scan d'ecosysteme | 30-50s | Excel/PowerPoint, Work Tools |
| Courte annonce / evenement | Mode C : Carte sociale ultra-courte | 8-15s | Thank You, Remote Control |
| Fonctionnalite orientee developpeur | Mode D : Demo approfondie developpeur | 60-90s | Managed Agents, Agent View |
| Declaration de marque / prise de position | Variante du Mode C | 10-60s | "Keep Thinking", "Ads" |

## Annexe B : Template de video fonctionnalite 30 secondes

| Temps | Contenu | Animation |
|-------|---------|-----------|
| 0-3s | Icone minimaliste + revelation du nom de fonctionnalite | Icone en rebond entrant + texte en fondu entrant |
| 3-7s | Probleme / contexte | Barre de legende captionAt() |
| 7-18s | Demonstration du produit | clickAt() × 2-3, showPreviewAt() |
| 18-25s | Magic Moment | Task Sequence (passage ligne par ligne au vert) |
| 25-28s | Etat du resultat | Panneau showRightAt() |
| 28-30s | Fermeture logo | Final Card (version simplifiee) |

## Annexe C : Template de video fonctionnalite 60 secondes

| Temps | Contenu | Animation |
|-------|---------|-----------|
| 0-3s | Ouverture minimaliste (icone dans l'espace negatif) | Icone en zoom rebondissant |
| 3-8s | Nom de fonctionnalite + contexte | cameraTo() + captionAt() |
| 8-20s | Operations utilisateur (2-3 etapes) | clickAt() × 2-3 |
| 20-40s | Traitement systeme (Magic Moment) | Task Sequence + respiration Pulse |
| 40-50s | Presentation des resultats | showPreviewAt() + Staggered Reveal |
| 50-55s | Verification secondaire / preuve | Panneau showRightAt() |
| 55-60s | Fermeture logo | Final Card

---

## TODO / Notes Personnelles

### L'avantage concurrentiel d'Anthropic n'est pas seulement le modele — c'est qu'on se souvienne d'eux

La version courante : Anthropic a un bon produit, donc forcement un bon marketing. Apres avoir regarde 77 videos, je pense le contraire : **le marketing est la ligne principale.**

L'equipe marketing est professionnelle. 77 videos avec une precision de production et une coherence strategique qui ne ressemble pas a quelque chose filme a la va-vite par des ingenieurs. Le rythme de publication suit le playbook d'une entreprise mediatique — campagnes en rafale, pas goutte-a-goutte regulier. Les videos d'annonces de nouvelles fonctionnalites font 5x plus de vues que celles de disponibilite de fonctionnalites.

L'objectif est clair, tout tourne autour. "Keep Thinking" n'est pas un slogan accroche au mur — c'est une strategie de contenu. Palette chaude, cuts secs, pas d'intro logo, pas de CTA. Tout transmet le meme message : on n'a pas besoin de se vendre. 77 videos, zero exception.

Memoire de marque. Fond blanc chaud, accent terracotta, UI sombre — tu sais que c'est Claude des la premiere frame. 77 videos martelant le meme style visuel jusqu'au reflexe. Maintenant quand on dit "video IA aux tons chauds," c'est Claude qui vient en premier. La memoire de marque ne se construit pas avec un logo — elle se construit par la repetition.

---
