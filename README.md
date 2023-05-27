# https://github.com/vercel/turbo/issues/5098

- Install and use node 20 (nvm, fnm, volta, etc)
- Run npm install
- Run npm run build
- See exit code is 0


Reproduces even if you cd into the docs directory and run command there without turbo

```
cd apps/docs
npm run build
```
