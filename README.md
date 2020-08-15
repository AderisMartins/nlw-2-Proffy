# nlw-2

## 💻 Projeto
Projeto criado durante a NLW-2 promovido pela [Rocketseat](https://rocketseat.com.br/)

## Começando 🚀

#### Web

##### Abrindo o diretório Web
```ps
$ cd web
$ yarn install
```

##### Start no projeto
```ps
$ yarn start
```

##### Instalando dependências, só são usados caso tenha problemas em rodar o comando "yarn install"
```ps
$ yarn add @types/react-router-dom -D
$ yarn add axios
```

##### Para iniciar o server e necessário dar um start no banco: 
```ps
$ yarn knex:migrate
```

#### Server

##### Abrindo o diretório Server
```ps
$ cd server
$ yarn install
```

##### Start no projeto
```ps
$ yarn start
```

##### Instalando dependências, só são usados caso tenha problemas em rodar o comando "yarn install"
```ps
$ yarn add @types/cors -D
$ yarn add @types/express -D
$ yarn add ts-node-dev -D
$ yarn add knex
```

#### Mobile

##### Abrindo o diretório Mobile
```ps
$ cd mobile
$ yarn install
```

##### Start no projeto
```ps
$ yarn start
```
##### Instalando dependências, só são usados caso tenha problemas em rodar o comando "yarn install"

##### Instalando fontes usadas
```ps
$ expo install expo-font @expo-google-fonts/archivo
$ expo install expo-font @expo-google-fonts/poppins
```

##### Instalando dependências
```ps
$ yarn add @react-navigation/native
$ expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
$ yarn add @react-navigation/stack
$ yarn add @react-navigation/bottom-tabs
$ yarn add axios
$ expo install @react-native-community/async-storage
```
