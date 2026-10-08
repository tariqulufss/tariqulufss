# Hi, I'm Tariqul Islam 👋

Laravel backend developer building booking platforms, SEO-driven marketing sites and clean, well-tested APIs.

<!-- Replace with your own links -->
[Portfolio](https://tariqulislamrc.vercel.app) · [LinkedIn](https://linkedin.com/in/your-handle) · [Email](mailto:tariqulislamrc@gmail.com)

---

## What I do

- Build and maintain production **Laravel** applications for the hospitality and cleaning industries.
- Design **versioned JSON APIs** that a Next.js frontend consumes, with token auth, validation and stable pagination.
- Ship **technical SEO** features in the backend: metadata, structured data, sitemaps, `robots`, `llms.txt` and caching.
- Integrate third-party services such as **Smoobu** (property bookings) and **Brevo** (email).
- Work in **AI-assisted workflows** with Claude Code: I turn requirement documents (BRDs, user stories, client feedback) into database schemas, architecture decisions and tested code.

## Tech stack

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Vue](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Inertia](https://img.shields.io/badge/Inertia.js-9553E9?style=flat&logo=inertia&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Pest](https://img.shields.io/badge/Pest-F28D1A?style=flat&logo=pestphp&logoColor=white)

| Area | Tools |
| --- | --- |
| Backend | PHP 8.4, Laravel 12/13, Eloquent, queues, Sanctum, Fortify, spatie/permission, spatie/activitylog |
| Frontend | Blade, Vue 3, Inertia v3, Tailwind CSS, Nunjucks prototypes, Wayfinder |
| Data | MySQL 8 (schema design, generated columns, CHECK constraints, reversible data migrations) |
| Quality | Pest, PHPStan/Larastan, Laravel Pint, a 100% line-coverage target on new code |
| Workflow | Git feature branches and pull requests, Bruno API collections, Claude Code, Laravel Boost |

## Featured work

### 🧺 ULaundry backend
Laravel 13 admin app (Inertia + Vue) plus a versioned `/api/v1` JSON API for a Next.js customer site. It serves a laundry service catalogue and a versioned price list.
- Layered architecture: **Controller → Action → Service → Repository (via interface) → Model**, with DTOs and API Resources.
- Filtering, sorting and pagination with a fixed query-string contract and stable tie-breakers.
- Money as integer pence, effective-dated prices that are closed and reopened rather than overwritten, and 404 for inactive or soft-deleted records.
- Pest feature tests, PHPStan and Pint, plus a Bruno collection documenting every endpoint.
- Started from a client-reviewed requirements pack: BRD, user stories, database schema and decision log.

### 🏠 United Stay (booking platform)
Booking site for serviced apartments with an admin dashboard, integrated with **Smoobu**.
- Security-deposit management: status handling, email notifications and admin visibility.
- Identification document upload wizard with submission tracking.
- Blog engine with image uploads and an API.
- SEO layer: per-page metadata, cached `SeoResolver`, sitemap generation.
- Booking extensions, shared admin and user login, and a bookings export API.
- Dozens of merged pull requests across feature, fix and release branches.

### 🧹 United Facilities Cleaning website
Large Laravel marketing site, which I co-develop with a teammate.
- Featured-blog toggle and filters in the admin panel, and SEO management with phone-number validation.
- Bot protection and email validation on subscription forms.
- Performance work: responsive images, video optimisation and CSS updates.
- SEO audit fixes: schema markup, NAP consistency, robots, sitemap, `llms.txt` and Google Tag Manager.
- Laravel version upgrade (in review).

### 📦 Laravel AutoSEO (package)
A reusable Laravel package, under the `UFSS\AutoSEO` namespace, that publishes AutoSEO articles to any Laravel site through a signed webhook.
- Bearer token and HMAC verification, validation, and upsert by external ID.
- Downloads images locally, writes SEO metadata and structured data, and adds sitemap entries.
- Works on a new site (its own table and blog pages) or maps onto an existing blog.

### 🧾 Quotation system
Laravel app that replaced a static `.docx` quotation template with generated, branded quotations.
- Brevo email delivery and quotation email templates.
- Admin UI fixes: modals, tables, archived-state styling.

### Other work
- **United Stay frontend**: a Nunjucks prototype with 5 city pages, style guide, wishlist and terms pages, built for stakeholder design review.
- **LMS**: analysed a Learning Management System BRD and produced a gap-checked MySQL schema (v2) and documentation.

## How I work

- Requirements first: I read the BRD, write the understanding, get client feedback, then model the database.
- Small layers with clear responsibilities, and dependencies injected through interfaces.
- Tests alongside the code: every filter, sort direction, validation rule and 404 path.
- Pull-request based delivery, with changes grouped into reviewable features.
- Active day to day since mid 2026, working across several repositories in parallel.

## GitHub snapshot

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=tariquluffs&layout=compact&hide_border=true)

> Most of my work lives in private repositories for clients and the `taskbe` organisation, so the public graph understates my activity.

## Let's connect

- 💼 Portfolio: https://tariqulislamrc.vercel.app
- 🐙 Personal GitHub: https://github.com/tariqulislamrc
- ✉️ tariqulislamrc@gmail.com
