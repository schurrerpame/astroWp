# Astro + WordPress Integration

This project synchronizes the backend of WordPress with a static site built using [Astro](https://astro.build). WordPress acts as a headless CMS, while the frontend is served statically using Astro.

The integration is set up with GitHub Actions, which allows the site to be deployed automatically via FTP whenever a new post is created or updated in the WordPress backend. When a new post is created, an event is triggered that initiates the deployment process.

🔗 [Live Static Site](https://pameschurrer.com/astro-web/)

This approach separates the backend of WordPress as a CMS while the fast, SEO-friendly static frontend is provided by Astro.

---

## Features

- Automatic synchronization between the WordPress backend and the static frontend with Astro.
- Automatic deployment to the server via FTP every time a post is created or updated.
- GitHub Actions setup to automate the deployment workflow.
- Optimized for SEO and performance on the generated site.

---