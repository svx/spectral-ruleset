# Spectral ruleset 

### Dependencies

The Spectral Ruleset requires Node version 14 or later.

### Install Spectral

`npm i @stoplight/spectral-cli -g`

### Usage

You can specify the ruleset directly on the command line:

`spectral lint -r https://raw.githubusercontent.com/svx/spectral-ruleset/main/spectral.yaml <api definition file>`

Or you can create a Spectral configuration file (`.spectral.yaml`) that references the ruleset:

```yaml
extends:
  - https://raw.githubusercontent.com/svx/spectral-ruleset/main/spectral.yaml
```

### Example

```bash
spectral lint -r https://raw.githubusercontent.com/svx/spectral-ruleset/main/spectral.yaml petstore.yaml
```