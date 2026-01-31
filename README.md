# Install

```
$ git clone git@github.com:77fdvarvam/github-globe.git --recursive && cd ./github-globe
$ npm install --force
```

# Usage

```
$ NODE_OPTIONS=--openssl-legacy-provider npm run dev
```

## Notes

For development purposes, we recommend using an empty `data.json` file to reduce loading time.  
Otherwise, `data.json` is populated by [77fdvarvam/github-stream](https://github.com/77fdvarvam/github-stream).

```
$ mv data.json data.json.bak
$ echo "[]" > data.json
```

It still fetches for `fallback.json` for now, but it reduces loading time...
