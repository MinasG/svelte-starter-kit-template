# SvelteKit starter template with TS & tailwindcss

## Feel free to use this template for your next project.

You can either click the `Use this template` button on the top right or if you like netlify you can deploy it straight away with the button below 👇🏼

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/MinasG/svelte-starter-kit-template)

## Progressive Web App (PWA)

This template is setup as a PWA.

You can change your PWA settings inside the `manifest.json` file inside the `static` directory. [This documentation](https://web.dev/add-manifest/) around the manifest.json is extremely useful to help you understand the various settings.

```
"short_name": "SvelteKit starter",
"name": "SvelteKit starter",
"start_url": "/",
"background_color": "#6366f1",
"display": "fullscreen",
"scope": "/",
"theme_color": "#6366f1",
"description": "SvelteKit starter",
```

If you don't wish for your app to be a PWA, you can delete all the images for the various devices (e.g: `android`, `apple` etc) inside the `static/images` directory. Followed by the `manifest.json` inside the `static` directory. The `service-worker.ts` inside the `src` directory and finally delete the following three lines inside the `app.html` which is also in the `src` directory.

```
<meta name="theme-color" content="#6366f1" />
<link rel="manifest" crossorigin="use-credentials" href="manifest.json" />
<link rel="apple-touch-icon" href="%sveltekit.assets%/images/apple/192.png" />
```

### Buy Me A Coffee

If I made your life easier or made you laugh, please feel free to buy me a cofee or pizza or whatever!

[![Buy Me A Coffee](https://minasg.com/images/buy-me-coffee.svg)](https://www.buymeacoffee.com/MinasG)

---

# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

## Developing

Once you've created a project and installed dependencies with `yarn` (or `npm install` or `pnpm install`), start a development server:

```bash
yarn dev

# or start the server and open the app in a new browser tab
yarn dev -- --open
```

## Building

To create a production version of your app:

```bash
yarn build
```

You can preview the production build with `yarn preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
