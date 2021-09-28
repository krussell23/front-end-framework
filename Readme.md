# Basic Framework For Front End Vanilla.js Projects

## Preflight Check
1. Run npm install from the framework root folder. This will create the node_modules and install the dependancies found in the package.json file.
```bash
  npm install
```

1. Run development build using the parcel bundler.
```bash
   npx parcel src/index.html
```
or
```
  npm start
```

1. Run production build using the parcel bundler.
```bash
   npx parcel build src/index.html
```
or
```
  npm run build
```

## Deploy to Netlify
1. Account at netlify
1. Click on team name slect sites tab
1. Site click on deploy from git
1. Select github
1. Show repo and select repo to build
1. Make sure to write the correct build command
```
  parcel build src/index.html
```

## VS Code
1. Make changes
1. Commit changes
1. Push changes to remote repo
1. Netlify detects changes and build new site