# Availabe Command

1. Run development enviroment `yarn watch`

# Config database enviroment file
1. Env file for development `cp env.example env.development`
2. Env file for production `cp env.example env.production`

# Database Migration

1. Create database `npx sequelize-cli db:create`

2. Create that table in database `npx sequelize-cli db:migrate`

3. Creating seed `npx sequelize-cli seed:generate`

4. Running seed `npx sequelize-cli db:seed:all`
