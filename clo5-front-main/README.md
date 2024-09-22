# Quantum Motors Configurator FRONT

## Description

This project is a web application that provides a configurator for managing car configuration.
This repository contains the FRONT.

The application is built with Next.JS

## Features

- Make a configuration

## Installation && Run

Before you start, make sure you have Node.js v20, yarn and Quantum Motors Configurator API.

#### Fill the .env.local file on this repository

This is all environments variables

- DATABASE_URL : The database dsn => example : "mysql://user:@localhost:3306/quantum-motors?schema=public"

* NEXT_PUBLIC_API_URL: The API url (default : http://localhost:3000 )
* NEXT_PUBLIC_DISPLAY_REACT_QUERY_DEBUGGER: Enable react query debugger panel (default : true)

#### Install the dependencies:

`yarn install`

#### Usage

To start the server with dev environment, run:

`yarn dev`

The server will start on http://localhost:4200.

#### Lint

To run the linter :

`yarn lint`

### Prepare production

To publish your application to production, here are the instructions :

- Please set `NEXT_PUBLIC_DISPLAY_REACT_QUERY_DEBUGGER=false`
- To compile : `yarn build`
- And start : `yarn start`

# Pour lancer via docker

- MacOs : https://code.visualstudio.com/docs/setup/mac
- Windows : https://code.visualstudio.com/docs/setup/windows
- Linux : https://code.visualstudio.com/docs/setup/linux
- Installer l'application Expo sur votre smartphone

## Prérequis :

1. code .  
   cela va ouvrir votre projet sur vscode (assurez vous d'avoir lancer docker desctop)
2. ctrl+shift P , ensuite Dev Containers: Reopen in container  
   cela va creer tout les container du projet et initialiser la db avec toutes les tables

### pour installer toutes les dependances:
1. yarn start  
   l'application écoute sur : localhost:4200  

### Contributing

Contributions are welcome! Please read the contributing guidelines first.
