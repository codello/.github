# Codello Repository Defaults

This is a special repository that provides common defaults for other projects by codello. These defaults are specific to the GitHub platform but may include configuration for third-party features on the platform. One such example is [Renovate](https://www.mend.io/renovate/).

## Using Renovate Templates

See the Renovate [documentation](https://docs.renovatebot.com/config-presets/#extending-from-a-preset). As a quick start you can use

```json
{
  "extends": "local>codello/.github:renovate-config"
}
```

## Versioning

This repository is versioned via git tags that loosely follow [Semantic Versioning](https://semver.org/lang/de/). However, it can be highly dependent on a project, what constitutes a breaking change and what not. If you intend to use contents of this repository for your projects it is recommended that you pin the specific commit SHA instead of relying on versioned tags. If you rely on tags you may experience breaking changes, even in a patch release. Usually you are better off, maintaining your own fork of this repo.
