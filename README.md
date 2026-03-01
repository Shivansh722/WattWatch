<p align="center">
<img src="https://github.com/user-attachments/assets/ed040304-5689-4323-b9c0-c9355b9c4365" width="200"/>
</p>

# WattWatch

<p align="center">
<img src="https://github.com/user-attachments/assets/1d444659-dbe0-48d1-9368-a79d10ccf8c5"/>
</p>

Display macOS power usage (wattage) in the menu bar

## Installation

WattWatch can be installed with Homebrew:

```
brew tap beutton/brew
brew install wattsec
```

## Compile

```bash
git clone https://github.com/beutton/wattsec.git
cd wattsec
./build.sh
open dist/WattSec.app
```

## Settings

<p align="center">
<img width="493" height="417" alt="image" src="https://github.com/user-attachments/assets/117ac43e-977a-4d7c-949f-18719ac2f4a8" />

</p>

- **Detail** - The number of watt decimal places to show (0, 1, or 2)
- **Pace** - The refresh interval (1s, 3s, or 5s)
- **Width** - The width of the metric in the menu bar (Dynamic or Fixed)
- **Launch** - Toggle Launch at Login
- **High Power Alerts** - Tells you when your energy consumption peaks
- **Session tracking** - Get insights

## Credit

- [Stats](https://github.com/exelban/stats) for SMC polling
