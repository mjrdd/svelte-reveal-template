# svelte-reveal-template

Everything you need to build a Svelte + Reveal.js + TailwindCSS project.

## Setup a new project

```bash
# clone the template in the repository
git clone https://github.com/mjrdd/svelte-reveal-template.git
```

## Developing

Once you've cloned the project template and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

Append your slides at `src/Slides.svelte`

```html
<script lang="ts">
	import { Code, Slide } from "$lib/components";
</script>

<!-- Add your slides here -->
```

## Building

To create a production version of your presentation:

```bash
npm run build
```

You can preview the production build with `npm run preview`.
