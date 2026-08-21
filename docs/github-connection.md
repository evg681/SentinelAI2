# Connect GitHub

Connect GitHub to allow SentinelAI investigate your repositories.
## Connect

1. Go to **Settings**.
2. Select **GitHub**.
3. Click **Connect**.
4. Reviww and allow read-only access to your repositories.

SentinelAI needs access to your GitHub account to investigate repositories and security issues.


## Permissions

SentinelAI requests read-only repository access.

This means SentinelAI can read repository content needed for an investigation, but it cannot:
- modify repository files
- create or merge pull requests
- push commits
- delete repositories

If GitHub shows a permission request that does not match the expected read-only repository access, **do not approve the connection**. 
Contact your administrator or `Support` (support@sentinelai.co.il)

## Troubleshooting

**GitHub connection fails**

If the connection cannot be completed:

1. Make sure you are signed in to the correct GitHub account.
2. Check that your GitHub account has access to the repositories you want SentinelAI to investigate.
3. Review the permissions shown by GitHub before approving the connection.
4. Try the connection again.
5. If the problem persists, contact Support and include the error message shown by GitHub.

**SentinelAI cannot access a repository**
Check that:

- the repository is accessible from the GitHub account you connected;
- the connection was approved successfully;
- SentinelAI has the expected read-only repository access.
  
If the repository is still unavailable, contact `Support` (support@sentinelai.co.il) with the repository name and the error message, if posible.

**Disconnect GitHub**

If you no longer want SentinelAI to access your repositories, disconnect the GitHub integration from **Settings → GitHub**.

Disconnecting GitHub prevents SentinelAI from using the connection to access your repositories.
