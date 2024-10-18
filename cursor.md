✨ Features
 Built with Astro and Tailwind CSS
 Smooth animations and page transitions
 Light / dark mode
 Customizable theme colors & banner
 Responsive design
 Comments
 Search
 TOC
🚀 How to Use
Generate a new repository from this template or fork this repository.
To edit your blog locally, clone your repository, run pnpm install AND pnpm add sharp to install dependencies.
Install pnpm npm install -g pnpm if you haven't.
Edit the config file src/config.ts to customize your blog.
Run pnpm new-post <filename> to create a new post and edit it in src/content/posts/.
Deploy your blog to Vercel, Netlify, GitHub Pages, etc. following the guides. You need to edit the site configuration in astro.config.mjs before deployment.
⚙️ Frontmatter of Posts
---
title: My First Blog Post
published: 2023-09-09
description: This is the first post of my new Astro blog.
image: ./cover.jpg
tags: [Foo, Bar]
category: Front-end
draft: false
`config.ts`
---
🧞 Commands
All commands are run from the root of the project, from a terminal:

Command	Action
pnpm install AND pnpm add sharp	Installs dependencies
pnpm dev	Starts local dev server at localhost:4321
pnpm build	Build your production site to ./dist/
pnpm preview	Preview your build locally, before deploying
pnpm new-post <filename>	Create a new post