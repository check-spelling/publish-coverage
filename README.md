# publish-coverage

publish-coverage creates a branch in a coverage repository

## inputs

Name | Description | Default
-|-|-
repository | To retrieve with actions/checkout | _None_ Must be provided
ssh-key | To retrieve repository (must have write permissions to default branch) | _None_ Must be provided
coverage | Directory containing coverage to publish | `cover_db`
author-name | Name to use for commit | actor name
author-email | Email to use for commit | actor email

## render

publish-coverage/render collates branches from a coverage repository for publication by actions/upload-pages-artifact.

### inputs

Name | Description | Default
-|-|-
repository | Repository to list in title | _None_ Must be provided
