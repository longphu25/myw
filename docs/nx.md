# NX

## Simple NX
Here are some things you can do with Nx:

- Add UI library

```bash
# Generate UI lib
nx g @nx/react:lib ui
```

```bash
# NX   👀 View Details of ui
# Run "nx show project ui --web" to view details about this project.
nx show project ui --web
```

```bash
# Add a component
nx g @nx/react:component ui/src/lib/button
```

- View interactive project graph

```bash
nx show project ui --web
```

- View project details

```bash
nx graph
```

- Run affected commands

```bash
# see what's been affected by changes
nx affected:graph
# run tests for current changes
nx affected:test
# run e2e tests for current changes
nx affected:e2e
```

## Shadcn-UI
[Monorepo Setup with Nx , Nextjs & Shadcn-UI](https://medium.com/readytowork-org/monorepo-setup-with-nx-nextjs-and-shadcn-ui-3b72c3599470)

```bash
nx g @nx/react:lib shared

pnpm install tailwindcss-animate class-variance-authority clsx tailwind-merge
```
TASK : https://medium.com/readytowork-org/monorepo-setup-with-nx-nextjs-and-shadcn-ui-3b72c3599470
https://github.com/bj-budhathoki/nx-shadcn/blob/main/shared/src/components/ui/button.tsx
https://egghead.io/lessons/next-js-run-an-nx-generator-with-the-nx-console-vscode-extension

https://nx.dev/recipes/storybook/overview-react
https://github.com/nrwl/nx/blob/master/docs/generated/packages/nx/documents/watch.md
https://blog.nrwl.io/easy-documentation-with-docusaurus-and-nx-4b932d8ad0e4
https://nx.dev/concepts/buildable-and-publishable-libraries#publishable-libraries
https://nx.dev/nx-api/storybook/documents/best-practices
https://github.com/nrwl/nx-examples
https://nx.dev/recipes/module-federation/federate-a-module
https://nx.dev/getting-started/installation
https://github.com/nrwl/nx-recipes/tree/main/react-monorepo
https://nx.dev/getting-started/tutorials/react-monorepo-tutorial
https://nx.dev/getting-started/tutorials/react-monorepo-tutorial#inferred-tasks