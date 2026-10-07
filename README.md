# WQ Coffee — wq coffee ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `wqcoffeeltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/wqcoffeeltd.mjs`).
> To change the content, edit that file and run `node build.mjs wqcoffeeltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@wqcoffeeltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Quote) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
WQ Coffee Ltd, a private limited company registered in England and Wales (company number 15635406), operates a takeaway coffee service and mobile coffee stand serving customers in Brighton and the surrounding area: speciality coffee and espresso drinks prepared to order, a mobile stand for markets and public events, coffee service for private events and weddings, and regular office and workplace coffee. Event bookings are quoted in advance in writing. Allergen information is provided on request, and food and drink are prepared in line with food hygiene requirements. Site: wqcoffeeltd.shop
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
