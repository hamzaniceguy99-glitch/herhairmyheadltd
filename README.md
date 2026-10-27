# Her Hair My Head — her hair my head ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `herhairmyheadltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/herhairmyheadltd.mjs`).
> To change the content, edit that file and run `node build.mjs herhairmyheadltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@herhairmyheadltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per service / $Per service / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Her Hair My Head Ltd is a hairdressing business in Sevenoaks, Kent, working since 2021. We cut and style, colour, work on condition and repair, and consult properly before committing to anything. One rule we do not bend: a patch test 48 hours before colour, for every client, and again whenever the product changes or after any reaction. Hair colour contains oxidative dyes that cause genuine allergic reactions, occasionally severe ones, and the test is both the manufacturer's written instruction and a condition of our insurance. A salon that colours you today because you are in a hurry has skipped the one step that protects you. We also say no when a head of hair will not take the colour being asked for without damage, and we do not diagnose scalp conditions. Site: herhairmyheadltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
