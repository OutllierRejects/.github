# OutllierRejects · .github

Welcome to the **.github** repo for OutllierRejects! This repository holds organization-wide configurations and community files that apply to every project under our GitHub org. Think of it as the blueprint for how we work, collaborate, and keep things organized.

---

## 📢 About OutllierRejects
We’re not just another AI or competition crew—we’re both. We build ML/AI tools, share research code, and occasionally flex our algorithmic chops in contests. If you thrive on edge cases, weird corner-case bugs, or squeezing extra performance from your models, you’ll fit right in.

---

## 🗂 What’s in This Repo?
These files automatically get applied to all repos under the OutllierRejects organization:

- **Issue Templates** (`.github/ISSUE_TEMPLATE`):
  - Bug report
  - Feature request
  - Research discussion
- **Pull Request Template** (`.github/PULL_REQUEST_TEMPLATE.md`):
  - Checklist for code style, tests, and documentation
- **Contributing Guide** (`CONTRIBUTING.md`):
  - How we expect you to code, document, and test
  - Branching and PR conventions
- **Code of Conduct** (`CODE_OF_CONDUCT.md`):
  - Basic rules to keep the community friendly and productive
- **Workflows** (`.github/workflows/`):
  - CI/CD pipelines (linting, tests, model checks)
  - Auto-label bots, dependency updates
- **Funding/Support** (`FUNDING.yml`):
  - Ways to support open-source efforts if you want (totally optional)

---

## 🛠 How to Use This Repo
1. **Organization-Level Settings**  
   You don’t need to do anything—GitHub automatically picks up templates and workflows in `.github/`. Whenever a new issue or PR is opened in any org repo, these templates and CI configs will be used.

2. **Adding/Updating Templates**  
   - Fork or clone this repo.
   - Modify files under `ISSUE_TEMPLATE/`, `PULL_REQUEST_TEMPLATE.md`, or `workflows/`.
   - Submit a PR to merge changes here. Once approved, all repos in OutllierRejects inherit the update.

3. **Contributing to Policies**  
   Found a better way to write code, test models, or run CI?  
   - Update `CONTRIBUTING.md` or add a new workflow.  
   - Make a PR, and ping maintainers for a quick review.

---

## ✏️ Contributing Guidelines
- **Follow our style**:  
  - PEP8 (Python), Google style (JS/TS), or project-specific linters.  
  - Write clear, concise commit messages:  
    ```
    feat: add new data-loader for multi-modal input
    fix: correct off-by-one in nlp preprocessing
    doc: update README with model training steps
    ```
- **Write Tests/Checks**:  
  - Every new feature or fix should include a quick test or script to verify it works.  
  - If you add a model, include a minimal example that loads it and runs inference.
- **Use Issue Labels**:  
  - `bug`, `enhancement`, `research`, `documentation`, `help wanted`.  
  - This helps us triage and track what’s going on.
- **Respect the Code of Conduct**:  
  - Be professional and respectful. Call out bad behavior through the official channels, not in public threads.

---

## 🎯 Communication
- **Chat/Discussion**:  
  - We use GitHub Discussions in individual repos for deep technical debates.  
  - For quick questions, ping us on our Discord:  
    `discord.gg/OutlierRejects`  
- **Meetups & Office Hours**:  
  - Weekly Zoom session (every Thursday at 7:00 PM IST) for code reviews, brainstorming, and random AI chatter.  
  - Link shared in our Discord announcements channel.
- **Mailing List**:  
  - Subscribe via `outllierrejects@lists.github.com` (internal org mailing list).

---

## 📜 License & Acknowledgments
Most projects under OutllierRejects are licensed under **MIT** by default. Check each repo’s `LICENSE` file for specifics.

Thanks to everyone who has:
- Debugged at 3 AM
- Squashed that mysterious GPU memory leak
- Shared notebooks, scripts, models, or just good memes

Let’s keep pushing boundaries, sharing knowledge, and owning those edge cases.

---

> “Outliers aren’t mistakes—they’re the ones who rewrite the rules.”  
> — OutllierRejects Team
