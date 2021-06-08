# SAT_data
Datasets de tests pour le solver SAT. Contient les benchmarks, mais également les données Tripadvisor

Pour Tripadvisor
- *HF_tripAdvisorSAT_areaX.csv*
  - fichier CSV (séparateur tab "\t")
  - colonne 1 : pays d'origine de l'utilisateur (100 000 000 + idCountry). Table de correspondance dans "*HF_tripCountries.csv*"
  - colonnes suivantes :
    - pas de AreaX : idLocation (lieu visité). Table de correspondance dans "*HF_tripLocations.csv*"
    - Area5 : commune. Table de correspondance dans "*HF_gadm36_correspondance_5.csv*"
    - Area4 : communauté de communes. Table de correspondance dans "*HF_gadm36_correspondance_4.csv*"
    - Area3 : canton. Table de correspondance dans "*HF_gadm36_correspondance_3.csv*"
    - Area2 : département. Table de correspondance dans "*HF_gadm36_correspondance_2.csv*"
    - Area1 : région. Table de correspondance dans "*HF_gadm36_correspondance_1.csv*"
