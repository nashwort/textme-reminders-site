# TextMe Reminders website

This folder contains a simple static website intended to support the TextMe Reminders project and its Twilio A2P registration.

## Files

- `index.html` — public home page and SMS opt-in instructions
- `privacy.html` — Privacy Policy
- `terms.html` — Terms & Conditions, including SMS Terms
- `styles.css` — site styling
- `twilio-registration-copy.txt` — suggested text to paste into Twilio's campaign form

## IMPORTANT: replace these placeholders before publishing

Search all files for the following yellow placeholder text and replace it:

- `YOUR_REGISTERED_BRAND_NAME` — use the exact registered brand name shown in Twilio.
- `YOUR_TWILIO_NUMBER` — use your Twilio SMS number in a clear format, e.g. `(920) 555-1234`.
- `YOUR_SUPPORT_EMAIL` — use an email address you are comfortable publishing publicly.

Do not submit the A2P campaign while any placeholder remains on the live website.

## Quick local preview

Double-click `index.html` to open it in your browser. The links to the Privacy Policy and Terms should work locally.

## Publish for free with GitHub Pages

1. Sign in to GitHub and create a new public repository named `textme-reminders-site`.
2. Upload all files in this folder to the root of the repository.
3. Open the repository's **Settings**.
4. Open **Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then save.
7. Wait for GitHub Pages to publish the site.

Your URLs will look similar to:

- Home: `https://YOUR-GITHUB-USERNAME.github.io/textme-reminders-site/`
- Privacy: `https://YOUR-GITHUB-USERNAME.github.io/textme-reminders-site/privacy.html`
- Terms: `https://YOUR-GITHUB-USERNAME.github.io/textme-reminders-site/terms.html`

Use the Privacy and Terms URLs in the matching Twilio fields.

## Twilio opt-in proof

Because the campaign is using a text-keyword opt-in, the home page includes public instructions telling users to text `START` to your Twilio number. After the site is published, the home page URL can be used as the public proof of the opt-in method if Twilio asks for a URL.

Make sure the live page shows:

- the keyword `START`
- the Twilio phone number
- the registered brand/operator name
- recurring automated reminder messages
- message frequency varies
- message and data rates may apply
- STOP instructions
- HELP instructions
- links to Privacy Policy and Terms

## Important note

This package is a practical starter template for the project and Twilio registration. It is not legal advice. If the service later expands beyond a personal/hobby app or starts collecting more data, accepting payments, or serving the general public, review and update the policies accordingly.
