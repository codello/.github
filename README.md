# Codello Repository Defaults

This is a special repository that provides common defaults for other projects by codello. These defaults are specific to the GitHub platform but may include configuration for third-party features on the platform. One such example is [Renovate](https://www.mend.io/renovate/).

## Using Renovate Templates

See the Renovate [documentation](https://docs.renovatebot.com/config-presets/#extending-from-a-preset). As a quick start you can use

```json
{
  "extends": "github>codello/renovate-config"
}
```

## Versioning

The contents of this repository provide defaults for other projects but are in many cases not explicitly referenced. This makes versioning contents basically impossible.

In addition it can be highly dependent on a project, what constitutes a breaking change. In order to avoid confusion, this repository does not provide version numbers. If you use the renovate config in this repository, you should consider every change a potentially breaking change. Usually you are better off, maintaining your own fork of this repo.
