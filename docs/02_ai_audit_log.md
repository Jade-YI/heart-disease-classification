Journal d’audit de l’utilisation de l’IA

Ce document décrit les utilisations significatives de l’intelligence artificielle au cours du projet. Pour chaque utilisation, il précise la demande formulée, la réponse obtenue, les modalités de vérification, les éventuels problèmes identifiés ainsi que la décision finale prise par l’autrice.

L’IA est utilisée comme outil d’assistance à l’organisation, à la rédaction, à la programmation et à la vérification méthodologique. Les hypothèses de recherche sont formulées par l’autrice. Les décisions analytiques finales, la vérification des résultats et leur interprétation restent également sous sa responsabilité.

⸻

AI-001 · 2026-09-19 · Type : organisation / rédaction

* Source : ChatGPT — organisation initiale du projet et rédaction du fichier README.md.
* Ce que j’ai demandé / ce que l’IA a fait :
    J’ai demandé à l’IA de m’aider à créer et organiser la structure des fichiers et dossiers du projet, notamment les données, le code, les figures, la documentation, les hypothèses, le journal des décisions et le journal d’utilisation de l’IA. Je lui ai également demandé une aide à la rédaction du fichier README.md.
* Réponse de l’IA :
    L’IA a proposé une arborescence structurée du projet, une séparation entre les différents types de fichiers et plusieurs documents distincts pour les hypothèses, les décisions analytiques, l’audit de l’IA et le résumé final. Elle a également proposé une structure et un contenu pour le fichier README.md.
* Comment j’ai vérifié :
    J’ai vérifié l’arborescence dans le dépôt local et sur GitHub après la création des fichiers. J’ai également contrôlé les chemins, les noms des fichiers et leur cohérence avec l’organisation réelle du projet.
* Constat :
    ✅ La structure proposée était globalement adaptée au projet. Certaines parties ont néanmoins dû être ajustées en fonction des fichiers réellement utilisés.
* Impact :
    Léger. L’utilisation de l’IA concerne principalement l’organisation et la documentation du projet et n’a pas influencé les hypothèses scientifiques ni les résultats de l’analyse.
* Traitement final :
    J’ai conservé la structure générale proposée, tout en l’adaptant aux besoins réels du projet. Le fichier README.md a été rédigé avec l’assistance de l’IA puis intégré au dépôt.
* Preuve :
    Arborescence du dépôt, fichier README.md et historique Git correspondant.
* Leçon :
    Une structure proposée par l’IA peut faciliter l’organisation initiale d’un projet, mais elle doit être adaptée aux besoins réels et vérifiée après sa mise en place.

⸻

AI-002 · 2026-09-20 · Type : méthode / interprétation / rédaction

* Source : ChatGPT — discussion sur la formulation et la vérification méthodologique des hypothèses avant l’analyse.
* Ce que j’ai demandé / ce que l’IA a fait :
    Les hypothèses concernant les associations entre les facteurs de risque potentiels et l’AVC avaient été formulées par moi avant l’utilisation de l’IA. J’ai demandé à l’IA d’évaluer si ces prédictions pouvaient être présentées de manière méthodologiquement correcte dans le document d’hypothèses, de signaler les éventuels problèmes et de les reformuler en français sans modifier leur contenu scientifique initial.
* Réponse de l’IA :
    L’IA a recommandé d’interpréter avec prudence la catégorie Unknown de la variable smoking_status, car elle correspond à une information inconnue et non à un comportement tabagique spécifique. Lorsque j’ai proposé que l’association entre le genre masculin et l’AVC puisse diminuer après contrôle du tabagisme, l’IA a suggéré que le tabagisme pouvait être envisagé comme un médiateur dans un chemin hypothétique genre → tabagisme → AVC, plutôt que comme un facteur de confusion. L’IA a également reformulé mes hypothèses en français et les a organisées dans un format Markdown.
* Comment j’ai vérifié :
    J’ai comparé les remarques de l’IA avec la définition des variables du jeu de données. La distinction entre facteur de confusion et médiateur doit également être vérifiée à partir du contenu du cours et du raisonnement causal avant d’être utilisée dans l’interprétation finale.
* Constat :
    ⚠️ Partiellement vérifié. La prudence concernant la catégorie Unknown est cohérente avec la définition de cette modalité. En revanche, la qualification du tabagisme comme médiateur dépend du modèle causal retenu et ne doit pas être considérée comme établie sur la seule base de la réponse de l’IA.
* Impact :
    Léger à modéré sur la formulation et le raisonnement méthodologique. Aucun impact sur l’origine des hypothèses, qui ont été formulées indépendamment avant l’intervention de l’IA.
* Traitement final :
    J’ai conservé la recommandation de prudence concernant smoking_status = Unknown. La distinction entre médiateur et facteur de confusion est conservée comme point méthodologique à vérifier et non comme conclusion définitive. Les qualificatifs d’association « forte », « modérée » ou « faible » restent mes prédictions formulées avant l’analyse et ne constituent pas des conclusions générées par l’IA. Les hypothèses scientifiques initiales n’ont pas été remplacées.
* Preuve :
    Document des hypothèses, définition des variables et décisions DEC-001 et DEC-002.
* Leçon :
    Une suggestion méthodologique de l’IA, notamment sur la distinction entre médiateur et facteur de confusion, doit être vérifiée à partir du modèle causal et des connaissances du domaine avant d’être retenue.

---

AI-003 · 2026-09-22 · Type : code / visualisation / traitement des données

* Source : Claude — génération du code pour décrire et représenter graphiquement la proportion d’individus ayant eu un AVC dans la population étudiée.
* Ce que j’ai demandé / ce que l’IA a fait :
    J’ai demandé à l’IA de générer du code permettant de calculer la répartition des individus selon la survenue d’un AVC et de produire une représentation graphique correspondante.
* Réponse de l’IA :
    L’IA a proposé un code comptant le nombre d’individus avec et sans AVC, puis a généré un diagramme en barres avec le statut d’AVC sur l’axe des x et l’effectif (n) sur l’axe des y.
* Comment j’ai vérifié :
    J’ai examiné le graphique obtenu et comparé sa représentation avec l’objectif de cette partie de l’analyse, qui était de montrer la proportion des AVC dans l’ensemble de la population plutôt que de mettre principalement en avant les effectifs absolus.
* Constat :
    ⚠️ Le code initial permettait de représenter correctement les effectifs, mais ce choix graphique ne correspondait pas entièrement à mon objectif de présentation. Une représentation en proportions permet de rendre plus directement visible la part des individus ayant eu un AVC dans la population étudiée.
* Impact :
    Léger. La modification concerne uniquement la présentation descriptive des données et ne modifie ni les observations du jeu de données ni les résultats statistiques.
* Traitement final :
    Je n’ai pas conservé la représentation initiale basée sur n. J’ai modifié le graphique afin d’utiliser la proportion comme mesure sur l’axe des y, avec une échelle allant de 0 à 1. Le choix final de la représentation graphique résulte donc de ma propre évaluation de l’objectif descriptif.
* Preuve :
    Code correspondant à la section de description de la répartition des AVC dans le document Quarto et graphique généré.
* Leçon :
    Un graphique techniquement correct proposé par l’IA n’est pas nécessairement le plus adapté à l’objectif analytique ; le choix de l’échelle et de la mesure représentée doit être vérifié indépendamment.    
    
    