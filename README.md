# template-sveltekit-package

This is a [SvelteKit](https://kit.svelte.dev/) package project which I use as a [GitHub template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template):

## Keeping dependencies up-to-date

I update dependencies regularly. These are the steps:

1. Run `pnpm create svelte@latest .` to regenerate the SvelteKit skeleton project into the existing directory.
1. **Where should we create your project?** Hit enter to use the current directory.
1. **Directory not empty. Continue?** Yes.
1. **Which Svelte app template?** Library project.
1. **Add type checking with TypeScript?** Yes, using JavaScript with JSDoc comments.
1. Add ESLint, Prettier and Vitest.
1. Revert `README.md`.
1. Delete folder `node_modules` and file `pnpm-lock.yaml` and run `pnpm i`.
