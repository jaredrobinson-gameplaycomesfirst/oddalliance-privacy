# Odd Alliance privacy-policy hosting

This public repository is reserved for the approved Odd Alliance privacy policy. It contains no game source, signing keys, personal email addresses, or unfinished policy claims.

No policy has been published yet. Developer identity and a public support/privacy contact are still being confirmed, along with the application's complete SDK data practices.

## Publish after approval

1. Add the finalized, approved policy as `site/index.html`. Include the app/developer identity, public contact, data handling, third-party services, security, retention/deletion and effective date.
2. Confirm that it contains no draft notices or placeholders and is readable on mobile.
3. Enable GitHub Pages with **GitHub Actions** as the source if not already configured.
4. Manually run **Publish approved privacy policy** from the Actions tab. There is no automatic publication on pushes. The workflow refuses a missing or visibly unfinished policy and publishes only `site/`.
5. Verify anonymous HTTPS access at `https://jaredrobinson-gameplaycomesfirst.github.io/oddalliance-privacy/` before using the URL in the app or Google Play Console. This is the intended address, not a currently published policy.

The site should use self-contained HTML/CSS without tracking scripts, cookies, forms or external embedded assets. GitHub Pages logs visitors' IP addresses for security; account for hosting in the policy.
