---
tags: [dataview, dashboard, analytics]
---

#  Tableau de Bord Dynamique

Ce tableau agrège automatiquement les données techniques présentes dans les fiches énergies. Si une fiche est modifiée, ce tableau se met à jour instantanément.

```dataview
TABLE WITHOUT ID
    file.link as "Source d'Énergie",
    type as "Typologie",
    puissance_gw as "Puissance (GW)",
    cout_lcoe as "Coût LCOE (€/MWh)",
    objectif_2050 as "Objectif 2050"
FROM #energie
SORT puissance_gw DESC