# Portfolio workflow

The user explicitly requested pushing new portfolio code to https://github.com/pofceka/myportfolio.git whenever we add or change something.

After completing and validating each requested change, commit and push the changes to this repository. Never force push or overwrite unrelated user changes. Report a push failure clearly.

This is a buildless static site in dist/. Run node --check dist/app.js for JavaScript changes. Preserve clearly marked placeholders until real content is supplied.

The existing private Sites deployment is maintained from ../ayubkhon-portfolio. For changes in this workspace, keep its dist/, BRIEF.md, and BRAND.md synchronized before following the Sites publication workflow. Keep hosting credentials and local publication archives out of GitHub.
