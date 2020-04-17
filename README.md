# Package starter kit

### Simple rules to follow
1. Update package.json file with a proper git url and needed package name instead of `@orgname/packagename`
2. ALWAYS use index.ts as entry/export point at src/index.ts
3. Package is prepared to be used with absolute paths for folders inside of `src`, so if you package is under `src/my-package` you can use `import smth from 'my-package'`
