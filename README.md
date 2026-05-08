# Tasseo Landing Page

This repository contains the public marketing and policy website for Tasseo.

Tasseo is a mystical oracle app for cup readings, symbolic interpretation, astrology, ritual history, and conversational guidance. Users can upload Turkish coffee, espresso, tea, latte, matcha, or similar cup photos, then continue each reading as a personal Oracle chat.

The production mobile application source code is private and is not included in this repository. This repo is only for the public-facing landing page, support page, privacy policy, and terms of service.

## Website

- Landing page: `index.html`
- Support and contact: `support.html`
- Privacy Policy: `privacy.html`
- Terms of Service: `terms.html`
- Shared styling: `styles.css`

## Product Positioning

Tasseo is presented as a living oracle that remembers the user's journey locally on their device, rather than a generic horoscope or one-time fortune report.

Core themes:

- Cup Vision for Turkish coffee, espresso, tea leaves, latte, matcha, and modern drink patterns
- Oracle Chat for follow-up questions after each reading
- Local ritual history stored on the user's phone
- Living Memory for personalized context inside the app experience
- Symbol Collection with hidden motifs and spiritual categories
- Astrology-based onboarding and first reading
- XP, levels, streaks, credits, premium plans, and rewarded credit options
- Multilingual and theme-aware user experience

## Download Links

The landing page includes separate download calls to action for iOS and Android.

Replace the placeholder `href="#"` values in `index.html` when the store pages are ready:

```html
<a href="#" class="download-btn download-btn-ios">
<a href="#" class="download-btn download-btn-android">
```

Suggested final targets:

- iOS: App Store product URL
- Android: Google Play product URL

## Contact

Support email:

`berkailabs+tasseo@gmail.com`

## Local Preview

This is a static website. You can preview it with any local static server:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173/index.html
```

## Notes

- Do not add private mobile app source code to this repository.
- Keep public legal/support copy aligned with the app's actual data behavior.
- Ritual conversations and chat history should be described as stored locally on the user's device unless the production app behavior changes.
