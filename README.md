# Wolf Grey Context legal pages

Separate public legal-policy pages for your private Wolf Grey Context application. This folder does **not** include the application's code, financial records, or credentials.

## Before publishing

- In `eula.html` and `privacy.html`, replace `[FULL LEGAL NAME OF OWNER OR BUSINESS]` with the exact legal owner, not an assumed trade name.
- Replace `[CONTACT EMAIL]` and `REPLACE_WITH_CONTACT_EMAIL` in both files.
- In `privacy.html`, replace the bracketed sections on data sharing, real security practices, storage, retention and deletion with statements verified against the implementation. Confirm OpenAI API use and any other services.
- Confirm the warranty, liability, legal-entity and jurisdiction clauses in the EULA fit your situation. An attorney's review is prudent before customer use.
- Ensure the pages accurately describe what is implemented before using production financial data.

## GitHub Pages instructions

1. Create a new **public** repository named `wolf-grey-legal` on GitHub, separate from private `wolf-grey-context`.
2. Upload `eula.html`, `privacy.html`, and `style.css` to the root of `wolf-grey-legal`. (README.md may also be uploaded.)
3. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
4. Test each actual URL from an incognito browser window before pasting into the Intuit Developer portal.

Example URL patterns after publishing:
- `https://YOUR-USERNAME.github.io/wolf-grey-legal/eula.html`
- `https://YOUR-USERNAME.github.io/wolf-grey-legal/privacy.html`

These example URLs are placeholders and **do not exist** until you publish the repository.

The EULA and Privacy Policy are different from the license for your source code. Keep the core repo proprietary / All Rights Reserved for now if you want to retain commercial licensing control. Do not add an Apache-2.0 or MIT LICENSE to the core repo unless you intentionally want to grant those rights.
