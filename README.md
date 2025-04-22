This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

### Set Up Project:

```
npx create-next-app@latest --typescript
```
* You should have an existing Next.js project or create a new one using the following command:
```
npm i drizzle-orm
npm i -D drizzle-kit
```
* You should have installed Drizzle ORM and Drizzle kit. You can do this by running the following command:
```
npm i @neondatabase/serverless
```
* You should have installed the dotenv package for managing environment variables.
```
npm i dotenv
```
* Push Connection String With Database PSQL
```
npx drizzle-kit push
```
* Generate migrations:
```
npx drizzle-kit generate
```
* Apply migrations:
```
npx drizzle-kit migrate
```
Document Reference: https://orm.drizzle.team/docs/tutorials/drizzle-nextjs-neon

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
