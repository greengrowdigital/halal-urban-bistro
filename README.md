# THE HUB — The Halal Urban Bistro

Award-winning demo website for **The Halal Urban Bistro (THE HUB)**, a premium halal smashburger spot in Queens Village, NY. Zabiha halal · farm-to-table · open 5pm–2am, Tue–Sun.

## Pages

- `index.html` — Hero, signature menu, reviews, locations preview
- `menu.html` — Full menu with cart drawer (burgers, chicken, breakfast, paratha, sides, sweets, drinks)
- `story.html` — Brand story, halal commitment, Maple Smash origin, Ramadan giving
- `locations.html` — Hillside Ave flagship + Union Square Holiday Market booth + hours + transit
- `order.html` — Mock pickup/delivery flow with cart, checkout modal, order confirmation

## Stack

Static HTML — no build step. Inline CSS + vanilla JS, served as-is from Vercel.

- Fonts: Fraunces (display) + Bebas Neue (titles) + Inter (body)
- Animations: Reveal-on-scroll via IntersectionObserver, marquee, scroll progress
- Cart state persists in `localStorage` across menu / order pages

## Deploy

```
vercel --prod
```

Routes configured in `vercel.json` with `cleanUrls`.
