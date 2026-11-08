# Dragon Emperor IV: The Eternal War

Playable demo of Taiyo's fictional 1997 strategy RPG for the Taiyo Vision 32-bit system.

A miniature war-table kingdom drops into stereoscopic battles of 400 vs 400 sprite soldiers on a 144x80 battlefield, drawn as instanced sprite batches. View it in mono, red/cyan, side-by-side or cross-eye stereo on a desktop, or in WebXR on a Meta Quest (open the GitHub Pages link in the Quest Browser and press Enter VR).

New players get an nine-page **How to play** guide when they press Start, covering the war table, match-ups, orders, magic, duels, spoils and the view controls. Every page lists both keyboard and Quest 2 controls, with a controller diagram that lights up the buttons that page uses (the Quest list comes first when opened in the Quest browser). It can be skipped, the "Don't show this at start" choice is remembered, and it can be reopened from **How to play** on the title screen. It works on desktop and in VR.

## Difficulty
Pick one on the title screen (left trigger in VR):
- **Squire:** enemy troops hit 22% softer, enemy magic recharges slowly, the rivals mostly fight each other, Duskmarch keeps a 10-week truce, your garrisons recover fast, and Kaelen is always rescued if captured.
- **Knight (default):** enemy troops hit 10% softer, the enemy counter-picks less often, the rivals target each other as well as you, Duskmarch keeps a 6-week truce, your generals level faster, and Kaelen's bodyguard rescues him if he's captured.
- **Warlord:** the original tuning. Both rivals hunt you first, and losing Kaelen ends the war.

**Ludicrous gore** (checkbox under the slider) ignores the slider: every death leaves big splatters and a fountain of droplets, and about one death in sixteen erupts in a huge blood explosion that paints the ground around it. **Blood** is set with the slider on the title screen (0 = off, remembered between visits). Every soldier who dies leaves a splatter on the ground where he fell, with a spray of droplets at higher settings; higher settings make splatters bigger and more frequent. Splatters stay for the whole battle (up to about 680 at once) and clear when the next battle begins.

## Troop types

| Type | Strong against | Weak against | Notes |
|---|---|---|---|
| Infantry | Cavalry | Archers, Knights | Spears and shields |
| Cavalry | Archers, Mages, Monks | Infantry, Knights | Fastest on the ground |
| Archers | Infantry, Harpies, Dragonriders | Cavalry, Knights | Keep shooting flyers even up close |
| Knights | Infantry, Cavalry, Archers | Mages, flyers | 11 HP, slow, 80% troop limit, shrug off spells better |
| Monks | (none) | Most things | Heal nearby soldiers; Elowen's **Mending Light** heals the army and raises up to 25 fallen |
| Mages | Knights, Dragonriders | Cavalry, Harpies | Ranged magic bolts |
| Harpies | Mages, Monks, Archers in melee | Archers at range, Knights | Fly over rivers, walls and woods |
| Dragonriders | Infantry, Cavalry, Knights | Archers | 14 HP flyers, only 40% troop limit |

New generals: **Sir Aldric Ironvow** (Knights) and **Sister Elowen** (Monks) for Aldmere, **Zareth the Pyromancer** (Mages) and **Kessa Wyrmrider** (Dragonriders) for the Ashen Legion, **Nyx of the Talons** (Harpies) and **Thessaly the Seer** (Mages) for Duskmarch. Each type has its own ability: Shield Wall, Sanctuary, Arcane Surge, Dive and Inferno.

## Weekly castle tasks and loyalty

Select one of your castles to set its task for the coming weeks (in VR, press Y with the castle selected to cycle):
- **Rest** (default): generals there recover 50% faster.
- **Search**: each week there is a 22% chance to turn up a relic or one of three wandering generals: Garrick the Sellsword (Infantry), Lyra Swiftwind (Harpies) and Tor Ironhoof (Cavalry).
- **Fortify**: raises the walls one level a week, up to 3; each level adds 120 HP to the gate in sieges. Recovery is slower while the masons work.
- **Reward**: +15 loyalty a week for every general there.

Every general but Kaelen has **loyalty** (♥ in the castle panel). Wins raise it, losses and idle weeks lower it, and a relic gift gives +20. A general under 40 is restless; under 25, he may defect to a neighbouring enemy castle. Enemy castles fortify too, slowly.

