# Workflow

## Branches
### `main` branch
Main branch for the repository. Do not commit directly to this branch. Pull requests from the `dev` branch should be merged to this branch.

### `dev` branch
Branch for development. Features completed in feature branches will be commit to this branch. To do so, pull requests should be made from the feature branches.

## Feature branches
All new features should be created as a feature branch and should branch off from `dev` branch. 
**Format:** `<key>/<feat/bug>/<feature name>`

Examples:
- `T06-4/feat/login` 
- `T06-4/bug/login`
- having the key will ensure that the relevant branch codes will reflected in the jira issues.

If you are unsure of where to find the key of the jira issues, you may refer to the image below circled
// insert picture here

## Committing messages
### Commit Types
- `feat` - new feature
- `fix` - a bug fix
- `refactor` - changes that is not related to feature or fix
- `style` - changes that does not affect the codes, related to code formatting
- `test` - including new or correcting previous tests

### Examples of commit messages to link the commits to jira issues
**Format:** `[key] <commit type>: <commit message>`

Examples: 
- `[T06-4] feat: added test function`
- `[T06-4] fix: login issue`