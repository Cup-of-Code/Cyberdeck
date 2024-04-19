# Building a Cyberdeck - A Quest of Hacking the Matrix

"What's a **cyberdeck?**", you ask.

>"A cyberdeck is a personal mobile computer found in many cyberpunk novels and video games that is used by hackers or 'Deckers' to temporarily connect their mind or 'jack in' to cyberspace. [...] In the real world, cyberdecks are **Artisan Crafted Computers** often powered by single board computers with some sort of display and keyboard made in the cyberpunk aesthetic."
> — [cyberdeck.cafe](https://www.cyberdeck.cafe)

![Cyberdeck1](https://github.com/Cup-of-Code/Cyberdeck/assets/102232378/b01c228d-b235-477c-a837-bdac2ef96703)


## Table of Contents
- [Introduction](#introduction)
- [Inspiration](#inspiration)
- [Design Process](#design-process)
- [Hardware List](#hardware-list)
- [Build Guide](#Build-Guide)
- [Software](#Software)
- [Project Reflections](#project-reflections)
  

## Introduction
I have been working on this project for some time and decided I wanted to document the process while I work on the last steps to finish it.

## Inspiration
IDEA: Inspired by the technology in William Gibson's book *Neuromancer*, a lot of people have been building their own version of a cyberdeck. So I decided to do the same :)

Being inspired by the decks that are showcased on [cyberdeck.cafe](https://www.cyberdeck.cafe) as well as the [r/cyberdeck](https://www.reddit.com/r/cyberdeck) subreddit, I came up with my own version of an *artisan crafted computer*. A dual screen, mechanical keyboard, Raspberry Pi powered "portable" computer. In its finished form, it will probably be functionally similar to a low-end laptop, only a hell of a lot cooler looking! :)

Being inspired by the decks that are showcased on [cyberdeck.cafe](https://www.cyberdeck.cafe) as well as the [r/cyberdeck](https://www.reddit.com/r/cyberdeck) subreddit, I came up with my own version of an *artisan crafted computer*. A dual screen, mechanical keyboard, Raspberry Pi powered "portable" computer. In its finished form, it will probably be functionally similar to a low-end laptop, only a hell of a lot cooler looking! :)

<details>

<summary>Design Process</summary>

## Design Process:
The shell of the deck is designed by me in Fusion360 with the model looking like this:

![shell housing 3](https://github.com/Cup-of-Code/Cyberdeck/assets/102232378/1bec13af-5b7d-4786-8f1b-4792befdce49)
(The honeycomb grid here will later be filled by individual hexagons printed in transparent PLA that will allow the passthrough of RGB backlight)




The process of getting to this version of the housing was quite long. It took many printed iterations and consequent design alterations before landing on the model above. And there is room for improvement. Currently, the spacing between the edge of the screen, where the HDMI-in port sits, is too close to the edge of the housing, which makes it difficult to attach an HDMI cable that fits, therefore angled contacts and flat FFC cables are used instead.
</details>


<details> 
<summary>Hardware List</summary>

  ## Hardware List:
  
The following is an approximate list of materials used in this build:

- 3D printed housing.
- 2x 7" Waveshare LCD displays.
- One mechanical keyboard:
  - DZ60 RGB PCB,
  - Gazzew Boba U4T silent tactile switches,
  - Honey and milk XDA keycap set.
- Raspberry Pi 5 8GB version.
- A small 4 port USB A 3.0 hub.
- Some type of battery power solution (TBD since the Pi5 has higher power requirements than its predecessors).
- (and a whole lot of cables).
</details>
