Step by step

`$` means that use terminal.

1. `$` `npm install / yarn install`
2. edit config/config.json
3. create database that name is `st2de`
4. export NODE_ENV=development or set NODE_ENV=development (Windows)
5. `$` `./node_modules/sequelize-cli/lib/sequelize db:migrate`
6. `$` `./node_modules/sequelize-cli/lib/sequelize db:seed:all`
7. `$` `npm start`

then, go to: http://localhost:3000/api/tasks or http://localhost:3000/tasks
