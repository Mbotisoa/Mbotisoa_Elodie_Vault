---
tags:
  - visualisation
  - graph
  - schema
---


*La transition énergétique* est un système complexe mêlant flux physiques (électrons) et flux financiers. Pour compléter les tableaux de données, nous utilisons ici des outils de schématisation visuelle.
---

![[image-1.png]]
---
## 2. Diagramme de Répartition (Mermaid)
Obsidian permet de générer des graphiques simples via le langage Mermaid pour visualiser les proportions du mix.

```mermaid
pie title Mix Électrique France (Répartition Simplifiée)
    "Nucléaire (Pilotable)" : 62
    "Hydraulique (Stockable)" : 10
    "Éolien (Variable)" : 9
    "Solaire (Variable)" : 5
    "Thermique (Fossile)" : 7