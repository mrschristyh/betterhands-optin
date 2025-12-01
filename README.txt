Better Hands, LLC — SMS Opt-In Mini Site
===================================================

This tiny static site is designed to satisfy Twilio's toll‑free SMS verification reviewers.
It provides a public, branded opt‑in page showing explicit consent, STOP/HELP language,
frequency, and links to Terms & Privacy.

FILES
-----
- index.html     → Main opt‑in page with an unchecked consent checkbox
- terms.html     → Simple Terms page
- privacy.html   → Simple Privacy page

HOW TO HOST (FREE)
------------------
Option A) GitHub Pages (free)
  1) Create a GitHub account (if needed).
  2) Create a repo named: betterhands-optin (public).
  3) Upload these files (drag‑and‑drop).
  4) Settings → Pages → Build from "main" branch / root.
  5) Wait for the URL (e.g., https://<your‑user>.github.io/betterhands-optin).

Option B) Static hosts (free)
  - Providers like static.app or awardspace.com allow uploading a static site
    and give you a public HTTPS URL. Upload all files to the root.

WHAT TO SUBMIT TO TWILIO
------------------------
• The public URL to index.html (with visible branding and consent language)
• Exact opt‑in wording (copy/paste from the page)
• Sample message flows (see below)

SAMPLE SMS TEMPLATES (COPY/PASTE)
---------------------------------
# Confirmation (double opt‑in) — send after web form submission
Better Hands, LLC: Thanks for signing up! Reply YES to confirm you want recurring automated texts about property opportunities & updates. Msg&data rates may apply. Reply STOP to opt out, HELP for help. Freq varies. Terms: <your site>/terms.html Privacy: <your site>/privacy.html

# Welcome — send only after user replies YES
Better Hands, LLC: You’re in! We’ll text property opportunities & updates. Reply STOP to cancel, HELP for help. Msg&data rates may apply. Freq varies. Terms: <your site>/terms.html Privacy: <your site>/privacy.html

# HELP keyword auto-reply
Better Hands, LLC: For help, email info@betterhands.com. Reply STOP to cancel. Msg&data rates may apply.

# STOP keyword auto-reply
You’ve opted out of Better Hands, LLC texts. No more messages will be sent. Reply START to re‑subscribe.

# START keyword auto-reply (optional)
You’re re‑subscribed to Better Hands, LLC texts. Reply STOP to cancel, HELP for help. Msg&data rates may apply.
