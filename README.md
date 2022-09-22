# Vite + Deno

This is an example repo of running Vite with Deno.

You can see live site at: https://vite-deno-example.deno.dev

This repo is based on `vue` template for Vite:
https://stackblitz.com/edit/vitejs-vite-ifm7jc?file=index.html&terminal=dev

## Running

You need to have Deno v1.25.4 or later intalled to run this repo.

Start a dev server:

```
$ deno task dev
```

Build production assets:

```
$ deno task dev
```

Start a production server: _(requires build first)_

```
$ deno task serve
```

// TODO: add build step with Deno Deploy

## Papercuts

Currently there are two "papercuts" for Deno users:

- peer dependencies need to be referenced in `vite.config.js` - in this example
  it is only `vue` package that needs to be referenced
- `package.json` is still required because of CommonJS resolution
