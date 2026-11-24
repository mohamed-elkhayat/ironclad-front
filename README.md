# Ironclad Front

A real-time strategy game in the classic base-building style, in a single HTML file with no build step and no assets.

**Play online:** https://mohamed-elkhayat.github.io/ironclad-front/ (once GitHub Pages is on)

Or download `index.html` and open it in a browser to play solo offline.

## Gameplay
- Build **Power Plants** to keep the grid up. Low power halves production speed, slows turrets and takes the radar offline.
- An **Ore Refinery** comes with a Harvester. Harvesters gather ore automatically and turn it into credits.
- **Barracks** train Riflemen (good against infantry) and Rocketeers (good against armor).
- The **War Factory** builds Light Tanks, Heavy Tanks, Howitzers (long range, splash damage, needs a Radar Dome) and extra Harvesters.
- The **Radar Dome** turns on the minimap. **Gun Turrets** defend the base.
- You win when every enemy structure and combat unit is destroyed.

## Two players
1. Open the game at https://mohamed-elkhayat.github.io/ironclad-front/ and tap **Host a match**.
2. Send your friend the invite link (Share or Copy). It looks like `…/ironclad-front/#join-ABCD`.
3. Your friend opens it and taps **Join match ABCD**, or types the code under **Two players**.

No accounts are needed. The two browsers connect directly (WebRTC); the free PeerJS service only introduces them. The host's browser runs the battle, so the host should keep the game open and in front. If the friend leaves, the AI takes over their side.

Some mobile networks block direct connections. If joining times out, try Wi-Fi on one or both phones.

When the game runs as a claude.ai artifact, it uses claude.ai's live room instead.

## Phones and tablets
Tap a unit to select it, then tap the ground to move or an enemy to attack. Drag scrolls the map, and pinching zooms. The on-map buttons cover the rest: **Select** (the next drag box-selects), **Army**, **Attack** (attack-move), **Stop** and **Clear**. To place a building, tap where it goes, then tap the outline again to confirm.

## Controls
| Input | Action |
|---|---|
| Drag | Box-select units |
| Click | Select, move to ground, or attack an enemy |
| Double-click | Select all units of that type on screen |
| Right-click / Esc | Deselect or cancel |
| A, then click | Attack-move |
| S / Q | Stop / select whole army |
| Ctrl+1–9, 1–9 | Assign / recall control groups |
| Arrows, screen edges, wheel | Scroll the map (touch: drag) |
| Ctrl+wheel, +/−, pinch | Zoom |
| H / P | Jump to base / pause |

Right-click a build button to cancel it. Select a Barracks or War Factory and click the ground to set a rally point.

The enemy AI builds its own economy and base, defends itself and sends attack waves that grow over time. There are three difficulty levels.
