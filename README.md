# debian-install-python-buildenv - Github action

Github action - Install Debian Python Build Environment

It may be only used by Debian or Ubuntu based images.

## Example

```yaml

    steps:

      - name: 'Adding Debian repo definitions of Frank Brehm'
        uses: fbrehm/debian-install-python-buildenv@main
        with:
          additional_packages: python3-fb-tools

```

## Inputs

```yaml
inputs:
  additional_packages:
    description: "A withespace separated list of packages additional to the base build packages"
    type: string
```

