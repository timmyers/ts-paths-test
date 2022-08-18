# Typescript example of using `paths` option for absolute imports

## To run
```
yarn ts-node ./index.ts
```

## Explanation
There are actually two things configured here:

- tsconfig.json `compilerOptions.paths`
This setting allows you to configure the desired path aliases.
This makes the typescript compiler happy.

- tsconfig.json `ts-node`
This makes the above actually work when using `ts-node`.