<h1>Compte rendu Activite 4: Spring Security</h1>


<h2>Structure du projet:</h2>

Ce projet contient quatre packages principaux (entities,repository,security,web), la classe `HospitalAppApplication` et le dossier templates

Le package `entities` contient les classes d'entité suivantes:

- `Patient`: décrit un patient avec des informations telles que le nom, la date de naissance, etc.

Le package `repository` contient les interfaces de repository suivantes:

- `PatientRepository`: fournit des méthodes pour interagir avec la base de données pour la classe `Patient`.

Le package `security` contient les classes de configuration suivantes qui existe dans different packages pour l'authentification et l'autorisation des utilisateurs:
Les trois packages qui sont sous ce package la:

Le package `security` contient les classes de configuration suivantes pour l'authentification et l'autorisation des utilisateurs:

- `SecurityConfig`: configure la sécurité de l'application.

Le package `security.entities` contient les classes d'entité suivantes pour l'authentification et l'autorisation des utilisateurs:

- `AppRole`: décrit un rôle d'utilisateur pour l'authentification et l'autorisation.
- `AppUser`: décrit un utilisateur avec des informations telles que le nom d'utilisateur, le mot de passe, etc.

Le package `security.repo` contient les interfaces de repository suivantes pour l'authentification et l'autorisation des utilisateurs:

- `AppRoleRepo`: fournit des méthodes pour interagir avec la base de données pour la classe `AppRole`.
- `AppUserRepo`: fournit des méthodes pour interagir avec la base de données pour la classe `AppUser`.

Le dossier `templates` contient les pages HTML suivantes:

- `editPatient.html`: page pour modifier les informations d'un patient.
- `formPatient.html`: page pour ajouter un nouveau patient.
- `template.html`: barre de navigation commune à toutes les pages.
- `patients.html`: page pour afficher une liste de patients.
- `login.html`: page pour l'authentification des utilisateurs.
- `noAuthorized.html`: page pour afficher un message d'erreur lorsque l'utilisateur n'est pas autorisé à accéder à une page.





