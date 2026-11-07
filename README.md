# Pocket Grid

An original bird’s-eye miniature arcade racing game built with HTML Canvas and vanilla JavaScript. No dependencies or external assets.

## Play

1. Download this repository using **Code → Download ZIP** and extract it.
2. Open `index.html` in a modern browser.
3. Choose a circuit and an owned car, then click **Start Race**.

Alternatively, run `python3 -m http.server 8000` from the extracted folder and visit http://localhost:8000.

## Features

- 10 distinct circuits and 10 purchasable cars with different speed, acceleration, handling and energy.
- Four AI rivals and three-lap races, with ordered checkpoints.
- Coins for every finish: 180 for a win, then 110, 80, 55 or 35.
- Five levels each of engine, tires and body upgrades, stored per car.
- Consumable turbo, fire gun, shield, oil slick and repair powers.
- Browser-local progress saving and touch driving buttons.

## Controls

| Action | Key |
| --- | --- |
| Accelerate / brake | W / S or up / down |
| Steer | A / D or left / right |
| Turbo | Space |
| Fire gun | F |
| Shield | Q |
| Oil slick | E |
| Repair | X |
| Pause | P |
| Recover to road | R |

Start with 350 coins, the Cricket, and some powers. Purchase cars, upgrades and supplies between races. Powers are consumed when used. Browser storage can be unavailable in private browsing or for local files; serving over localhost provides a consistent origin.

## Verification

JavaScript syntax checked. All 40 AI circuit/opponent combinations completed three laps in simulation. Car purchasing, engine upgrading, all five power consumptions, repair and victory payout checked. Browser rendering and race countdown checked. A complete manual driving playthrough has not been verified.

## Source

All game logic, styling, track definitions and original vector artwork are in `index.html`. No build step is required.
