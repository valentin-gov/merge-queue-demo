# merge-queue-demo

Throwaway repo to demonstrate GitHub's **merge queue**.

The CI workflow runs on both `pull_request` and `merge_group`, so when PRs are
queued, GitHub builds them together on a temporary `gh-readonly-queue/...` branch
and only merges if that combined build is green.