## New Game+: the Ages

Unite the realm and, after the battle's results, the war table shows the victory screen with **Begin Age II** (in VR a large board appears: **A** begins the next Age, **X** starts over at Age I; the trigger is ignored there so you can't skip it by accident). A story card opens the new Age, and:
- Every Aldmere general who survived keeps their level, XP, relic and loyalty; wandering generals you recruited return with you; the vault carries over.
- Enemy generals gain 2 levels per Age (up to 10) and increasingly carry relics; enemy castles start with stronger walls.
- The enemy hits harder, recharges magic faster and counter-picks more each Age.
- New battle conditions appear: **Blizzard** from Age II (slower troops, shorter archer range, snow and white-out) and **Blood Moon** from Age III (everyone deals 25% more damage under a red sky).

Progress is saved in the browser: the title screen shows **Continue · Age N**, and losing restarts the current Age with the same carried-over generals. **Start over at Age I** wipes it.

## Boss battles

- **The Ashen Wyrm.** In any battle where Vorgrath fights, his dragon is a boss with its own health bar. Every 7-11 seconds it either swoops with fire across your densest ranks or **lands**: the landing stomp flattens nearby troops, and for about 4 seconds it sits on the field breathing fire while your soldiers, archers and mages can attack it. Your spells also wound it whenever it is low (landing, grounded or diving). Slay it and the enemy's morale collapses, Vorgrath loses his Dragon's Breath for the rest of the battle, and the campaign rewards the **Wyrmheart** relic (+20% spell power, +10 HP, +1 spell charge).
- **Queen Ysolde's Eclipse** (costs 2 charges): the sun goes dark for 7 seconds, your troops deal 30% less damage, your morale drops, and lightning strikes your thickest ranks.

## Sieges

Every battle for a castle is a siege. A stone wall with towers runs the full width of the field in front of the defenders, with a wooden gate placed in the clearest lane across the field; rocks and ruin walls in that lane are cleared away, and a causeway crosses any water, so the gate can always be reached. Attackers path to the gate and batter it (Knights ×2.2, Dragonriders ×1.8, Mages ×1.4, Infantry ×1.2, Cavalry ×0.6, Archers and Monks barely scratch it). The gate starts at 180 HP plus 120 per level of fortification. Defenders behind the wall take 30% less damage from arrows, bolts and spells, and the defending AI holds the wall while the gate stands. Harpies and Dragonriders fly straight over. When the gate falls the defenders lose heart and the attackers surge. A broken gate stays broken for the rest of the battle. The HUD shows the gate's health. Skirmish can also set up a siege either way round.

## Skirmish

**Skirmish** on the title screen sets up a one-off battle: pick up to three generals for each side from all fourteen, the battlefield, the conditions (clear, fog, night, storm or random), a level (as written, all Lv 5 or all Lv 10) and whether generals carry random relics. Nothing carries over to the campaign. Afterwards you can take a rematch with the same setup or go back to the title.

## Relics

Twelve relics, each held by one general: Sunsteel Blade (+2 attack, +25% duel damage), Aegis of Highmere (+2 defense), Heartwood Charm (+12 HP), War Standard (+40 troops), Mana Pearl (+1 spell charge and starts charged), Stormglass Orb (+25% spell power), Duelist's Gauntlet (+1.5 s to choose in duels), Swiftmail (faster stamina), Lion Banner (+15% starting morale), Ember Ring (+10% troop damage), Ward of Ash (-20% magic damage taken) and Crown of Echoes (abilities recharge 30% faster). In the campaign, winning a battle has a 55% chance to turn up a relic (taking Vorgrath always does); it goes to the general who earned the most XP that battle, or to the vault if everyone already carries one. Hand out vault relics from a castle's panel.

