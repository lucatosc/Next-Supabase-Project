This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) that allows new users to be registered to a Supabase database.


## Getting Started
Check out the article I wrote at https://aboutmonica.com/blog/creating-new-supabase-users-in-next-js/ for more context into how to use this example application.

Setup a project in Supabase https://supabase.io/ and configure your env variables to have:


```bash
export SUPABASE_KEY="SUPABASEKEYFROMSETTINGSSCREEN"
export SUPABASE_URL="SUPABASEURLFROMSETTINGSSCREEN"
```

The key and URL values should be replaced with those found in your Supabase project.

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform] from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
