[![Build Status](https://github.com/opspec-pkgs/azure.apimanagement.logger.create/workflows/build/badge.svg?branch=main)](https://github.com/opspec-pkgs/azure.apimanagement.logger.create/actions?query=workflow%3Abuild+branch%3Amain)

<img src="icon.svg" alt="icon" height="100px">

# Problem statement

create an azure api management logger

# Example usage

## Visualize

```shell
opctl ui github.com/opspec-pkgs/azure.apimanagement.logger.create#2.0.0
```

## Run

```
opctl run github.com/opspec-pkgs/azure.apimanagement.logger.create#2.0.0
```

## Compose

```yaml
op:
  ref: github.com/opspec-pkgs/azure.apimanagement.logger.create#2.0.0
  inputs:
    apiCredentialsKey:  # 👈 required; provide a value
    apiManagementServiceName:  # 👈 required; provide a value
    eventHubAuthRule:  # 👈 required; provide a value
    eventHubName:  # 👈 required; provide a value
    eventHubNamespaceName:  # 👈 required; provide a value
    loggerDescription:  # 👈 required; provide a value
    loggerName:  # 👈 required; provide a value
    loginId:  # 👈 required; provide a value
    loginSecret:  # 👈 required; provide a value
    loginTenantId:  # 👈 required; provide a value
    resourceGroup:  # 👈 required; provide a value
    subscriptionId:  # 👈 required; provide a value
  ## uncomment to override defaults
  #   accessTokenMinutesValid: 60
  #   apiCredentialsIdentifier: "integration"
  #   loginType: "user"
```

# Support

join us on
[![Slack](https://img.shields.io/badge/slack-opctl-E01563.svg)](https://join.slack.com/t/opctl/shared_invite/zt-51zodvjn-Ul_UXfkhqYLWZPQTvNPp5w)
or
[open an issue](https://github.com/opspec-pkgs/azure.apimanagement.logger.create/issues)

# Releases

releases are versioned according to
[![semver 2.0.0](https://img.shields.io/badge/semver-2.0.0-brightgreen.svg)](http://semver.org/spec/v2.0.0.html)
and [tagged](https://git-scm.com/book/en/v2/Git-Basics-Tagging); see
[CHANGELOG.md](CHANGELOG.md) for release notes

# Contributing

see
[project/CONTRIBUTING.md](https://github.com/opspec-pkgs/project/blob/main/CONTRIBUTING.md)
