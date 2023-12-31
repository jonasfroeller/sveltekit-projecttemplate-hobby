# SvelteKit - Project Template

![Svelte](https://img.shields.io/badge/svelte-%23f1413d.svg?style=for-the-badge&logo=svelte&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

[![commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![gitHub license](https://badgen.net/github/license/jonasfroeller/SvelteKit_ProjectTemplate)](https://github.com/jonasfroeller/SvelteKit_ProjectTemplate/blob/master/LICENSE)
[![Buymeacoffee](https://badgen.net/badge/icon/buymeacoffee?icon=buymeacoffee&label)](https://buymeacoffee.com/jonasfroeller)

## Deployment

The project can be deployed to Vercel, Netlify or Cloudflare-Pages.

[![Vercel](https://therealsujitk-vercel-badge.vercel.app/?app=svelte-kit-project-template.vercel.app)](https://svelte-kit-project-template.vercel.app)
![CloudflarePages](https://img.shields.io/website/https/sveltekit-projecttemplate.pages.dev?logo=cloudflarepages&label=cloudlare)
![Netlify](https://img.shields.io/website/https/svelte-kit-project-template.netlify.app?logo=netlify&label=netlify)

## Tech Stack

-   **JS-Framework**: [SvelteKit](https://kit.svelte.dev/docs/creating-a-project)
-   **CSS-Utility-Class-Library**: [TailwindCSS](https://tailwindcss.com/docs/guides/sveltekit)
    -   [@tailwindcss/typography](https://tailwindcss.com/docs/typography-plugin)
    -   [@tailwindcss/aspect-ratio](https://github.com/tailwindlabs/tailwindcss-aspect-ratio)
    -   [@tailwindcss/container-queries](https://github.com/tailwindlabs/tailwindcss-container-queries)
-   **Translation**: [typesafe-i18n](https://github.com/ivanhofer/typesafe-i18n)
-   **Icons**: [iconify](https://iconify.design/docs/icon-components/svelte/)
-   **UI-Components**: [shadcn-svelte](https://github.com/huntabyte/shadcn-svelte)
-   **Code-Formatting**: [Prettier](https://prettier.io/)
-   **Code-Linting**: [Eslint](https://eslint.org/)
-   **Accessibility**: [autoprefixer](https://www.npmjs.com/package/autoprefixer), [rtlcss](https://www.npmjs.com/package/rtlcss)
-   **Performance**: [html-minifier](https://www.npmjs.com/package/html-minifier)

### Assets

**Fonts (google fonts but privacy-friendly)**: [api.fonts.coollabs.io](https://docs.coollabs.io/fonts/get-started)

## Development

### Important Commands

```bash
# install dependencies
npm i

# run development sever
npm run all

# or start the server and open the app in a new browser tab
npm run all -- --open

# build project
npm run build

# preview build
npm run preview
```

## Contributing

Install [commitizen](https://github.com/commitizen/cz-cli)

```bash
npm add -g commitizen
```

### Usage of Commitizen

Use `npm run commit` or `npx cz` instead of `git commit -m "..."`  
Use `npm run prepare` before committing the first time.
