# github-claude-code-setup-practice

A practice repository for setting up and experimenting with [Claude Code](https://claude.com/claude-code), Anthropic's official CLI for agentic coding.

## About

This repo is used to explore Claude Code's workflows and features, including:

- Configuring Claude Code in a real project
- Working with slash commands, skills, and hooks
- Practicing common software engineering tasks with an AI coding assistant

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Manoj10041996/github-claude-code-setup-practice.git
   cd github-claude-code-setup-practice
   ```
2. Start making changes and experimenting.

## GitHub Personal Access Token (PAT) Setup

To push/pull over HTTPS (e.g., when a credential helper isn't configured), you'll need a GitHub Personal Access Token.

1. Go to **GitHub → Settings** (click your profile photo, top right).
2. Scroll down to **Developer settings** (bottom of the left sidebar).
3. Select **Personal access tokens → Tokens (classic)** (or **Fine-grained tokens** for more restrictive scoping).
4. Click **Generate new token**.
5. Give it a descriptive name, set an expiration, and select the scopes it needs (at minimum `repo` for private repo access).
6. Click **Generate token** and copy it immediately — GitHub only shows it once.
7. Store it locally in a `.env` file (already excluded via `.gitignore`) as:
   ```
   gh_token=<your_token_here>
   ```

**Never commit your token.** Treat it like a password — anyone with it can access your repositories according to the scopes you granted.

## License

No license specified yet.
