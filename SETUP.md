# Sneha Singh — Anya-themed GitHub Profile Setup

## Files included

- `README.md` — profile README for the special repository `Sneha21-09/Sneha21-09`.
- `hero.svg`, `skills.svg`, `missions.svg` — animated header and section banners. The hero embeds the custom Anya-inspired portrait and animated rings.
- `assets/anya-portrait.jpg` — editable source portrait used inside the hero.
- `assets/anya-laptop.gif`, `assets/anya-cheer.gif`, `assets/anya-dev-loop.gif` — actual animated character GIFs (not still images).
- `.github/workflows/profile-3d.yml` — optional daily 3D contribution skyline workflow.
- `PROJECT-INVENTORY.md` — full list of the 14 visible public repositories and their summaries.

## Upload steps

1. Open `https://github.com/Sneha21-09`.
2. Create or open the special profile repository named exactly `Sneha21-09` (same as the username).
3. Set it to **Public**.
4. Extract this ZIP on the computer. Open the extracted `sneha-anya-github-profile` folder.
5. Upload the contents of that folder to the repository root: `README.md`, the three SVG files, `assets/`, and `PROJECT-INVENTORY.md`. Commit to the `main` branch.
6. For the optional workflow, also upload `.github/workflows/profile-3d.yml`. If Windows hides `.github`, enable **View → Show → Hidden items** in File Explorer. Alternatively, create the file using GitHub's **Add file → Create new file** and enter the path `.github/workflows/profile-3d.yml`.
7. Open the repository's **Actions** tab, select **Anya's 3D Contribution Skyline**, and choose **Run workflow**. The workflow is optional; the README and GIF animations work without it.
8. After the workflow succeeds, refresh `https://github.com/Sneha21-09`. The contribution skyline may take a little time to appear.

## Important notes

- The README lists all 14 public repositories visible in the screenshots. Project descriptions are based only on visible profile/repository descriptions; entries with limited details are kept intentionally short.
- `HFT-COMPILER-FRAMEWORK` is shown as a pinned external repository owned by `devinasharma094`; it is not counted among Sneha's 14 owned public repositories.
- LinkedIn and public email are omitted because no public URLs were provided.
- The technology list is limited to what is visible in repository descriptions/language labels. Confirm and add any additional skills before publishing.
- The character GIFs contain frame-to-frame movement. The SVG also uses CSS/SMIL-style motion; GitHub/client support for SVG animation can vary, while GIF animation is the reliable moving character element.
- Stats cards use third-party services and can occasionally be rate-limited or unavailable.
- This is an unofficial, fan-made theme and is not affiliated with the anime's rights holders.


## Visual sizing and motion check

The README now uses `assets/anya-hero-motion.gif` as its main hero so the name **Sneha Singh** types in letter by letter while Anya moves. The supporting Anya GIFs are displayed at larger widths (270–280 px) to avoid tiny character artwork and excess empty-looking space. Keep the `assets/` folder structure unchanged when uploading.
