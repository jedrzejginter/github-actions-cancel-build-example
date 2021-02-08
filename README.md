# Github Actions + [cancel-workflow-action](https://github.com/styfle/cancel-workflow-action)

Example of cancelling currently running workflows on new commit. To see it in action, push `commit A` and then, within 60 seconds push `commit B`. The second commit should cancel workflow triggered by the first commit.
