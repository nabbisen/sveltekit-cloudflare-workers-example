# SvelteKit + CloudFlare Workers example

## A `wrangler` skeleton project

### Install `wrangler`

```sh
bun install -D wrangler@latest
```

### Create a project

```sh
# in an empty directory
bunx wrangler init ./ -y
```

Test it:

```sh
bunx wrangler dev
```

## A `wrangler` project where SvelteKit is integrated into

### Create a project

```sh
bun create cloudflare@latest myproject --framework=svelte
```
