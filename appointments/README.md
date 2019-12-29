# Running tests

```
npm test
```

# Formatting code

```
npm run fmt
```

# Building the app

```
npm run build
```

# Checking out a specific file from a different branch/tag

```
git checkout tags/extracting-helpers -- src/sampleData.js
git checkout tags/chapter-2-exercises -- dist/styles.css
```

# Running git diff on a specific branch/tag while excluding some directories/files 

```
git diff tags/appointment-first-name -- . ':!node_modules' ':!package-lock.json' ':!README.md' ':!package.json'
```

# Running git diff on a specific file

```
git diff tags/extracting-helpers -- test/AppointmentsDayView.test.js
```
