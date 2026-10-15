# Ashish Kumar Singh — multi-role portfolio

A Next.js, React, TypeScript and Tailwind CSS portfolio designed for Software Engineer, Frontend Developer, DevOps Engineer and Data Analyst applications.

## Run locally

```bash
pnpm install
pnpm dev
```

Visit `http://localhost:3000`. Build before deployment with `pnpm build`.

## Keep it credible

- Update identity, links and verified project metadata in `lib/data.ts`.
- Do not add outcome metrics, live links, or repository URLs until they can be verified.
- Project filters and role pages are driven from this single configuration file.

## Resumes

Place four factual PDFs in `public/resumes/` using the filenames in `public/resumes/README.md`. Until then, the UI explains the setup instead of returning a broken download.

## Deploy to Vercel

1. Push this folder to a GitHub repository.
2. Import that repository at Vercel and accept the detected Next.js settings.
3. Build command: `pnpm build`; output directory: leave empty.
4. Add no environment variables unless a contact-form provider is configured.
5. Verify every route and each resume link after uploading PDFs.

## Completion checklist

- [x] Four role-specific routes
- [x] Filterable, searchable projects
- [x] Real experience and project evidence only
- [x] Responsive navigation and accessible semantic controls
- [x] SEO and Open Graph metadata
- [x] Resume setup/error state
- [ ] Add four tailored factual PDFs
- [ ] Connect a contact-form service, if desired
