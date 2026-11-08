# Dragon Emperor IV: The Eternal War

Playable demo of Taiyo's fictional 1997 strategy RPG for the Taiyo Vision 32-bit system.

A miniature war-table kingdom drops into stereoscopic battles of 400 vs 400 sprite soldiers on a 144x80 battlefield, drawn as instanced sprite batches. View it in mono, red/cyan, side-by-side or cross-eye stereo on a desktop, or in WebXR on a Meta Quest (open the GitHub Pages link in the Quest Browser and press Enter VR).

## Difficulty
Pick one on the title screen (left trigger in VR):
- **Squire:** enemy troops hit 22% softer, enemy magic recharges slowly, the rivals mostly fight each other, Duskmarch keeps a 10-week truce, your garrisons recover fast, and Kaelen is always rescued if captured.
- **Knight (default):** enemy troops hit 10% softer, the enemy counter-picks less often, the rivals target each other as well as you, Duskmarch keeps a 6-week truce, your generals level faster, and Kaelen's bodyguard rescues him if he's captured.
- **Warlord:** the original tuning. Both rivals hunt you first, and losing Kaelen ends the war.

## The campaign
The war table is a living map of 18 castles joined by roads. Aldmere (you), the Ashen Legion and Duskmarch all move armies in real time. Click one of your castles (the strongest generals with troops are pre-ticked; tick up to five), then click any castle on the map and your army marches there along the roads. In VR: point at your castle and pull the right trigger, then point at the target and pull it again; A cancels. Armies that meet on a road clash, and an army that reaches an enemy castle attacks it. Every battle drops into a battlefield that matches the castle's region. Taking a castle grows your territory, and armies claim empty castles along their route. Capturing a nation's ruler makes it collapse; a nation left with no castles scatters. Once no rival holds a castle, the unclaimed castles swear fealty and the realm is yours: the war is won when every castle flies Aldmere's banner, and lost if Kaelen is captured or your last castle falls. Every week (18 seconds), generals resting in castles heal and muster fresh troops. An advisor line always says what's happening and what to do next, a short feed lists recent events, and rings on the map mark castles with ready generals (gold), castles under threat (red) and castles one road from your selection (white). When you have nothing to do, time fast-forwards automatically. Pause with Space or the Pause button, and change the speed up to 4x.

Generals gain experience from kills, wins, duels and captures. Each level raises their HP, attack and defense, increases how many troops they command (110 at level 0 up to 400), and strengthens their spell. Ranks run from Captain to Warlord.

## How a battle works
Every round opens with the two generals trading taunts: the camera zooms in on each in turn while they speak in a Taiyo-style dialogue box. In VR the diorama glides toward you so each speaking general stands about 75 cm in front of you, then glides back to where you had it when the battle begins. Any trigger, Space or a click skips it.

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
- **Generals** fight on the field, take damage, and each has a spell: Starfall, Arrow Storm, Thunder Lance, Ash Rain, Dragon's Breath. MP holds spell charges, and weaker troop types get more magic to compensate: archer generals hold 5 charges, start with 2 and refill one every ~10 s; infantry hold 3, start with 1, ~16 s; cavalry hold 2, start with none, ~26 s, and gain half as much MP from kills. Dragon's Breath costs 2 charges. Higher levels recharge faster, kills add MP, and each cast spends one charge with a 4-second cooldown.
- **Capture:** a general who falls in a duel or to a spell is taken prisoner. When an army breaks, its general flees for the map edge and your troops chase him (cavalry is best at this); catch him before he escapes and he's yours. Between rounds you can try to persuade prisoners to join you with fresh troops, and the enemy will try the same with yours. Capturing Vorgrath ends the battle.
- **Duels:** challenge the enemy general, or answer his challenge. Refusing costs morale. The armies form a ring and each exchange is Strike / Guard / Power: Strike beats Power, Guard beats Strike, Power breaks Guard. A golden glow means he is winding up a Power blow.

## Sound
Everything is synthesized live in the browser: formant-filtered voices for battle cries and crowd cheers, war drums with rotating rhythms (faster when an army is charging), a din of steel that swells with the fighting, and a valley reverb over it all.

## Controls
- **Desktop:** drag to orbit, right-drag or WASD to pan, Q/E to turn, scroll or pinch to zoom (far enough to see the whole table). 1-4 orders, 5 duel, 6 withdraw, Space aims your spell (click the field to fire, Esc cancels). In duels J/K/L = Strike/Guard/Power. Y/N answer a challenge. Number keys pick a general.
- **Quest:** grip to grab the table, both grips to scale and turn it. Left stick slides the battlefield, right stick turns and zooms, B resets. Point the right controller to aim your spell and pull the right trigger to fire (otherwise it orders a charge). Left trigger cycles orders, A challenges to a duel, X twice withdraws. When the enemy challenges you, a war horn sounds, the controllers buzz and the HUD flashes: A accepts, X declines (the triggers keep fighting). In duels: right trigger Strike, left trigger Guard, A/X Power. When choosing a general: left trigger next, right trigger deploy.

Dragon Emperor I not required.
