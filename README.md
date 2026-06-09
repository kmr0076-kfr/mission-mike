# Mission Mike

A tiny pixel-art backyard-BBQ survival game. Mike is a goateed guy hosting a party - grilling burgers, boiling hotdogs, hosting events, and serving guests. The catch: he auto-drinks a beer on a timer, so his drunkenness keeps climbing. Too drunk (100%) = face-plant = game over.

**Personal side project.** Not Whistler/Axiom work. Don't sync to Monday.com or push to any Whistler/Axiom GitHub org.

## How to play

Double-click `index.html` to open it in Chrome. (Single self-contained file - no install, no server, no internet.)

- **Click / tap a station**, then **carry the finished plate to a guest** before their patience ring runs out.
- **SPACE / click** plays the active mini-game (stop the bar in the green, hold-and-release, or mash).
- **E** = eat your own plate to sober up (but you forfeit the serve + combo).
- **M** = mute.
- **CLICK / SPACE** to start, **ENTER** to retry.

## The one mechanic: ride the green band

The drunk meter is a push-your-luck dial you *want* to ride:

| Band | Range | Effect |
|------|-------|--------|
| Sober | 0-39 | Normal speed, 1.0x points |
| **Tipsy (the zone)** | 40-74 | +25% speed, points ramp up to **2.0x** - live here |
| Hammered | 75-99 | Wobbly, screen shakes, multiplier capped |
| Face-plant | 100 | Game over |

Beers (passive + the keg + the "buddy" guest + toasts) constantly push you UP. Coffee, water, and eating your own food pull you back DOWN. Sit as close to 74 as you dare for the biggest score. Chain quick serves for a combo multiplier on top.

High score persists in your browser (`localStorage`).

## Stations & events

Grill, hotdog cart, party table, keg (beer run = points but +drunk), coffee (big sober, cooldown), water (small sober). Random party events fire and escalate: the boys show up, hungry crowd, dog's loose (tap it!), toast, happy hour. The day ramps afternoon -> dusk -> night as it gets harder. Endless until Mike goes down.
