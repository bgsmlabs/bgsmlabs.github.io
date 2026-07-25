# Charte Graphique — Jeu des 7 Familles

> Branche `jeu-des-7-familles` | Dernière mise à jour : 19 juillet 2026

## 1. Format

| Propriété | Valeur |
|-----------|--------|
| Ratio | 63 × 88 mm (poker) |
| Résolution digitale | **2016 × 2816 px** (multiples de 16) |
| Border-radius | 14 px |
| Fond page | `#E8E2D5` |

## 2. Structure de la carte

```
┌──────────────────────────────┐
│  BANDEAU HAUT        304 px  │  Fond couleur parti, texte blanc
│  "MISSION ELECTION" (9px)    │  Inter 600, uppercase, letter-spacing 0.08em
│  "NOM FAMILLE"      (18px)   │  Inter 900, uppercase, letter-spacing 0.01em
├──────────────────────────────┤
│                              │
│  ILLUSTRATION       2208 px  │  Plein fond (background-image sur .card)
│  Style Ligne Claire          │  Décor contextuel obligatoire
│  Pas de banderole dessinée   │  Pas de slogan, pas d'emoji
│                              │
├──────────────────────────────┤
│  BANDEAU BAS         304 px  │  Fond couleur parti, texte blanc
│  "NOM PERSONNAGE"   (18px)  │  Inter 900, uppercase, letter-spacing 0.01em
│  "Sous-titre"        (9px)  │  Inter 600, mixed-case, letter-spacing 0.08em
└──────────────────────────────┘
```

**Règle d'or :** Les deux bandeaux ont le **même fond** (couleur du parti) et le **même padding** (12px 20px 10px).

### Hauteurs exactes

| Élément | Sur carte 370×517 (écran) | Sur 2016×2816 (full) |
|---------|--------------------------|----------------------|
| Bandeau haut | 56 px | 304 px |
| Bandeau bas  | 56 px | 304 px |
| Illustration | 405 px | 2208 px |

## 3. Typographie

| Usage | Police | Graisse | Taille | Style |
|-------|--------|---------|--------|-------|
| Label bandeau ("MISSION ELECTION") | Inter | 600 | 9 px | Uppercase, letter-spacing 0.08em, opacity 0.9 |
| Nom famille ("LA FRANCE INGÉRABLE") | Inter | 900 | 18 px | Uppercase, letter-spacing 0.01em |
| Nom personnage ("ALAIN SOUMIT") | Inter | 900 | 18 px | Uppercase, letter-spacing 0.01em |
| Sous-titre ("Le tribun cacochime") | Inter | 600 | 9 px | Mixed-case, letter-spacing 0.08em, opacity 0.9 |
| UI (navigation, sélecteur) | Inter | 400-600 | 11-13 px | — |
| Cormorant Garamond | Réservé UI page | — | — | Jamais sur les cartes |

## 4. Couleurs des partis

| Parti | Couleur | Hex |
|-------|---------|-----|
| La France Ingérable (ex-Extrême Gauche) | Rose foncé | `#C2185B` |
| Écologiste | Vert | `#388E3C` |
| Social-démocrate | Rose social | `#E91E63` |
| Centre | Orange | `#F57C00` |
| Droite | Bleu | `#1976D2` |
| Extrême droite | Bleu marine | `#0D1B3E` |
| Réac' | Violet | `#7B1FA2` |

## 5. Illustrations — Style Artistique

### Références
Les illustrations de référence sont : **Bastiano Limite, Enguerrand Placement, Latifa Shaw, Madelon Lyfans** (catalogue Mission Élection) et **Alain Soumit** (7 familles).

### Anatomie & Caricature

| Trait | Description |
|-------|-------------|
| **Proportions** | Tête légèrement surdimensionnée (~1/5 du corps), corps allongé, mains expressives |
| **Nez** | Proéminent, long, souvent busqué ou bulbeux — signature caricaturale |
| **Yeux** | Lourds, paupières tombantes ou cernes marquées, regard fatigué ou calculateur |
| **Bouche** | Grande, dents visibles (souvent jaunies ou irrégulières), rictus prononcé |
| **Menton** | Marqué, parfois fuyant ou au contraire prognathe |
| **Mains** | Longues, osseuses, doigts articulés |
| **Silhouette** | Personnage en pied, centré, pose frontale 3/4, poids sur une jambe |

