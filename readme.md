# Martin Forsell 🎶🎷

Site for Martin Forsell :-)


## Development

```sh
$ npm run start
```

## Production

```sh
$ npm run build
```

## Deployment

Automatically deploys to [Surge](https://surge.sh/) on push to master, running the following script:
```json
...
  "git": { 
    "scripts": { 
      "pre-push": "npm run build && surge --project ./dist --domain martinforsell.surge.sh"
    }
```