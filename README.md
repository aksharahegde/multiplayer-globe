# Multiplayer Globe App with Nuxt

Display website visitor locations in real-time using [Nuxt](https://nuxt.com) and [NuxtHub](https://hub.nuxt.com).

[https://multiplayer-globe.nuxthub.workers.dev](https://multiplayer-globe.nuxthub.workers.dev)

<a href="https://multiplayer-globe.nuxthub.workers.dev">
<img src="./public/og-image.png" alt="Multiplayer Globe App with Nuxt" />
</a>

## Credits

Inspired by <a href="https://github.com/cloudflare/templates/tree/main/multiplayer-globe-template">Cloudflare's multiplayer-globe-template</a>.

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

> [!TIP]
> A random location is generated in development as we don't have access to Cloudflare's geolocation data on the incoming request.

## Production

Build the application for production:

```bash
pnpm build
```

## Deploy

> [!IMPORTANT]
> We are currently working on the `nuxthub deploy` command deployment to CF Workers with Durable Objects, make sure to follow us on [X](https://x.com/nuxt_hub) or sign-up on [NuxtHub](https://admin.hub.nuxt.com) to know when the feature is out!

