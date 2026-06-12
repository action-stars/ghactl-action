# GitHub Actions CLI (`ghactl`) GitHub Action

## Description

<!-- AUTO-DOC-DESCRIPTION:START - Do not remove or modify this section -->

Installs GitHub Actions CLI (`ghactl`).

<!-- AUTO-DOC-DESCRIPTION:END -->

## Inputs

<!-- AUTO-DOC-INPUT:START - Do not remove or modify this section -->

|  INPUT  |  TYPE  | REQUIRED |         DEFAULT         |                      DESCRIPTION                      |
|---------|--------|----------|-------------------------|-------------------------------------------------------|
|  token  | string |   true   | `"${{ github.token }}"` |        GitHub token to use for authentication.        |
| version | string |  false   |       `"latest"`        | Version of `ghactl` to install; defaults to `latest`. |

<!-- AUTO-DOC-INPUT:END -->

## Outputs

<!-- AUTO-DOC-OUTPUT:START - Do not remove or modify this section -->
No outputs.
<!-- AUTO-DOC-OUTPUT:END -->
