# bakeryos-keyring

Pacman keyring for BakeryOS repositories. It provides the keys needed to verify BakeryOS packages.

## Install

```sh
sudo pacman -S bakeryos-keyring
```

On install, the keys are automatically initialized and populated:

```sh
sudo pacman-key --init
sudo pacman-key --populate bakeryos
```

## License

GPL-3.0-or-later. See `LICENSE`.
