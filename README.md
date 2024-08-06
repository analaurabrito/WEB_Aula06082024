# Lista de comandos usados no projeto

npm init -y
npm i tyscript
npx tsc --init

npm run dev
npm i ts-node

npm run build

# Scripts tsconfig.json
"rootDir": "./src",
"outDir": "./build",

# Scripts package.json

"build": "npx tsc",
"dev": "npx ts-node ./src/server.ts",