# TMB Super Patch
###### Release 0.1.0
---
## Notes
This is a Helix Floor patch built around the recently released Fender Super Reverb model in 3.80. I tend to depend mostly on my volume and tone knobs for variations in gain and presence, but I've created some snapshots that leave some gain stages out to achieve the same thing that way. There's a wah in there as well as a univibe and chorus effect in case the mood hits, and there are some snapshots that include/exclude those as well. There are a few reverbs and a couple of delays in the mix; the spring reverb and final ambience reverb are intended to remain on all the time as is the short 333ms delay. There's a longer hall reverb and 1/4 note delay available in stomp mode. The bright switch on the amp is also mapped to a stomp mode switch. This patch is given freely but without warranty; use it how you see fit and feel free to share any meaningful changes you make!

## Installation
1. Click on the `TMB Super Patch.hlx` file to install the patch
2. Open the `Favorites` folder, select all and drag into the Favorites panel of Helix Edit (optional)

If you install the favorites, you'll be able to create your own patches with only the components of my patch you're interested in.

## Signal Chain

1. The patch expects a signal on the guitar input; it isn't gated, the pad is off and impedence is "Auto". If you're getting tones of noise, you may want to set the gate to the minimal threshold that cuts off your ground hum. If you're using active pickups, you probably want to turn on the pad.

2. Retro Reel: this is a newer modulation effect that I've found works great to boost the signal and add some texture at the start of the chain. Toggling this on will make everything a bit fuller and louder.

3. Klon: this is set much as how I use the real thing with my Princeton. The tone is cut slightly, very little gain and a healthy level boost into the next stage. As in real life, this tends to stay on 99% of the time for me.

4. King of Tone: this is set much as how I use the real thing with my Princeton. It sounds okay toggled on by itself, but really works best as a tone-shaper and additional boost after the Klon. Tone is boosted a bit as are gain and level, but in overdrive mode with the normal gain structure.

5. Super Reverb: amp settings are personal. That said, this works great with my Tele with Lollar '52s, Taylor with Lollar P-90s, Silver Sky with stock pickups and Gretsch loaded with a set of TV Jones Classic Plus.

6. Spring Reverb: this is set with a moderately low mix and just adds some life to the signal. I tend to leave this on all the time.

7. UniVibe: this is in an odd place, but it just works great as a vibrato and sounds best after the reverb and before the speaker.

8. Cabinet: there's a 4x10 Super Reverb cabinet mic'd with a 47 condenser and a 2x12 Alnico Blue cabinet mic'd with a 121 ribbon. both are panned to the middle, but it sounds good if you pan them hard right/left, too.

9. Stereo Chorus: this is set lush and will give you 'that' 80's sound if you engage it with all the drives turned off. This is the least-used effect for me, but I like to have it on tap.

10. Short Plate Reverb: this is the first of two reverbs that run parallel to the delays. This has a short 2.2sec decay and stays on most of the time for me.

11. Medium Hall Reverb: this is the second of two reverbs that run parallel to the delays. This has a medium 4.4sec decay and I tend to use it for ultra-clean or lead tones.

12. 333ms Tape Delay: this is the first of two delays that run parallel to the reverbs. This is a bit more than a slap delay but kept reasonably low in the mix. I tend to keep this on 99% of the time.

13. 1/4 Tape Delay: this is the second of two delays that run parallel to the reverbs. This locks into the tap-tempo and has more width and volume than the short delay. I tend to use this for ultra-clean, sparse or lead sections as well.

14. Ambience: this just adds a little space around everything; it's barely noticeable. I tend to keep this on.

## Snapshots

1. Clean: Amp, Spring Reverb, 333ms Delay, Ambience
2. Crunch: Retro Reel, Klon, Amp, Spring Reverb, 333ms Delay, Ambience
3. Lead: Retro Reel, Klon, King of Tone, Amp, Spring Reverb, Plate Reverb, Hall Reverb, 333ms Delay, 1/4 Delay, Ambience
4. Clean Vibe: Retro Reel, Amp, Spring Reverb, UniVibe, Plate Reverb, 333ms Delay, Ambience
5. Clean Chorus: Retro Reel, Amp, Spring Reverb, Chorus, Plate Reverb, 333ms Delay, Ambience
6. Dirt Vibe: Retro Reel, Klon, Amp, Spring Reverb, UniVibe, Plate Reverb, 333ms Delay, Ambience
7. Dirt Chorus: Retro Reel, Klon, Amp, Spring Reverb, Chorus, Plate Reverb, 333ms Delay, Ambience
8. Kitchen Sink: all of it. everything.

## Stomp Mappings
FS01 UniVibe
FS02 Chorus
FS03 Plate Reverb
FS04 Hall Reverb
FS05 333ms Delay

FS07 Bright
FS08 Retro Reel
FS09 Klon
FS10 King of Tone
FS11 1/4 Delay

EXP2 Wah
