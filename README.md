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

## configuration

edit refreshd

- HI_CMD:

the command used to switch to high refresh rate

- LOW_CMD

the command used to switch to low refresh rate

- DEFAULT

default refresh rate state, can be `HI` or `LOW`

## usage

refreshd store your refresh rate state in `~/.cache/refreshd`

- restore last refresh rate:

 `refreshd restore`

- restore default refresh rate:

 `refreshd reset`

- toggle refresh rate:

 `refreshd toggle`

- switch to high refresh rate:

 `refreshd high`

- switch to low refresh rate:

 `refreshd low`
