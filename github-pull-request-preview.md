# GitHub Pull-Request Previews

Pre-visualize your documentation changes in a non-production environment before merging them into your synced branch.

## 1. Overview
When a PR is submitted to a tracked GitHub branch, GitBook generates a unique staging URL. This acts as a final validation layer to ensure formatting and content are correct before the live site updates.



## 2. Accessing Previews
This feature is enabled by default if the GitBook App has read-only PR permissions.
* **Locating the Link:** Look for the GitBook status check within your GitHub PR.
* **Viewing:** Click **Details** to open the preview.
* **Access Control:** Currently, previews are restricted to authorized GitBook users.

## 3. Security & Forks
To prevent "domain spoofing," GitBook disables previews for PRs originating from **repository forks** by default. 
> **Risk:** Since previews are served under your `.gitbook.io` or custom domain, a malicious user could use a fork to host unauthorized content under your brand.

You can manually enable fork previews within your **Git Sync settings** if required.
