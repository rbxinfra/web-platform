# Roblox Web Platform

This repository is a hub to all the repositories in the Roblox platform sorted by aspect.

# Notice

## Usage of Roblox, or any of its assets.

# ***This project is not affiliated with Roblox Corporation.***

The usage of the name Roblox and any of its assets is purely for the purpose of providing a clear understanding of the project's purpose and functionality. This project is not endorsed by Roblox Corporation, and is not intended to be used for any commercial purposes.

Any code in this project was soley produced with or without the assistance of error traces and/or behaviour analysis of public facing APIs.

## Teams Layout

The default team for maintaing this repository is [Web Platform Maintainers](https://github.com/orgs/rbxinfra/teams/web-platform-maintainers).<br />
For each respective sub category:
- Platform Libraries (/lib) -> [Library Maintainers](https://github.com/orgs/rbxinfra/teams/library-maintainers) -- This is the default team for this aspect, the submodule itself defines CODEOWNERS for each team.
- Micro Services (/services) -> [Micro Services Platform](https://github.com/orgs/rbxinfra/teams/micro-services-platform)
- Web Core (/web) -> [Web Platform Maintainers](https://github.com/orgs/rbxinfra/teams/web-platform-maintainers) -- Internal talks on delegating a new team for this, see [BIZOPS-2761](https://jira.vmminfra.net/browse/BIZOPS-2761).
- Web API Core (/api-sites) -> [Web Api Platform](https://github.com/orgs/rbxinfra/teams/web-api-platform)
- CI/CD + Tooling (/tools) -> [Platform CI](https://github.com/orgs/rbxinfra/teams/platform-ci) -- Not all of these tools are to do with CI/CD, therefore within submodules, CODEOWNERS are broken by respective teams (e.g. entity-schema-generator --> [Data Access Platform](https://github.com/orgs/rbxinfra/teams/data-access-platform), translation-resources-generator --> [Internationalization Team](https://github.com/orgs/rbxinfra/teams/internationalization-team))
