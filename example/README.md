# github-actions-docs

Some dummy text before action-docs have been written

<!-- BEGIN_ACTION_DOCS -->

# github-actions-cleanup-workflow-runs
GitHub action to cleanup workflow runs from a repository

# inputs
| Title | Required | Type | Default| Description |
|-----|-----|-----|-----|-----|
| DRY_RUN | False | string | `true` | Whether to run the action in dry-run mode <true|false> |
| DELETE_OLDER_THAN | False | string | `7` | The age of deployments to delete (in days) |
| BRANCH_NAME | False | string |  | The branch name. Empty means all branches. |
| WORKFLOW_FILE | False | string |  | The workflow file name (e.g. workflow.yaml). Empty means all workflows. |
| REPO_NAME | False | string | `${{ github.event.repository.name }}` | The repository name (e.g. api) |
| GITHUB_TOKEN | True |  |  | GitHub token |
<!-- END_ACTION_DOCS -->

# Local development

Some dummy text after action-docs have been written