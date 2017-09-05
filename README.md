# Plateforme ADAPTAC

## Architecture technique

### BDD
PostgreSQL (instance Amazon RDS micro)

### Serveur
- instance Amazon EC2 nano
- Node.js
- Koa.js
- TypeScript

### Client
- Ionic hybride
- TypeScript
- RxJS


## Architecture logique

Le client communique avec le serveur via GraphQL.

Le serveur communique avec la BDD via ... (à définir)

## Environnement de développement

### IDE
Pour assurer un format identique quel que soit l'IDE utilisé, l'indentation est défine au niveau du fichier .editorconfig à la racine du projet. Il faut donc s'assurer que l'IDE que l'on utilise prend bien en compte ce fichier. Pour VS Code, il faut installer le plugin correspondant.
