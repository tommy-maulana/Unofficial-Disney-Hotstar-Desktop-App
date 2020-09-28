# [Unofficial] Disney+ Hotstar Indonesia Desktop App

![](screenshot.png)

## Installation

Download our latest release and you're off to the races!

| Windows | macOS | GNU/Linux (64-bit only) |
| -- | -- | -- |
| [Download](#) | [Download](#) | [Download](#) |



## Development Guide

### Setup

First, clone the project:

```bash
git clone https://github.com/tommy-maulana/Unofficial-Disney-Hotstar-Desktop-App.git

cd Unofficial-Disney-Hotstar-Desktop-App
```

Install dependencies for both the CLI and the Electron app:

```bash
# Under Linux and macOS:
npm run dev-up

# Under Windows:
npm run dev-up-win
```

Then, install Nativefier globally with ```npm install -g nativefier```

and then run this project:

```bash
nativefier --name 'Disney+ Hotstar Indonesia' 'hotstar.com/id'
```

## License

[MIT](LICENSE.md)
