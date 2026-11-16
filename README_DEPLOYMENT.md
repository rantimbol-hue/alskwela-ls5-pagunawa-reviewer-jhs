# ALSKwela JHS LS5 — GitHub Pages and Offline Installation

**App name:** JHS ALS A&E Reviewer LS 5 - Pag-unawa sa Sarili at Lipunan
**Home Screen short label:** JHS A&E LS5 Pag-unawa
**Question bank:** 120 original draft items / 27 curriculum competencies / 3 fixed sets of 40.

## Publish
1. Create a new public GitHub repository, e.g., `alskwela-ls5-pagunawa-reviewer-jhs`.
2. Extract this ZIP. Upload all files from its root to the repository ROOT, not inside a folder.
3. In Settings > Pages, choose `Deploy from a branch`, `main`, and `/(root)`.
4. Open the published `https://USERNAME.github.io/REPOSITORY/` link in Chrome.
5. Add the URL in ALSKwela Glide with an **Open Link** action, not an embedded web view.

## Offline use (Android)
1. Connect to Wi-Fi or mobile data; open the hosted URL directly in Chrome.
2. Reload while online and check for **Offline files saved successfully**.
3. Use Chrome menu > Install app / Add to Home Screen, or **Create shortcut** if that is the option available.
4. Turn on airplane mode, launch via Home Screen, take several questions and view Taglish feedback.
5. Complete a trial, download PDF or choose **Print / Save as PDF** for preserving Filipino punctuation and symbols.

## Important
- App progress stays in browser storage; do not clear browser data or uninstall before exporting reports.
- Installing from a new GitHub repository lets this app coexist with other JHS and Elementary reviewers.
- Offline PWA installation depends on HTTPS and first successful cache installation.
- On some Android browsers, **Create shortcut** still works offline after the cache is ready.
- The question bank is a teacher-review draft, not official DepEd A&E 2027 exam content.
- Verify wording, correctness, option plausibility, fairness, and actual Android behavior before release.

## Local file map
- index.html (120 embedded questions, randomized/fixed 40-item trials, local progress, Taglish feedback, PDF report)
- sw.js (offline service worker)
- manifest.webmanifest (installed app metadata)
- icon-192.png, icon-512.png (Home Screen icons)
- question_bank_120.json (editable bank; embedded copy is authoritative for this release)
- .nojekyll
