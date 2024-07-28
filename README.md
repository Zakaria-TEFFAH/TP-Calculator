# TP-Calculator


***********************************************
Cette application de calculatrice est développée en React. Elle propose des opérations de base comme l'addition et la soustraction. Elle enregistre les activités dans un fichier de log, intègre ces logs dans Elasticsearch via Logstash, visualise les logs avec Kibana, inclut des tests unitaires et utilise GitHub Actions pour l'intégration continue et le linting.

Fonctionnalités
Opérations de calcul : addition et soustraction.
Enregistrement des logs dans un fichier local.
Intégration des logs dans Elasticsearch avec Logstash.
Visualisation des logs dans Kibana avec un tableau de bord.
Tests unitaires pour certaines fonctions de l'application.
Pipeline CI/CD avec GitHub Actions pour exécuter les tests et le linter.

**************************************************************************

Tests
Pour exécuter les tests unitaires :

sh
Copier le code
npm test
******************************************************
CI/CD avec GitHub Actions
Le pipeline GitHub Actions est configuré pour exécuter les tests et le linter à chaque push sur la branche main. La configuration se trouve dans .github/workflows/ci.yml.
