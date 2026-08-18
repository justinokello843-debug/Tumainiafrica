# Tumaini Africa — Website

Two self-contained pages (HTML, CSS, and JavaScript each in a single file, no build step required):

- `index.html` — the main site
- `give.html` — the dedicated donation page (linked from every "Donate" button)

## Deploying this site

1. Create a new GitHub repository and upload both files so they sit at the top level of the repo (not inside a subfolder).
2. Go to vercel.com, sign in with GitHub, click **Add New → Project**, select this repository, and click **Deploy**. No configuration needed.
3. Your site goes live at a free `https://your-project-name.vercel.app` URL. `give.html` will automatically be reachable at `.../give.html`.
4. Every future edit and push automatically redeploys within seconds.

## Editing the donation page later

- All currency, amount, and payment-method content lives inside `give.html`.
- To add a real payment gateway (Flutterwave, Paystack, Stripe, etc.), search `give.html` for the comment `GATEWAY_INTEGRATION_POINT` and replace that block with your real checkout button or payment link.
