gulp pre-commit
================

### Using gulp pre-commit with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git@github.com:ClarityMovement/gulp-pre-commit.git
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: gulp-pre-commit
