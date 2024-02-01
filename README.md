# suyog-google.github.io

## How to publish an assetlinks.json
This very simple page allows you to publish an assetlinks.json file at the location [domain.com]/.well-known/assetlinks.json, for the purpose of testing.

To make sure this works, you must:

Use the name [yourgithubusername].github.io for the repository name.
Put the following text at the beginning of your assetlinks.json file:
---
layout: none
permalink: .well-known/assetlinks.json
---
Yes, this is invalid JSON, but the actual served content will be fine.

