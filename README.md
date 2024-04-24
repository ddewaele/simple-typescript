## Simple TypeScript app


To create a new project from scratch execute the following instructions:

```
mkdir simple-typescript
cd simple-typescript
npm init -y
npm install --save-dev typescript
npm install --save-dev @types/node
```

The following tsconfig.json can be used:
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

## References

- https://www.digitalocean.com/community/tutorials/typescript-new-project