# NotifyAOD website

Public privacy policy and support for NotifyAOD, by Ali H. Adapted from the owner's `swimxd/blurb-website` layout: plain HTML/CSS, system fonts, automatic dark mode, and GitHub Pages.

- Website: https://swimxd.github.io/notifyaod-website/
- Privacy policy: https://swimxd.github.io/notifyaod-website/privacy.html
- Support: https://swimxd.github.io/notifyaod-website/support.html

GitHub Pages publishes `main` from the repository root. There is no JavaScript, analytics, form backend, external font, or app download in this repository. It contains no Android app source or signing material.

The privacy policy describes NotifyAOD 1.2.0 (`com.notifyaod.app`). On September 24, 2026 it was checked against the app's merged manifest, which includes Google Play Billing's network permissions, and against its notification handling, local stores (choices, recovery journal, purchase/preview record, pause record), diagnostics, and health alerts. NotifyAOD no longer has an accessibility service (removed in October 2026 for Google Play policy), so the policy does not mention one. Notification data stays on the phone. Update the policy whenever data practices change, and keep it consistent with the Play Data safety form.

The developer contact is the existing public support inbox, `blurbapp.support@gmail.com`; messages should mention NotifyAOD. The app links to the privacy policy, the support page and the public issue tracker. Publishing this website does not publish the app or complete Play declarations.

Preview locally with any static HTTP server, for example `python -m http.server 8080`, then open http://localhost:8080/.
