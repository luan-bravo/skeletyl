Manuform repository wiring diagrams](https://github.com/abstracthat/dactyl-manuform) to accomplish this.

## Modifications made
I used some Pro Micros with USB-C connectors I had lying around. The Dactyl Minidox firmware was a perfect fit, due to the shared 3x5+3 layout and the decisions of not using the microcontroller boards used on the Skeletyl original project and of using QMK to generate the firmware.

## Issues
Because I was not able to find (and perhaps not willing to pay the price of) places in my country that would produce flexible boards, the wiring was handmade all by myself. This was the toughest part of the project by far, as I had barely any experience with soldering or hardware in general. This lead me to a 3-day long quest with my multimeter to find out why it was outputting some characters but not many others. Turns out I had wired all diodes' cathodes to their neighbor anodes instead of their cathodes. This caused the signal to get weaker and weaker the further down the key row the pressed key was, allowing just the key on the edge of each side to type. Let's just I got a whole lot better at soldering now.

## How it feels to chew 5 gum
Even though I have been daily driving this keyboard for about a year now, this still feels like an alien device to me. I'm still amazed on how long I can type with it with such little fatigue. I honestly thought that going with the [high heels]() would be a bad idea; adding such a high camber to the keyboard. However, I ended up loving it and it feels very comfortable even when raising my desk and typing while standing up (great habit I've also gotten into).

I now have officially become a preacher of the word of the holy ortholinear concave split thumb-cluster-ful keyboards. This also comes bundled with the preaching of keyboard-centric software developing setups (tools like ih3 window manager, tmux but mainly neovim).

## TO-DO
- [ ] Proofread readme file
- [ ] Add images of the result to the repo and attach to readme

- [ ] Add trackball to keyboard (and figure out the wiring and firmware implementation)
- [ ] Remove unused variables from removed Colemak layer
- [ ] Figure some feature to add to the Colemak/QUERTY vacant keys
- [ ] Add Game layer
