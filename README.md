Only non-generated files are `/assets` (and `/capacitor.config.json` is generated but it makes sense to change it sometimes).

Install deps
```
  yarn
```

Copy files after updating
```
  yarn run cap sync
```

Open android studio on this project (not needed after updates)
```
  yarn run cap open android
```

Run the app with button `debug 'app'` (top right), see console in tab `Debug` (bottom left).