# Enabling GitHub Sync

## 1. Get Started
In your space, navigate to the menu and select **Synchronize with Git**. Choose **GitHub** and click **Configure**.



## 2. Authenticate
Link your GitHub account when prompted. You may need to re-authenticate even if your account was previously linked to ensure active session tokens.

## 3. Install GitBook App
Authorize the GitBook app on GitHub. You can grant access to all repositories or specific ones based on your security needs.



## 4. Repository Selection
Select the target repository and branch. 
> **Note:** If the repo is missing, verify that the GitBook app is installed in the correct GitHub organization or personal scope.

## 5. Initial Sync Direction
Choose a primary data source:
* **GitBook → GitHub:** Overwrites the repo with GitBook content.
* **GitHub → GitBook:** Overwrites GitBook with repository content.

## 6. Sync Workflow
GitBook will lock "Live Edits" and switch to **Change Requests**.
* **Merging in GitBook:** Triggers a commit to GitHub.
* **Committing to GitHub:** Triggers an automatic update in GitBook.
