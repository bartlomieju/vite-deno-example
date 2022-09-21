# Vite + Deno

This is an example repo of running Vite with Deno.

This is based on `vue` template for Vite: https://stackblitz.com/edit/vitejs-vite-ifm7jc?file=index.html&terminal=dev

## Papercuts

Currently there are two "papercuts" for Deno users:
- peer dependencies need to be referenced in `vite.config.js` - in this example
it is only `vue` package that needs to be referenced
- `package.json` is still required because of CommonJS resolution