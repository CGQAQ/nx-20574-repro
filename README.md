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
