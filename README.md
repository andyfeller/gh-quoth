> _Quoth the Raven: "Nevermore"_

# gh-quoth

A `gh` extension to create an issue for discussion based upon another.

## Quickstart

1. `gh extension install andyfeller/gh-quoth`
1. `gh quoth --target-repo=<owner>/<repo> <number>`
1. `gh quoth --target-repo=<owner>/<repo> <url>`
1. Profit! :moneybag: :money_with_wings: :money_mouth_face: :money_with_wings: :moneybag:

## Usage

```shell
$ gh quoth --help

Create an issue for discussion based upon another.

USAGE
  gh quoth [flags] {<number> | <url>}

FLAGS
  -d, --debug                          Enable debug logging
  -h, --help                           Displays help usage
  -R, --repo=[HOST/]OWNER/REPO         Select another repository for sourcing issue to quoth
  -T, --target-repo=[HOST/]OWNER/REPO  Select another repository for creating issue
```
