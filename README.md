# Roblox Web Platform

This repository is a hub to all the repositories in the Roblox platform sorted by aspect.

## Teams Layout

The default team for maintaing this repository is [Web Platform Maintainers](https://github.com/orgs/rbxinfra/teams/web-platform-maintainers).<br />
For each respective sub category:
- Platform Libraries (/lib) -> [Library Maintainers](https://github.com/orgs/rbxinfra/teams/library-maintainers) -- This is the default team for this aspect, the submodule itself defines CODEOWNERS for each team.
- Micro Services (/services) -> [Micro Services Platform](https://github.com/orgs/rbxinfra/teams/micro-services-platform)
- Web Core (/web) -> [Web Platform Maintainers](https://github.com/orgs/rbxinfra/teams/web-platform-maintainers) -- Internal talks on delegating a new team for this, see [BIZOPS-2761](https://jira.vmminfra.net/browse/BIZOPS-2761).
- Web API Core (/api-sites) -> [Web Api Platform](https://github.com/orgs/rbxinfra/teams/web-api-platform)
- CI/CD + Tooling (/tools) -> [Platform CI](https://github.com/orgs/rbxinfra/teams/platform-ci) -- Not all of these tools are to do with CI/CD, therefore within submodules, CODEOWNERS are broken by respective teams (e.g. entity-schema-generator --> [Data Access Platform](https://github.com/orgs/rbxinfra/teams/data-access-platform), translation-resources-generator --> [Internationalization Team](https://github.com/orgs/rbxinfra/teams/internationalization-team))
