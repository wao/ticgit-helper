# ticgit-helper
Some script help to work with TicGit-ng

## Auto add commit informations to related ticket

Add following strings in your comment of commit 

   `[your_ticket_id] a test commit`

The commit information will be added to ticket comment automaticly.

Multiple tickets are support, just like following:

    `[your_ticket_id_1, your_ticket_id_2] a test commit`

Usage:
    link `git-hooks/post-commit.ticgit` to your `.git/hook/post-commit`
