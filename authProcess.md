# Authentication with jwt

### Backend:-

1. **setup a graphql server using typegraphql and TypeORM**

- First, install TypeORM globally:
  `npm install typeorm -g`

- Next:
  `typeorm init --name folderName --database mysql`

- If you want ben awad ts.config
  `npx tsconfig.json`

- Install dependencies
  ` yarn add apollo-server-express bcryptjs cookie-parser cors dotenv graphql jsonwebtoken express pg type-graphql`

- Install as dev dependencies
  `yarn add -D @types/bcryptjs @types/cookie-parser @types/cors @types/express @types/graphql @types/jsonwebtoken @types/node`

- Upgrade packages(upgrade all the packages by using space bar),
  `yarn upgrade --latest`

- set user name and password(and other stuff) in the ormconfig.json

2. **Register a user**

3. Login and Create access and refresh tokens

// imp:- set request.credential="include"

4. Authenticated mutations/queries

5. Refresh the token

6. Revoke tokens for a user

### Frontend

1. Setup Apollo and GraphQl code Generator

2. React Router

3. Register/Login

4. Persisting session on refresh

5. Handling expired tokens

6. Fetching current user in header, etc...
