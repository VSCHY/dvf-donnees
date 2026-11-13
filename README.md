# DVF par commune — miroir d'Indice Immo par Quartier

Ventes immobilières DVF (demandes de valeurs foncières, DGFiP), d'après les fichiers géolocalisés
d'Etalab (livraison du 22 octobre 2026), découpées par commune et par année :
`{année}/{code INSEE}.json`. Ce sont les ventes telles que les lit
[Indice Immo par Quartier](https://www.indice-immo-quartier.fr/methodologie) : une ligne par vente
(disposition), ventes en bloc écartées, prix au m² entre 200 et 30 000 €.

Format : `{"v":1,"m":[[type, prix, surface, date, lon, lat, pièces, terrain], …]}`, détails dans `index.json`.

Licence : Licence Ouverte 2.0 (Etalab). Source : DVF (DGFiP, via Etalab). Les fichiers d'origine
et leur empreinte SHA-256 sont listés dans `index.json`.
