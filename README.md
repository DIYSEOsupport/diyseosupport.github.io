# DIYSEO Gumroad Landing Page

## Files
- `index.html` — the homepage (diyseosupport.github.io). The older `landing.html` was archived on 2026-11-11.

Both HTML files embed the logo and the single guide image directly, so images do not depend on relative asset paths after publishing. The header and footer use the same cropped DIYSEO wordmark. The page has one featured guide and two primary guide CTAs.

## Preview and publish
From this folder, use the Gumroad CLI commands supported by your installed version. Preview first and verify both images, theme switching, and the product destination. The guide link is: https://diyseosupport.github.io/maps-guide-landing/

Requested commands:
```bash
gumroad pages preview index.html
gumroad pages push profile index.html
```

Publishing has not been performed by this project preparation. Confirm the CLI is authenticated and the preview is correct before pushing to your profile.


Logo note: the header and footer use the supplied circular DIYSEO artwork embedded as GIF data in the HTML, so the logo does not rely on relative image paths. The provided source artwork itself is static (not animated).


## Animated logo note
The header and footer use the same embedded animated DIYSEO GIF, so their brand colors match. The original uploaded logo image was static despite its `.gif` filename; this project creates a subtle looping pulse animation. The page does not show a separate “Visit the Gumroad store” footer CTA.
