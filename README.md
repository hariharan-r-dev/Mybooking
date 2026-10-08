# MyBooking marketing website

A responsive 14-page marketing website for the planned MyBooking beauty marketplace. Built with Vite and vanilla JavaScript. Uses charcoal `#2A2A2A`, sky blue `#87CEEB`, white, and locally hosted Plus Jakarta Sans. Plus Jakarta Sans is used consistently for display headings, body copy, and controls; no secondary italic font is used.

## Development

Requires Node.js 22.12+ (this environment uses Node 24).

```sh
cd /workspace/Mybooking
npm --cache /workspace/.npm-cache ci
npm run dev -- --port 5173
```

## Validation

```sh
npm run build
npm test
```

Tests use the environment's `/usr/bin/chromium` and validate all pages, navigation, mobile overflow, booking-mode tabs, FAQs, help search, cookie choices, launch dialogs, and local enquiry downloads. On other machines, configure the Chromium executable in `playwright.config.js`.

## Pages

Home, About Us, Careers, Blog, Contact Us, Press, Help Center, FAQs, Booking Guide, Support, Privacy Policy, Terms of Service, Security, and Cookies.

## Before launch

This is a marketing prototype, not a connected marketplace. Booking and professional CTAs open a pre-launch information dialog. Enquiry forms create downloadable local text files; they do not send messages or collect leads. Blog cards link to real educational pages. Careers and Press do not fabricate jobs or announcements. Privacy and Terms are clearly identified as drafts requiring business details and legal review. Cookie preferences are saved locally; no analytics or advertising integrations are present.

The hero image is AI-generated editorial artwork and does not represent a real customer or provider. Plus Jakarta Sans is distributed under the included SIL Open Font License.

Requested references: Mangomint's medical spa page and Boulevard's homepage. Both reference sites’ HTML and styles were inspected during the typography revision. Mangomint declares TT Commons Pro, TT Commons Mono, and IvyPresto Display; Boulevard declares Basis Grotesque Pro, Rework Headline, DM Sans, and Roboto Mono. MyBooking retains its own locally hosted Plus Jakarta Sans rather than copying commercial font assets. Typography uses 16px body copy, 14px navigation and controls, 12px uppercase labels, relaxed heading tracking, and a responsive display scale.
