# Design preview

Client review demo for Aesha Begum, a calligraphy and hand-engraving artist working with luxury brands.

| File | Page |
| --- | --- |
| `index.html` | Homepage (Aesha Begum, Calligraphy & Engraving) |
| `assets/` | Folder for the hero video (`hero.mp4`, not added yet) |

The page is static and self-contained: no build step and no dependencies. Fonts load from Google Fonts, so the script lettering only shows correctly when the page is online. The enquiry form runs in the browser only and sends nothing.

## Before you deploy: 1 optional change

- [ ] **Add the hero video (if available).** Put a calm, warm-toned clip (pen nib writing or hand engraving, ideally under 8 MB) at `assets/hero.mp4`. If the file is missing, the page shows its animated ink background instead, so the demo still works without it.

The test link is already kept out of search engines: `index.html` has `<meta name="robots" content="noindex, nofollow">` in its `<head>`. Leave it in until launch.

Do not change anything else in the page without checking with Ahmed first.

## Deploying to the test link

1. Upload `index.html` and the `assets` folder to the same folder on the test server.
2. Open `index.html`. Wait about 3 seconds for the opening animation to finish.
3. Check it on desktop and on a phone. The hero responds to the mouse or a finger (gold ink writing), the Services section scrolls sideways on desktop and stacks on phones, and the "Try it yourself" section updates the name live.

## Notes for the dev team

- This is a design preview. Every effect is plain CSS and vanilla JavaScript, so it can be carried into the production build as it is.
- Still placeholder, all clearly marked on the page: portfolio tiles (tagged "Sample"), the portrait, client logos, the testimonial, the email address and the Instagram handle. Replace them with the client's own photos and details before launch.
- Do not add brand names, logos or testimonials the client has not supplied and approved in writing. She works with luxury brands and may be under NDA.
- Remove the `noindex` line only when the site goes live on the client's own domain.
