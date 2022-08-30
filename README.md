# Putty-like ST which is looking like Konsole 

A fork of [ST](https://st.suckless.org/) with few cosmetical changes:
- colors are taken from KDE Konsole dark theme
- right mouse button click paste the clipboard content like Putty
- selection with mouse goes both to global clipboard


# Screenshots

![screenshot](kha84/st/blob/main/screenshot.png)

# Installation 

```
sudo apt install fonts-font-awesome libxft-dev
git clone https://github.com/kha84/st.git
cd st
sudo make clean install
/usr/local/bin/st
```
