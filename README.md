# Typescript NodeJS minimal starter

This repo contains all setup required to run a basic typscript NodeJS application.

## npm run-scripts

To build your typescript application run: `npm run build`
To run your application run: `npn run start`
To rebuild and run you application in a single command: `npm run dev`

## Typescript configuration

The `tsconfig.json` file contains all typescript compiler settings. I always turn on all the strict options to reduce the number of runtime issues.

## Prettier

This project uses prettier in a pre commit hook to enforce consistend formatting. https://prettier.io/docs/en/precommit.html
