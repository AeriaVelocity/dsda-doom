# DSDA-Doom (AeriaVelocity fork)

> [!NOTE]
> This README specifically pertains to this fork of DSDA-Doom. For the original
> project, see
> [https://github.com/kraflab/dsda-doom](https://github.com/kraflab/dsda-doom).
> The original README is available at [README-ORIG.md](README-ORIG.md).

## Why a fork?

I decided to fork DSDA-Doom for symbolic reasons, because it's my new favourite
source port of DOOM (as of 2024-08-17). I'm probably not going to make any
changes or improvements - this is just so I can have my own fork of the source
port I like.

## Building

These build instructions are for Fedora. YMMV for other Linuxes (Linuces?) or
other operating systems or devices.

### Dependencies

```sh
sudo dnf install cmake gcc gcc-c++ clang pkg-config mesa-libGL-devel libzip-devel SDL2-devel SDL2_mixer-devel zlib-devel SDL2_image-devel libmad-devel fluidsynth-devel dumb-devel libvorbis-devel portmidi-devel freeglut-devel
```

### Cloning

```sh
git clone https://github.com/AeriaVelocity/dsda-doom.git
```

### Building & Installing

```sh
cd dsda-doom
cmake prboom2
make
sudo make install
```

## Licence

DSDA-Doom is licensed under GPLv2+ (GNU General Public License 2.0 or later),
as was PrBoom+, Boom and the original DOOM before it.
