<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome SaaS Starter Kits [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/spekulatius/awesome-saas-starter-kits/actions/workflows/lint.yaml/badge.svg)](https://github.com/spekulatius/awesome-saas-starter-kits/actions/workflows/lint.yaml)

<!-- subtitle -->

A curated list of open source and source-available starter kits, boilerplates, and building blocks for launching a SaaS product.

</div>

<!-- TOC -->

## Contents

- [Full-Stack Starter Kits](#full-stack-starter-kits)
  - [Free & Open Source](#free--open-source)
  - [Paid & Source-Available](#paid--source-available)
- [Next.js](#nextjs)
- [Laravel](#laravel)
- [Django & Python](#django--python)
- [Ruby on Rails](#ruby-on-rails)
- [Auth & Multi-Tenancy](#auth--multi-tenancy)
- [Billing & Payments](#billing--payments)
- [Related Lists](#related-lists)

<!-- CONTENT -->

## Full-Stack Starter Kits

Framework-agnostic or multi-framework starter kits sold or maintained as a standalone product, rather than tied to one language ecosystem.

### Free & Open Source

- [Open SaaS](https://github.com/wasp-lang/open-saas) - Free, MIT-licensed React/Node.js boilerplate powered by the Wasp full-stack framework, with auth, Stripe/Polar payments, background jobs, and email sending built in.
- [create-t3-app](https://github.com/t3-oss/create-t3-app) - CLI scaffolder for the T3 Stack (Next.js, tRPC, Prisma/Drizzle, Tailwind, NextAuth); a minimal, unopinionated foundation rather than a batteries-included SaaS kit.

### Paid & Source-Available

- [ShipFast](https://shipfa.st/) - One-time-purchase Next.js boilerplate popular in the indie hacker community, bundling auth, Stripe payments, transactional emails, and SEO.
- [Supastarter](https://supastarter.dev/) - Next.js, Nuxt, and SvelteKit starter kit built on better-auth, with billing, multi-tenancy, and internationalization included.
- [MakerKit](https://makerkit.dev/) - Next.js or Remix SaaS starter kits for Supabase or Firebase; free "lite" versions are open source, with a paid Pro tier adding billing and multi-tenancy.

## Next.js

- [Next.js SaaS Starter](https://github.com/nextjs/saas-starter) - Official Vercel-maintained starter combining Next.js, Postgres, Stripe, and shadcn/ui.
- [next-saas-stripe-starter](https://github.com/mickasmt/next-saas-stripe-starter) - Community starter adding Prisma, Neon, Auth.js v5, and a role-based admin panel on top of Stripe billing.
- [SaaS Boilerplate](https://github.com/ixartz/SaaS-Boilerplate) - Full-stack Next.js app with Clerk auth, multi-tenancy, roles & permissions, i18n, and a landing page, built on Tailwind CSS and shadcn/ui.
- [Nextacular](https://github.com/nextacular/nextacular) - Multi-tenant SaaS starter kit on Next.js, Prisma, and Stripe, with custom domains and workspaces out of the box.
- [BoxyHQ SaaS Starter Kit](https://github.com/boxyhq/saas-starter-kit) - Enterprise-focused boilerplate with SSO/SAML, teams, webhooks, and Stripe billing.
- [Makerkit Next.js Supabase SaaS Starter Kit (Lite)](https://github.com/makerkit/nextjs-saas-starter-kit-lite) - Free version of MakerKit's Supabase-backed Next.js starter.

## Laravel

- [Laravel Starter Kits](https://laravel.com/starter-kits) - Official React, Vue, and Livewire scaffolding maintained by the Laravel team; the baseline most Laravel SaaS kits build on.
- [Wave](https://github.com/thedevdojo/wave) - MIT-licensed starter kit built on Voyager, with subscription billing via Stripe or Paddle, roles, a blog, and an admin panel.
- [Electrik](https://github.com/electrikhq/electrik) - Source-available Laravel 12 + Livewire 3 + Tailwind 4 starter kit with Cashier billing, teams, and roles.
- [Laravel-SaaS-Starter-Kit](https://github.com/skanderbenali/Laravel-SaaS-Starter-Kit) - Multi-tenant starter with team management, role-based permissions, and subscription billing.

## Django & Python

- [SaaS Pegasus (Open Source Edition)](https://github.com/saaspegasus/django-boilerplate) - MIT-licensed foundation of the paid SaaS Pegasus product, with a modern front-end stack ready out of the box.
- [Django-SAAS-Boilerplate](https://github.com/PaulleDemon/Django-SAAS-Boilerplate) - Lightweight open source Django starter for bootstrapping SaaS projects.

## Ruby on Rails

- [Bullet Train](https://github.com/bullet-train-co/bullet_train) - MIT-licensed "Rails on Rails" template with team management, roles, subscriptions, i18n, and generator-driven scaffolding.
- [Jumpstart Pro](https://jumpstartrails.com/) - Paid Rails SaaS template with multitenancy, Stripe/PayPal billing, and Hotwire/Turbo throughout.

## Auth & Multi-Tenancy

Drop-in building blocks most of the kits above wire up first, useful on their own for a custom build.

- [Better Auth](https://github.com/better-auth/better-auth) - Open source, framework-agnostic TypeScript auth library with 2FA, passkeys, and RBAC built in; used by Supastarter and others in place of a hosted provider.
- [Clerk](https://clerk.com/) - Hosted auth and user management with a generous free tier and drop-in components for React/Next.js SaaS apps.
- [WorkOS](https://workos.com/) - Enterprise-readiness layer (SSO, SCIM, audit logs, directory sync) commonly bolted onto a starter kit once it needs enterprise customers.

## Billing & Payments

- [Stripe Billing](https://stripe.com/billing) - Subscription and usage-based billing infrastructure most starter kits integrate first.
- [Lemon Squeezy](https://www.lemonsqueezy.com/) - Merchant-of-record billing that handles global VAT/sales tax, a popular Stripe alternative in indie SaaS kits.
- [Paddle](https://www.paddle.com/) - Merchant-of-record billing platform used by Wave and others as a Stripe alternative.

## Related Lists

- [Awesome API-as-a-Business](https://github.com/spekulatius/awesome-api-as-a-business) - A curated list of resources for building, running, and growing an API as a business.
- [awesome-saas-boilerplates-and-starter-kits](https://github.com/tyaga001/awesome-saas-boilerplates-and-starter-kits) - A broader, implementation-detail-heavy catalog of starter kits organized by stack.

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/spekulatius/awesome-saas-starter-kits/graphs/contributors)!
