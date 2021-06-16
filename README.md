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

## Use

Check out the [asdf documentation](https://asdf-vm.com/#/core-manage-versions?id=install-version) for instructions on how to install and manage versions of Kubectl.

## Acknowledgement

This plugin was created based on [asdf-community/asdf-kubectl](https://github.com/asdf-community/asdf-kubectl).
