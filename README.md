

# AGAPE — Group 5

Welcome to the **AGAPE Group 5 AI Full-Stack Project Repository**!

This repository is for our Saturday AI Full-Stack session held on **17 October 2026**. Each team member created a personal *About Me* webpage using React and Vite, deployed it online, and uploaded their source code to their individual GitHub branch.

## Team Members

| Name       | Role    | Live Website         | Source Code                          |
| ---------- | ------- | -------------------- | ------------------------------------ |
| Oreoluwa   | Captain | Add your Vercel link | [View Branch](../../tree/oreoluwa)   |
| Temitope   | Member  | Add your Vercel link | [View Branch](../../tree/temitope)   |
| Ayomikun   | Member  | Add your Vercel link | [View Branch](../../tree/ayomikun)   |
| Emmanuella | Member  | Add your Vercel link | [View Branch](../../tree/emmanuella) |

*Update the website and branch links with the correct details for each team member.*

## Repository Guidelines

To keep the project organised and make collaboration easier, we use the following structure:

- **Main branch:** Contains the project documentation and team links.
- **Individual branches:** Each member maintains a separate branch containing their personal webpage and related project files.
- **Pull requests:** Changes to the main README should be submitted through a pull request for review before merging.

## Getting Started

### 1. Upload Your Project to GitHub

Make sure your React and Vite project is available on your computer. Open the project directory in the VS Code terminal.

If your project is not already connected to Git, initialise a repository and create a branch using your name.

```bash
git init
git checkout -b oreoluwa
git add .
git commit -m "Create Oreoluwa's About Me page"
```

Replace `oreoluwa` with your own name or branch name.

Connect your project to the group repository:

```bash
git remote add origin https://github.com/orizee01/AI-fullstack-group-5
git push -u origin oreoluwa
```

If Git is already initialised, skip `git init`. If the `origin` remote already exists, update it using `git remote set-url origin <repository-url>`.

**Verify your upload:** Visit the [repository branches page](https://github.com/OluwaSeun-Femi/AI-fullstack-grp4/branches) and confirm that your branch appears.

Your Vite project should exclude generated folders such as `node_modules` and `dist` through its `.gitignore` configuration.

### 2. Update the Team README

Once your code is uploaded and your website is deployed, add your details to the team table.

1. Open the [README on GitHub](https://github.com/OluwaSeun-Femi/AI-fullstack-grp4/blob/main/README.md).
2. Select the pencil icon to edit the file.
3. Find your row in the team table.
4. Add your deployed website URL and a link to your GitHub branch.
5. Select **Commit changes**.
6. Create a new branch for the documentation update, using a name such as `add-oreoluwa`.
7. Submit a pull request for the captain to review and merge.

Use this format for your source code link:

```markdown
[View Branch](../../tree/oreoluwa)
```

Change the branch name to match your own.

### Alternative: Update the README Through VS Code

You can also make the documentation change from your terminal:

```bash
git fetch origin main
git checkout -b add-oreoluwa origin/main
```

Edit the README, then run:

```bash
git add README.md
git commit -m "Update team member details"
git push -u origin add-oreoluwa
```

Open GitHub, create a pull request, and request a review from the captain.

After completing the README update, return to your project branch when you want to continue working on your webpage.

## Troubleshooting

| Issue                                | Suggested Solution                                                                                                 |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| Node.js or npm is unavailable        | Install a supported Node.js LTS version and restart VS Code.                                                       |
| PowerShell blocks scripts            | Review the PowerShell execution policy and adjust it if appropriate.                                               |
| Git does not recognise your identity | Configure your Git username and email using `git config --global`.                                                 |
| The `origin` remote already exists   | Update it with `git remote set-url origin <repository-url>`.                                                       |
| GitHub requests a password           | Authenticate using GitHub's supported sign-in method in VS Code or Git Credential Manager.                         |
| Push permission is denied            | Confirm that you have repository access and have accepted any collaborator invitation.                             |
| Vercel authentication fails          | Run `npx vercel login`, then deploy again using the Vercel CLI.                                                    |
| Vercel deployment is unsuccessful    | Check the build logs and project configuration. You can also use another static hosting provider, such as Netlify. |

## Technologies Used

- **React 19 + TypeScript** — building the user interface
- **Vite** — development server and build tooling
- **Vercel** — hosting and deployment
- **Git and GitHub** — source control and team collaboration

## Project Goal

The goal of this exercise is to practise building a personal webpage, deploying a frontend application, managing Git branches, and collaborating through pull requests.

Each member is responsible for maintaining their own branch and ensuring their website and source code links are correctly documented.
