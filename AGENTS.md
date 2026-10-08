# Running — Instructions aux assistants IA

## Objectif

Aider à analyser mes entraînements de course à pied,
évaluer ma progression et préparer mes objectifs sportifs.

Privilégier des conseils individualisés, fondés sur mes
données réelles plutôt que sur des plans génériques.

## Sources de données

- `profile.md` : profil, capacités, habitudes et objectifs.
- `data/runs/` : sorties d'entraînement réalisées.
- `data/races/` : compétitions et résultats officiels.
- `data/tests/` : tests de terrain.
- `plans/` : plans d'entraînement (lorsqu'ils existent).

Les dossiers de données seront ajoutés progressivement.

Lire le profil et les activités récentes avant de proposer
un programme ou d'interpréter une nouvelle séance.

## Fiabilité des données

- Distinguer mesures, déclarations, estimations et hypothèses.
- Ne jamais inventer une mesure absente.
- Distinguer séances réalisées et séances prévues.
- Conserver les observations historiques datées.
- Signaler les contradictions entre sources.
- Privilégier les temps officiels pour les compétitions,
  tout en conservant les mesures GPS séparément.
- Tenir compte des limites du capteur cardiaque optique.
- Ne pas présenter la FCmax, la VMA, la VO2max ou les
  zones cardiaques estimées comme des mesures certaines.

## Analyse des entraînements

- Comparer les séances avec leur contexte : fatigue,
  récupération, dénivelé, météo, compétition récente.
- Tenir compte du volume hebdomadaire et des activités
  quotidiennes, notamment la marche.
- Distinguer charge cardiovasculaire et fatigue musculaire.
- Évaluer les progrès sur plusieurs séances, pas sur
  une seule mesure.
- Utiliser l'allure, la FC et le ressenti conjointement.
- Ne pas imposer une cible cardiaque théorique si les
  sensations et les données réelles la contredisent.

## Recommandations d'entraînement

- Privilégier la régularité et la progression durable.
- Conserver une majorité d'entraînement facile.
- Éviter d'augmenter fortement volume et intensité
  simultanément.
- Adapter les séances à la récupération effective.
- En cas de douleur persistante, privilégier une réduction
  de charge et ne pas poser de diagnostic.
- Distinguer une proposition de séance d'une prescription.
- Expliciter les incertitudes et les compromis.

Les durées de séance incluent l'échauffement en courant,
sauf indication contraire.

## Organisation des données

- Un fichier Markdown par activité réellement effectuée.
- Noms de fichiers commençant par la date ISO (YYYY-MM-DD).
- Métadonnées structurées en YAML front matter.
- Unités cohérentes : km, secondes, bpm, mètres.
- Séparer les mesures du ressenti et de l'analyse.
- Ne pas modifier rétroactivement les données brutes
  pour les faire correspondre à une interprétation.

## Périmètre technique

Dépôt de données Markdown maintenu dans Git.
Pas de CI, de site web ou de GitHub Pages souhaités
sans demande explicite.
