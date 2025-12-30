# How to download and use ani-cli

## Enable COPR
First, we need to enable COPR to be able to download ani-cli


*Change the command based on your distro*
```bash
sudo dnf copr enable derisis13/ani-cli
```

<br>
<br>
## Downloading the software


*Change the command based on your distro*
```bash
sudo dnf install ani-cli
```


You may also need to install some further packages
```bash
sudo dnf install grep sed curl mpv
```

<br>
<br>

## Using the software
You can launch the software by:

```bash
ani-cli
```

### A few usefull controls are:
Download any anime you'd like

```bash
ani-cli -d
```


Search history
```bash
ani-cli -c
```


Further info
```bash
ani-cli --help
```
