# ts-bookshelf-api

1. initialize project
```shell
npm init --y
```

2. install typescript
```zsh
npm install --save-dev typescript
```

3. Create tsconfig.json then paste this json
```
{
  "compilerOptions": {
    "module": "commonjs",
    "esModuleInterop": true,
    "target": "es6",
    "moduleResolution": "node",
    "sourceMap": true,
    "outDir": "dist"
  },
  "lib": ["es2015"]
}
```

4. Create app.ts with this simple code
```
console.log('Hello Typescript');
```

5. Compile ts file to js
```zsh
npx tsc
```

6. Run the app.js
```zsh
node dist/app.js
```
