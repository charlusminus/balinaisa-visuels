# balinaisa-visuels

Visuels produits du catalogue Balinaisa (mobilier teck massif), optimisés pour le
simulateur IA de lead-gen (référence produit envoyée au générateur d'image).

- 1 fichier JPEG par référence, dans `products/<id>.jpg`.
- Les produits disposant de deux angles ont un **composite face + dos** (les deux vues
  dans un seul fichier), ce qui garantit les deux angles au générateur sans alourdir le payload.
- Images compressées (~100 Ko en moyenne), fond neutre.

Servi via jsDelivr : `https://cdn.jsdelivr.net/gh/charlusminus/balinaisa-visuels@main/products/<id>.jpg`

Source de vérité du catalogue (ids, prix, descriptifs) : dépôt privé `balinaisa-assets` (`n8n/catalogue-node.js`).
