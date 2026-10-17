# ASC Manko de Ndiane

Site de l'Association Sportive et Culturelle Manko de Ndiane (Sénégal).

- Inscription des joueurs, catégories U7 à U20 calculées avec la date de naissance
- Dons par Wave et Orange Money
- Cartes de membre avec aperçu
- Adapté aux ordinateurs, Android et iPhone, en vert et blanc

Le site est un seul fichier : `index.html`.

## Renseigner les informations de l'association

Ouvrez `index.html`, cherchez `À RENSEIGNER PAR LE BUREAU` et remplissez :

| Champ | Exemple |
|---|---|
| `wave` | `"77 123 45 67"` |
| `orange` | `"78 123 45 67"` |
| `whatsapp` | `"221771234567"` (format international, sans + ni espaces) |
| `fee` | `10000` (frais d'inscription en FCFA) |
| `cards` | prix des cartes Supporter, Membre, Bienfaiteur |

## Mettre le site en ligne avec GitHub Pages

1. Dans le dépôt, ouvrez **Settings**, puis **Pages**.
2. Dans **Branch**, choisissez `main` et le dossier `/ (root)`, puis **Save**.
3. Après une minute, le site est disponible à l'adresse `https://NOM-UTILISATEUR.github.io/NOM-DU-DEPOT/`.

## Paiements

Le site ne reçoit pas l'argent. Le membre paie dans son application Wave ou Orange Money, puis envoie la référence de la transaction au bureau par WhatsApp. Le bureau vérifie et valide.
