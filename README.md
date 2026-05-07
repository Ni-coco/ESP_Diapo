# ESP_Diapo

Ce diaporama utilise **Reveal.js** et charge les slides depuis `slides/*.html`.

## Lancer le diapo (important)

Comme les slides sont chargees via `fetch()`, **il faut un serveur local** (ouvrir `index.html` en `file://` ne marche pas a cause du CORS).

### Option 1 (macOS / Linux) : Python

Dans le dossier du projet :

```bash
python3 -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

### Option 2 (macOS) : double-clic

Double-clique `serve.command` (il lance le serveur et affiche l'URL).

## Modifier une partie du diapo

Chaque bloc est dans un fichier dans `slides/`.
Chacun peut modifier **son fichier** sans toucher a `index.html`.

