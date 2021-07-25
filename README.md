# Eleventy starter set (Nunjucks-based)

This is a starter set for the [Eleventy](https://11ty.dev) [static site generator (SSG)](https://staticgen.com). See the [online demo](https://eleventy-solo-starter-njk.vercel.app/). Of course, there are many **far better** ones on the [Eleventy “Starter Projects” page](https://www.11ty.dev/docs/starter/)!

## How to use

1. Clone this to a local repo.
2. Make appropriate changes to `/_data/metadata.json` and `_data/siteparams.json` to conform to your site’s parameters.
3. Run `npm install` to load all the dependencies in `package.json`, which includes Eleventy.
4. Run `npm run start` from your terminal app. You can then view the site in [http://localhost:8080](http://localhost:8080) on your computer.
5. Read the sample posts and their Markdown files to see how everything works.
6. Edit the content to make it your own!
7. When ready, [deploy the site](https://www.11ty.dev/docs/tutorials/#put-it-on-the-web) to your chosen host.

## What’s under the hood

- Build processing through [Vite](https://vitejs.dev), borrowing heavily from the [eleventy-with-vite](https://github.com/fpapado/eleventy-with-vite) repo by [Fotis Papadogeorgopoulos](https://github.com/fpapado), as explained in "[Eleventy + Vite = elite](https://www.brycewray.com/posts/2021/07/eleventy-vite-elite)."
- Responsive images through the [`eleventy-img` plugin](https://www.11ty.dev/docs/plugins/image/) and an `image` shortcode.
- [PostCSS](https://postcss.org) and [Tailwind CSS](https://tailwindcss.com). As of version 2.1.0, Tailwind includes the still-in-preview **[@tailwindcss/jit](https://github.com/tailwindlabs/tailwindcss-jit) library**; read more about it in [this announcement](https://blog.tailwindcss.com/just-in-time-the-next-generation-of-tailwind-css).