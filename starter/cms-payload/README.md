---
name: Payload with Next.js Starter
slug: cms-payload
description: Next.js app with Payload, all in one repo.
framework: Next.js
useCase:
  - Starter
css: CSS Modules
deployUrl: https://vercel.com/new/git/external?repository-url=https://github.com/vercel/examples/tree/main/starter/cms-payload&project-name=cms-payload&repository-name=cms-payload
demoUrl: https://nextjs-vercel.payloadcms.com
relatedTemplates:
  - blog-starter-kit
  - nextjs-boilerplate
  - isr-blog-nextjs-wordpress
---

# Next + Payload Serverless Demo

This example shows how to utilize `@payloadcms/next-payload` to deploy Payload serverless, in the same repo alongside of a Next.js app.

## Demo

https://cms-payload.vercel.app

## Deploy your own

Deploy the example using [Vercel](https://vercel.com?utm_source=github&utm_medium=readme&utm_campaign=next-example):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https://github.com/vercel/examples/tree/main/starter/cms-payload&project-name=cms-payload&repository-name=cms-payload)

## Clone and Deploy

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), or [pnpm](https://pnpm.io) to bootstrap the example:

```bash
npx create-next-app --example cms-payload cms-payload-app
```

```bash
yarn create next-app --example cms-payload cms-payload-app
```

```bash
pnpm create next-app --example cms-payload cms-payload-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).

Fill out the same environment variables that are shown in the `.env.example` with your own values, and then you're good to go!

### Developing locally

To develop with this package locally, make sure you have the following required software:

1. MongoDB
2. Node + NPM / Yarn
3. An S3 bucket to store media (optional)

### Getting started

Follow the steps below to spin up a local dev environment:

1. Clone the repo
2. Run `yarn` or `npm install`
3. Run `cp .env.example .env` and fill out all ENV variables as shown
4. Run `yarn dev` to start up the dev server

From there, you can visit your admin panel via navigating to `http://localhost:3000/admin`. Go ahead and start working!
