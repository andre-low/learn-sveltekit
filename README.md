# Learning SvelteKit

Creating a Twitter clone by following along with Joy of Code's Full Stack SvelteKit for Beginners
- [Blog post](https://joyofcode.xyz/sveltekit-for-beginners)
- [YouTube playlist](https://www.youtube.com/playlist?list=PLA9WiRZ-IS_zXZZyW4qfj0akvOAtk6MFS)
- [GitHub repo (update migrated branch)](https://github.com/JoysOfCode/sveltekit-for-beginners/tree/migration)

The tutorial was originally written for the pre-release-candidate version of SvelteKit. There have since been several [breaking changes](https://github.com/sveltejs/kit/discussions/5748) for the [release candidate](https://svelte.dev/blog/whats-new-in-svelte-october-2022), so I will also be referencing the latest [SvelteKit documentation](https://kit.svelte.dev/docs/introduction) where appropriate. The GitHub repo for the tutorial project also has an [updated branch with the relevant changes](https://github.com/JoysOfCode/sveltekit-for-beginners/tree/migration), but the written tutorial has not been updated.

## Styling
I will be using [TailwindCSS](https://tailwindcss.com/docs/guides/sveltekit) for styling instead of the CSS in the tutorial.

Tailwind resources:
- [Tailwind Awesome](https://www.tailwindawesome.com/): Showcase of nice Tailwind templates and UI kits, some free, some paid
- Pre-built components, code-snippets using native Tailwind utility classes:
  - [Hyper UI](https://www.hyperui.dev/)
  - [Flowbite](https://flowbite.com/)
  - [Lofi UI](https://codepen.io/collection/DqLkab)
  - [Meraki UI](https://merakiui.com/)
  - [MambaUI](https://www.mambaui.com/)
- Pre-built components, custom classes (think Bootstrap syntax):
  - [Daisy UI](https://daisyui.com/)

## create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

### Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm create svelte@latest

# create a new project in my-app
npm create svelte@latest my-app
```

### Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

### Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.
