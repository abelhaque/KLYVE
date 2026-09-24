KLYVE WEBSITE — one folder, ready to deploy
============================================

STRUCTURE
  index.html               HOME — open-loop concept, wallet+card explanation,
                           Fastercard comparison, built-in loop demo
  merchants.html           Merchant marketing landing page
  spend-crypto.html        Consumer page — "spend crypto anywhere"
  remittance.html          Remittance savings calculator (8 corridors)
  fee-savings.html         Merchant fee savings calculator
  merchant-calculator.html PLACEHOLDER — replace with your Merchant Pay Calculator app
                           (save your existing calculator build as this filename)
  payme-generator.html     PayMe personal payment page generator
  open-loop.html           Standalone "open loop" animated campaign page (shareable)
  franchise.html           National / regional franchise opportunity

All pages are cross-linked (shared top navigation + footer sitemap).
No build step; the only external dependency is the QR library (cdnjs)
used by PayMe pages when hosted online (graceful text fallback offline).

DEPLOY
  Replace the contents of your GitHub repo with this folder and push —
  Vercel redeploys automatically. Or drag the folder onto app.netlify.com/drop.
  Then on your phone: open the URL -> Add to Home Screen (PWA).

BEFORE GOING LIVE
  1. Replace merchant-calculator.html with your real calculator app.
  2. Update placeholder links: "Download the app" (#) on merchants.html and
     spend-crypto.html; the mailto address and call link on franchise.html.
  3. Point the PayMe footer link ("get your own PayMe page") in generated
     pages to payme-generator.html on your live domain.
  4. Check every fee/rate figure matches your real commercial terms.
