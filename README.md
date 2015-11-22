Normal run:
```
node bin/tsc.js -m amd -p src/services --diagnostics
```

Run with doing gc after parsing:
```
node --expose-gc bin/tsc.js -m amd -p src/services --diagnostics

```