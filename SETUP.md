# How to install your GitHub profile redesign

Your profile repository is `CzarGarcia/CzarGarcia`.

1. Copy `README.md`, `assets/hero.svg` and `assets/terminal.gif` into that repository, keeping the directory paths exactly as provided.
2. Add the included `.github/workflows/snake.yml` at the same path.
3. Commit and push to the repository's default branch (`main` in the workflow supplied). If the repository uses a different default branch, update the workflow trigger accordingly.
4. In the repository on GitHub, open **Actions** → **Generate contribution snake** → **Run workflow** to generate the first snake images. Then wait for the workflow to finish and for the `output` branch to be created.
5. Refresh your GitHub profile. The activity snake is generated daily, with GitHub dark/light mode variants.

Notes:
- The animated terminal is a real local GIF and works without external services.
- The custom hero SVG is static by design for reliability; the typing line and snake provide motion.
- Typing text, tech icons, shields and view counts depend on third-party image services and their uptime.
- The PLC project points to the portfolio because its public source URL could not be confirmed.
- For the contribution snake, the repository must allow GitHub Actions to write contents. If branch publishing fails, open **Settings → Actions → General → Workflow permissions** and enable read/write permissions for actions (where permitted), then rerun.
- If you rename your GitHub username or profile repo, update hardcoded profile and snake URLs.
