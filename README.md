## Notes

1. Uncomment rootDir and outDir. Once that is done just run tsc with no args
2. tsc -w Will continually watch for any changes

## Commands

```javascript
    tsc --init
    tsc -w
    npm init -y
    npm install nodemon concurrently

    "start:build": "tsc -w",
    "start:run": "nodemon build/index.js",
    "start": "concurrently npm:start:*"
```
