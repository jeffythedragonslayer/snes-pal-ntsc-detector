# PAL vs NTSC detector for the Super Nintendo Entertainment System

This was adapted from SlithyMatt's hello world example; it simply prints whether PAL or NTSC was detected.

If you're looking for the Nintendo Seal of Quality, you're gonna have a bad time.

<!-- ![Screencap from Snes9x Emulator](hello_snes9x.png) -->

To build, you need to install [cc65](https://github.com/cc65/cc65), with the
executables on your path.

Then run **build.sh** from bash, or just run the build directly on the command line:

```
cl65 -C smc.cfg -o pal-ntsc-detector.smc -l pal-ntsc-detector.list pal-ntsc-detector.asm
```

You can then load hello.nes into the SNES/SuperFamiCom emulator of your choice. It has been
tested on Linux and Windows using Snes9x. If you have an issue with any other emulator or
host environment, please post an issue to this repo. Thanks!

<img width="223" alt="ntsc_detected" src="https://user-images.githubusercontent.com/13253146/169671390-a3f477ef-b008-4724-b4a9-cc5cd4048bae.png">
