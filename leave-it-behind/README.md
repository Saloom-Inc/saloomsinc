# Leave It Behind 🌕

**A 2D Moon mission game about the hardware NASA left behind.**
Built for the NASA International Space Apps Challenge 2026: *Abandoned but not Forgotten: Storytelling about NASA's Discarded Equipment on the Moon and Mars.*

▶️ **Play:** https://saloom-inc.github.io/saloomsinc/leave-it-behind/

## The idea
Every object on the Moon is there because someone made a choice. The Apollo ascent stage could only lift so much, so crews threw out backpacks, boots, cameras and tools to carry rocks and film home, and left science instruments running on the surface.

In this game, you make those choices yourself.

## How to play
- **Move:** `A` `D` / arrow keys · **Jump:** `W` / `↑` / `Space` (low gravity!)
- **Pick up / drop / use:** `E`
- **At the lander:** `E` loads what you carry · `1`–`9` throw cabin items out · `L` lifts off
- Phones and tablets: on-screen buttons (landscape works best)

Collect samples, set up experiments at their marked sites, throw out dead weight, and lift off before your oxygen runs out. Too heavy and the ascent stage won't leave the ground.

## Missions
| # | Mission | Story |
|---|---|---|
| 1 | Apollo 11 · Tranquility Base | First science on the Moon: retroreflector + seismometer |
| 2 | Apollo 12 · Ocean of Storms | Walk to Surveyor 3 and bring its camera home |
| 3 | Apollo 17 · Taurus–Littrow | Orange soil, Tracy's Rock, the last moonwalk |

## Tech
Plain HTML5 canvas and JavaScript. No build step, no dependencies. Open `index.html` or serve the folder.

```
index.html      screens + HUD
css/style.css   UI styling
js/data.js      missions, items, facts
js/game.js      engine: terrain, physics, rendering, input, audio
```

## Sources
- NASA History Office: *Catalogue of Manmade Material on the Moon*
- NASA Space Science Data Coordinated Archive (NSSDCA)
- LROC & HiRISE imagery of landing sites

Weights are simplified game units. All art is original vector drawing; no NASA logos are used. Not affiliated with or endorsed by NASA.
