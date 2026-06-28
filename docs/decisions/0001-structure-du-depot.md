# Decision 0001 - Structure initiale du depot

Date : 2026-06-28

## Statut

Acceptee.

## Contexte

NeuroCore n'est pas uniquement un projet logiciel. Il regroupe biologie, mecanique, electronique, logiciel, firmware, experiences, documentation et videos.

Le depot doit donc etre capable de stocker la memoire complete du laboratoire Holivaw.

## Decision

Le depot est organise avec les dossiers suivants :

- `docs/`
- `hardware/`
- `electronics/`
- `cad/`
- `software/`
- `firmware/`
- `experiments/`
- `videos/`
- `media/`
- `references/`

## Alternatives considerees

### Depot unique centre sur le logiciel

Avantage : simple pour le developpement logiciel.

Inconvenient : ne represente pas la nature physique et experimentale du projet.

### Plusieurs depots separes

Avantage : separation forte des domaines.

Inconvenient : risque de fragmenter la documentation et de perdre la chronologie globale.

### Depot monorepo documentaire et technique

Avantage : une seule memoire du projet, plus facile a parcourir et a versionner.

Inconvenient : demande une discipline documentaire pour rester lisible.

## Consequences

Le projet adopte un depot unique, structure par domaines.

Cette decision pourra etre revue si certains sous-systemes deviennent suffisamment matures pour justifier des depots dedies.
