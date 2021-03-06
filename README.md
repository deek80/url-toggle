# URL Toggle

## Description
This Chrome extension lets you store a list of regular expression patterns and
replacements so you can quickly switch to a related site when
a match is detected.

For example, if you have the following pattern
and replacement:
```
pattern:     "https://(.+?)\.github\.io\/(.+?)\/.*"
replacement: "https://github.com/$1/$2/"
```

Then when you are on a hosted Github Pages site, this icon will
become enabled and let you navigate to the corresponding GitHub
repository with one click. You can add as many patterns and replacements as you like.

## Privacy/Security Notes
- Data is kept in Chrome synced storage (so available where you're signed in to Chrome on other computers)
- Data in storage is not encrypted so don't store any secrets
- No data is collected or transmitted to a third party by this extension
  (unless React or Chrome are doing something shady under the hood)
