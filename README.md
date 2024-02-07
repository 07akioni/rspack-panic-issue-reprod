# rspack-panic-issue-reprod

```
pnpm i
pnpm dev

# Then save main.tsx
```

Note:

You need to enable (just like current rspack.config.js): 

```
experiments: {
    rspackFuture: {
      newTreeshaking: true,
    },
  },
```

to make it panic.