+++
title = "Consultant externe (ingénieur logiciel) pour SERIAL SA"

project = "Le système de gestion de portefeuilles (côté serveur) de la banque a été développé dans les années 90 en `C++` et compilé avec un compilateur propriétaire (Sun) non-ANSI. Le but de ce projet était de porter le code au standard `C++ 98`."

date = "2017-03-24T19:28:09-05:00"
end_date = ""
main_achievements = [
  "Il n'existait aucun test automatique afin de valider que le système fonctionnait correctement. Afin de m'assurer que les changements apportés au code n'introduisirent pas d'erreur (particulièrement de calcul), j'ai implémenté un composant permettant d'enregistrer les requêtes et les réponses du système en production. J'ai ensuite rejoué ces enregistrements sur le nouveau système afin de le valider.",
  "Les fuites mémoires sur le code étaient plutôt graves. De plus, le code n'utilisait que des pointeurs partagés ce qui rendait la recherche des fuites difficile. Afin de les trouver, j'ai utilisé IBM Rational Purify pour instrumenter le code et enregistrer la call stack à chaque incrémentation ou décrementation de compteur de pointeurs partagés. Ensuite, à l'aide de `Python`, j'ai trié ces enregistrements afin de tout de suite voir où les décrémentations de références manquaient."
]
display_project = true
start_date = "2008"
responsabilities = [
  "Migration de code `C++` sur un système **Sun Solaris**.",
  "Migration du middleware [**Tuxedo**](http://www.oracle.com/technetwork/middleware/tuxedo/overview/index.html) de la  version 6.5 à la version 10.",
  "Traque acharnée et résolution des fuites mémoires qui étaient précédemment résolue à l'aide d'un méchanisme de redémarrage."
]
logo = "serial.png"
company = "Serial SA / Union Bancaire Privée"
website = "https://www.serial.ch"
+++
