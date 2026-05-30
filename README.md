# Countdown

___Track events until they happen or since they happened___

Tracking events until they happen, or since they happened, easier.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing

```
flatpak install flathub io.github.lainsce.Countdown
flatpak run io.github.lainsce.Countdown
```

## Building

```
git clone git@github.com:flathub/io.github.lainsce.Countdown.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.lainsce.Countdown.json
```
