# Dépenses par catégorie

Page web autonome qui lit un relevé CSV (Date, Catégorie, Libellé, Débit, Crédit) et affiche les dépenses de chaque mois en diagramme de Sankey.

Le fichier est lu **dans le navigateur** : il n'est envoyé à aucun serveur. `exemple_format.csv` contient des données fictives pour essayer la page.

Les catégories du fichier peuvent être corrigées : une opération à la fois, par règle sur le libellé (« Magasin U » → Maison) ou par fusion de catégories (Bars → Restaurants). Ces règles sont enregistrées dans le navigateur (localStorage) et peuvent être exportées ou importées en JSON.
