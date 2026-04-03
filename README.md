<img width="2674" height="583" alt="logo" src="https://github.com/user-attachments/assets/def9089e-0a4e-4af1-b6b9-e450a5e2a701" />

<br><br><br>

I’ve been exploring old game libraries with my youngest daughter, and together we have been working on a collection of presets to recreate an appropriate visual context for these games. The whole thing kind of grew beyond the original scope and turned into a hobby project, and I’ve decided to make the files available in case somebody is looking for something similar.

<br>

### Brief

Vriom 20th Century Cathode is a collection of pseudo-skeuomorphic Mega Bezel presets for pre-millennial consoles. They aim to simulate the feel of playing games on era appropriate 13-19 inch CRTs and provide more immersive retro gaming experiences.

<br>

### Philosophy

In a sense, the goal is similar to that of Soqueroeu’s presets, but messier. The Soqueroeu set is a wonderful, disciplined and consistent collection of retro screens, and this is not that. This is more about playing games on the small spare TV in the basement, away from the living room where parents are tired of hearing bleeps and bloops. You didn’t play on the TV you wanted, you played on the TV you had. Sometimes the colors bled, sometimes the screen was curved as all heck, sometimes it emitted a high pitch whine. Sometimes it attracted so much dust you started to worry.

The procedure: I scour the internet for CRTs from the appropriate time frame that share design sensibilities with the console in question. I then Frankenstein together a base for each preset and add colors, shapes and elements from the relevant consoles to reinforce the connection to the game platform. Photographic elements are used when possible, with vector based augmentations where needed. I then create a preset where the composite TV I’ve put together dictates the shape and curvature of the screen. Finally, I dial in the CRT settings to conform to my own memories of what these games should look like.

The goal is not to accurately reproduce every subpixel in a way that’s only possible on UHD HDR TVs. The goal is also not to present each system using the exact same parameters or form factors. This is a feelings-first approach with a few random variables affecting the experience, like in real life. Still, all scaling is integer based and I do try to get the math right whenever math is needed

Post-millennial systems are outside the project’s scope. CRTs survived well into the 2000s, but gen 6 generally didn’t have to work within the CRT limitations the way older, more sprite based systems did. If I do decide to include the 1998 Sega Dreamcast despite it being a gen 6 console, it’ll be included with presets for other CD-based systems.

<br>

### Future Plans/Improvements

We were a Nintendo home, but I have distinct memories of playing Atari, Sega or Commodore games at other people’s houses, again often on secondary TV sets. The idea is to expand the collection to include more system families. I’ll update the list as I go. Input from people who grew up with non-Nintendo sets is very welcome.

I’m also grateful for feedback on the scripts. I’m not a coder or scripter beyond markup/CSS, so I’m just yanking wires until I understand what’s going on. I’m sure the slangps are atrocious, so feel free to let me know how I’ve screwed up. I understand the idea of a cascading pipeline, but what I’m doing is not optimalized in any way.

#### Current shortlist for fixes and additions:

* Include more system families
* Test or simulate tests for 4K and ultrawide displays
* Clean up and future proof slangp pipelines
* Test presets on various cores

<br>

### Current Presets

Generally, all presets contain two backgrounds – one barebones and one more elaborate – and dark versions of each of these. There are exceptions.

#### Nintendo

* Famicom (2 backgrounds + dark modes)
* Nintendo Entertainment System (2 backgrounds + dark modes)
* Super Famicom/Super Nintendo Entertainment System EU (2 backgrounds + dark modes)
* Super Nintendo Entertainment System US (2 backgrounds + dark modes)
* Nintendo 64 (Variants based on the Funtastic series: Fire Orange, Grape Purple, Ice Blue, Jungle Green, Smoke Black, Watermelon Red)

All presets are also available as +1 integer upscales.

<br>

### Screenshots/Technical Rundown

#### Nintendo NES/Famicom

The NES presets are based on Philips 14CT2006 from the mid-1980s and general Mitsubishi mono sets from the same period. The Famicom is a lightly modified Paxon DM-405 color monitor.

<img width="2560" height="1440" alt="Batman - The Video Game (USA)-260403-150839" src="https://github.com/user-attachments/assets/eb531acd-638f-4053-bf14-b3e075d49778" />

<img width="2560" height="1440" alt="Shadowgate (USA)-260403-150314" src="https://github.com/user-attachments/assets/702a28ad-344e-4c4b-b0e2-c27e6cf674cd" />

<img width="2560" height="1440" alt="Super Mario Bros  2 (USA)-260403-145705" src="https://github.com/user-attachments/assets/66febe73-3db7-4bab-8a5e-79945a913f9c" />

<img width="2560" height="1440" alt="Super C (USA)-260403-145938" src="https://github.com/user-attachments/assets/56155afc-71ba-46a2-94b6-f3ea660c29f1" />

#### Nintendo SNES/SFC

The US SNES is based on the Toshiba CF13E23. It’s hard to find TVs that reflect the overall shape of the SNES, so I went a bit more literal with the button designs to compensate. The Super Famicom is generally inspired by Grundig CRTs from the first half of the 1990s.

<img width="2560" height="1440" alt="Super Castlevania IV (USA)-260403-142358" src="https://github.com/user-attachments/assets/2633eeaf-7828-492a-b266-5e1b31ee7fd4" />

<img width="2560" height="1440" alt="Donkey Kong Country 2 - Diddy&#39;s Kong Quest (USA) (En,Fr) (Rev 1)-260403-144424" src="https://github.com/user-attachments/assets/cc542d7a-15f2-461f-83d7-3ed41476daa4" />

<img width="2560" height="1440" alt="Super Mario World (USA)-260403-144235" src="https://github.com/user-attachments/assets/48f7c1dc-ce1d-4497-b08d-09a74d69c7ee" />

<img width="2560" height="1440" alt="Rockman   Forte (Japan)-260403-143536" src="https://github.com/user-attachments/assets/cf4b1279-27e4-4c63-b304-6130540280cf" />

#### Nintendo 64

A heavily modified LG Netee from 1999. The presets are based on the translucent Funtastic consoles, and the fullscreen glow has been configured to light up the plastic as you play.

<img width="2560" height="1440" alt="Diddy Kong Racing (U) (M2) (V1 1)  ! -260403-151309" src="https://github.com/user-attachments/assets/d310cb39-3f78-406a-9153-f6ae47079cbc" />

The color is applied by the decal layer, which contains a PNG with a 0° hue value (pure red). If you want to use a value not available in the presets, you can offset this value to pick any hue you’d like.

<img width="12165" height="5214" alt="nintendo_n64_decal" src="https://github.com/user-attachments/assets/4cd4d8d9-0bf5-4eaa-ba12-2a2c3115e9d3" />

N64 games are notoriously inconsistent when it comes to scaling. The preset snaps to integer scales, so scaling up the video by a few percentages forces the preset graphics to contract. If you pick the color you want, adjust the video scale and save a game level preset, you’ll be set.

<img width="2559" height="1437" alt="image" src="https://github.com/user-attachments/assets/65f257bd-7931-451f-b513-e5b6493f093c" />

<br>

### Installation

Place the main folder in the regular Mega Bezel directory (shaders/Mega\_Bezel\_Packs). 

<br>

### Changelog

**v 1.1.3** 2026.04.03

* Reworked slangp pipeline — full replacement needed after download
* Further graphical improvements
* Further reflection improvements

**v 1.1.2** 2026.03.21

* All graphics cleaned up and redone for 8K
* Improved reflections

**v 1.1.1** 2026.03.20

* Initial upload
