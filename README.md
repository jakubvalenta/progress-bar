# Progress bar

A simple command line program to draw a unicode progress bar.

## Installation

Requires Python 3. No other installation is required.

## Usage

Draw a bar showing a 30% progress:

```shell
./progress-bar 30
██████████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 30.00%
```

Draw a bar showing a 20.34% progress:

```shell
./progress-bar 20.34
████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 20.34%
```

Draw a bar showing a progress equal to the ratio between 7 and 13:

```shell
./progress-bar 7 13
██████████████████████████████████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 53.85%
```

Draw bars with custom width:

```shell
./progress-bar 20.34 --width 50
██████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 20.34%

./progress-bar 7 13 --width 50
███████████████████████████░░░░░░░░░░░░░░░░░░░░░░░ 53.85%
```

## Help

```shell
./progress-bar -h
```

## Contributing

__Feel free to remix this project__ under the terms of the [Apache License,
Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
