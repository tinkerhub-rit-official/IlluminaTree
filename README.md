````markdown name=README.md url=https://github.com/tinkerhub-rit-official/IlluminaTree/blob/7c6c68fb4599a130bd08854517e3c019507a443e/README.md
# IlluminaTree — TinkerHub RIT Hackathon Starter

Welcome to IlluminaTree — the official starter repository for participants in the Illuminate Tree online hackathon organised by TinkerHub RIT.

This repository is a lightweight template that every participant should fork, use as the base for their project, and then submit their *fork* as the entry. Do NOT push your project work to the original (upstream) repository — work in your fork only.

---

Table of contents
- Overview
- Quick start — how to participate
- Recommended repository structure
- What to include in your fork (submission checklist)
- Branching & commit guidance
- How to share / submit your project
- License & Code of Conduct
- Contact

---

Overview
--------
IlluminaTree is a minimal repo intended to be forked by each hackathon participant or team. Use your fork to develop your project, store supporting media (videos, images, documents), and provide clear instructions so judges and organisers can review your work.

Quick start — how to participate
--------------------------------
1. Fork this repository to your GitHub account (use the GitHub "Fork" button).
2. Clone your fork locally:
   - git clone https://github.com/<your-username>/IlluminaTree.git
3. Create a branch for your work:
   - git checkout -b feature/<project-name>
4. Add your project code and supporting files to the fork (see recommended structure below).
5. Commit frequently with clear messages and push to your fork:
   - git push origin feature/<project-name>
6. When you are ready, make sure your main branch (or a clearly named release branch) in your fork contains the final submission and follow the submission instructions provided by hackathon organisers (normally this is a submission form that asks for the URL to your fork).

Important: Do NOT push to tinkerhub-rit-official/IlluminaTree (the upstream repository). All development and final files must live in your fork.

Recommended repository structure
-------------------------------
This is a suggested layout — adopt it to your project needs:

- README.md                — your project README (required)
- LICENSE                  — your chosen license (optional but recommended)
- src/                     — source code for your project
- docs/                    — additional documentation, design notes
- assets/ or images/       — screenshots, icons
- videos/                  — demo video(s) (MP4 preferred) or links
- data/                    — sample datasets (if size permits) or instructions to fetch
- examples/                — example usage or sample inputs/outputs

What to include in your fork (submission checklist)
---------------------------------------------------
- [ ] A clear project README (at the repository root) that explains:
  - Project name and short description
  - Features and what problem it solves
  - How to run/build/test the project (step-by-step)
  - Any dependencies and minimum requirements
  - License and author/team information
- [ ] Source code in a folder (e.g., `src/`)
- [ ] Demo video showing the working project:
  - Either include the video file in `videos/demo.mp4` (if size permits) or add an embeddable link (YouTube/Drive) in the README
  - If you include a hosted link, include a local thumbnail/screenshot in `assets/`
- [ ] Screenshots and images in `assets/` or `images/`
- [ ] Any supporting documents (design doc, user manual) in `docs/`
- [ ] A short CHANGELOG or notes about what you submitted and how to evaluate it
- [ ] (Optional) A release or tag on your fork for the final submission version

Media and large files
---------------------
- If your demo video or data files are large, prefer hosting (YouTube, Google Drive, Dropbox, etc.) and put a link in the README. Also add a small thumbnail screenshot to `assets/` for quick preview.
- Keep the repository reasonably sized; if you must add large datasets, clearly document how reviewers can obtain them.

Branching & commit guidance
---------------------------
- Use a feature branch for active development (e.g., `feature/<project-name>`).
- Keep `main` or `master` in your fork as the stable copy of your submission.
- Use clear, descriptive commit messages.
- Do not open pull requests against the upstream repo unless organisers specifically ask for it.

How organisers / judges will review
-----------------------------------
Organisers will review submissions via the fork URL you provide in the hackathon submission form. Make sure:
- The fork is public (unless organisers request private forks and provide access).
- The submission branch or `main` contains your final project and media.
- Your README contains instructions for running and evaluating the project.

Examples
--------
- videos/demo.mp4 — demo video
- assets/screenshot-1.png — screenshot of the app
- src/ — your application code and build scripts
- README.md — explains how to run the demo and what to look for

License & Code of Conduct
-------------------------
- Choose a license for your project (MIT, Apache-2.0, etc.) and add a LICENSE file to your fork.
- Follow the TinkerHub RIT hackathon Code of Conduct. Be respectful to other participants and organisers.

Contact / Help
--------------
If you need help, contact the hackathon organisers via the official event channels (Slack/Discord/email) provided on the event page. Do not open issues on the upstream repository for your project work — use your fork's issue tracker if you need to track bugs or tasks.

Good luck and have fun building — we can't wait to see what you create!

TinkerHub RIT — Illuminate Tree Hackathon
````
