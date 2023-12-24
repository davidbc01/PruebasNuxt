# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm run dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm run build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm run preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.

<hr>

## Instalación de Tailwind

Ejecutar los siguientes comandos
```sh
npm install -D tailwindcss postcss autoprefixer
```
```sh
npx tailwindcss init
```

Añadir al archivo *nuxt.config.js* este contenido
```sh
postcss: {
    plugins: {
      tailwindcss: {},
      autoprefixer: {},
    },
  },
```

Añadir al archivo *tailwind.config.js* este contenido
```sh
content: [
    "./components/**/*.{js,vue,ts}",
    "./layouts/**/*.vue",
    "./pages/**/*.vue",
    "./plugins/**/*.{js,ts}",
    "./app.vue",
    "./error.vue",
  ],
```

Crear un nuevo directorio con el archivo **main.css** en *./assets/css/main.css* con el siguiente contenido
```sh
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Modificar de nuevo el archivo *nuxt.config.js* con este contenido
```sh
css: ['~/assets/css/main.css'],
```

<hr>

Para la creación de los proyectos con este framework ejecutar este comando (o ver la [docu](https://tailwindcss.com/docs/guides/nuxtjs)):
```sh
npx nuxi@latest init PruebasNuxt
```

<hr>

## Instalación de Flowbite

Ver proceso de para instalar en la [página oficial](https://flowbite.com/docs/getting-started/nuxt-js/#install-flowbite).