### Trait & Encrage

| Caractéristique | Règle |
|-----------------|-------|
| **Contour** | Noir, épaisseur constante (~2-3 px à l'échelle 537×800), net et sans tremblement |
| **Lignes intérieures** | Noires, plus fines que le contour, pour plis, articulations, détails du visage |
| **Style** | Ligne claire franco-belge pure — pas de hachures, pas de dégradé de ligne |
| **Ombres** | Aplats de couleur plus foncée (pas de trames, pas de dégradé), ombre portée au sol |

### Couleurs

| Règle | Description |
|-------|-------------|
| **Palette** | Tons saturés, francs, « bande dessinée » — pas de pastels, pas de photoréalisme |
| **Aplats** | Couleurs uniformes, sans texture ni dégradé (sauf très rares exceptions) |
| **Peau** | Tons chair BD : rosé pâle, ocre clair, brun saturé — jamais photoréaliste |
| **Vêtements** | Teintes vives, contrastées avec le fond et la peau |
| **Fond (catalogue)** | Blanc pur `#FFFFFF` + ombre portée grise au sol |
| **Fond (7 familles)** | Contextuel, même style BD que le personnage, sans dégradé atmosphérique |

### Props & Accessoires

Chaque personnage tient un **objet-signature** qui raconte son rôle :
- Bastiano : feuille blanche
- Enguerrand : pile de livres
- Latifa : clipboard / planchette
- Madelon : micro
- Alain : poing levé + keffieh

### Expressions

- Grimaces, sourires carnassiers, clins d'œil, regards en coin
- Pas de neutralité — chaque visage est une **caricature émotionnelle**
- Dents souvent apparentes, sourcils très marqués

### Ce qui est DIFFÉRENT pour le 7 familles (vs catalogue)

| Élément | Catalogue | 7 Familles |
|---------|-----------|------------|
| Fond | Blanc pur | **Contextuel obligatoire** (manif, usine, hémicycle…) |
| Texte dans l'image | Bulle avec nom + sous-titre + logo parti | **Aucun** — les bandeaux font le texte |
| Logo parti | Cercle avec initiales dans la bulle | **Aucun** dans l'illustration |
| Format | 537×800 | 2016×2816 (personnage dans les 2208 px centraux) |
| Ombre au sol | Oui | Oui, cohérente avec le décor |

### Ce qui est IDENTIQUE

- Trait noir constant, ligne claire
- Caricature du visage (nez, yeux, bouche, menton)  
- Aplats de couleur saturés, sans texture
- Personnage en pied, centré, pose frontale 3/4
- Objet-signature dans les mains
- Expression faciale exagérée, « gueule » mémorable

### Prompt-type pour génération

```
Style: Ligne Claire franco-belge pure (Hergé, Jacobs, Franquin). Bold consistent black outlines, flat saturated comic colors, no gradients, no textures, no cross-hatching.

Character: Full-body caricature, centered, 3/4 frontal pose. Exaggerated facial features: prominent nose (long/bulbous), heavy-lidded eyes with dark circles, wide mouth showing teeth, strong chin. Long bony hands. Head slightly oversized (~1/5 body).

Background: [CONTEXTUEL — manif, usine, hémicycle, campus…]. Same flat comic style as the character, no atmospheric gradients.

Props: [OBJET-SIGNATURE] in hands.

Ground shadow: flat grey ellipse under feet, consistent with scene.

CRITICAL: NO text, NO speech bubbles, NO logos, NO banners with words anywhere in the image.
```

### Décors par personnage (La France Ingérable)

| Personnage | Décor | Objet-signature |
|------------|-------|-----------------|
| Alain Soumit (grand-père) | Amphithéâtre occupé, drapeaux rouges/noirs, foule | Poing levé, keffieh |
| Arlette Lagrève (grand-mère) | Piquet de grève devant usine, banderoles CGT | Mégaphone |
| Mohamed Publik (père) | Assemblée nationale, micros, caméras | Poing sur tribune |
| Ouria Boutefeu (mère) | Barricade en feu, rue pavée | Cocktail molotov |
| Thomas Woke (fils) | Campus universitaire, drapeaux arc-en-ciel | Téléphone en mode selfie |
| Rima Kassos (fille) | Vitrine brisée, CRS en fond | Pavé à la main |

### Règles
- ❌ **Pas de banderole/texte/bulle dessinée** dans l'illustration
- ❌ **Pas d'emoji, pas de slogan, pas de logo parti** sur la carte
- ✅ Style **strictement identique** aux références catalogue pour le trait, les couleurs, la caricature
- ✅ L'illustration est une image **plein fond** (`background-image` sur `.card`)
- ✅ Format de génération : 2016 × 2816 px (personnage dans les 2208 px centraux)

## 6. FAL API (édition d'image)

### Endpoint
```
openai/gpt-image-2/edit
```

### Workflow complet
1. Générer l'illustration avec `image_generate` ou ComfyUI (2016×2816)
2. Si l'illustration a une banderole dessinée → créer un masque (blanc = zone à éditer) et appeler l'API edit pour la supprimer
3. L'illustration finale ne contient **aucun texte**

### Paramètres FAL
```python
{
    "prompt": "KEEP character identical. Edit ONLY masked area. Fill with natural background.",
    "image_urls": [base64_image],
    "mask_image_url": base64_mask,
    "image_size": "auto",  # ou {"width": 2016, "height": 2816}
    "quality": "high",
    "output_format": "png"
}
```

### Clé API
- Variable : `FAL_KEY`
- Fichier : `/opt/data/.env`

## 7. Structure des données (JavaScript)

```javascript
{
  name: "LA FRANCE INGÉRABLE",       // Nom affiché (uppercase)
  initials: "LFI",                    // Initiales (non affichées)
  color: "#C2185B",                   // Couleur du parti
  members: [
    {
      name: "Alain Soumit",           // Nom affiché (uppercasé par CSS)
      subtitle: "Le tribun cacochime",// Sous-titre (mixed-case)
      img: "alain-soumit.png"         // Fichier illustration
    },
    // ... 5 autres membres
  ]
}
```

**Champs obsolètes (conservés dans les données mais non affichés) :** `emoji`, `label`, `slogan`

## 8. Intégration HTML

### Structure DOM d'une carte
```html
<div class="card" style="background-image: url(illustration.png)">
  <div class="card-header" style="background: #C2185B">
    <div class="family-label">Mission Election</div>
    <div class="family-name">NOM FAMILLE</div>
  </div>
  <div class="card-illustration"><!-- vide, l'image est en fond de .card --></div>
  <div class="card-footer" style="background: #C2185B">
    <div class="char-name">NOM PERSONNAGE</div>
    <div class="char-subtitle">Sous-titre</div>
  </div>
</div>
```

### Rendu JS
```javascript
// Le fond de .card est l'illustration (background-image)
card.style.backgroundImage = `url(${mem.img})`;

// Header : fond = couleur parti (semi-transparent si image)
header.style.background = mem.img ? fam.color + 'e6' : fam.color;

// Footer : fond = couleur parti (toujours opaque)
footer.style.background = fam.color;
```

## 9. Déploiement

- **Source** : `bgsmlabs/mission-election` (branche `jeu-des-7-familles`)
- **Prod** : `bgsmlabs/bgsmlabs.github.io` → `https://bgsmlabs.github.io/mission-7-familles/`
- **Fichiers à déployer** : `index.html` + toutes les `*.png` (illustrations)

## 10. Checklist pour une nouvelle carte

1. [ ] Décor contextuel défini (pas de fond neutre)
2. [ ] Illustration générée en 2016×2816, style Ligne Claire
3. [ ] Aucune banderole/texte dessiné dans l'illustration
4. [ ] Si banderole → FAL edit avec masque pour la supprimer
5. [ ] Fichier `.png` nommé et placé dans les deux repos
6. [ ] Données ajoutées dans `families[].members[]`
7. [ ] Déployé → test visuel sur la page live
8. [ ] Capture affichée dans le fil Telegram