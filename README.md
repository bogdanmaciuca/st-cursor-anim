# st-cursor-anim
Simple Terminal with Neovide-like cursor animations.

![](https://github.com/bogdanmaciuca/st-cursor-anim/blob/external/st-fork-gif.gif?raw=true)

This is a fork of [git://git.suckless.org/st](). It is my attempt at implementing Neovide-like cursor animations in a terminal.

## Dependencies:
- `libx11-dev`
- `libxft-dev`
- install with `sudo apt install libx11-dev libxft-dev` on **Ubuntu** based systems

## Building
```
git clone https://github.com/bogdanmaciuca/st-cursor-anim
cd st-cursor-anim
make           # or: "sudo make clean install" to install on your system
```

## Configuration
`cursormovetime` in `config.h`: time (in ms) of the cursor animation

## Support
For the time being i am pretty invested in this project and am willing to bring it to a usable and stable level. Will probably solve issues in a timely manner if my schedule allows me to do so.

