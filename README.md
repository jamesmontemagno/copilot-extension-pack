## GitHub Extension Pack

GitHub Extension Pack bundles the essential GitHub tooling for Visual Studio Code so you can review pull requests, collaborate through Codespaces, leverage Copilot, and automate with Actions without hunting through the marketplace one extension at a time.

### Extensions included
- GitHub Actions (`GitHub.vscode-github-actions`)
- GitHub Copilot (`GitHub.copilot`)
- GitHub Copilot Chat (`GitHub.copilot-chat`)
- GitHub Pull Requests and Issues (`GitHub.vscode-pull-request-github`)
- VS Code Speech (`ms-vscode.vscode-speech`)
- GitHub Repositories (`GitHub.remotehub`)
- GitHub Codespaces (`GitHub.codespaces`)

### Getting started
1. Install the extension pack from the VS Code Marketplace.
2. Reload VS Code if prompted.
3. Sign in to GitHub to unlock Copilot, Codespaces, and Pull Request workflows.

### Automated publishing
- Configure a `VSCE_TOKEN` secret in your repository with a Marketplace Personal Access Token that has the `Marketplace (Publish)` scope.
- Trigger the **Publish Extension Pack** workflow manually to choose between stable or pre-release publishing, or simply create a GitHub release (mark it as pre-release to push to the pre-release channel).
- If you ship a stable build, remind users to flip individual extensions to their pre-release channel inside VS Code if they want bleeding-edge features for Copilot, Codespaces, or other bundled tools.

### Feedback and contributions
Open issues and feature requests in your fork of this project, or adjust the `extensionPack` list in `package.json` to align with your team's toolkit.
