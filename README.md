# PABRIK ROTI [![version](https://img.shields.io/badge/version-2.4.66-blue)](https://github.com/myreceiptt/pabrikroti-master/releases/tag/v.2.4.66-travconn) [![status](https://img.shields.io/badge/status-active-brightgreen)](https://github.com/myreceiptt/pabrikroti-master/blob/preview/SECURITY.md#-supported-versions) [![Build Status](https://github.com/myreceiptt/pabrikroti-master/actions/workflows/ci.yml/badge.svg)](https://github.com/myreceiptt/pabrikroti-master/actions/workflows/ci.yml) [![Deployed to Vercel](https://img.shields.io/badge/Vercel-deployed-success?logo=vercel)](https://coupon.travelconnect.co/)

> "This is not just a factory. This is a rehearsal of freedom—kneaded with code, fermented by its community, and baked through the heat of shared struggles."
>
> — Prof. NOTA

## Staging 2.4.66 by TravelConnect

Link #1: [coupon.travelconnect.co](https://coupon.travelconnect.co/) [![status](https://img.shields.io/badge/deploy-live-brightgreen)](https://coupon.travelconnect.co/)  
Link #2: [travconn.endhonesa.com](https://travconn.endhonesa.com/) [![status](https://img.shields.io/badge/deploy-live-brightgreen)](https://travconn.endhonesa.com/)

---

## Quick Start

```bash
yarn install && yarn dev
```

> If you find this useful, consider starring ⭐ the repository! Please!
>
> — Prof. NOTA

---

## About This Repo (TravelConnect)

This repo is a prototype built with **TravelConnect** to demonstrate how onchain access can enhance real-world ecosystems. We use the **Base** blockchain and the **thirdweb SDK** to provide **Smart Accounts** for users, then apply onchain rules to unlock perks and experiences.

### What it proves

- **NFT coupons** can gate access to perks (claimable benefits, eligibility, and access control).
- **Tokens** can represent loyalty points / reward points that accumulate through participation.
- Smart Accounts can make onboarding smoother while keeping access rules enforceable onchain.

### Context & story

TravelConnect builds a travel ecosystem to improve efficiency and expand the value of travel companies across Asia, with a network of offices and teams collaborating to create new products for the industry.

We built this app as a proof-of-concept—developed together with TravelConnect leadership (including CEO **Yuku NG**)—to validate the Web3 mechanism before deeper integration. A future phase can connect the gating logic to TravelConnect’s user database so only registered users can access specific perks and content.

### Technology

- Next.js (App Router) + React + TypeScript
- Tailwind CSS
- thirdweb SDK (Smart Accounts + EVM wallet/contract integrations)
- Base blockchain (EVM-compatible)
- Vercel deployment

## 📜 Licenses

