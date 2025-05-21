<p align="center">
    <a href="https://wippy.ai" target="_blank">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://github.com/wippyai/.github/blob/main/logo/wippy-text-dark.svg?raw=true">
            <img width="30%" align="center" src="https://github.com/wippyai/.github/blob/main/logo/wippy-text-light.svg?raw=true" alt="Wippy logo">
        </picture>
    </a>
</p>
<h1 align="center">.github</h1>

This repository contains organization-wide GitHub configuration files and templates.
These files help standardize workflows, issue templates, pull request templates, and other GitHub-specific settings across all repositories in our organization.

## Purpose

The `.github` repository serves as a central place to store default community health files and GitHub Actions workflow templates.
When a file is added to this repository, it will be used by any repository within our organization that doesn't have its own version of that file.

## Contents

This repository may include:

### Workflow Templates

- `.github/workflow-templates/`: Reusable GitHub Actions workflow templates that can be selected when creating new workflows in repositories across the organization
    - These templates appear alongside GitHub-provided workflow templates when creating a new workflow
    - They don't automatically run in repositories but provide standardized starting points

### Templates

- `.github/ISSUE_TEMPLATE/`: Organization-wide issue templates
- `.github/PULL_REQUEST_TEMPLATE.md`: Default pull request template
- `CODE_OF_CONDUCT.md`: Organization-wide code of conduct
- `CONTRIBUTING.md`: Default contributing guidelines
- `SECURITY.md`: Security policy and vulnerability reporting instructions
- `SUPPORT.md`: Support resources and how to get help
- `FUNDING.yml`: Funding information for the organization's projects
- `GOVERNANCE.md`: Project governance structure and decision-making processes

## Usage

These files will be automatically used as defaults for repositories that don't have their own versions.
To override any of these files, simply create the same file in your repository's `.github` directory.

## References

- [GitHub Docs: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [GitHub Docs: Starting with workflow templates](https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization)
