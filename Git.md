# Learn Git and GitHub

## 20231023 11:26

```sh
OSSD|main ⇒ ggpull
From github.com:hyosung11/OSSD
 * branch            main       -> FETCH_HEAD
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint: 
hint:   git config pull.rebase false  # merge
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
OSSD|main⚡ ⇒
```

It looks like you have some divergent branches in your GitHub repository when trying to pull the latest changes. This happens when the remote branch and your local branch have diverged.

To resolve this, you have a few options:

1. Rebase your local branch onto the remote branch. This will replay your local commits on top of the remote commits:

    ```sh
    git pull --rebase origin main
    ```

2. Merge the remote branch into your local branch. This will create a merge commit: 

```
git config pull.rebase false 
git pull
```

3. Fast-forward your local branch to the remote branch. This will drop any local commits and make your branch point to the same commit as the remote:

```
git config pull.ff only
git pull
```

The error suggests setting one of these as your default pull strategy with `git config --global pull.rebase true` or `false`.

Typically rebasing or fast-forwarding is preferred to keep a linear commit history, but it depends on your workflow.
