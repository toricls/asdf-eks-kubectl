# asdf-eks-kubectl

Amazon EKS vended kubectl plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Install

```
asdf plugin-add kubectl https://github.com/toricls/asdf-eks-kubectl.git
```

If you'd like use both this plugin and [`asdf-kubectl`](https://github.com/asdf-community/asdf-kubectl) then install the plugin under a different name such as `eks-kubectl`.

```
asdf plugin-add eks-kubectl https://github.com/toricls/asdf-eks-kubectl.git
```

## Prerequisites

- jq

## Usage

List all available versions:

```
asdf list-all kubectl
```

Install and point specific EKS-vended kubectl version:

```
# Install
asdf install kubectl 1.20.4

# Set version
asdf global kubectl 1.20.4
```

Use `eks-kubectl` instead of `kubectl` if you installed the plugin with different name such as `eks-kubectl`.

See also the [asdf documentation](https://asdf-vm.com/#/core-manage-versions?id=install-version) for more instructions.

## Acknowledgement

This plugin was created based on [asdf-community/asdf-kubectl](https://github.com/asdf-community/asdf-kubectl).
