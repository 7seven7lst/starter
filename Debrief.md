# Installs

## If we want to create migration and initial db config

1. `npm install sequelize-cli -g`
2. cd into your repo, then 
3. `sequelize init ` will create initial scafold of the folder structure
3. `sequelize migration:create` to create a migration file in the /migration folder
3. `sequelize db:migrate` will migrate all the migration 
4. `sequelize db:migrate:undo` will revert ONLY the latest migration 



