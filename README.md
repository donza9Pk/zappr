# zappr

Approvals for Github pull requests.

## Development

Export your [Github credentials](https://github.com/settings/applications):

```
export GITHUB_CLIENT_ID=<your-client-id>
export GITHUB_CLIENT_SECRET=<your-client-secret>
```

**Build & run:**

```
npm install
npm run build
npm start
```

**Debug client & server:**

```
npm run build-client -- -d
npm run build-server -- -d
npm run run-all
```

Enable debug logs...

...in the terminal:

```
export DEBUG="zappr:*"
```

...in the browser console:

```
window.DEBUG.enable('zappr:*')
```

**Test:**

```
npm test
```

**Docker image:**

```
./tools/build.sh
```

## Documentation

You can find the documentation [here](doc/readme.md).
