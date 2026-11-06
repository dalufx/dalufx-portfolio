# Dalufx Portfolio Website

A responsive personal portfolio for Guru Oguaka Chukwudalu Favour / Dalufx, built using semantic HTML5 and CSS3 only.

## Project structure

```text
portfolio/
├── index.html
├── css/
│   └── style.css
├── assets/
│   ├── images/
│   └── icons/
│       └── dalufx-bull-crest.svg
└── README.md
```

## Run locally

1. Extract the `portfolio` folder.
2. Open `index.html` in a modern browser.
3. No installation, build process, package manager, or JavaScript is required.

## Publish with Netlify

1. Sign in to Netlify.
2. Choose the option to manually deploy a site / drag and drop.
3. Upload the contents of the `portfolio` folder (including `index.html`, `css`, and `assets`).
4. Open the published URL and test every section and link.

## Personalise before publishing

- **Portrait:** Add your preferred portrait to `assets/images/` and update the hero visual in `index.html` if you want a photograph instead of the illustrated bull crest.
- **Bull crest:** The included `assets/icons/dalufx-bull-crest.svg` is a custom, editable SVG-style brand emblem. Replace it with your official logo if you already have one.
- **Marquee:** In `index.html`, find the `.marquee-track` section. Edit the message in both repeated `<span>` elements to change the scrolling text. Keep both copies in sync so the loop stays seamless.
- **Skills/tools:** Add only tools, technologies, qualifications and proficiency levels you can confirm.
- **Projects:** The Jennifer's Website link was supplied by you. Other project cards are labelled placeholders. Replace their descriptions and visuals with your real work, project links, and actual contributions.
- **Experience:** The timeline describes a broad learning and practice journey based on the supplied three-year experience. Replace or expand it with accurate dates, jobs, courses, certificates and achievements if you want a formal CV-style timeline.
- **Testimonials:** Replace the placeholder with genuine, approved feedback only.
- **Social media:** Add your real social links when ready. None have been invented.
- **Open Graph image:** Add an image named `dalufx-social-preview.jpg` inside `assets/images/` for richer link previews, or change/remove the `og:image` metadata. The website works without this image, but social previews may lack a custom image.
- **Phone:** WhatsApp uses the international Nigerian format `2349137613781`, based on the supplied number `09137613781`.

## Design notes

- Midnight black is the foundation, gold provides the premium identity, and emerald green is a restrained accent.
- The bull crest is a static vector asset; no image library is required.
- CSS Grid and Flexbox adapt the content for mobile, tablet and desktop.
- Mobile navigation uses a CSS checkbox toggle; keyboard focus styling is included.
- The marquee is CSS animated and pauses on hover. Users who prefer reduced motion receive reduced animation.
- The page includes semantic landmarks, skip navigation, accessible focus indicators, descriptive labels and reduced-motion support.

## Honest functionality limits

- This site contains no JavaScript. The mobile navigation and marquee are CSS-only.
- The marquee's words are edited in the HTML source; there is no visitor-facing editor or admin panel.
- The contact buttons open WhatsApp, phone dialler or the visitor's email application. The website does not send messages itself.
- A contact form would need a backend or a form-processing service to deliver submissions.
- The projects section does not claim fictional achievements or client results.
- Forex trading is presented as market learning with risk awareness, not as a promise of returns or personalised financial advice.

## Quality-assurance checklist

- [ ] Replace placeholders and confirm all biography details.
- [ ] Test the navigation links on mobile and desktop.
- [ ] Test WhatsApp, email, telephone and project links.
- [ ] Add real project screenshots and alt text when available.
- [ ] Add a social preview image if desired.
- [ ] Check contrast, keyboard navigation and reduced-motion behaviour.
- [ ] Test on a phone, tablet and desktop browser.
- [ ] Validate the HTML and run an accessibility/performance audit before describing the site as audited.


## Added Dalufx links and product concepts
- WhatsApp CV/contact link: https://wa.me/2349137613781?text=Hello%20Favour,%20I%20saw%20your%20CV
- Dalufx company website: https://dalufxwebsite.netlify.app
- GitHub repository: https://github.com/dalufx/dalufx-portfolio
- DFX Animated concept page: open `dfx-animated.html` from the deployed site.
- Upcoming concepts: DFX CBT and DFX Antivirus.

### Important implementation notes
The portfolio and DFX Animated concept remain static HTML/CSS. The DFX Animated sign-in is a non-functional UI preview; it does not create accounts, store passwords, generate AI videos or process subscriptions. The proposed Premium price is ₦30,000/month. The supplied phone number 08107139343 is displayed as a payment-enquiries contact only; verify the official bank name and account name before making any payment. DFX Antivirus is a roadmap concept, not currently a working malware scanner or security product.

## Update: device layouts and fixes
- Three layouts: phone (up to 600px), tablet (601-1024px, a balanced in-between design) and laptop/desktop (above 1024px).
- Phone has a sticky WhatsApp / Call / Contact bar and full-width buttons; tablet uses 2-column cards.
- Fixed the clipped "DALUFX" wordmark and tagline in the hero crest (they now sit below the shield).
- Fixed the tight headline spacing and the off-centre label on the DFX Animated page.

## Update 2
- Contact section now lists both numbers: +234 913 761 3781 (main) and +234 810 713 9343 (second line / payment enquiries).
- The three placeholder project slots were replaced with a "More work is on the way" call-to-action.
- The testimonial placeholder was replaced with a "commitments" card written in the owner's own voice (not a client quote). Replace it with a real client testimonial whenever you have one.
- Footer wording simplified.

## Update 3
- Added a "Meet the founder" profile block (photo in a framed card with text) right after the About section. The photo is `assets/images/favour-portrait.jpg`; swap the file to change it.

## Update 4: live DFX clock
- New "Right now" section with an analog DFX clock (moving hour, minute and second hands), a digital clock, today's date, greeting, time zone, day and week of the year.
- It uses `js/clock.js` and reads each visitor's own device time and time zone. This is the only JavaScript on the site (the rest is HTML/CSS), and the clock section shows a short note if JavaScript is off.
