# Tooling

[![Built with Devbox](https://www.jetify.com/img/devbox/shield_galaxy.svg)](https://www.jetify.com/devbox/docs/contributor-quickstart/)

This repo contains the tooling to work with K8s...

The setup is as follows:

1. Install DevBox

```shell
curl -fsSL https://get.jetify.com/devbox | bash
```

2. Start DevBox

```shell
git clone git@github.com:heathen1878/k8s-tooling.git

devbox shell --config ~/source/k8s-tooling/
```

3. Bonus Configuration

Start automatically when you open a shell

```shell
if [[ -z "DEVBOX_SHELL_ENABLED" && $- == *i* ]]
then
    devbox shell --config ~/source/k8s-tooling
fi
```