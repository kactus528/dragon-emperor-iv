# Dragon Emperor IV: The Eternal War

Playable demo of Taiyo's fictional 1997 strategy RPG for the Taiyo Vision 32-bit system.

A miniature war-table kingdom drops into stereoscopic battles of 400 vs 400 sprite soldiers on a 144x80 battlefield, drawn as instanced sprite batches. View it in mono, red/cyan, side-by-side or cross-eye stereo on a desktop, or in WebXR on a Meta Quest (open the GitHub Pages link in the Quest Browser and press Enter VR).

## The campaign
The war table is a living map of 18 castles joined by roads. Aldmere (you), the Ashen Legion and Duskmarch all move armies in real time. Click one of your castles, tick up to five generals and pick a destination; your army marches along the roads. Armies that meet on a road clash, and an army that reaches an enemy castle attacks it. Every battle drops into a battlefield that matches the castle's region. Taking a castle grows your territory; capturing a nation's ruler makes it collapse. Every week, generals resting in castles heal and muster fresh troops. Pause with Space or the Pause button, and change the speed up to 4x.

Generals gain experience from kills, wins, duels and captures. Each level raises their HP, attack and defense, increases how many troops they command (110 at level 0 up to 400), and strengthens their spell. Ranks run from Captain to Warlord.

## How a battle works
Each side fields three generals, each leading 400 troops of one type. Spears beat cavalry, cavalry rides down archers, archers shred infantry. You pick a general for each round, the Ashen Legion tries to counter-pick, and survivors carry their losses into the next round. The battle ends when one side runs out of generals.

- **Orders:** Charge (hits harder, takes more), Hold (everyone stops where they stand, fights only what comes close, takes less damage and restores morale), Flank (sweeps around the enemy's sides), Retreat (falls back to the general), Withdraw (pulls your general out with the troops he has left).
- **Battlefields:** pick one on the war table or leave it on Random. Every battle generates a fresh layout, and soldiers path around obstacles with a flow field.
  - *Thornfield Crossing:* a river crossed only at a bridge and fords, a lake, woods, boulders.
  - *Greyfang Highlands:* snow-capped cliff ridges wall off the field; armies funnel through the passes.
  - *Mirewater Fen:* bogs slow everyone, deep pools block the way, reeds and dead trees.
  - *Sunscar Ruins:* dunes cut into lanes by the broken walls of a dead city, with a palm oasis.
  - *Frostmere:* a frozen lake that slows every army, broken through in places.
  - *Eldwood:* deep woods across most of the field and a stream with fords.
  - *Ashen Wastes:* a lava river crossed by two stone bridges, lava pools, embers.
  Woods slow troops (cavalry most) and halve arrow damage to anyone inside.
- **Morale:** kills and spells raise it, losses lower it. An army below 20% starts to rout.
- **Generals** fight on the field, take damage, and each has a spell: Starfall, Arrow Storm, Thunder Lance, Ash Rain, Dragon's Breath.
- **Capture:** a general who falls in a duel or to a spell is taken prisoner. When an army breaks, its general flees for the map edge and your troops chase him (cavalry is best at this); catch him before he escapes and he's yours. Between rounds you can try to persuade prisoners to join you with fresh troops, and the enemy will try the same with yours. Capturing Vorgrath ends the battle.
- **Duels:** challenge the enemy general, or answer his challenge. Refusing costs morale. The armies form a ring and each exchange is Strike / Guard / Power: Strike beats Power, Guard beats Strike, Power breaks Guard. A golden glow means he is winding up a Power blow.

## Sound
Everything is synthesized live in the browser: formant-filtered voices for battle cries and crowd cheers, war drums with rotating rhythms (faster when an army is charging), a din of steel that swells with the fighting, and a valley reverb over it all.

## Controls
- **Desktop:** drag to orbit, right-drag or WASD to pan, Q/E to turn, scroll or pinch to zoom (far enough to see the whole table). 1-4 orders, 5 duel, 6 withdraw, Space aims your spell (click the field to fire, Esc cancels). In duels J/K/L = Strike/Guard/Power. Y/N answer a challenge. Number keys pick a general.
- **Quest:** grip to grab the table, both grips to scale and turn it. Left stick slides the battlefield, right stick turns and zooms, B resets. Point the right controller to aim your spell and pull the right trigger to fire (otherwise it orders a charge). Left trigger cycles orders, A challenges to a duel, X twice withdraws. In duels: right trigger Strike, left trigger Guard, A/X Power. When choosing a general: left trigger next, right trigger deploy.

Dragon Emperor I not required.
