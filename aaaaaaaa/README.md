# aaaaaaaaaaa

## Basic Stuff

### Install:

Locally: `npm i --save-dev typescript`
Globally: `npm i -g typescript`

### Set up .tsconfig.json

`tsc --init`

### Target `dist` dir as out

````JSON
{
  "compilerOptions": {
    ...

    "outDir": "./dist"
    ...
  }
}
```

### Compile

`tsc`

This will use the .tsconfig as information on how to process things, by default it is assumed that .tsconfig's location is the root directory of the Typescript project

### Add as `build` script

Within package.json:

```
{ 
  ...
  "scripts": {
    "build": "tsc",
    ...
  },
  ...
}
```

### Hooray

I guess
