# Organzational assets

This repository contains special workflows and documentation that is used to customize the GitHub organization.

## Workflows

- [**Release Go Library**](.github/workflows/release-go-library.yml)  
  This workflow creates a new release for a Go library and publishes it to GitHub.

## Development

Most often we will promote workflows we have observed in other repositories to this repository. When creating a new workflow, make sure that you always:

- Create a [reusable workflow][reusable-workflow]
- Create a matching [workflow template][workflow-template]
- Select an icon name from the [GitHub Octicons][octicons] and reference it as `octicon <icon-name>`

[mkdocs]: https://www.mkdocs.org/
[reusable-workflow]: https://docs.github.com/en/actions/sharing-automations/reusing-workflows
[workflow-template]: https://docs.github.com/en/actions/sharing-automations/creating-workflow-templates-for-your-organization
[octicons]: https://primer.style/foundations/icons