## The campaign
The war table is a living map of 18 castles joined by roads. Aldmere (you), the Ashen Legion and Duskmarch all move armies in real time. Click one of your castles (the strongest generals with troops are pre-ticked; tick up to five), then click any castle on the map and your army marches there along the roads. You can run several campaigns at once: as soon as one army sets off, select another castle and send a second (or third) army while the first is still on the road. Click a marching army (it has a generous click area, and armies win over castles behind them) to change its orders: redirect it to an enemy castle, use Change course to send it anywhere, Halt it on the road and March on later, or Turn back. In VR, point at the army and pull the trigger, then press A for Change course or X to Halt/March on. In VR: point at your castle and pull the right trigger, then point at the target and pull it again; A cancels. Armies that meet on a road clash, and an army that reaches an enemy castle attacks it. Every battle drops into a battlefield that matches the castle's region. Taking a castle grows your territory, and armies claim empty castles along their route. Capturing a nation's ruler makes it collapse; a nation left with no castles scatters. Once no rival holds a castle, the unclaimed castles swear fealty and the realm is yours: the war is won when every castle flies Aldmere's banner, and lost if Kaelen is captured or your last castle falls. Every week (18 seconds), generals resting in castles heal and muster fresh troops. An advisor line always says what's happening and what to do next, a short feed lists recent events, and rings on the map mark castles with ready generals (gold), castles under threat (red) and castles one road from your selection (white). When you have nothing to do, time fast-forwards automatically. Pause with Space or the Pause button, and change the speed up to 4x.

After every battle a results screen tallies enemy slain and soldiers lost, fills each general's XP bar (with a fanfare on level-ups), slams down a rank from S to D, and lists the spoils: castles won, prisoners taken, new ranks. Click or pull the trigger to skip ahead. Generals gain experience from kills, wins, duels and captures. Each level raises their HP, attack and defense, increases how many troops they command (110 at level 0 up to 400), and strengthens their spell. Ranks run from Captain to Warlord.

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
  Woods slow troops (cavalry most) and halve arrow damage to anyone inside. Archers are nimble skirmishers: when a meteor (Starfall or Ash Rain) is coming down near them, about half of them scatter out of the blast. Lightning gives no warning, but after each bolt about half the archers nearby break and spread out, so a storm can't keep hammering the same packed clump.
