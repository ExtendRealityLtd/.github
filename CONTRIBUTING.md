# Contributing

We are keen for developers to contribute to open source projects to keep them great!

Whilst every effort is made to provide features that will assist a wide range of development cases, it is inevitable that we will not cater for all situations.

Therefore, if you feel that your custom solution is generic and would assist other developers then we would love to review your contribution.

There are however, a few guidelines that we need contributors to follow so that we can have a chance of keeping on top things. Guidelines ensure we can keep consistency across the project and make it easier for people to consume and contribute.

## Getting Started

* Make sure you have a GitHub [account].
* Create a new issue on the GitHub repository, providing one does not already exist.
  * Clearly describe the issue including steps to reproduce when it is a bug (fill out the issue template).
  * Make sure you fill in the earliest version that you know has the issue.
* [Fork] the repository on GitHub.

## Making Changes

* Please avoid working directly on your master branch.
* Create a topic branch from where you want to base your work.
  * Name your branch with the type of issue you are fixing. `fix`, `perf`, `chore`, `feat` are valid types.
* Make commits of logical units.
* Make sure your commit messages are in the proper format.

## Coding Conventions

Please follow the relevant coding conventions depending on the project type listed below:

* [Unity project conventions].

## Documentation Guidelines

Please follow the documentation guidelines listed below:

* [Unity documentation guidelines].

## Commit Messages

We follow the [Conventional Commits] standard when creating commit subject lines and messages.

The commit message lines should never exceed 72 characters and should be entered in the following format:

> **Example:**
```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
```

### Type

The type must be one of the following:

* feat: A new feature.
* fix: A bug fix.
* perf: A code change that improves performance.
* chore: Changes to the build process or auxiliary tools or libraries such as documentation generation.

### Scope

The scope could be anything specifying the place of the commit change, such as, `Controller`, `Interaction`, `Locomotion`, etc...

### Subject

The subject contains succinct description of the change:

* use the imperative, present tense: "change" not "changed" nor "changes".
* don't capitalize first letter, unless naming something, such as `Bootstrap`.
* no dot (.) at the end of the subject line.

### Body

Just as in the subject, use the imperative, present tense: "change" not "changed" nor "changes" The body should include the motivation for the change and contrast this with previous behaviour. References to previous commit hashes is actively encouraged if they are relevant.

> **Incorrect commit summary:**
```
Added feature to improve teleportation
```
> **Incorrect commit summary:**
```
feat(Teleport): Add feature
```
> **Incorrect commit summary:**
```
feat(my-teleport-feature): my feature.
```

> **Correct commit summary:**
```
feat(Teleport): add fade camera option on teleport
```

##' Breaking Changes

Any commit that includes a breaking change should clearly denote in the commit body with the phrase `BREAKING CHANGE:` followed by a description of what the breaking change is and any required migrations expected of consumers such as references to deprecated methods.

> **Example:**
```
feat(Teleport): add fade camera option on teleport

A brief description of the feature with rationale as to why it was
implemented.

BREAKING CHANGE: Explanation of the change that will cause previous
versions to break with this change and what consumers can do to migrate
their previous version to the new operation such as mentioning
deprecated methods and the updated equivalent.
```

## Submitting Changes

* Push your changes to your topic branch in your repository.
* Submit a pull request to this repository into the appropriate branch:
  * If your change is a `fix`, `perf` or `chore` then target the `master` branch as this will create a new patch release.
  * If your change is a `feat` without breaking changes then target the `next` branch as this will create a new minor release.
  * If your change contains breaking changes then target the `next-major` branch as this will create a new major release.
* The repository team will aim to look at the pull request as soon as possible, provide feedback where required and merge when it is deemed a satisfactory addition.

## Copyright Notices

Do not include any copyright notices in any files committed to the repository. As the author of the commit you will continue to retain the copyright for the code committed but do so under the license stated in the repository as outlined in the [GitHub Terms Of Service].

[Account]: https://github.com/join?source=header-home
[Fork]: https://help.github.com/en/github/getting-started-with-github/fork-a-repo
[Unity project conventions]: https://github.com/ExtendRealityLtd/.github/blob/master/CONVENTIONS/UNITY3D.md
[Unity documentation guidelines]: https://github.com/ExtendRealityLtd/Guidelines.Documentation
[Conventional Commits]: https://www.conventionalcommits.org/
[GitHub Terms Of Service]: https://help.github.com/en/articles/github-terms-of-service#6-contributions-under-repository-license
