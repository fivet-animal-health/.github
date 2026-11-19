# .github

Organisation-wide defaults for Fivet Animal Health's repositories.

GitHub uses the files here in any repository in the organisation that doesn't have its own:

- **`pull_request_template.md`**: the description every new PR starts with. It asks what the change does, how it was tested, how risky it is, and what has to happen when it's released.

To change a template for every repository, open a PR here. To give one repository a different template, add a `pull_request_template.md` to that repository's `.github/` folder.

This repository is public because GitHub only applies these defaults from a public `.github` repository. Keep it to templates. Code, server details and anything else internal belong in a private repository, such as `handbook`.
