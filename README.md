# Stay at Home Thoughts

Thoughts and notes on things I've been working on during the COVID-19 stay at home order in Illinois. 

In general, I extensively journal, especially during the summer which is historically when I'm making the memories I cherish most + learning faster than I can store new stuff in my head. In the past, the more personal stuff has been private, because, well it's personal. The project stuff has been private because it's confidential. Since it looks like I'm gonna have some time to work on projects that aren't bound by NDAs, and the sun is out more so my brain thinks it should be kicking into summertime reflection mode, I'll try updating this now and then.

## March

It seems like I’m going to be home til at least June (betting my remaining winter quarter final is cancelled or made remote) and I think classes will be remote next quarter too. Stanford has already said their quarter will be remote and Northwestern generally doesn’t chart it’s own path. Because of that, I’m going to focus on improving the spaces I spend the most time in, especially before things shut down and I can't order parts. Focus areas are my bedroom, desk, and basement theatre. 

* Bedroom: When I came home from school, I brought most of my stuff with me (because of my above predictions). This included the sound system + projector from the dorm suite, which I’ve now setup in my room. My room is all empty walls and shelves (not a fan of random clutter), so it was easy to project on. When I was younger I always dreamed up having this kind of setup, thanks to COVID-19, I guess it’s finally happening. No more sneaking my Game Boy Advance under my pillow for late night Tetris.

| | |
|:-------------------------:|:-------------------------:|
|<img src="/March/room-home.jpeg?raw=true" width="1000"/>|<img src="/March/room-toy.jpeg?raw=true" width="1000"/>|

* Desk: Now rocking a dual monitor setup since I brought home my dorm monitor and also have my TADA68 keyboard back. Honestly, so far not totally my jam. I just feel like my brain isn’t wired to be able to handle that much disjoint active window space.

* Basement Theatre: My parent’s house has an unfinished basement, and back in the early 2010’s with my savings from tech consulting, I set up a home theatre using a projector and a bed sheet in one of the corners. It hasn't really been upgraded since, except some furniture changes thanks to hand-me-downs. I first started thinking about what an upgrade would look like in my month at home between my gap year at Apple and the start of freshman year at Northwestern. But the jump to 4K + better audio always seemed way too expensive and I just wasn’t planning to be home that much. Now that I will have an extended stay at home, I’ve started seriously investigating what an upgrade would look like. Right now, I’m thinking the P0’s are 1) 4K HDR, 2) Dolby Atmos (sound is significantly more important than picture quality for me), and 3) light control as when others are in the basement, it’s quite hard to see the current screen. Existing theatre below featuring raw concrete, piping, and a bedsheet:

<img src="/March/theatre-old.jpeg?raw=true" width="800"/>

--- 

