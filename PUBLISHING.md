# Publishing the Website

## Upload the repository

1. Create a **public** repository named `portfolio` in the `athaillahbagas` GitHub account.
2. Add the contents of this folder to the repository root (`README.md` and `docs/` should be at the top level).
3. Review every public-facing draft for accuracy and permission.

## GitHub Pages setup

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Set branch to **main**, folder to **/docs**, then **Save**.
4. The expected default Pages path (subject to account configuration) is `https://athaillahbagas.github.io/portfolio/`.

The website has no build dependencies. Check deployment status under Actions and/or Settings → Pages.

## Updating a case study

- Complete the narrative in `templates/CASE-STUDY.md` privately first.
- Create or update a public HTML page under `docs/projects/`.
- Add a homepage link only after the piece is verified and cleared for publication.
- Verify links on the live site.

## Reminder

GitHub Pages webpages are public even when the underlying repository may be private under some plans. Do not place any secrets in `docs/`.
