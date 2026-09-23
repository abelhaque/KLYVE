KLYVE WEBSITE — one folder, ready to deploy
============================================

STRUCTURE
  index.html               Merchant marketing landing page (home)
  spend-crypto.html        Consumer page — "spend crypto anywhere"
  remittance.html          Remittance savings calculator (8 corridors)
  fee-savings.html         Merchant fee savings calculator
  merchant-calculator.html PLACEHOLDER — replace with your Merchant Pay Calculator app
                           (save your existing calculator build as this filename)
  payme-generator.html     PayMe personal payment page generator
  open-loop.html           "The open loop" animated campaign page
  franchise.html           National / regional franchise opportunity

All pages are cross-linked (shared top navigation + footer sitemap).
No build step, no dependencies except: payme-generator pages load the QR
library from cdnjs when hosted online (graceful text fallback offline).

DEPLOY
  Option A (fastest): drag this whole folder onto app.netlify.com/drop
  Option B: push the folder to a GitHub repo and import it into Vercel
  Then on your phone: open the URL -> Add to Home Screen (PWA).

BEFORE GOING LIVE
  1. Replace merchant-calculator.html with your real calculator app.
  2. Update placeholder links: "Download the app" (#) on index.html and
     spend-crypto.html; the mailto address and call link on franchise.html.
  3. Point the PayMe footer link ("get your own PayMe page") in generated
     pages to payme-generator.html on your live domain.
  4. Check every fee/rate figure matches your real commercial terms.
