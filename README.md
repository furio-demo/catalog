# catalog

The map of the `furio-demo` workspace, built by [Furio](https://github.com/getfurio/furio).

Every hour (or on demand from the Actions tab) the `Map` workflow reads the `.architecture/`
folder of every repo in the org with a read-only token (`FURIO_TOKEN`), merges them into
`model.json` and publishes it on GitHub Pages: https://furio-demo.github.io/catalog/
