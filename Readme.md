# Test-Backend

# TEST USING EXPRESSJS
Express.js.

# STACKS

- Node.js 
- Express.js 
- Sequelize
- MySQL 

# HOW TO Install

 git clone https://github.com/imam347/BTS-Test.git

# Install Library
Npm install

# CREATE env and edit
 ```bash

    NODE_ENV="development"

    MYSQL_DB_HOST="localhost"
    MYSQL_DB_PORT=3306
    MYSQL_DB_USER="root"
    MYSQL_DB_PASS="root"
    MYSQL_DB_NAME="bts-test"

    JWT_SECRET="Testing123"
    JWT_EXPIRES_IN="12h"
 ```

# MIGRATE
 npx sequelize-cli db:migrate


# RUNNING
 npm run start