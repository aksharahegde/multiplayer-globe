# Multiplayer Globe App with Nuxt

Display website visitor locations in real-time using [Nuxt](https://nuxt.com) and [NuxtHub](https://hub.nuxt.com).

[https://multiplayer-globe.nuxthub.workers.dev](https://multiplayer-globe.nuxthub.workers.dev)

<a href="https://hello.nuxt.dev">
<img src="https://github.com/nuxt-hub/hello-edge/assets/904724/99d1bd54-ef7e-4ac9-83ad-0a290f85edcf" alt="Hello World template for NuxtHub" />
</a>

## Features

- Server-Side rendering on Cloudflare Workers
- ESLint setup
- Ready to add a database, blob and KV storage
- One click deploy on 275+ locations for free

## Setup

Make sure to install the dependencies with [pnpm](https://pnpm.io/installation#using-corepack):

```bash
pnpm install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
pnpm dev
```

Note that a random location is generated in development as we don't have access to Cloudflare's geolocation data on the incoming request.

## Production

Build the application for production:

```bash
pnpm build
```

## Deploy

Deploy the application on the Edge with [NuxtHub](https://hub.nuxt.com) on your Cloudflare account:

```bash
npx nuxthub deploy
```

Then checkout your server logs, analaytics and more in the [NuxtHub Admin](https://admin.hub.nuxt.com).

You can also deploy using [Cloudflare Pages CI](https://hub.nuxt.com/docs/getting-started/deploy#cloudflare-pages-ci).

