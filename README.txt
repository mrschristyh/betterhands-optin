Better Hands, LLC — Twilio-Ready SMS Opt-In (Marketing-Only)
===================================================

WHAT CHANGED
------------
• Removed all "demo" wording.
• On submit, page now shows a real-looking confirmation message.
• Wording specifies MARKETING messages only (to avoid Twilio error 30504).
• Checkbox is unchecked by default and not required (consent must be optional).
• STOP/HELP, frequency, and rates language is present.
• Terms & Privacy pages included.

SUBMITTING TO TWILIO
--------------------
In the verification form, describe the use case as:
"Better Hands, LLC sends real estate investment marketing updates and property opportunities to subscribers who opt in via a website checkbox consent form at <YOUR LIVE URL>. Message frequency varies. Reply STOP to cancel, HELP for help. Msg & data rates may apply."

Upload screenshots of:
1) The main opt-in area (business name visible, checkbox, consent text, links)
2) The confirmation toast after pressing Submit
3) The Terms and Privacy pages

RECOMMENDED SMS TEMPLATES
-------------------------
Confirmation (double opt-in):
Better Hands, LLC: Thanks for signing up! Reply YES to confirm you want recurring automated marketing texts about property opportunities & updates. Msg&data rates may apply. Reply STOP to opt out, HELP for help. Freq varies. Terms: <your site>/terms.html Privacy: <your site>/privacy.html

Welcome (after YES):
Better Hands, LLC: You’re in! We’ll text property opportunities & updates. Reply STOP to cancel, HELP for help. Msg&data rates may apply. Freq varies. Terms: <your site>/terms.html Privacy: <your site>/privacy.html

HELP keyword:
Better Hands, LLC: For help, email info@betterhands.com. Reply STOP to cancel. Msg&data rates may apply.

STOP keyword:
You’ve opted out of Better Hands, LLC texts. No more messages will be sent. Reply START to re-subscribe.

GITHUB PAGES QUICK DEPLOY
-------------------------
1) Create a public repo (e.g., betterhands-optin) and upload index.html, terms.html, privacy.html.
2) Repo → Settings → Pages → Set "Branch: main" and "Root". Save.
3) Wait for the live URL to appear (e.g., https://<username>.github.io/betterhands-optin).

NOTE
----
Twilio also checks that your business information in their form matches what appears on your website. You may optionally add your physical business mailing address into the footer of index.html to match your submission.
