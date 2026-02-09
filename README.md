Repo to reproduce type issue using `@tailwindcss/vite` with Nuxt version 4.3.1.

`working-4.2.2/` contains a Nuxt project using Nuxt version 4.2.2. 
Once dependencies are installed, the project runs with no type errrors.

`latest-4.3.1/` contains a Nuxt project using Nuxt version 4.3.1. 
Once dependencies are installed, there is a type error in `nuxt.config.ts` when adding the tailwindcss vite plugin.