# LeetCode Auto-Sync Template 🚀

This is a complete template repository to fully automate exporting your LeetCode solutions every day. It includes a GitHub Action to fetch your solutions, and a custom Chrome Extension to automatically sync your LeetCode session securely.

## Setup Instructions

### 1. Repository Setup
1. Fork this repository or create a new private repository and copy these files into it.
2. The GitHub Action in `.github/workflows/sync.yml` is already configured!

### 2. Chrome Extension Setup
1. Generate a **GitHub Personal Access Token (Classic)** with `repo` and `workflow` permissions.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** (top right corner).
4. Click **Load unpacked** and select the `chrome-extension` folder found in this repository.
5. Click the extension icon in your browser toolbar, paste your PAT and your repository name (e.g., `YourUser/LeetCode-Solutions`), and click **Save**.
6. While logged into LeetCode, click **Push Cookie to GitHub Now**.

Your GitHub action will now run seamlessly every day at midnight!
