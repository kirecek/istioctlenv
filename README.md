# istioctlenv

[Istioctl](https://istio.io/latest/docs/setup/install/istioctl/) version manager inspired by [tfenv](https://github.com/tfutils/tfenv) which is inspired by [rbenv](https://github.com/rbenv/rbenv)
🤷‍♂️

## Installation

### Manual

1. Check out istioctlenv into any path (here is `${HOME}/.istioctlenv`)

  ```console
  git clone https://github.com/kirecek/istioctlenv.git ~/.istioctlenv
  ```


2. Add `~/.istioctlenv/bin` to your `$PATH` any way you like

  ```console
  export PATH="$HOME/.istioctlenv/bin:$PATH"
  ```

## Usage

### istioctlenv install [version]

Install a specific version of Istio.

If no parameter is passed, the version to use is resolved automatically via .istioctl-version files, defaulting to 'latest' if none are found.

## LICENSE

- [istioctlenv itself](https://github.com/kirecek/istioctlenv/blob/master/LICENSE)
- [tfenv](https://github.com/tfutils/tfenv/blob/master/LICENSE)
- tfistioctlenv uses big part of tfenv's source code
