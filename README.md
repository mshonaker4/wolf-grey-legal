# Wolf Grey Context legal pages

Public policy pages for the local Wolf Grey Context application. Application code, credentials, financial records, private source paths and review artifacts stay in the separate private project.

## Review status

The October 6, 2026 revision describes the implemented local, on-demand, read-only QuickBooks connector. At the owner’s request, Wolf Grey Context is described as an internal project rather than a separately formed legal entity; “Provider” means its owner and operator. The owner confirmed `formosavacation@gmail.com` as the public contact email and Colorado governing law on October 6, 2026. The changes are ready for owner review and merge before deployment. GitHub Pages was not configured when checked on October 6, 2026; repository visibility alone does not publish a website.

## What these pages describe

- API acquisition: company information, accounts/classes, Profit and Loss and Balance Sheet reports. No accounting writes, payments or scheduling.
- Supported manual-export import, local searchable snapshots and deterministic comparison controls.
- Credentials stored separately with restrictive file permissions; atomic updates, file locking and expiring OAuth state. No application-level encryption or customer isolation claim.
- No automatic model API calls in the application. A separately selected cloud assistant receives any content shown to it under that service's settings and terms.
- Local retention until operator deletion, without an automated deletion service. Revocation and deletion are separate operations; external assistants, backups and source copies require separate handling.
- No advertising or sale functionality in the current code. The public pages have no scripts or forms; GitHub's hosting practices apply to website visits.

These statements describe the current implementation. Review the pages whenever data flows, storage, security, deletion, service providers or customer functionality change. EULA clauses on ownership, warranty, liability and governing law require the provider's review; no claim of legal compliance or enforceability is established by matching the code. An attorney's review remains appropriate before customer use.

## Project name and future customer use

Using the project name does not establish a legal entity or a registered trade name. These pages do not establish whether registration is required for the operator’s activities. Before external customer licensing, confirm the actual contracting provider and applicable registration requirements. If conducting business in Colorado under an assumed name, consult [Colorado’s trade-name guidance](https://www.sos.state.co.us/pubs/business/FAQs/tradeNames.html). Internal app registration with Intuit does not itself settle that question.

## Publish after review

1. Review and merge the policy change to `main` in this public repository.
2. Open [repository Pages settings](https://github.com/mshonaker4/wolf-grey-legal/settings/pages).
3. Under **Build and deployment**, choose **Deploy from a branch**, then **main** and **/(root)**, and save. See [GitHub's publishing-source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
4. Wait for the deployment to succeed. Open both pages without signing in and verify the final provider, contact details and content.
5. Enter the working URLs in the Intuit production app's Privacy Policy and End User License Agreement fields. Policy URLs are not OAuth redirect URIs.

Expected addresses after successful deployment:

- EULA: `https://mshonaker4.github.io/wolf-grey-legal/eula.html`
- Privacy Policy: `https://mshonaker4.github.io/wolf-grey-legal/privacy.html`

These are deployment targets, not confirmed live URLs. Use the exact addresses reported by GitHub Pages if the hosting configuration changes. Publishing policies does not establish Intuit app approval, OAuth consent or live report validation.

## Source-code licensing

The EULA controls authorized application use; it is separate from a license granting general rights to the source code. Preserve the core repository's proprietary status unless the owner explicitly chooses a source-code license. No MIT or Apache license is added by this update.
