# Les servlets — Travail de groupe

Présentation, exercice, QCM, résumé et projet sur le sujet **Les servlets** (Java).

## Équipe
Habib Hamrouni · Mariem Hamdi · Ranim Hasni · Syrine Ghorbel · Yasmine Jaoua · Yassine Ghariani

## Dates
- Meeting en ligne d'avancement avec l'enseignant : dans environ une semaine
- Présentation devant la classe : **lundi 30 novembre**

## Environnement commun
| Outil | Version |
|---|---|
| Java | 17 |
| Maven | 3.9+ |
| Tomcat | 9 (`javax.servlet`) — à confirmer au vote |
| IDE | libre (Eclipse, IntelliJ, VS Code) |

## Lancer le projet
1. Cloner : `git clone <lien-du-depot>`
2. Ouvrir le dossier `projet/` comme projet **Maven** dans ton IDE
3. Configurer un serveur Tomcat 9 et déployer le `war`
4. Ouvrir http://localhost:8080/servlets-projet/ (le chemin dépend de ta config)

## Structure
- `presentation/` : slides
- `exercice/` : énoncé + correction
- `qcm/` : QCM de fin de séance
- `resume/` : page résumé pour le groupe
- `projet/` : projet Maven (servlets + sujet d'un autre groupe)

## Répartition des tâches
| Partie | Contenu | Responsable |
|---|---|---|
| 1 | Introduction, conteneur, cycle de vie | |
| 2 | doGet/doPost, request/response, formulaires, mapping | |
| 3 | Sessions, cookies, RequestDispatcher | |
| 4 | Exemple illustratif (démo) | |
| 5 | Exercice + correction | |
| 6 | QCM + page résumé | |
| 7 | Idée et prototype du projet | |

## Règles Git
- Chacun travaille sur sa branche : `git checkout -b prenom-partie`
- `git pull` avant de commencer, commits fréquents et messages clairs
- Ne pas modifier la partie d'un autre sans le prévenir
- Fusion dans `main` par pull request
