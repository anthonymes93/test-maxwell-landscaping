# Maxwell Landscaping — static website

Plain HTML, CSS and JavaScript. No React, bundler or build step.

## Pages
- index.html — homepage
- services.html — all six service detail sections
- projects.html — clearly labeled inspiration gallery (replace with real client work)
- about.html
- quote.html — request form

## Before publishing
1. Confirm Maxwell Landscaping's actual services and coverage area. The six services are illustrative until confirmed.
2. Replace Unsplash images with authorized Maxwell photography, particularly the inspiration gallery.
3. **Configure the contact form**. The form is intentionally not presented as working: enter a real destination email into the form's `data-recipient` in `quote.html` to enable a mailto fallback, or replace the client-side handler with a Cloudflare Pages Function using Turnstile + Resend for reliable submissions.
4. Add the business phone, email, logo and verified business credentials.

Design approximates the provided reference: near-black backgrounds, bright lime green, oversized uppercase heavy headings, square controls, white quote form. Exact proprietary font could not be identified from screenshots. Google Fonts Archivo Black + Inter are used as close web-safe alternatives.
