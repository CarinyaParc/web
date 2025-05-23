# CarinyaParc/web

This monorepo contains our farm website.

- [carinyaparc.com.au](https://carinyaparc.com.au) - our farm website and blog

## What's inside?

We're using [Turborepo](https://turbo.build/repo) to manage this monorepo because
there's a lot going on.

### apps/

Each directory in the apps folder is a separate website that we deploy. The name
of the directory always corresponds to the domain name of the website:

- `sites/carinyaparc.com.au` is the website for the farm. It, and the
  rest of sites, are built with [Next.js](https://nextjs.org/), [Sanity.io](https://sanity.io), [TailwindCSS.com](https://tailwindcss.com), and [shadcn/ui](https://ui.shadcn.com/).

### packages/

The packages in this monorepo are reusable self-contained bits that we want to
share across our apps and websites. Much of it is configuration for the different
tools we use:

- `packages/eslint-config`
- `packages/tailwind-config`
- `packages/typescript-config`
- `packages/ui` is a React component library that contains any components that
  we want to share across our websites. The package encompasses everything from
  page layouts, UI building blocks, and complex widgets. We often use
  [Shadcn](https://ui.shadcn.com) when looking to add new components, and we style
  everything with [Tailwind](https://tailwindcss.com).

## Getting started

To run any of the websites locally, you'll first need to install the dependencies
and packages. We recommend using [pnpm](https://pnpm.io/) to manage your dependencies.

```sh
pnpm install
```

If you take a peek in `package.json` you'll see we have a few different scripts
to run our apps. If you just want to run everything at once, you can just do:

```sh
pnpm run dev
```

For everything else, there is an individual script to run each app independently:

- `pnpm run dev:reactflow.dev`




---

## Support our work

React Flow and Svelte Flow are open-source MIT-licensed libraries, and it will
be forever. Our libraries enable thousands of solo developers and organizations
like Stripe and Linkedin to build their node-based apps. With so many active
users, it takes time and effort to maintain the library, docs, and community.
We can’t do that without your support.

[<img src="./assets/readme-pro.png">](https://reactflow.dev/pro)

Why Subscribe? With your subscription, you are ensuring the sustainable
maintenance and development of both React Flow and Svelte Flow. This is how we
make sure these libraries stay MIT-licensed. In return, you get high-quality,
maintained, updated libraries, along with benefits like direct support,
prioritized feature requests, and access to our Pro Examples.

---

## Contact us

We're happy to try and answer any questions you have about our libraries. We're
also always excited when folks want to share their projects with us. There are
a few ways you can get in touch:

- Use the contact form on our [website](https://#.com/contact).
- Drop us an email at [info@x.com](mailto:info@x.com)