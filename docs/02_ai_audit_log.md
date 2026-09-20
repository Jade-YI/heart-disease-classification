# Journal d’audit de l’utilisation de l’IA

Ce document décrit les utilisations de l’intelligence artificielle au cours du projet. Pour chaque utilisation importante, il précise la demande formulée, la réponse reçue, les éléments retenus ou rejetés et les vérifications effectuées.

L’IA est utilisée comme outil d’assistance à l’organisation, à la rédaction, à la programmation et à la vérification méthodologique. Les hypothèses de recherche, les décisions finales, la vérification des résultats et leur interprétation restent sous la responsabilité de l’autrice du projet.

---

## AI-001 — 2026-09-19

**Étape du projet :** Organisation initiale du projet

**Objectif de l’utilisation :**  
Obtenir une assistance pour organiser les fichiers et les dossiers du projet, ainsi que pour rédiger le fichier `README.md`.

**Demande adressée à l’IA :**  
Proposer une structure claire et reproductible pour le projet, notamment pour les données, le code, les figures, la documentation, les hypothèses, le journal des décisions et le journal d’utilisation de l’IA. Fournir également une aide à la rédaction du fichier `README.md`.

**Résumé de la réponse de l’IA :**

- proposition d’une arborescence structurée pour le projet ;
- séparation des données, figures et documents méthodologiques ;
- création de fichiers distincts pour les hypothèses, les décisions analytiques, l’audit de l’IA et le résumé final ;
- proposition d’une structure et d’un contenu pour le fichier `README.md`.

**Éléments retenus :**  
La structure générale du projet et la séparation entre les différents documents ont été retenues. Le fichier `README.md` a été rédigé avec l’assistance de l’IA.

**Éléments modifiés ou rejetés :**  
La structure proposée a été adaptée aux besoins du projet et aux fichiers réellement disponibles.

**Vérification effectuée :**  
L’arborescence a été vérifiée dans le dépôt local et sur GitHub. Les chemins et les noms des fichiers ont été contrôlés après leur création.

**Impact sur le projet :**  
Élevé sur l’organisation et la documentation du projet, mais sans impact sur la formulation des hypothèses scientifiques.

---

## AI-002 — 2026-09-20

**Étape du projet :** Vérification et rédaction des hypothèses avant l’analyse

**Origine des hypothèses :**  
Toutes les hypothèses concernant les associations entre les facteurs de risque potentiels et l’AVC ont été formulées par l’autrice avant l’intervention de l’IA. L’IA n’a pas été utilisée pour produire ces hypothèses.

**Objectif de l’utilisation :**  
Vérifier si les hypothèses personnelles pouvaient être présentées de manière méthodologiquement correcte dans le document et obtenir une reformulation en français.

**Demande adressée à l’IA :**  
Évaluer si les prédictions formulées par l’autrice étaient adaptées au document d’hypothèses, signaler les éventuels problèmes méthodologiques, puis les reformuler en français sans modifier leur contenu scientifique initial.

**Résumé de la réponse de l’IA :**

- l’IA a recommandé une interprétation prudente de la catégorie `Unknown` de la variable `smoking_status`, car cette catégorie représente une information inconnue et non un comportement tabagique particulier ;
- lorsque l’autrice a proposé que l’association entre le genre masculin et l’AVC puisse diminuer après ajustement sur le tabagisme, l’IA a indiqué que le tabagisme pourrait être considéré comme un médiateur dans le chemin `genre → tabagisme → AVC`, plutôt que comme un facteur de confusion ;
- l’IA a reformulé les hypothèses en français et les a organisées dans un format adapté au fichier Markdown.

**Éléments retenus :**  
La distinction proposée entre facteur de confusion et médiateur a été retenue comme point méthodologique à vérifier. La recommandation d’interpréter avec prudence la catégorie `Unknown` de `smoking_status` a également été retenue.

**Éléments modifiés ou rejetés :**  
Les niveaux d’association « forte », « modérée » ou « faible » restent des prédictions personnelles formulées avant l’analyse. Ils ne sont pas considérés comme des conclusions produites par l’IA.

Les hypothèses scientifiques initiales n’ont pas été remplacées par des hypothèses proposées par l’IA.

**Vérification effectuée :**  
Les suggestions ont été comparées aux définitions des variables du jeu de données. Avant l’interprétation finale, les notions de facteur de confusion et de médiateur seront également comparées au contenu du cours.

**Impact sur le projet :**  
Modéré sur la formulation et la précision méthodologique, mais limité sur le contenu scientifique, puisque les hypothèses ont été formulées indépendamment par l’autrice.

**Décisions associées :** DEC-001 et DEC-002