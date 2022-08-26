# GrumPHP Conventions

Centralised GrumPHP configuration used by Headsnet projects.

## Installation

Install via Composer:

```bash
composer require --dev headsnet/grumphp-conventions
```
## Usage

The convention configuration has various parameters which can be overridden if necessary.

```yaml
# Project grumphp.yml
imports:
    - { resource: vendor/headsnet/grumphp-conventions/grumphp.yml }

parameters:
    convention.gitlab_lint.api_token: 'MY TOKEN'

```
