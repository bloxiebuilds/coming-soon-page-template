# 📖 coming-soon-page-template — Instructions

Get your coming soon page live in minutes. No coding experience needed.

---

## 📋 Table of Contents

1. [Getting Started](#1-getting-started)
2. [Editing the Config Block](#2-editing-the-config-block)
3. [Setting Your Launch Date](#3-setting-your-launch-date)
4. [Setting Up Email Signup](#4-setting-up-email-signup)
5. [Adding Social Links](#5-adding-social-links)
6. [Setting Your Theme](#6-setting-your-theme)
7. [Deploying to GitHub Pages](#7-deploying-to-github-pages)
8. [FAQ](#8-faq)

---

## 1. Getting Started

1. Go to [github.com/bloxiebuilds/coming-soon-page-template](https://github.com/bloxiebuilds/coming-soon-page-template)
2. Click **"Use this template"**
3. Name your repo and click **"Create repository"**
4. Open `index.html` in your browser to preview instantly!

---

## 2. Editing the Config Block

Open `index.html` and find the `CONFIG` block near the top:

```js
const CONFIG = {
  productName:  "Something Big",
  tagline:      "We're working on something you'll love.",
  launchDate:   "2026-09-01",
  darkMode:     "toggle",
  accentColor:  "#f472b6",
  signupUrl:    "#",
  signupLabel:  "Notify me when it's ready",
  socials: [...]
};
```

| Field | What to put |
|-------|-------------|
| `productName` | Your product or brand name |
| `tagline` | A short teaser line |
| `launchDate` | Your launch date in `YYYY-MM-DD` format |
| `accentColor` | Any hex color |

---

## 3. Setting Your Launch Date

Set `launchDate` in `YYYY-MM-DD` format:

```js
launchDate: "2026-12-25",  // Christmas launch!
```

The countdown will tick down automatically to that date.

---

## 4. Setting Up Email Signup

Set `signupUrl` to wherever you collect emails:

- **Google Form** — paste your form URL
- **Mailchimp** — paste your signup URL
- **Hide the form** — leave it as `"#"`

```js
signupUrl: "https://forms.google.com/your-form-url",
```

---

## 5. Adding Social Links

In the `socials` array, each link looks like:

```js
{ label: "Twitter", url: "https://twitter.com/yourhandle" },
```

Add more by copying a line. Remove any by deleting its `{ ... },` block.

---

## 6. Setting Your Theme

| Value | Result |
|-------|--------|
| `true` | Always dark |
| `false` | Always light |
| `"toggle"` | Visitor can switch |

---

## 7. Deploying to GitHub Pages

1. Push your repo to GitHub (public)
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Click **Save** — live at:

```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME
```

---

## 8. FAQ

**Q: The countdown shows 00 00 00 00 — why?**
Make sure `launchDate` is in `YYYY-MM-DD` format and is a future date.

**Q: Can I hide the email signup?**
Yes — set `signupUrl` to `"#"` and the form will disappear.

**Q: Can I use this for a product, album, or event launch?**
Absolutely — it works for anything!

---

<p align="center">coming-soon-page-template was made by <a href="https://github.com/bloxiebuilds">bloxiebuilds</a></p>
