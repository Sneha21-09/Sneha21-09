# Sneha Singh — Anya Theme GitHub Profile Setup

## Included in this package

- `README.md` — complete profile page with a typing hero, animated character, skills, hanging ID, featured project cards, expandable repository collection and contribution skyline.
- `anya-hero-motion.gif` — full-width animated hero; **Sneha Singh types in letter by letter** while Anya changes pose. It is not a static portrait.
- `anya-laptop-transparent.gif` and `anya-cheer-transparent.gif` — transparent animated Anya GIFs used as supporting character moments.
- `skills.svg`, `dashboard.svg`, `missions.svg`, `connect.svg` — custom pink / purple / gold visual panels. The dashboard ID swings from a lanyard; project cards use individual Anya props for data drift, mining safety, GIS, air intelligence and task tracking.
- `.github/workflows/profile-3d.yml` — scheduled 3D contribution skyline workflow.
- `profile-3d-contrib/` — generated contribution skyline SVGs.
- `PROJECT-INVENTORY.md` — verified repository inventory and a copy-ready project-card template for future additions.

## Upload / replace the profile

1. Open `https://github.com/Sneha21-09/Sneha21-09`.
2. Extract this ZIP on your computer.
3. Open the extracted `Sneha21-09-Anya-Profile-EXCELLENT` folder. Select **all files and folders**, including hidden `.github`.
4. Upload them to the **root** of the `Sneha21-09/Sneha21-09` repository using **Add file → Upload files**.
5. Keep the folder structure exactly as supplied. Do not move GIFs or SVGs into another folder; the README uses root-relative paths.
6. Commit the upload. GitHub will replace files with matching names.
7. Open the profile page and hard-refresh with `Ctrl + Shift + R`.
8. Open **Actions → Anya's 3D Contribution Skyline** and run it manually once. Wait for a green successful run before expecting freshly generated contribution art.
9. After confirming the new profile looks correct, you may delete obsolete files from the earlier upload if they are still present: `hero.svg`, `anya-cheer.gif`, `anya-dev-loop.gif`, `anya-laptop.gif`, `anya-portrait.jpg` and `DESIGN-REFERENCE.png`. Do not delete the new `anya-hero-motion.gif`, `anya-cheer-transparent.gif`, `anya-laptop-transparent.gif`, or the `.github` / `profile-3d-contrib` folders.

## Add a new repository later

1. Open `README.md` in the profile repository and click the pencil icon.
2. Find `Repository Collection`. Open the correct `<details>` group: AI / ML / Data Science / GIS or Web Development.
3. Copy an existing project-card `<tr> ... </tr>` block from that group.
4. Replace the repository name in both the visible title and GitHub URL, then update the one-line description and technology `<code>` tags.
5. Keep the card inside the same `<table>`. Pair it with another card in the same row, or leave an empty second `<td>`.
6. Save the README commit.
7. If the total public repository count changes, update the `14` count in `dashboard.svg` and `missions.svg`. Update the featured cards only when you want to promote a project.

A copy-ready row is also stored in `PROJECT-INVENTORY.md`.

## Animation notes

- The hero GIF types Sneha's name letter by letter and animates Anya's pose.
- The dashboard's full ID assembly rotates gently around its lanyard pivot using SVG animation.
- The character GIFs animate independently.
- GitHub may cache images; if a change does not appear immediately, change the `?v=` number on that image in `README.md` and hard-refresh.
- SVG motion may vary by client. The static layout remains readable if an SVG animation is not played.

## Accuracy notes

The dashboard uses visible profile facts (14 repositories, 3rd year, 5th semester, VIT Vellore). No contribution counts, project completion percentages, email address, LinkedIn URL or Instagram URL have been fabricated. Add public contact links only after Sneha supplies the exact URLs.
