# Repository setup 

We recommend that CNCF projects separate docs into their own repository, away from code. This has the following advantages:

- Docs contributors don't need to know the full code build pipeline 
- It simplifies repo management/continuous integration setup 


For more information:

- The [`cncf/project-template`](https://github.com/cncf/project-template) repository contains many of the files needed to set up a new repository

## CLA/DCO

CLA/DCO should be set up for a project as a part of their project onboarding.

## Licence files 

Unless otherwise specified, documentation for CNCF projects is licenced under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). Code is licenced under [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0).

Most CNCF documentation repositories are a mix of code (website code) and documentation itself, so they need two licence files.

For documentation this means you must: 


1. Add copyright notices for both the code and the docs to the repository's `README` and the website's footer

For the repository: 

```
# License

$PROJECT_NAME is licensed under an [Apache 2.0 license](./LICENSE).

The #PROJECT_NAME documentation is licensed under a [CC-BY-4.0 license](./LICENSE-docs). 
```

For the footer:

- [`cncf/hugo-netlify-starter`](https://github.com/cncf/hugo-netlify-starter/blob/main/layouts/partials/footer.html) contains a basic implementation, where the year and project name are parameterized.


2. Add both the CC-BY-4.0 `LICENCE-docs` and Apache 2.0 `LICENCE` files to the root directory of the documentation
    - Plain text versions of both [here](https://github.com/cncf/project-template)

For more information:

- Read [CNCF's project copyright guidelines](https://github.com/cncf/foundation/blob/master/copyright-notices.md)
- And the [IP Policy](https://github.com/cncf/foundation/blob/master/charter.md#11-ip-policy)

## README

All docs repositories should have a README file that includes build instructions. Look at [Longhorn's](https://github.com/longhorn/website) for an example, and the [`cncf/project-template`](https://github.com/cncf/project-template) for boilerplate.