- **Morale:** kills and spells raise it, losses lower it. An army below 20% starts to rout.
- **Formations** (F or the buttons; Y in VR): Wedge smashes Line (+30%) and Spread (+40%) but breaks on a Square (-30%); Square hits Wedges hard, moves slowly and takes 45% more magic; Spread takes about half damage from magic but hits softer. Changing formation takes a moment to settle. The enemy reads your formation and counters it.
- **Abilities** (R; left-stick click in VR), 22 s cooldown: infantry **War Cry** (+morale, +30% damage), cavalry **Thunder Charge** (+60% speed, +25% damage), archers **Eagle Eye** (+50% damage, longer range).
- **Power-ups:** every 10-16 seconds a glowing 3D orb (a lit sphere with a bright core, a tilting ring, a halo and a pool of coloured light on the ground) appears between the armies (up to three at once). Nearby soldiers, and every cavalryman, are drawn to it; the first side to touch it claims it and the enemy can't. **Mana Crystal** +1 spell charge, **Healing Spring** heals your general 25%, **Reinforcements** 15 fresh soldiers at your general, **War Banner** +30% damage for 8 s, **Dread Horn** shakes enemy morale, **Swift Boots** refill stamina and reset your ability. **Resurrection** (red ☥) raises up to 30% of your starting army from where they fell. **Thundercloud** summons a storm cloud that follows the enemy army for 8 seconds and drops a lightning bolt on a random soldier about once a second. Troops on Hold only chase orbs that are very close.
- **Drama:** kill streaks call out (Carnage, Rampage, Slaughter...) and swing morale; big multi-kills and duel clashes freeze the frame for a beat, and a general falling or an army breaking drops into slow motion. An army down to its last 15% makes a **last stand** (+60% damage, -35% damage taken, won't rout). Routed troops **rally** if their general survives six seconds. After 90 seconds the smaller army starts to tire.
- **Telegraphs:** the enemy general glows and shouts "gathers power!" 1.6 seconds before every spell, so you can scatter (Spread) or strike first. Floating tags above each army show its formation and whether the match-up is STRONG, EVEN or WEAK.
- **Battle conditions:** some battles roll **Fog** (archer range -30%), **Night** (archer damage -20%) or **Storm** (random lightning hits both sides; Thunder Lance recharges 60% faster).
- **Generals** fight on the field, take damage, and each has a spell: Starfall, Arrow Storm, Thunder Lance, Ash Rain, Dragon's Breath. MP holds spell charges, and weaker troop types get more magic to compensate: archer generals hold 5 charges, start with 2 and refill one every ~10 s; infantry hold 3, start with 1, ~16 s; cavalry hold 3, start with 1, ~20 s, and gain less MP from kills. Dragon's Breath costs 2 charges. **Thunder Lance** (cavalry) calls a 10-second storm of 8 bolts (more at higher levels): each click, Space or right-trigger pull drops one precise bolt where you aim, so you can snipe the enemy general or pick apart clumps. Unused bolts strike the thickest enemy ranks when the storm ends, and Esc releases them early. **Arrow Storm** (archers) works the same way: one charge gives 7 volleys (more at higher levels), and each click or trigger pull drops a tight barrage of 20 arrows in a small circle where you aim. Higher levels recharge faster, kills add MP, and each cast spends one charge with a 4-second cooldown.
- **Capture:** a general who falls in a duel or to a spell is taken prisoner. When an army breaks, or a general withdraws, he has to run to any edge of the field to escape, pathing around rivers and walls, while the other army chases him (cavalry is best at this). Catch him before he crosses the edge and he's a prisoner; this works both ways. Generals have a **stamina** bar (STA, under morale): sprints nearly double their speed for a couple of seconds and refill slowly while they jog. Steer your fleeing general with WASD/arrows or the left stick (he still drifts toward his edge, and the stick goes back to sliding the table afterwards), and sprint with Space or the right trigger; enemy generals sprint when chasers get close, and generals seeking a duel burst across long gaps. Between rounds you can try to persuade prisoners to join you with fresh troops, and the enemy will try the same with yours. Capturing Vorgrath ends the battle.
- **Duels:** like Dragon Force, a duel only starts when the two generals meet on the field. Press Seek duel and your general rides out to find his rival; a strong enemy will hunt yours, and a badly outmatched one will avoid you (which costs his army morale). When they meet, the camera swings to a side-on fighting-game view: health bars and portraits at the top, a countdown in the centre, and a LOCKED IN tag the moment either fighter commits. Both moves are revealed together at the clash. Strike beats Power, Guard beats Strike, Power breaks Guard. A gold glow and a rising whine mean he is winding up a Power blow. Run out the clock and you Strike by reflex. The timer is 5 s on Squire, 4 s on Knight, 3 s on Warlord.

## Sound
Everything is synthesized live in the browser: formant-filtered voices for battle cries and crowd cheers, war drums with rotating rhythms (faster when an army is charging), a din of steel that swells with the fighting, and a valley reverb over it all.

## Controls
- **Desktop:** drag to orbit, right-drag or WASD to pan, Q/E to turn, scroll or pinch to zoom (far enough to see the whole table). 1-4 orders, 5 seek duel (press again to stop), 6 withdraw, Space aims your spell (click the field to fire, Esc cancels). In duels J/K/L = Strike/Guard/Power. Number keys pick a general.
- **Quest:** grip to grab the table, both grips to scale and turn it. Left stick slides the battlefield, right stick turns and zooms, B resets. Point the right controller to aim your spell and pull the right trigger to fire (otherwise it orders a charge). Left trigger cycles orders, A seeks a duel (again to stop), X twice withdraws. When the enemy hunts your general, a war horn sounds and the controllers buzz. In duels the table glides in close and a scoreboard floats above the fighters: right trigger Strike, left trigger Guard, A/X Power. When choosing a general: left trigger next, right trigger deploy.

Dragon Emperor I not required.

## Debug log

If something breaks, open **Debug log** on the title screen (or the **Log** button in the view bar). It keeps the last 400 entries in the browser, even through crashes and VR sessions: errors with stack traces, warnings, battle and campaign milestones, XR session start/end, WebGL context loss, and a heartbeat every 30 seconds with frame rate, unit and particle counts. **Copy** or **Download .txt** and send it over. A single bad frame no longer freezes the game: the error is logged and the next frame carries on. A red toast appears on desktop when an error is logged.
