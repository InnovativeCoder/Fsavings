![An application for personal finance](https://res.cloudinary.com/dj3ua4rkx/image/upload/v1675546670/fsavings/logo_dwtoqn.png)

# FSavings

- **Framework**: [Next.js](https://nextjs.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
<!-- - **Content**: [Notion API](https://developers.notion.com) -->
- **Database**: [Supabase](https://supabase.com)
- **Open Graph Images**: [Cloudinary](https://cloudinary.com)
  <!-- - **Newsletter**: [Revue](https://www.getrevue.co) -->
  <!-- - **Deployment**: [Vercel](https://vercel.com) -->

## Project Overview

- `components/*` - Various components used throughout the site.
- `layouts/*` - The different layout options available to use on each page.
- `lib/*` - Short for "library", a collection of helpful utilities or code for external services.
- `pages/api/*` - [API routes](https://nextjs.org/docs/api-routes/introduction)
<!-- - `pages/blog/*` - Static pre-rendered blog pages that fetch information from the Notion API. -->

- `pages/*` - All other static pages.
- `public/*` - Static assets including robots.txt
- `styles/*` - A handful of global styles, and reusable classes utilzing @apply with Tailwind.
- `data/*` - a simple object containing global data about the site.

## Running Locally

```bash
$ npm install
$ npm run dev
```

Create a `.env` file similar to `.env.example` and include the appropriate keys.

## Notion Article Template

Duplicate [the following Notion database](https://www.notion.so/0d3e00c6bbe54231897b9fcbc7747f78?v=4d7f0006d9a144b5bd8b9251f2ec39cd), grab the database ID and add it to the environment variables in the `.env` file.
