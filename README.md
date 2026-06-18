# SozialCM Website

A bilingual website for **SozialCM** - a GDPR-compliant case management platform for social services, built with Astro.

## 📋 About SozialCM

**Digital. Secure. Stress-Free. Case Management for Social Services**

SozialCM is a case management platform that helps professionals in social services simplify documentation, save time, and stay organized. Currently specialized in **school social work**, with plans to expand to all social service sectors (youth welfare, refugee services, care facilities, addiction counseling).

**Key Features:**
- Simple case documentation with real-time insights
- GDPR-compliant & secure (German servers, encryption, role-based access)
- Mobile & desktop accessible
- Seamless team handovers
- Reduces documentation stress by up to 50%

**Current Status:** Pilot Phase

## 🚀 Project Structure

```text
/
├── public/
│   └── images/
│       ├── sozialcare-dashboard.png
│       ├── sozialcare-case-list.png
│       ├── sozialcare-case-details.png
│       └── sozialcare-follow-ups.png
├── src/
│   ├── components/
│   │   ├── AnalyticsTracker.astro
│   │   ├── CookieConsent.astro
│   │   ├── Footer.astro
│   │   ├── GoogleAnalytics.astro
│   │   ├── Navigation.astro
│   │   └── PageTracker.astro
│   ├── i18n/
│   │   ├── index.ts
│   │   ├── ui.ts
│   │   └── locales/
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── de/
│   │   │   └── index.astro
│   │   └── en/
│   │       └── index.astro
│   ├── styles/
│   └── types/
└── package.json
```

## ✨ Features

- 🌍 **Bilingual**: Full German (DE) and English (EN) support
- 📊 **Analytics**: Google Analytics integration with privacy-conscious tracking
- 🍪 **Cookie Consent**: GDPR-compliant cookie consent management
- 🖼️ **Image Gallery**: App preview screenshots with modal lightbox
- 🎨 **Modern Design**: Clean, minimalistic interface optimized for social work professionals
- ⚡ **Fast Performance**: Built with Astro for optimal speed
- 📱 **Fully Responsive**: Mobile-first design

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 🔧 Configuration

Create a `.env` file in the root directory with your environment variables for analytics.

## 🎯 Target Audience

- **Current:** School social workers in Germany
- **Future:** All social service organizations (youth welfare, refugee support, care facilities, addiction counseling)

## 📧 Contact

- **Email:** sozialcm@johnxlabs.de
- **Project:** SozialCM
- **Location:** Würzburg, Germany

---

**Built as SozialCM** - Modular tech, meaningful care.
