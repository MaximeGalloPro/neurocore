# Architecture generale de NeuroCore

NeuroCore est pense comme une plateforme experimentale modulaire permettant, a long terme, d'interagir avec un reseau neuronal biologique.

Cette architecture doit rester progressive : chaque sous-systeme doit pouvoir etre compris, teste et documente independamment avant integration.

## Sous-systemes

### Reseau neuronal biologique

Le reseau neuronal est le coeur biologique du systeme.

Options envisagees :

- neurones primaires ;
- neurones derives de cellules souches ;
- organoides a plus long terme.

Decision initiale : ne pas choisir trop tot le modele biologique final. Les premieres phases doivent d'abord documenter les contraintes, les risques, les competences necessaires et les infrastructures minimales.

### Chambre de culture

La chambre de culture doit maintenir un environnement compatible avec la survie des cellules.

Objectifs :

- environnement propre ;
- maintien des conditions physiques ;
- observation ;
- integration future avec perfusion et capteurs.

### Perfusion

Le systeme de perfusion doit apporter les nutriments et evacuer les dechets.

Objectifs :

- controle du debit ;
- renouvellement du milieu ;
- limitation des contaminations ;
- automatisation progressive.

### Controle environnemental

Le controle environnemental regroupe les fonctions de mesure et regulation.

Parametres principaux :

- temperature ;
- CO2 ;
- humidite ;
- etat des capteurs ;
- alertes ;
- automatisation.

### Interface neuronale

L'interface neuronale doit permettre la lecture et, plus tard, la stimulation de l'activite electrique.

Pistes :

- MEA ;
- microelectrodes ;
- amplification faible bruit ;
- filtrage ;
- acquisition haute resolution.

### Electronique

L'electronique assure la mesure, le conditionnement du signal et le pilotage.

Briques probables :

- amplification ;
- filtrage ;
- ADC ;
- DAC ;
- alimentation ;
- isolation ;
- controle de pompes et actionneurs.

### Logiciel

Le logiciel doit rendre le systeme observable et pilotable.

Fonctions visees :

- acquisition ;
- traitement du signal ;
- visualisation ;
- automatisation ;
- journalisation ;
- analyse assistee par IA.

## Decision d'architecture initiale

Le depot separe volontairement la documentation, le materiel, l'electronique, le logiciel, le firmware, les experiences et les videos.

Raison : NeuroCore est un projet pluridisciplinaire. Une structure separee evite que le depot devienne uniquement un depot de code alors qu'il doit rester la memoire complete du laboratoire.
