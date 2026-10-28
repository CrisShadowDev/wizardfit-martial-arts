# Uncle Matt Martial Arts Store - Mock v2 Build Report
Date: 2026-10-28 (America/New_York)
Owner: Uncle Matt (Matt Brooks) only. NOT WizardFit.

## What was built / finished
- Mock v2 from the existing wizardfit-martial-arts template, sequentially: local build first, then GitHub, then Vercel. Not batched.
- 10 gear products + 2 POD placeholders = 12 products.
- Instagram mock section: handle TBD, no account linked, no posts made.
- All images are PLACEHOLDER SVGs, labeled PLACEHOLDER, not real photos.
- Checkout is TEST ONLY, no charge. Config placeholders only, no real Stripe or supplier keys.
- No money spent, no domain bought, no sends, no social posts.

## GitHub - DONE
- Repo: https://github.com/CrisShadowDev/wizardfit-martial-arts (created 2026-10-28, 201, branch main)
- Before this build the repo did NOT exist (404, Oct 27 rate limit had blocked it; rate_remaining was 4999 at check time).
- Files uploaded one by one, sequentially, all 201 except README first attempt 422 (auto_init README existed), then updated with its SHA, 200.
- Verified tree (19 files): README.md, app.js, config.js, index.html, products.json, style.css, images/*.svg (12).

## Vercel - DONE, file deployment, NOT Git-linked
- Project: wizardfit-martial-arts, prj_nED8UHPR7qeaesNFGSTxbuFSmAvK, team reality-dev-phantom
- New deployment: dpl_QvzAbV6AJK8t2CvX2P5gAYgA3XdH, READY, production
- URL: https://wizardfit-martial-arts-mhaql7iqt-reality-dev-phantom.vercel.app
- Aliases: https://wizardfit-martial-arts.vercel.app , https://wizardfit-martial-arts-reality-dev-phantom.vercel.app
- Previous deployment (v1, no placeholder images): dpl_Bh3UidqbbTjSKsfAxeuURAo9MCHc, also READY, superseded by the new deployment.
- Git-link limitation, unchanged: Vercel projects are NOT Git-linked (create_git_project failed 403 team-scope in prior builds, and get_project/list_deployments with teamId still return 403). File deployments were used. Future GitHub pushes will NOT auto-pull to Vercel until Vercel team access is granted by the user. Do NOT claim Git pull works.

## Placeholder list
- images/boxing-gloves.svg, hand-wraps.svg, bjj-gi.svg, focus-mitts.svg, kick-pads.svg, mouthguard.svg, headgear.svg, shin-guards.svg, gear-bag.svg, belt-display.svg
- images/pod-tee.svg, pod-hoodie.svg (POD placeholders)
- All labeled PLACEHOLDER in the SVG and on the product card.

## Still needed from Matt before it can go live
1. Instagram handle + approval to link / feature it.
2. Final product list and planning prices (confirm / add / remove).
3. POD design(s) or a decision to drop POD.
4. Supplier choice + supplier API permission / keys via Secure Vault (never in chat or code).
5. Stripe owner choice: Crishtian's vs Uncle Matt's, with explicit approval.
6. Real product photos to replace every PLACEHOLDER image.
7. Domain decision, if any - none bought, none claimed.
