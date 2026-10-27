# Engineering Playground

Interaction and motion studies by **Hafsoh Bashar**, a product designer who designs in Figma and builds in code.

Each piece is plain HTML, CSS and JavaScript (no build step, no dependencies). Open it in a browser, or use the live links below. Most include a **Play demo** button that runs a scripted walkthrough, and **H** hides the controls for clean screen recording.

**Live gallery:** https://dhunidesigns.github.io/Engineering-Playground/

---

## Shuttlers: Homepage Redesign (concept)

A concept redesign of the Shuttlers homepage, built to pitch for a role there. Inspired by Zipline's scroll flow, Waymo's city map and road scene, Allfeat's stacked cards and footer, and Noovo's calm feel, in Shuttlers' own greens. Not affiliated with Shuttlers.

![Shuttlers homepage redesign](media/shuttlers-redesign.gif)

Hero that curves as you scroll · headline that fills line by line · odometer figures · stacked service cards · tap-a-city route map · safety hotspots on the bus · a bus that drives the route as you scroll into the download CTA · tone-on-tone footer wordmark · Phone view button

**Component upgrades** (rebuilt in plain JS from these libraries): seat booking with a Kobra-style OTP input (spring digit flip-in, gliding focus ring, paste sweep, invalid shake, success sweep) and Kobra toasts · 21st.dev Limelight nav, Background Paths hero and Spotlight cards · libraries.dev Border Beam on the route finder and Magnetic buttons · Astryx-style seat badges · searchable stop picker (Kobra Combobox) with swap button and sliding date chips · animated business icons. Demo code: `246810`.

[Live site](https://shuttlers-concept.vercel.app) · [Live demo](https://dhunidesigns.github.io/Engineering-Playground/shuttlers-redesign/) · [Source](shuttlers-redesign/index.html) · [Video](media/shuttlers-redesign.mp4)

---

## 4AM: Subscription & Billing

The current plan card lifts and expands into a swipeable plans carousel. Pick a plan, subscribe, and the card lands back in the billing screen as your new plan, with a new transaction row and a toast. Adding a payment card shows a live card preview that fills in as you type.

![4AM subscription flow](media/4am-subscription.gif)

Shared-element card expansion · spring-physics carousel with rubber-banding and flick velocity · blurred label crossfades · loading and success states · payment-methods sheet with an add-card form and live card preview

[Live demo](https://dhunidesigns.github.io/Engineering-Playground/4am-subscription/) · [Source](4am-subscription/index.html) · [Video](media/4am-subscription.mp4)

---

## LVL UP: Onboarding

Splash to three-page onboarding for a short-form learning app. Lesson cards shuffle, an AI tutor thinks and writes a summary word by word, and the community orbits around the app icon.

![LVL UP onboarding](media/lvlup-onboarding.gif)

Animated splash and logo reveal · card shuffle · streaming text with skeleton loaders · orbiting avatars with pulse rings · swipeable pager with parallax

[Live demo](https://dhunidesigns.github.io/Engineering-Playground/lvlup-onboarding/) · [Source](lvlup-onboarding/index.html) · [Video](media/lvlup-onboarding.mp4)

---

## Ride Dispatch Dashboard

A tablet dashboard for booking rides, couriers and freight. The car drives the route on a vector map, ride progress fills as it moves, and booking a new driver updates the whole screen.

![Ride dispatch dashboard](media/ride-dashboard.gif)

Animated route with a moving vehicle marker · live progress stepper and ETA · sliding tabs and mode switcher · skeleton loading · booking states and toasts

[Live demo](https://dhunidesigns.github.io/Engineering-Playground/ride-dashboard/) · [Source](ride-dashboard/index.html) · [Video](media/ride-dashboard.mp4)

---

## Sello: Marketing Site

The landing page for Sello, an AI sales assistant that answers Instagram and TikTok DMs, checks stock, writes up orders and hands the chat back to the seller to get paid. Fully responsive.

![Sello marketing site](media/sello.gif)

Product dashboard that zooms in on scroll · live AI inbox chat loop · a waitlist button that flies from the hero to the bottom of the screen and lands in the final CTA · auto-advancing steps with progress bars · scroll-driven feature rows · full-page footer with a rising wordmark

[Live site](https://sello-vert.vercel.app) · [Source](sello/)

---

## NYTA: Agency Site

A website for NYTA, a Dubai influencer agency that connects brands with local talent.

![NYTA agency site](media/nyta.gif)

Editorial layout · auto-playing case-study slider · client testimonial carousel · responsive navigation

[Live site](https://nytaagency.vercel.app) · [Source](nyta-agency/)

---

## Travel Waitlist

A landing page for a travel launch, rebuilt from the Figma prototype. Hover a photo and it pops above the others. Hover the waitlist pill and it morphs straight into a frosted-glass form: the title slides up, Close drops in, and the description and fields rise one by one. Validation, a loading state and a personalised confirmation complete the flow.

![Travel waitlist](media/travel-waitlist.gif)

Shared-element pill-to-card morph · backdrop blur and frosted glass · pointer-driven 3D tilt with glare · inline validation · success state that updates the page

[Live demo](https://dhunidesigns.github.io/Engineering-Playground/travel-waitlist/) · [Source](travel-waitlist/index.html) · [Video](media/travel-waitlist.mp4)

---

## Signature Pad

A signature modal for a referral partner agreement, shown on a tablet. Draw with smooth, pressure-like strokes, type it in a script typeface, or upload an image. Pick an ink colour, and Done flies the signature straight into the form.

![Signature pad](media/signature-pad.gif)

Canvas drawing with velocity-based stroke width · sliding tabs · typeface dropdown with blurred swaps · drag-and-drop upload · shared-element transition into the form · bottom sheet on phones

**Upload flow:** choose or drop a JPG, PNG, PDF or SVG, watch it upload with live progress, remove or replace it, then drop it into the form.

![Signature upload flow](media/signature-upload.gif)

[Live demo](https://dhunidesigns.github.io/Engineering-Playground/signature-pad/) · [Source](signature-pad/index.html) · [Draw & type video](media/signature-pad.mp4) · [Upload video](media/signature-upload.mp4)

---

## Run locally

```bash
git clone https://github.com/DhuniDesigns/Engineering-Playground.git
cd Engineering-Playground
open index.html   # or double-click any index.html
```

Built with plain HTML, CSS and JavaScript (Web Animations API and spring physics, no frameworks).

---

Designed and built by **Hafsoh Bashar** ([@DhuniDesigns](https://github.com/DhuniDesigns)).
