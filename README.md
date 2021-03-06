# pytorch-pfn-extras

Supplementary components to accelerate research and development in PyTorch.

## Installation

```sh
pip install pytorch-pfn-extras

### Optinal dependencies
# For PlotReport / VariableStatisticsPlot extensions
pip install matplotlib

# For IgniteExtensionsManager
pip install pytorch-ignite torchvision
```

## Documentation

* [Extensions Manager](docs/extensions.md)
* [Reporting](docs/reporting.md)
* [Lazy Modules](docs/lazy.md)
* [Distributed Snapshot](docs/snapshot.md)
* [Config System](docs/config.md)

## Examples

* [Custom training loop](example/mnist.py)
* [Ignite integration](example/ignite-mnist.py)

## Contribution Guide

You can contribute to this project by sending a pull request.
After approval, the pull request will be merged by the reviewer.

Before making a contribution, please confirm that:

- Code quality stays consistent across the script, module or package.
- Code is covered by unit tests.
- API is maintainable.

## License

MIT License
