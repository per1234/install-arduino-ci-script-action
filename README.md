# `per1234/install-arduino-ci-script-action`

A [GitHub Actions](https://github.com/features/actions) action for installing [per1234/arduino-ci-script](https://github.com/per1234/arduino-ci-script).

Although written for use with Travis CI. At least some of the functions of the per1234/arduino-ci-script script are usable with GitHub Actions.

Please see [action.yml](./action.yml) for the documentation of the action's inputs.

## Example usage

```yaml
- uses: per1234/install-arduino-ci-script-action@v1
  with:
    installation-path: extras/ci/tools/arduino-ci-script
```

#### Contributing
Pull requests or issue reports are welcome! Please see the [contribution rules](.github/CONTRIBUTING.md) for instructions.
