## Typescript learning

# Installing the typescript globally

## Installation

make new folder on desktop

```bash
  cd folder_you_created
  code .
  npm i -g typescript
```

## Configuring the Tsc Config file to compile the files locally

```bash
  tsc --init
```

this will create a file name : tsconfig.json
on a folder

Now how to configure it

```bash
 {
  "compilerOptions": {
    "target": "es2016",
    "module": "ES6",
    "rootDir": "./src",
    "outDir": "./dist",
    "noEmitOnError": true,
    "esModuleInterop": true,
    "forceConsistentCasingInFileNames": true,
    "strict": true,
    "skipLibCheck": true
  }
}
```

So you have index.ts file in src folder . So when you run the below command

```bash
  tsc
```

This will compile and make a new file in a dist folder
