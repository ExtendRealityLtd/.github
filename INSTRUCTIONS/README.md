# .github

A collection of documents to provide consistent information across repositories.

## Usage

These files can be used as a template for the `.github` contents in other repositories or can be directly linked to to prevent synchronization issues.

### Adding to an existing project

Add this `.github` repository as a subtree to your existing repository root directory:

* `cd <your-git-repository-root-directory>`
* `git subtree add --prefix=.github --squash https://github.com/ExtendRealityLtd/.github.git master`

### Updating in an existing project

If any content updates exist in this `.github` repository then pull them down to your existing repository root directory:

* `cd <your-git-repository-root-directory>`
* `git subtree pull --prefix=.github --squash https://github.com/ExtendRealityLtd/.github.git master`