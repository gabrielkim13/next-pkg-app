This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app), including [pkg](https://github.com/vercel/pkg) support.

## Getting Started

First of all, install dependencies using [Yarn](https://yarnpkg.com/):

```sh
yarn
```

Run the `pkg` script to generate the single-binary executable for the sample Next.js application:

```sh
yarn pkg
```

Then run it with:

```sh
NODE_ENV=production ./next-pkg-app
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
  - [Custom Server](https://nextjs.org/docs/pages/building-your-application/configuring/custom-server) - used to override the directory in which the Next.js application searches for the `.next` and `public` directories.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

And also check out **pkg**'s [README](https://github.com/vercel/pkg).
