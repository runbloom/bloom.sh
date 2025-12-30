# What is ani-cli
ani-cli is a lightweight anime watching tool.


It gets rid of ads, trackers and constant buffering.


You could download any anime and view your watch history.

<br>
<br>

# How to download and use ani-cli

## Trust signed develpers
We will be downloading the software using the 'scoop' package we need to do a few things before


Open your PowerShell
```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```
Then run

<br>

Then close the PowerShell and relaunch it


This time do
```bash
irm get.scoop.sh | iex
```
Then run

<br>
<br>

## Downloading the software

Again, close PowerShell and relaunch it
```bash
scoop install git; scoop bucket add extras; scoop install mpv fzf ani-cli
```
Then run

<br>

You may also need to install some further packages
```bash
scoop install ffmpeg
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
````
