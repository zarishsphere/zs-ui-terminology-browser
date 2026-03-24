# zs-ui-terminology-browser

> **Part of:** [ZarishSphere Platform](https://github.com/zarishsphere) | **Layer:** Frontend Microfrontend
> **Framework:** Next.js 16.2 | **Language:** TypeScript 6.0 | **Design:** Carbon DS 11.x
> **Status:** 🔴 Bootstrap

Terminology browser — ICD-11, SNOMED, LOINC, CIEL

## Repository Structure

```
zs-ui-terminology-browser/
├── src/
│   ├── app/             # Next.js 16.2 App Router pages
│   ├── components/      # React 19.x components (Carbon DS 11.x)
│   ├── hooks/           # Custom React hooks (FHIR hooks)
│   ├── lib/             # Utilities, FHIR client helpers
│   ├── types/           # TypeScript 6.0 type definitions
│   └── i18n/            # Translation files (EN, BN, MY, UR, HI, TH)
├── public/              # Static assets
├── .github/
│   └── workflows/       # CI/CD pipelines
├── Makefile
├── package.json
├── tsconfig.json
└── README.md
```

## Technology Stack

| Component | Version |
|-----------|---------|
| React | **19.x** |
| Next.js | **16.2** |
| TypeScript | **6.0** |
| Carbon Design System | **11.x** |
| TanStack Query | **v5** |
| Dexie.js (offline) | **4.0** |

## Getting Started

```bash
git clone https://github.com/zarishsphere/zs-ui-terminology-browser.git
cd zs-ui-terminology-browser
pnpm install
pnpm dev
```

---

*Part of the [ZarishSphere Platform](https://zarishsphere.com) — Free · Open Source · FHIR R5 · Offline-First*
