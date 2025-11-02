# TD-API-NodeJS
Ce TD a pour but de nous apprendre à faire une API local à l'aide de Node.js <br>

# Structure du projet

```
TD-API-NodeJS/
├── src/
│   ├── controllers/
│   │   └── userController.ts
│   ├── routes/
│   │   └── userRoutes.ts
│   ├── app.ts
│   └── server.ts
├── .env
├── tsconfig.json
├── package.json
└── README.md
```

# Le necessaires

Principale : express, dotenv <br>
Developpement : typescript ts-node <br>

# Comment faire ?

```
git clone https://github.com/[ton_pseudo]/TD-API-NodeJS.git
cd TD-API-NodeJS
npm install
```

# Lancement du serveur

```
npm run build
npm start
```

Ou en mode développement :

```
npm run dev
```

Le serveur démarre sur le port défini dans `.env` :

```
PORT=4000

curl -X GET http://localhost:4000/users 
```
