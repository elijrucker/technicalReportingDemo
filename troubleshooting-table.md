# Troubleshooting

| # | Problem | Likely cause | Fix | Highlight on diagram |
|---|---|---|---|---|
| 1 | `command not found` / not recognized | Git isn't installed, or the command line needs restarting | Install Git using the link in the guide, then reopen the command line | "Requires Git" box |
| 2 | `not a git repository` | You're outside your project folder | Use `cd` to move into the cloned project folder | Computer (local repository) |
| 3 | `Authentication failed` (private repositories) | Wrong username or token, or the token has expired | Generate a new Personal Access Token and re-enter it | "Requires PAT sign-in" box and arrows |
| 4 | `Repository not found` | Typo in the URL, or you haven't been given access | Recheck the URL, then ask whoever onboarded you to add you as a collaborator | Cloud (remote repository) |
| 5 | Pull fails with a conflict message | Your local changes clash with incoming updates | Save your work first, then ask a teammate before trying anything else | `git pull` arrow |
