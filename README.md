
Ride Wallah - Static Booking Site (Ready-to-Deploy)
--------------------------------------------------

This is a simple static website for Ride Wallah (English only) with a booking form
that sends submissions to your email via Formsubmit/Formsubmit.co.

Files inside:
- index.html   -> Main website
- styles.css   -> Styles
- thank-you.html -> Thank you landing page after form submit
- README.md    -> this file

How booking emails work:
- The booking form posts to Formsubmit.co which will send form content to your email:
  https://formsubmit.co/rsmishra89822@gmail.com
- First time someone submits, Formsubmit sends a confirmation email which you must accept to start receiving messages.

How to preview locally:
- You can open index.html directly in the browser to view the static site.
- For the form to work properly it should be served over HTTP(S). Easiest hosting: Vercel (free) — see instructions below.

Quick Vercel deploy:
1. Create a GitHub repo and push these files to the repository's root.
2. Sign in to Vercel and click New Project -> Import Git Repository -> pick this repo.
3. Vercel will auto-detect a static site. Deploy.
4. Visit the assigned URL and test the booking form.
