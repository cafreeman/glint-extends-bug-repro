# Glint Extends Bug Repro

Contains two packages: `config` and `consumer`. `config` contains a tsconfig with glint configuration. `consumer` extends `config` and tries to run glint

```
pnpm install
cd packages/consumer
pnpm check
```

You should see that Glint complains that no configuration could be found.
