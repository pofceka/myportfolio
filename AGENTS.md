# Portfolio project instructions

## Website and source

This folder is the canonical working copy of Ayubkhon Yuldashev's portfolio.
- GitHub: https://github.com/pofceka/myportfolio
- Branch: main
- Live website: https://ayubkhon-desktop-portfolio.goofy-slug-2603.chatgpt.site/
- Site project ID: appgprj_6afbefe814b48191b58745259ad2f1f4
- Site access: private, requires the owner's ChatGPT sign-in. Preserve its audience unless the user explicitly asks to change it.

## Files and preview

The website is buildless HTML, CSS, and JavaScript in dist/.
- dist/index.html: content and structure
- dist/style.css: layout, responsive styles, animations
- dist/app.js: interactive behavior
- BRIEF.md and BRAND.md: the current content and design direction

Run `python3 -m http.server 8000 --directory dist` from this folder and open http://localhost:8000 for a local preview. Use the live URL for browser inspection when signed in. Reading and editing the source does not require a browser login. Never assume another chat's browser tab, running server, variables, or credentials are available.

## User's standing instructions

After every completed and validated portfolio addition or change, commit and push it to https://github.com/pofceka/myportfolio.git. This is already authorized. Do not force push or overwrite unrelated user changes. Check git status before editing, preserve pending work, and report failed pushes.

The latest design reference is https://adasilv2.framer.website/. Match its layout and animation style. The user explicitly permits clearly labeled placeholders when personal information or assets are missing. Verified background: Computing and Information Technologies student at RIT Dubai, building Pullar with SwiftUI and SwiftData, learning Python and AI, graphic design background, seeking software development internships. LinkedIn: https://www.linkedin.com/in/ayubkhon-yuldashev/.

## Validation and publication

For JavaScript changes, run `node --check dist/app.js`. Check relevant browser interactions and responsive layout when browser access is available; report verification limits honestly.

Read the Sites skill before publishing. Reuse the project_id in .openai/hosting.json; never create a second Site for this project. Use native Sites tools to acquire fresh credentials. Keep credentials in memory only, never in Git or project instructions.

The existing Sites source/deployment checkout is /Users/aubuldasev/Documents/Codex/2026-11-17/cr/work/ayubkhon-portfolio. Synchronize changed dist/, BRIEF.md, and BRAND.md there before the Sites source and publication workflow. Keep this folder's GitHub origin intact. If that deployment checkout is missing, recover source for the same Site through the Sites workflow. Never change the private audience merely to make a preview accessible.
