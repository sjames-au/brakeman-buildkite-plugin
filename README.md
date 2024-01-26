# Brakeman Buildkite Plugin

A Buildkite plugin that runs [Brakeman](https://brakemanscanner.org/), a static analysis security vulnerability scanner for Ruby on Rails applications.

## Requirements

- Buildkite Agent v3.x
- Ruby
- Brakeman

## Example

Add the following to your pipeline configuration:

```yaml
steps:
  - plugins:
      - sjames-au/brakeman#v1.0.0