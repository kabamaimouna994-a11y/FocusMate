# Répartition technique et plan de commits – FocusMate

## 1. Membre 1 – Dashboard et gestion des tâches

**Branche :** `feature/dashboard-tasks`

**Responsabilités :**
- Authentification : connexion et inscription.
- Gestion des utilisateurs.
- Tableau de bord et statistiques.
- Gestion des tâches.
- Filtres et recherche.

**Fichiers attribués :**
- `index.html` : structure générale, authentification et dashboard.
- `js/app.js` : authentification, utilisateurs, tâches et statistiques.
- `css/style.css` : styles généraux, authentification, navigation, dashboard et tâches.

**Commits prévus :**
1. `test(auth): vérifie les parcours de connexion et inscription`
2. `feat(auth): améliore la validation des formulaires`
3. `feat(tasks): améliore les filtres et la recherche`
4. `feat(dashboard): améliore les statistiques et l'affichage`

## 2. Membre 2 – Calendrier, devoirs et objectifs

**Branche :** `feature/study-planning`

**Responsabilités :**
- Affichage du calendrier.
- Gestion des devoirs.
- Création et suivi des objectifs.

**Fichiers attribués :**
- `js/calendar.js`
- `js/assignments.js`
- `js/goals.js`
- `css/goals.css`
- `equipe/membre2.md`

**Commits prévus :**
1. `feat(calendar): améliore la navigation mensuelle`
2. `feat(assignments): complète la gestion des devoirs`
3. `feat(goals): ajoute la création des objectifs`
4. `feat(goals): ajoute le suivi de progression`

## 3. Membre 3 – Notes, ressources et concentration

**Branche :** `feature/personal-space`

**Responsabilités :**
- Gestion des notes.
- Gestion des ressources pédagogiques.
- Mode concentration.
- Documentation et intégration continue.

**Fichiers attribués :**
- `js/notes.js`
- `js/resources.js`
- `js/focus.js`
- `js/edit-delete.js`
- `css/notes.css`
- `css/resources.css`
- `css/focus.css`
- `README.md`
- `.gitignore`
- `.github/workflows/ci.yml`
- `equipe/membre3.md`

**Commits prévus :**
1. `feat(notes): améliore la gestion des notes`
2. `feat(resources): améliore la gestion des ressources`
3. `feat(focus): ajoute le mode concentration`
4. `docs(readme): documente le projet`
5. `ci(github): vérifie la syntaxe et lance les tests`

## 4. Travail collectif

Les trois membres participent :
- Aux tests de l'application.
- Aux revues de Pull Requests.
- À la résolution des conflits Git.
- À la validation des fonctionnalités.
- À la préparation des releases `v1.0.0` et `v1.0.1`.

Le fichier `tests/app.test.js` est géré collectivement.

## 5. Règles de collaboration

1. Chaque membre travaille sur sa propre branche.
2. Les branches sont créées à partir de `master`, après intégration de la base commune.
3. Chaque membre modifie uniquement les fichiers qui lui sont attribués.
4. Les commits respectent la convention Conventional Commits.
5. Les modifications sont régulièrement envoyées sur GitHub.
6. Chaque membre propose ses modifications par Pull Request.
7. Chaque Pull Request est relue par un autre membre avant fusion.
8. Les modifications de `index.html` sont coordonnées par le membre 1.
9. Toute modification d'un fichier attribué à un autre membre doit être discutée au préalable.

## 6. Objectif final

Obtenir une application fonctionnelle, testée et documentée, avec une branche `master` à jour, une CI verte et deux releases : `v1.0.0` et `v1.0.1`.