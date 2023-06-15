# refreshd
A simple tool to switch refresh rates

## installation
```sh
cp refreshd ~/.local/bin/refreshd
```
or
```sh
sudo cp refreshd /usr/local/bin
```

## usage
refreshd store your refresh rate status in `~/.cache/refreshd`

- restore last refresh rate:

	`refreshd reset`

- toggle refresh rate:

	`refreshd toggle`

- switch to high refresh rate:

	`refreshd high`

- switch to low refresh rate:

	`refreshd low`
