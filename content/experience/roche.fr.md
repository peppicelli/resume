+++
display_project = true
title = "Stagiaire"
website = "http://www.roche.com/about/business/diagnostics.htm"
company = "Roche Molecular Systems (Pleasanton California)"

project = "La division *diagnostic* de Roche Molecular Systems développe des machines pour l'analyse du sang (in vitro), et en particulier celles qui utilisent la technique [PCR](https://fr.wikipedia.org/wiki/R%C3%A9action_en_cha%C3%AEne_par_polym%C3%A9rase) (Réaction en chaîne par polymérase). Ces machines produisent beaucoup de données qui doivent ensuite être analysées par des mathématiques plutôt complexes. Ce projet consistait à continuer le développement d'un outil interne permettant aux mathématiciens d'implémenter et de tester leurs algorithmes sur des jeux de données provenant de tout types de machines."

main_achievements = [
  "L'outil pouvait importer des données d'une base de donnée **Microsoft SQL Server**. Tout se passait bien quand l'importation se faisait depuis le même réseau que celui de la base de données. Cependant lorsque l'utilisateur se trouvait sur un autre réseau (à travers un VPN), les performances étaient très mauvaises. J'ai analysé et ré-écrit les requêtes SQL dans le code jusqu'à ce que les performances soient les mêmes en dehors et sur le même réseau.",
  "J'ai réécrit le méchanisme de sérialisation des données afin d'avoir un format plus facile à maintenir (du binaire par défaut dans `C#` à du *XML* proprement documenté)."
]

responsabilities = [
  "Développement d'un outil graphique en **.Net** (avec `C#`).",
  "Développement dans un environement médical avec des audits de la FDA (chaque ligne de code devait être tracé, des définitions des besoin des utilisateurs aux tests)"
]

date = "2017-03-29T23:56:27-05:00"
end_date = ""
start_date = "2007"
logo = "roche.png"

+++
