# My Skeletyl Budget Build
This is a fork of [danterazo's dactyl minidox firmware](https://github.com/danterazo/minidox-qmk) .

This is my first ergonomic keyboard build attempt, and it was a complete success! I'm writing this readme (using the Skeletyl) much time after I already completed the project, but I felt the need as I came by this folder and now know a little more on how to properly behave as a software developer, and as well to better document this feat of mine.

## Why
The reasons that I started this project were not only because [ThePrimeAgen]()'s work heavily influences me as a software developer with his well-founded opinions and that I could not afford [his sponsor's keyboard](), but also the fact that my job, college and hobbies all required typing (all day, every day) and this was starting to bring me some soreness to my wrists, like as if there were rubber bands putting pressure pressure around them.
This was a very big sign and opportunity to dive deep into this rabbit hole that had already taken a peek at a distance before.

## How
I mixed some of [Bastard's Skeletyl STL files](https://github.com/Bastardkb/Skeletyl), the previously mentioned [firmware](https://github.com/danterazo/minidox-qmk) as well as the guiding of the [Dactyl Manuform repository wiring diagrams](https://github.com/abstracthat/dactyl-manuform) to accomplish this.

## Modifications made
I used some Pro Micros with USB-C connectors I had lying around. The Dactyl Minidox firmware was a perfect fit, due to the shared 3x5+3 layout and the decisions of not using the microcontroller boards used on the Skeletyl original project and of using QMK to generate the firmware.

## Issues
Because I was not able to find (and perhaps not willing to pay the price of) places in my country that would produce flexible boards, the wiring was handmade all by myself. This was the toughest part of the project by far, as I had barely any experience with soldering or hardware in general. This lead me to a 3-day long quest with my multimeter to find out why it was outputting some characters but not many others. Turns out I had wired all diodes' cathodes to their neighbors' anodes instead of their cathodes, which caused the signal to get weaker and weaker the further down the key row the pressed key was, allowing just the key on the edge of each side to type. Let's just I got a whole lot better at soldering now.

## How it feels to chew 5 gum
Even though I have been daily driving this keyboard for about a year now, this still feels like an alien device to me. I'm still amazed on how long I can type with it with such little fatigue. I honestly thought that going with the [high heels]() would be a bad idea with such high camber to the keyboard, but I love it and it feels very comfortable even when raising my desk and typing while standing up (great habit I've also got into).

I now have officially become a preacher of the word of the h'ly ortholinear concave split thumb-cluster-ful keyboards. This also comes bundled with the preaching of keyboard-centric software developing setups (tools like i3 window manager, tmux but mainly neovim).

## TO-DO
- [ ] Proofread readme file
- [ ] Add images of the result to the repo and attach to readme

- [ ] Add trackball to keyboard (and figure out the wiring and firmware implementation)
- [ ] Remove unused variables from removed Colemak layer
- [ ] Figure some feature to add to the Colemak/QUERTY vacant keys
- [ ] Add Game layer