Northwestern has said they will stop sending emails about new COVID-19 cases on campus, which doesn’t sound like a great sign, glad I went home a couple weeks ago now (homework can be done remotely and still hoping my last on campus final is cancelled). Whipped up a little background script that checks the Northwestern status page + alerts when there is a new case. [NUCOVID19Watcher](https://github.com/atfinke/NUCOVID19Watcher).

---
So I went through with the basement theatre upgrade (now called A.Theatre since the dorm suite edition is no more) to distract me from all the things going and because it looks like I might be here even longer than anticipated. My summer internship plans @ Disney seem like they are not going to work out. LA would have been super fun, but with everything closed down, guess it doesn't make a huge difference anyway. I moved all the old theatre sound equipment and AV setup upstairs for my parents to use.

#### Equipment
* Image: Optoma UHD60, Silver Ticket 16:9 135” screen (no more bedsheet)
* Sound: Klipsch Speakers: R-34-C, R-120SW, RO-280F x 2, R-41SA x 2, R-51M x 2
* Boxes: Denon AVR-X3500H, Apple TV 4K, Xbox One X, TP-Link 8 Port Gigabit Ethernet Switch
* Other: Tons of speaker wire, fish hooks, and 120 x 96” navy blue and black curtains

After spending hours test driving it with Disney+, the 4K HDR and screen are awesome upgrades alone, but the sound pushes it over the top. Oh and the curtains work fantastically with a little curtain door on the side. I can't emphasize enough how much value these curtains add. After watching movies, I still feel disorientated and it takes me a second to remember I’m still in my basement. I love that feeling.

Seeing the markets in turmoil makes me think I converted stocks to theatre supplies at just the right time. Some construction pics (shoutout to dad for permission + help drilling hooks/cables into his ceiling):

| | |
|:-------------------------:|:-------------------------:|
|<img src="/April/theatre-one.jpeg?raw=true" width="1000"/>|<img src="/April/theatre-two.jpeg?raw=true" width="1000"/>|
|<img src="/April/theatre-four.jpeg?raw=true" width="1000"/>|<img src="/April/theatre-three.jpeg?raw=true" width="1000"/>|

---

Yay all the new iPad trackpad features and the Magic Keyboard were announced and ended up looking pretty cool. I quickly updated WikiRaces (2020.3) to support pointer interactions as well as did a curation pass on the final articles list. Some bug fixes.
<br></br>
## April

Theatre still working great. I reassembled the old gaming pc I built that had been stripped for parts for a crypto mine (RIP 2017-2018). Moved it behind the theatre screen and hooked it up to all the equipment, so now have Steam on the big screen. Already used it for a few game nights much to the shock of friends that didn’t realize I was capable of owning a Windows only machine.

I’m now focused on my next game relating to space + physics. I’ve always had this idea in my brain about making a game where you have to use gravity slingshots to your advantage (Notes.app tells me it was first written down in 2017), and well, now I have plenty of time to tinker. Maybe rewatching Interstellar got me subconsciously thinking about it again. Anyway, working on it [here](https://github.com/atfinke/Gravity-Putt).

---

I’ve now made some progress and gotten some awesome feedback (thanks Garrett, Peter, + Maxine)! I’ve dropped the spaceship theme and it’s now going to be golfing in space. The quality isn’t close to what I want it to be, but hopefully it gets better. Also excited to try and have it ship as a universal purchase (macOS, iOS, tvOS), all released on the same day, which will be a first for me.

Boo: It’s April and it’s snowing.

<img src="/April/snow.jpeg?raw=true" width="400"/>

---

I’ve put down the golf game for now. I’m getting a little sick of it and the quality still isn’t what I want it to be. Picking up a word game that I’ve been thinking about that is essentially the card game palace (shoutout Cooper, Dana, Michael) + bananagrams. Repo [here](https://github.com/atfinke/Untitled-Word-Game). Reading up on a lot of old scrabble AI research papers ([like this one](https://dl.acm.org/doi/abs/10.1145/42411.42420)) and really trying to push the performance of the work. Currently, I have it setup so the AI plays itself so I can find pitfalls in the rules. I’m still trying to get a sense if this is actually fun.

---

Picked the golf game up and am determined to at least ship it before moving to the next project (probs the word game), then decide its future based on reception. Trying out Microsoft’s App Center analytics on the macOS + tvOS side of things to see what’s up with their products these days. Investigated lots of unusual frame drops. Working theory is shader complications. 

Now on a fully wack sleep cycle of waking up between 5 and 7pm and going to sleep around 6 or 7am (I try to go to bed before the sunrise). Game nights are now game mornings.

---

Boo: have homework that involves lots of repetitive math.  
Yay: I can just throw it in a jupyter notebook. Given everything is pass/fail, not worried if I lose points for not using grid paper.

---

Shipped the golf game (officially Gravity Putt). Still not feeling great about the quality, and will likely pull it down before the end of the summer if I can’t think of a way to make it better, but learned a lot about graphics, pipelines, shaders, concurrency tricks, and App Center, so definitely worthwhile. 

Working in the theatre has been great. I added a Power/HDMI/Ethernet USB-C hub right next to the main chair for my laptop / iPad Pro which removes the poor WiFi reception problem and gives an easy tap into the theatre equipment. Also started working on my [Spring 2020](https://open.spotify.com/playlist/7nGoorL8apZ7PajkOYnTEs?si=Dks1LZ5WSy2ie8gMwA06eA) playlist and with it some polish on [Playlist Curator](https://github.com/atfinke/PlaylistCurator) and [time](https://github.com/atfinke/time). Occurred to me that I haven't touched the projector in my room in a while because the theatre is so much better. Everything sounds amazing down here.
<br></br>
## May

For a year or two now I’ve really wanted to make a really nice remote/keyboard hardware device for dynamic shortcuts on my computer, based on what app is active. Problem is I would always try doing it over the summer then quickly run out of time / heavily **heavily** prioritize work until I barely mentally/physically cross the finish line, only to start fall quarter three days later. Thanks to COVID, I've got plenty of time now. Unfortunately, one of the main reasons for my desire for this project was to take advantage of the free aluminum, shop tools, and circuit components at Northwestern, but that’s all closed down for now. So I’ll need to create a workshop at home to do this project right.

Last night, I finally got a proof of concept working, an old arcade LED button + bluetooth microprocessor triggering Xcode to build on my laptop. [Video](https://github.com/atfinke/RX/blob/master/experimenting/xcode_run/video.mp4)! I’m using a Circuit Playground Express + [Today at Me](https://github.com/atfinke/Today-at-Me) on my laptop to listen for events. I’m definitely going to do this for real now that I think my full original vision is feasible, without compromises. 

---

Step 1 to completing the remote is becoming a hardware engineer and upgrading my desk/workspace. Got an old picnic table from the garage to extend my desk to use for breadboarding / soldering / etc.

---

Today, I tested my skills by trying to fix a dead iPhone 6S. Unfortunately, the 6S didn’t make it, and lost its motherboard, camera, and home button along the way. However, once I ripped the Taptic Engine out, I was able to hook it up to an Arduino Uno, which was neat. I think this means I am ready to take my remote idea to the next step and get my honorary EE degree. 

Kicking off engineering planning for two parallel tracks for the remote (hence forth [RX](https://github.com/atfinke/RX/)), one with battery + wireless charging (R2) and one with USB power (R1). Both will have the same software stack (+ use bluetooth) to make development easier. The ideal version is the one with battery + charging (thinking just plopping it down on the same charger as my phone), but without having sourced buttons and other factors, it’s hard to predict power usage. Therefore, I will build the wired version first which will let me gather data for the wireless edition.

The main goal is obviously to make it the **best** quality as possible and I’ve figured out that I can send a CAD file to a company that will then mill it out of aluminum and anodize it. Next steps:

- Enclosure: Iterate with play-doh, then iterate with a 3D printer (note: need to acquire printer), then finally, send the cad file to the vendor.
- Software: Feeling pretty confident that I can get things to work given the proof of concept success and easy integration with [Today at Me](https://github.com/atfinke/Today-at-Me). 
- Hardware: Need to find small Arduino + bluetooth microcontrollers, + some sweet, high quality buttons.

Also, wondering if I can add some analytics to Today at Me to track how I use it and my computer in general.

---

Got sidetracked by a random thought about adding a subscription service to WikiRaces. Added custom races (let people choose start/end pages, voting process, + more) and some stats for the service. Removed old compatibility hacks. Added some more future proofing. Also switched from Travis CI to GitHub actions which are way nicer. [Release Notes](https://github.com/atfinke/WikiRaces/releases/tag/2020.05). 

Took almost all the store + subscription code verbatim from [MagicLines](https://apps.apple.com/tt/app/magiclines-wdw/id1486055176) and changed the strings to say WikiRaces+. Kinda crazy timing that after taking years to ship a Disney parks app that I was proud of, met my quality bar, and even throwing out a few completed projects, the parks closed indefinitely a few weeks after release.

---

Starting to acquire most of the essential workshop parts, though lots of things are out of stock or have shipping delays. Completed the initial play-doh model of the remote to get a sense of how big I want it to be in the XY plane. Spent a bunch of time researching 3D printers and settled on the Ender 5. A 3D printer is something I’ve also thought about for a while, but for the same reasons as the theatre upgrade, put off till now. I had unlimited access to what I now know was an industrial resin 3D printer freshman year of high school that I used all the time. But when I researched getting my own (plastic instead of resin), I didn't want to have to deal with the reliability issues that seemed common on consumer versions available then.

It took a few failed prints and some tangled filaments, but the printer is now working great and fascinating to watch.  I did a print of just the top of R1 Proto V0, then completed the first print of 1/2 of [R1 Proto V1](https://github.com/atfinke/RX/tree/master/R1/cad) model! Looks great, but still using old buttons and likely way too big. I think I can trim it down a lot now that I have a better idea of the dimensions of the expected buttons and microcontrollers. Finding high quality, full RGB buttons is surprisingly difficult. I need buttons that have full RGB, not just single color, to achieve many of the ideas I have for the final version, but so far, it seems much harder to source.

| | |
|:-------------------------:|:-------------------------:|
|<img src="/May/remote-play.jpeg?raw=true" width="1000"/>|<img src="/May/remote-R1ProtoV1.jpeg?raw=true" width="1000"/>|

Adjusting the project goals for R1. Given the lack of battery + wireless charging, the space requirements drop dramatically, so instead of building with the same enclosure for each, going with a slimmed down enclosure design.

---

Woke up and decided today was the day to try building a keylogger to "spy" on myself. I love looking at trends/patterns in the analytics data I get back from WikiRaces players, so I thought it would be neat to generate analytics about my own computer usage. Right now I'm tracking clicks, keys, commands, and words. I was also taking periodic screenshots and then creating a composite image, but it never looked that interesting, so it was disabled. Had to dive into some crufty IOKit stuff and play around with permissions, but I now have an initial version working [here](https://github.com/atfinke/logger).

---

Back to RX continuous iteration and testing. Got the old buttons hooked up to an Arduino Uno to experiment with fading and PWM pins (finally, an Arduino project of mine where the LEDS don't just blink). This all might just work. 

<img src="/May/remote-R1ProtoV1-fade.jpeg?raw=true" width="400"/>

Also, I got a little sidetracked and started building little 3D printed accessories to make things around me better, like a remote stand for the new theatre. It’s super satisfying to go from idea -> cad -> printed part in just a few hours (most of which is waiting for the print). Printed 1/2 of the [R1 Proto V2](https://github.com/atfinke/RX/tree/master/R1/cad) cad based on learnings from V1 and project scope adjustments. Came out super well and at a much better overall size. Thinking about ways to both seal up the bottom and secure the microprocessors. 
| | |
|:-------------------------:|:-------------------------:|
|<img src="/May/remote-R1ProtoV2.jpeg?raw=true" width="1000"/>|<img src="/May/remote-R1ProtoV2-base.jpeg?raw=true" width="1000"/>|

---

Found out there is a [Disney Peaceful Piano](https://open.spotify.com/artist/5lmSBamD6zMcpHPqPpwmwN?si=hcKwMfOwQNmV8AB-XBwJ6w) series on Spotify and it's been great. Also rediscovered the great [song](https://open.spotify.com/track/5u5aVJKjSMJr4zesMPz7bL?si=T6Q5JbYRRUmWGemcPKn0WA) that’s in Ocean's 11 when the crew is watching the [Bellagio Fountains](https://www.youtube.com/watch?v=4wTD-jwmz5s).

---

Got the PWM microcontroller for all the LED buttons in the mail, soldered up some headers (yikes I don't enjoy that) and ran some basic tests. Seems to work as expected! Since I still don't have the final RGB LED buttons, and lack any RGB led, I just used red, green, and blue individual leds. Sourced some adafruit metal buttons from a small shop in the UK, but shipping takes forever, ugh.

<img src="/May/remote-pwn.jpeg?raw=true" width="400"/>

Today, some super thoughtful WikiRaces fan mail hit my inbox. It's not easy to find the email for App Store support for my apps, with most of the messages I get generally spam and requests from Mark Gurman for leaks (<- actually true). But today, a student at NYU found it and wrote how she and her friends loved playing it, especially now that folks have a bit more time on their hands (a little different vibe than the [tweets](https://github.com/atfinke/WikiRaces#player-tweets) I got sent). She had some good feature ideas too, so now I’m thinking after this remote project is wrapped up, I might go back and do a few more iterations on the game before it's set in stone come November.

---

Today marks four years since I started my first internship at Apple. Also, four years since I skipped my high school graduation. And it’s now one month before my cancelled college graduation. Guess this means I’ll need to complete grad school if I ever want to be physically handed a diploma. Though I’ll admit, I imagine getting digitally handed my first NDA for iOS 10 back in 2016 felt way better than any diploma would today. Shoutout to my first manager Tim (+ Shant), not to be confused with my second manager, Tim, or my fourth manager’s manager, Tim, or the CEO, Tim.

Another button sample showed up today. Much better finish + build than the last, and a more uniform LED (single color though). Wish it was a bit bigger. Got more vendor responses on alibaba about specific button requests that I might further explore. It’s fascinating how every vendor has almost identical designs and all the companies that sell buttons on Amazon are just repackaging the ones from China. And many of the ones on Aliexpress are sourced from manufacturers on Alibaba. Even the adafruit button schematic was in chinese.

---

Seeking a 30mm high head ring RGB LED illuminated stainless steel momentary push button switch with independent LED and button operation. Seems like I'm getting traction with a few possible vendors in China, but the language barrier seems to be an issue. Lucky, my sleep schedule makes time zone differences a non-issue. Also discovered the Yueqing Button Empire.

---

Today I built most of the [software stack](https://github.com/atfinke/RX/blob/master/R1/) for both ends of the project (macOS + microcontroller). Gave SwiftUI another shot and I have many, ***many***, more thoughts on the framework (and documentation ecosystem) as a result. I moved away from my initial idea of integrating it with [Today at Me](https://github.com/atfinke/Today-at-Me) because permissions + python was turning into a nightmare. Plus, this new approach (config SwiftUI app + always on helper non-gui swift app) enables easier distribution, setup, and code reuse. Obviously this is only after a day’s worth of work, and there is lots of polish to come, but I’m already loving the little config utility app:

<img src="https://github.com/atfinke/RX/blob/master/R1/images/Config%20for%20V5.png?raw=true" width="400"/>

I continued talking with international vendors. Another barrier I’m hitting is minimum order quantities. I discovered that both the CNC milling company and some of the button vendors offer a black anodized finish which could look sweet. However, the button companies won’t make large (>18 mm) high head (kinda like arcade style instead of flat) buttons without at least a 50 quantity commitment. For now, I found a generic [16mm](https://www.aliexpress.com/item/32685616883.html) version with many similar specs to what I’m looking for in black. I bought a few samples so I could see the finish in person. I generally get a few instead of one because with almost anything from China, shipping time is around 3-4 weeks, so I'm willing to pay extra to get a full set of buttons for one RX. That way, if the button sku ends up being good enough that I’m willing to overlook the size/others diffs from the ideal, I don’t have to wait another month for the rest to arrive (or worse, they stop making them). Additionally, sometimes ordering four buttons at once is much cheaper than getting one and then three later due to high shipping costs. By the end of all of this, I’m going to have a lot of extra buttons.

---

Whipped out [R1 Proto V4](https://github.com/atfinke/RX/tree/master/R1/cad) with a lot more focus on the internals. I added a bunch of internal support after running some Inventor stress simulations that indicated things might go poorly if I applied pressure to the top of the structure, definitely something that could happen if I want to add any buttons to this remote. I'm also looking for ways to add more material as the CNC milling shop seems to bill primarily based on the max enclosure size, not material used internally, so I should try and maximize my usage. Right now Inventor claims it's around 0.75 lbs (if made with aluminum). I think a heavier final build will feel much higher quality.

<img src="/May/remote-R1ProtoV3V4.jpeg?raw=true" width="400"/>

---

Another day, another button sample. Good click, poor size, but finally a true RGB LED button to test with (hence building the stack yesterday). Got it all up and running ([video](https://github.com/atfinke/RX/blob/master/R1/videos/R1%20Proto%20V5.mp4)). Awesome to see so many components coming together and working for the first time. That video features an enclosure created with CAD by me, printed with a printer I got shipped from Hong Kong (using filament from Wisconsin). The button was sourced from the United Kingdom. One circuit board came from New York while the other from Pennsylvania. And the top end of the software stack was built by me yesterday (using frameworks + open source from countless others across the world). Using a laptop that just got it's bottom half replaced in Tennessee (yay AppleCare+) and a Mac Pro from Texas. Pretty cool. Adding international supply chain experience to my resume.

Made and printed [R1 Proto V5](https://github.com/atfinke/RX/tree/master/R1/cad) based on a ton of learnings from V4 already + the first RGB LED button. I think internal cable management is going to be more tricky than I anticipated due to the number of wires (likely 6x per button), the way some of the sample buttons have wire connections orientated, and the enclosure generally getting smaller with each iteration. Adding affordances into the structure to aid with this and will continue investigating. V5 features a two level design where level one (an attachment base/bottom cover) would be the boards + power and ground wire. Above, level two would be RGB data cables, running through the cuts in the structure and secured by another printed piece mounted on the extruded circles on the supports.
| | |
|:-------------------------:|:-------------------------:|
|<img src="/May/remote-R1ProtoV4V5.jpeg?raw=true" width="1000"/>|<img src="/May/remote-R1ProtoV5.jpeg?raw=true" width="1000"/>|

---

Still thinking about wire management. Tried out [Fritzing](https://github.com/fritzing/fritzing-app), which I found super addicting. I like making simple (lots of straight lines and right angles) looking circuit boards at the cost of efficiency, which makes things way more difficult. It’s like a complex art puzzle that hits a bunch of my interests. I’m thinking about making a board for R1 to ease some of the wiring, but I’m not committed yet. While the process of making boards is fun, Fritzing has a bunch of sharp pain points that make it difficult to step outside the expected use cases. Upon further investigation, other software in the pcb design space is a combination of too complex for what I’m looking for and too expensive.

---

Yesterday I accidentally pulled another all-nighter, and as I think I mentioned earlier, I don’t enjoy going to sleep after sunrise. That triggered today’s project, setting up removable blackout curtains over my bedroom window’s blinds. 

So far it seems like they will help a ton (only got to test them in the early evening). I got an excuse to use the 3D printer and made some extra parts to cover up holes where light could still get through. Then, I duct taped or otherwise covered any electronic LEDs in the room. I can now pretty much make it pitch black, or fully open, which is totally awesome. 

I’m feeling a little stalled on RX as I wait for the next round of button samples, which is likely a few weeks out. I’ve been trying to think of side projects I can work on (hence curtains), also really any use case for any of the extra buttons I’ll have soon. I just wrapped up some refactoring of R1Kit/Config/Helper that should enable RX’s with a variable number of buttons + more dragging and dropping of colors in the config app. A random idea I had was making a bunch of smaller RX’s for friends, but initially (i.e. last weekend) everything was hardcoded to 4 buttons. 

Another project I’m thinking of spinning up while waiting for new buttons is finally making myself a half decent website (+ maybe combine that with the MagicLines/WikiRaces+ server). I’ve been poking around with Keynote to see if any cool ideas come to mind. For whatever reason, I’m not feeling like returning to the word game, at least not yet.

---

Another day, another press request for Apple leaks.

I spent some time thinking about a new website, but I still haven’t thought of a new design or format I’d like.

I now want to build a gmail digest service so come Thursday (my last day of class), I can delete my university account from all my devices, and just get a weekly email if there are any noteworthy updates.

---

[Digest](https://github.com/atfinke/digest) created and it works great. For [Today at Me](https://github.com/atfinke/Today-at-Me), I always had to manually start it on login because you can’t set a .py script as a login item. Today I had the idea of using AppleScript to launch terminal to run the script, then bundle the script as a .app . Works great as a login item and now Today at Me and the digest server both run on login! I’m super excited it worked out so well.

I also updated the [college](https://github.com/atfinke/college) repo with the new things. I’m a little sad that in 36 hours it’s going to be over. Maybe I should keep updating it through the summer… 

Looking at that list, I’m proud of all the things I was able to accomplish and new things I learned despite going to school and class obligations and whatnot. Without a doubt, I learned infinitely more with those projects than I did in my computer science classes. Yay side projects. I have no clue what the future holds (i.e. when employed) when it comes to these adventures.
