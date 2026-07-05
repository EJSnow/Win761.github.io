---
layout: page.html
title: The Razor Crest
date: 2026-06-29
lastUpdated: July 6, 2026
tags: blog
---

Behold, the Razor Crest! (I've been rewatching *The Mandalorian* lately, hence the name.) I assembled this pc as an upgrade from the Redstone PC with the goal of sticking to the i7-4790 for as long as possible. I was mainly in need of a GPU upgrade anyways.<!-- excerpt -->

![The Razor Crest, June 29 2026](/images/razor-crest.jpg)

I've upgraded from the old RX 6400 to an RX 6600 and migrated to the Montech Air 100 ARGB case (optiplexen don't fit RX 6600's and the 255w psu wasn't gonna work either oh and thermals really sucked in the optiplex case). I also got a new monitor as the old Dell P2210 was kind of terrible and was possibly dying too (and may end up going to another pc otherwise I might have kept it as a secondary display).

Overall the build went pretty smoothly, though I did get a broken motherboard from eBay initially. It had significant CPU socket damage so obviously it wouldn't work.

![The CPU socket damage on the first motherboard](/images/razor-crest-motherboard-damage.jpg)

But I was able to return it and buy a second motherboard, which at least wasn't obviously broken. However I ran into issues with it not suspending (it would completely power off then reboot instead) or staying shut down but ultimately a CMOS reset (I also had to replace the CMOS battery) seems to have solved that problem (although I'm not 100% sure it wasn't because my sister gave the computer a funny look). Now that that problem's solved, the system pretty much works Flawlessly™. As expected, game performance is significantly improved over the Redstone PC except in Geometry Dash which is highly cpu-bound anyways. Not to mention the PC runs so much cooler AND quieter (granted my bar is pretty low coming from an *Optiplex*).

Considering the circumstances we're in right now, I'd say I did alright. This system should hopefully last for several years before needing major upgrades, though the CPU is definitely getting to the point where an upgrade might be desired. However, moving to a case with proper thermals and getting a reasonably good CPU cooler seems to have actually helped my CPU performance a little bit.

Also yes, the RX 6600 and i7-4790 are an awful pairing. But we do what we have to do to avoid buying DDR4 or *shiver* DDR5 RAM at the current prices. I'm not upgrading to a skylake cpu both because it's not hugely faster (who would have guessed?) and because aside from oem pcs (like optiplexen) DDR3 skylake boards seem to be unobtainium.

If anyone's curious, I have a Redragon K621 Horus TKL keyboard (with red switches) and the same old mouse from the redstone computer.

As previously, I did undervolt the GPU, and I also decided to try undervolting the CPU. However, I didn't get much improvement without any underclocking:

* CPU core/cache: -75mv offset
* GPU core: -65mv offset

Which is the furthest I could push them without getting crashes, according to my stress testing (prime95/ffmpeg on the cpu and Minecraft with Photon shaders on the gpu). I bet if I underclock them I could push the voltage down even further (and I may try that), but I really was expecting better from this hardware.


## Parts

#### CPU - Intel Core i7-4790 (5/5)

I love this CPU, it hits the nostalgia points perfectly and is still fast enough for low-end gaming in 2026 at least on Linux. Stolen from the Redstone PC

#### CPU cooler - Thermalright Assassin X 120 Refined SE ARGB (5/5) - $18.90

No comments. It keeps my cpu nice and cool.

#### Motherboard - Asus H97M-E (4/5) - $98.67

Bit rough around the edges (the BIOS is mildly confusing and outdated-feeling) but eh. It works. I had some minor problems that I think were caused by Windows fast startup (before I bought the board), but otherwise it kind of is just a mATX motherboard. It has an M.2 slot interestingly (though only 4 sata ports). note this price also includes an aftermarket io shield since the board didn't come with one (eBay is fun like that).

#### RAM - 16GB (2x8GB) Crucial DDR3-1600 (5/5)

dedotated wam

I stole this from the redstone pc so I wouldn't have to buy any ram in this market

#### Drives - Crucial MX500 500GB 2.5" SSD (4/5) + Western Digital Blue 1TB 2.5" 5400RPM HDD (2/5)

Also stolen from the redstone pc. The SSD is alright but not that fast because of SATA. The HDD is kinda slow but it's okay for mass data storage.

#### GPU - MSI Mech 2X Radeon RX 6600 (5/5) - $197.40

Much faster than my previous RX 6400 obviously. Reasonably efficient, and overall a great little card. Purchased used on eBay, and I haven't had any problems with it, it was in great shape, and I don't think it needs to be repasted even (still has pretty good temps).

#### Case - Montech Air 100 ARGB (5/5) - $69.90

Epic mATX case. Buuut I honestly think it's too big for me. Mostly too tall. So in the future I will either go with a compact mATX case like the Lian Li A3 or even an ITX case but I'd definitely prefer mATX. Other than that I do like this case. For $70, you get a good quality case that's also pretty easy to build in, 4 included ARGB fans (with a 6-port ARGB hub), and pretty solid cable management options. But the PCIe slots are the rip-off kind which I do not like. The included RGB controller's built-in effects are pretty basic but I put it on a static color anyways (my motherboard doesn't have an ARGB header sadly).

#### PSU - MSI MAG A550BN (5/5) - $52.12

it supplies power and doesn't look like a fire hazard and it was on the more affordable side

#### Wi-Fi adapter - TP-Link TX55E (5/5)

Stolen from the redstone pc. Sometimes doesn't quite wake up properly from suspend on this system although it worked fine on the redstone pc. Otherwise it's a great little card, no major complaints.

#### Monitor - Dell SE2426HG (5/5) - $99.99

Insane value (24" 1080p **240Hz** monitor for $100). I do wish the stand was better though.

## Little side thing

Of course, by the time I realized the first motherboard was broken, I had already taken apart the Redstone PC and removed the components I planned to reuse (the CPU, RAM, storage, and Wi-Fi card), and rather than putting it back together again (and having to repaste the cpu only to repaste it again a couple days later), I decided to create a temporary hybrid setup with Twilight and my new monitor. I set up Twilight with it on the desk where my PC was along with my keyboard, mouse, and Bluetooth speaker (partly to work around the fact that with the monitor plugged in Twilight reroutes audio to HDMI despite the monitor not having speakers). That setup actually worked pretty solidly. I got a free second screen (Twilight's builtin screen) and if I want I can unplug Twilight and take it anywhere I want fairly easily. Now that I've put my PC together I rather miss the second screen, but there are ways to still have one. ;)

![The temporary setup with Twilight and my new monitor](/images/twilight-temporary-setup.jpg)

## Pictures

*Note: Click an image to enlarge it.*

<div class="masonry-grid gallery">
  <div class="masonry-item">

![The parts lineup (with the first, non-working motherboard)](/images/razor-crest-7.jpg)

  </div>
  <div class="masonry-item">

![The assembled computer](/images/razor-crest-1.jpg)

  </div>
  <div class="masonry-item">

![Inside the assembled PC](/images/razor-crest-2.jpg)

  </div>
  <div class="masonry-item">

![Close-up of the GPU](/images/razor-crest-3.jpg)

  </div>
  <div class="masonry-item">

![](/images/razor-crest-4.jpg)

  </div>
  <div class="masonry-item">

![](/images/razor-crest-5.jpg)

  </div>
  <div class="masonry-item">

![First test boot](/images/razor-crest-6.jpg)

  </div>
  <div class="masonry-item">

![The front/top IO](/images/razor-crest-8.jpg)

  </div>
</div>

(On a little side note, I recently discovered how awesome 3:2 images are so naturally most of these images are cropped to 3:2.)
