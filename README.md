# Les Bons Deals — Découverte Europe

**Dépôt PUBLIC distinct du moteur de vols PRIVÉ**.

Cette expérimentation présente des destinations européennes et huit parcours de préférence, sans vente, sans formulaire, sans inscription, sans cookies déposés par notre code et sans clés API.

## Publication gratuite — GitHub Pages

1. Ouvrir [Settings → Pages](https://github.com/lahssinihilmi-hash25/les-bons-deals-2/settings/pages).
2. Sous **Build and deployment → Source**, choisir **Deploy from a branch**.
3. Dans **Branch**, sélectionner **main**, puis **/(root)** et cliquer sur **Save**. La publication s'effectue directement, sans autre automatisation à configurer.
4. Vérifier le statut du déploiement avant de partager : lien attendu `https://lahssinihilmi-hash25.github.io/les-bons-deals-2/` (à confirmer sur la page Pages).

**Ne pas rendre public** `lahssinihilmi-hash25/les-bons-deals` (il contient le moteur et les données privées).

## Mesure de l'intérêt (NON activée)

Le site contient une page distincte pour chacun des huit choix. Cette architecture permet d'utiliser **Cloudflare Web Analytics**, gratuit et sans cookies, pour obtenir des pages vues agrégées :
- `/index.html` : présentation (visites de la page).
- `/choix/barcelone.html`, `/choix/lyon.html`, `/choix/marseille.html`, `/choix/londres.html` : intérêt par destination.
- `/choix/prix-total.html`, `/choix/vol-direct.html`, `/choix/dates-flexibles.html`, `/choix/destination.html` : priorités de voyage.

**Pour activer Cloudflare** : ouvrir [Web Analytics](https://dash.cloudflare.com/?to=/:account/web-analytics) → Add a site → nom d'hôte `lahssinihilmi-hash25.github.io` → copier la balise `<script>` fournie (token de site public, pas une clé API). Coller le script avant `</body>` dans `index.html` et les pages du dossier `choix`. Les modifications déploieront automatiquement les pages.

Le service Cloudflare ne prend pas en charge les événements personnalisés; nous comptons donc les vues des pages de choix, et non les interactions brutes ou des « clients ». Les comptages ne sont pas uniques par personne. Vérifier la conformité de la politique de confidentialité avant d'activer les mesures.

## Interprétation

Les pages vues et clics sont des signaux d’intérêt, **pas des engagements d’achat**. Une page vue ne prouve pas une personne distincte et ne doit pas être présentée comme une inscription.

Aucune analyse n'est encore activée ni rapportée. Aucun lien vers le moteur privé, aucune vente, aucun formulaire.
