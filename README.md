# Pop Quiz !

## Quelle est la signification et le sens de COBOL ?

COBOL, acronyme de "Common Business-Oriented Language", est un langage de programmation introduit dans les années 1950. Le terme "Common", traduit par "Commun", souligne son objectif d'universalité et d'accessibilité pour différentes entreprises. L'expression "orienté affaires" reflète sa spécialisation dans les applications commerciales, bancaires, d'assurance, etc.

## Afin d'introduire les principes fondamentaux du COBOL, effectuer un travail de recherche sur les notions suivantes :

Dans le cadre d'un programme COBOL, définir et expliquer :

### Structure physique

La structure physique d'un programme COBOL est principalement organisée en lignes et caractères. Un programme COBOL est divisé en quatre divisions :
1. **IDENTIFICATION DIVISION** : contient les informations d'identification du programme.
2. **ENVIRONMENT DIVISION** : définit l'environnement matériel et logiciel.
3. **DATA DIVISION** : décrit toutes les données manipulées par le programme.
4. **PROCEDURE DIVISION** : contient le code exécutable du programme, organisé en sections et paragraphes.

Chaque ligne de code dans un programme COBOL suit une structure de colonnes spécifique, où certaines zones (colonnes) sont réservées pour des numéros de ligne, des indicateurs spéciaux (comme l'astérisque pour les commentaires), et le code lui-même.

### Structure logique

La structure logique d'un programme COBOL est déterminée par la manière dont il est organisé en divisions, sections, paragraphes, et sentences. Cette structure reflète la logique de traitement des données et l'exécution des instructions. Les sections et paragraphes dans la `PROCEDURE DIVISION` permettent d'organiser le code en blocs fonctionnels, facilitant ainsi la lecture, la maintenance et le débogage du programme.

### Ce qui est obligatoire

Dans un programme COBOL, certaines parties sont obligatoires :
- **IDENTIFICATION DIVISION** : Bien que minimaliste, elle doit contenir au moins le nom du programme.
- **PROCEDURE DIVISION** : C'est là que le code exécutable du programme réside. Un programme doit avoir au moins une instruction exécutable pour être considéré comme complet.

### Ce qui est facultatif

D'autres divisions et sections sont facultatives et utilisées en fonction des besoins spécifiques du programme :
- **ENVIRONMENT DIVISION** : Nécessaire pour des programmes qui interagissent spécifiquement avec leur environnement matériel ou logiciel, mais pas toujours requise pour des opérations simples.
- **DATA DIVISION** : Bien qu'essentielle pour la plupart des programmes pour définir les structures de données, un programme exécutant des tâches très basiques pourrait techniquement s'en passer.

### Importance des Colonnes

- Les instructions COBOL étaient historiquement saisies sur des cartes perforées IBM de 80 colonnes, une pratique qui influence encore la syntaxe du langage.

#### Structure des Colonnes

- **Colonnes 1 à 6** : Numéros de séquence ou de ligne, facultatifs.
- **Colonne 7** : Marque les lignes de commentaires (avec `*`) ou de débogage (avec `D`).
- **Colonnes 8 à 11** (Zone A) : Pour les en-têtes de division, section, paragraphes et descriptions de fichiers.
- **Colonnes 12 à 72** (Zone B) : Contiennent les instructions du langage.
- **Colonnes 73 à 80** : Champ d'identification, utilisé pour la numérotation par le système.

### Structure Hiérarchique

- Le COBOL est hiérarchiquement structuré avec des divisions, sections, paragraphes, phrases et déclarations.

#### Déclarations et Phrases

- **Déclarations** : Directives uniques commençant souvent par un mot réservé COBOL.
- **Phrases** : Peuvent contenir plusieurs instructions, terminées par un point.

#### Paragraphes

- Représentent une action spécifique et peuvent être appelés avec `PERFORM`.

#### Sections

- Organisent les paragraphes et contiennent des informations essentielles au programme, comme la `WORKING-STORAGE SECTION` pour les déclarations de variables.

### Sources Principales:

1. **IBM Knowledge Center:** IBM est une autorité incontestée dans le domaine des langages de programmation, y compris COBOL, qu'ils ont contribué à développer et à standardiser. Leurs documents fournissent des détails exhaustifs sur la syntaxe et la structure de COBOL, ce qui les rend indispensables pour toute discussion technique sérieuse sur COBOL.

2. **Micro Focus Documentation:** Micro Focus est une autre entreprise leader dans le domaine du développement logiciel COBOL. Leur documentation offre des perspectives pratiques sur l'implémentation et l'utilisation de COBOL dans des environnements modernes, ce qui est crucial pour comprendre comment COBOL s'adapte aux exigences actuelles.

3. **COBOL Standards (ISO/IEC 1989:2014):** Les normes internationales fournissent une base commune pour la syntaxe et les structures de COBOL, assurant l'uniformité et la compatibilité à travers différents compilateurs et environnements. Ces documents sont essentiels pour quiconque cherche à comprendre les fondements officiels de COBOL.

**Défense des Sources:**

- **Fiabilité et Autorité:** IBM et Micro Focus sont des acteurs majeurs dans le développement et la maintenance de COBOL. Leurs contributions à l'évolution du langage sont bien documentées, et leurs guides et documentations sont largement considérés comme des ressources fiables.

- **Complétude et Pertinence:** Les normes ISO/IEC pour COBOL offrent un cadre global qui garantit que les programmes sont écrits d'une manière qui est conforme et portable. Cela est crucial pour la maintenance à long terme et l'évolutivité des applications COBOL.

- **Mise à jour et Modernité:** Bien que COBOL soit un langage ancien, les ressources d'IBM et Micro Focus montrent comment il reste pertinent dans les environnements technologiques actuels, démontrant l'adaptabilité et la durabilité de COBOL.

**Conclusion:**

En s'appuyant sur des sources reconnues et fiables, cette analyse offre une compréhension claire et précise de la structure physique et logique de COBOL, ainsi que de ses éléments obligatoires et facultatifs. Ces informations sont essentielles pour quiconque travaille avec ou étudie COBOL aujourd'hui, soulignant l'importance de consulter des sources autorisées pour obtenir des informations exactes et à jour.