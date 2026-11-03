# TikTok URL prefix verification

Site prefix (after GitHub Pages is live):
https://taliapastor0.github.io/tiktok-automation-site/

## Reserved location
The repository root is the publishing root. Place the original signature file supplied by TikTok here, alongside index.html, terms.html and privacy.html. No signature file has been created: both its exact filename and its bytes must come from TikTok.

1. In TikTok Developers, open the app in Production, then URL properties > Verify properties > URL prefix.
2. Enter the complete site prefix above, including the trailing slash.
3. Download TikTok's original signature file. Preserve its filename and contents exactly.
4. Confirm the exact destination URL shown by TikTok. If it is below this prefix, add the file at the corresponding relative repository path.
5. Wait for Pages deployment, then check that exact URL publicly returns the original file, without a login or HTML error page.
6. Complete verification in TikTok Developers. Do not assume github.io is accepted until verification succeeds.
7. Replace the Notion URLs in the app configuration:
   - Terms of Service: https://taliapastor0.github.io/tiktok-automation-site/terms.html
   - Privacy Policy: https://taliapastor0.github.io/tiktok-automation-site/privacy.html
   - Website, if applicable: https://taliapastor0.github.io/tiktok-automation-site/

If TikTok requests a signature at the host root (https://taliapastor0.github.io/), this project repository does not publish there. Reassess hosting or use an owner-controlled domain; do not claim that a file under the project path satisfies a different requested path.

## Policy source and limits
The English policy pages are based on the owner's existing Notion documents, last updated November 3, 2026:
- Terms: https://app.notion.com/p/40d20549a1ee819ab07aebf896d197b5
- Privacy: https://app.notion.com/p/40d20549a1ee8141b230f79f2a559e52

The contact instruction was replaced with the supplied contact email. Actual downstream AI/hosting providers and retention periods remain to be confirmed before enabling those workflows or submitting the app for review. No unsupported no-storage promise was added.

Official verification guide: https://developers.tiktok.com/docs/en/getting-started-create-an-app