This project is protected under a [**Custom Limited License**](./LICENSE) by [Prof. NOTA & Prof. NOTA Inc.](https://nota.endhonesa.com/). Usage is only allowed for cultural, educational, and women- or child-focused projects approved by Prof. NOTA.

License available in multiple languages:

- 🏛️ [English (UK)](./licenses/LICENSE_en-GB.md)
- 🇮🇩 [Bahasa Indonesia](./licenses/LICENSE_ID.md)
- 🇺🇿 [Oʻzbekcha](./licenses/LICENSE_uz-Latn.md)
- 🇭🇰 [Cantonese – Hong Kong](./licenses/LICENSE_yue-Hant-HK.md)
- 🇲🇾 [Bahasa Malaysia](./licenses/LICENSE_ms-MY.md)
- 🇦🇪 [العربية – الإمارات](./licenses/LICENSE_ar-AE.md)

> 📩 For permission or inquiries, contact: [nota@endhonesa.com](mailto:nota@endhonesa.com)

---

## 📜 Manifestos

If you already have obtained the license, please read and understand the manifesto from [Prof. NOTA & Prof. NOTA Inc.](https://nota.endhonesa.com/) before starting to use it. Each deployment must respect the ideological foundation of Prof. NOTA Inc.

Manifestos are available in:

- 🏛️ [English (UK)](./manifestos/manifesto_en-GB.md)
- 🇮🇩 [Bahasa Indonesia](./manifestos/manifesto_id.md)
- 🇺🇿 [Oʻzbekcha](./manifestos/manifesto_uz-Latn.md)
- 🇭🇰 [Cantonese – Hong Kong](./manifestos/manifesto_yue-Hant-HK.md)
- 🇲🇾 [Bahasa Malaysia](./manifestos/manifesto_ms-MY.md)
- 🇦🇪 [العربية – الإمارات](./manifestos/manifesto_ar-AE.md)

---

## 🛠️ Getting Started

### Install dependencies

```bash
yarn install
```

### Review dependency updates (interactive)

```bash
yarn up -i
```

### Upgrade dependencies

```bash
yarn up -R
```

### Cleaning and re-install dependencies

```bash
rm -rf node_modules .yarn/install-state.gz && yarn install
```

### Run development server

```bash
yarn dev
```

### Lint and check all the code quality

```bash
yarn lint
```

### Build for production

```bash
yarn build
```

### Preview the production

```bash
yarn start
```

---

## Evergreen Notes

- `@types/node` is pinned to **24.x** to match the Node 24 runtime (Vercel).
- Yarn is **4.x**; use `yarn outdated` for update review and `yarn npm audit --severity moderate` for security checks.

## 📜 Resources

- [Prof. NOTA Inc.](https://nota.endhonesa.com/)
- [Prof. NOTA Console](https://prompt.endhonesa.com/)
- [Prof. NOTA Tutor](https://baca.endhonesa.com/)
- [Prof. NOTA Artefacts](https://docs.endhonesa.com/)

---

## 🤝 Contributing

Your contribution is not only welcome — it's part of the protocol.

If you believe in the mission of PABRIKROTI and want to help improve it, follow these simple steps:

1. Fork this repository
2. Create a new branch (`feature/your-feature-name`)
3. Commit your changes mindfully
4. Open a pull request to the `preview` branch

Before submitting your PR, make sure to run:

```bash
yarn lint
```

To keep our code clean and consistent.

If you have questions, feel free to open an issue or reach out via the Prof. NOTA community Discord.

> ✊ You’re not just contributing code — you’re shaping how the people eat, learn, and resist.
>
> — Prof. NOTA

---

### Join Prof. NOTA Discord

For feedback, questions, or cultural-technical collaboration, join Prof. NOTA discord at [https://discord.gg/5KrsT6MbFm](https://discord.gg/5KrsT6MbFm).

---

---

## Maintenance by Prof. NOTA Evergreen Standard

This repo is intended to stay evergreen while remaining production-safe.

### Runtime

- Node: **24.x** (see `.nvmrc` and `package.json#engines`)

  - ~~example alternatives: 22.x / 20.x (adjust if platform requires)~~

- Package manager:

  - **Yarn** (lockfile: `yarn.lock`, `packageManager: yarn@4.12.0`)
  - ~~PNPM (lockfile: `pnpm-lock.yaml`)~~
  - ~~NPM (lockfile: `package-lock.json`)~~

- Deploy target:

  - **Vercel**
  - ~~Netlify~~
  - ~~Self-hosted / Docker~~
  - ~~Other platform (document explicitly)~~

### Monthly Safe Updates (recommended)

1. Check what’s outdated:

   - `yarn up -R` (within existing semver ranges)
   - ~~pnpm outdated~~
   - ~~npm outdated~~

2. Upgrade safe (patch/minor) versions:

   - `yarn up -R`
   - ~~pnpm update~~
   - ~~npm update~~
   - or upgrade specific packages shown as non-major

3. Verify:

   - `yarn npm audit --severity moderate`
   - ~~pnpm audit~~
   - ~~npm audit~~
   - `yarn build`
   - ~~pnpm build~~
   - ~~npm run build~~

4. Deploy:

   - **Vercel auto-deploy from `main`**
   - ~~manual deploy according to platform workflow~~

### Major Updates (quarterly / scheduled)

Major upgrades (framework, runtime, or core tooling) must be done one at a time, with a dedicated PR and full testing.

Examples:

- Node major version
- Next.js / React major version
- Tailwind CSS major version
- Package manager major version

---

---
