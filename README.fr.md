# Comment Anthropic réalise des vidéos à 78M de vues

Analyse systématique de 77 vidéos produit officielles de Claude (oct. 2025 – mai 2026). Méthodologie extraite, système de design, cadres narratifs et schémas d'engagement.

[English](README.md) | [中文](README.zh.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Português](README.pt.md) | [Document complet de méthodologie →](analysis/METHODOLOGY.fr.md)

---

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
