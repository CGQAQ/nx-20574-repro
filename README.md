# 20574 repro repo

1. `npx nx@latest init`
2. `nx g @nx/next:app my-new-app`


if you use this repo, just run step two:
```console
$ nx g @nx/next:app my-new-app

 >  NX   Unable to resolve @nx/next:app.

   unable to find tsconfig.base.json or tsconfig.json
   Pass --verbose to see the stacktrace.

```

# Following https://github.com/nrwl/nx/issues/20574#issuecomment-1854602947
3. `npm init -y`
4. `npm install --save-dev @nx/next`
5. `nx g @nx/next:app my-new-app` 

it works now, but I don't want my root folder to be a npm package.