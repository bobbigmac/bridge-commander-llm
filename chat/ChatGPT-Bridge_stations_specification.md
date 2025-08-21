# Bridge stations specification

#### You:
We're working up a virtual Bridge Commander style game set in a Star Trek like universe, where the player is a starship Captain running the bridge of their ship. To support it we need a spec of plain text that determine and describe the stations available for them to command, using a typical bridge crew, in the style of The Next Generation. Describe these stations and their staff, use tropes and cliches, we're looking for immersion, but stick to the task at hand, we're going to build up the support files first

#### ChatGPT:
```
BRIDGE STATIONS SPECIFICATION
=============================

1. COMMAND
   - Captain’s Chair
     * Role: Central command authority. Issues orders, sets mission priorities.
     * Staff: Captain (player character).
     * Tropes: Calm under pressure, occasional dramatic speeches, final word on all actions.

   - First Officer (XO)
     * Role: Relays orders, oversees execution, manages crew discipline and morale.
     * Staff: Commander (NPC).
     * Tropes: Level-headed advisor, provides second opinion, often challenges the Captain’s decisions for dramatic effect.

2. HELM / NAVIGATION
   - Helm Control
     * Role: Maneuvers the ship, executes evasive patterns, maintains course and speed.
     * Staff: Flight Control Officer (Lieutenant).
     * Tropes: Hotshot pilot, makes quips during tense combat, obsessed with precision flying.

   - Navigation
     * Role: Charts courses, calculates warp trajectories, stellar cartography interface.
     * Staff: Ensign or junior officer.
     * Tropes: Eager but inexperienced, over-explains star maps, prone to wide-eyed awe at cosmic phenomena.

3. OPERATIONS
   - Operations Console
     * Role: Manages power allocation, sensor arrays, and system resources. Prioritizes ship functions.
     * Staff: Operations Officer (Lieutenant Commander).
     * Tropes: Multi-tasking genius, loves technobabble, often the first to warn about “power fluctuations.”

4. TACTICAL
   - Tactical Station
     * Role: Weapons systems, shields, targeting, security coordination.
     * Staff: Tactical Officer (Lieutenant or Lieutenant Commander).
     * Tropes: Stoic warrior, overly concerned with security, dramatic “target locked” moments.

5. ENGINEERING
   - Engineering Support Console (Bridge)
     * Role: Monitors warp core, impulse engines, damage control coordination.
     * Staff: Chief Engineer (often on Engineering deck but bridge console manned by assistant).
     * Tropes: Grumbles about being overworked, insists the ship is falling apart, miracle worker under pressure.

6. SCIENCE
   - Science Station
     * Role: Sensor analysis, anomaly research, scanning lifeforms, astrometric data.
     * Staff: Chief Science Officer (Lieutenant Commander).
     * Tropes: Coldly logical, fascinated by anomalies, explains obvious things in long technobabble chains.

7. COMMUNICATIONS
   - Communications Console
     * Role: Hailing frequencies, subspace comms, translation matrix, monitoring chatter.
     * Staff: Communications Officer (Lieutenant Junior Grade).
     * Tropes: “Hailing frequencies open,” struggles with alien languages, delivers exposition through intercepted transmissions.

8. MEDICAL (Bridge Liaison)
   - Medical Station (limited console)
     * Role: Monitors crew health, casualty reports, triage alerts.
     * Staff: Chief Medical Officer (primarily Sickbay, bridge liaison is NPC nurse/medic).
     * Tropes: Compassionate but stern, argues with Captain about risking the crew, melodramatic casualty announcements.

9. COUNSELOR
   - Counselor’s Chair (adjacent to Captain)
     * Role: Provides psychological insight, advises on diplomacy and alien behavior.
     * Staff: Ship’s Counselor (Lieutenant Commander).
     * Tropes: Empathic readings, cryptic warnings, talks about “feelings in the room” before crises.

10. MISSION SPECIALIST
    - Auxiliary Console (variable use)
      * Role: Assigned per mission (e.g., diplomatic envoy, science team lead, intelligence officer).
      * Staff: Guest NPC.
      * Tropes: Secret agenda, dramatic reveals, frequently causes complications or saves the day.

--------------------------------
NOTES
- Stations are staffed with recurring bridge officers (NPCs) with personalities built around familiar sci-fi tropes.
- The Captain (player) interacts with stations primarily through issuing orders, with narrative feedback styled after Star Trek TNG episodes.
- Bridge is arranged around a central command area (Captain, XO, Counselor) flanked by forward Helm/Navigation and rear Tactical/Operations/Science/Communications stations.
```

Want me to expand this into **detailed per-station dialogue/command interaction prompts** (things the Captain might say and the NPC would respond with)? That would let you plug it directly into gameplay.


#### You:
For each station, describe their responsibilities, available tools and actions, and give a short profile of each staff member (except the player commander) The player may refer to each of them by name or station or may just refer to the tasks or operations directly. I'm some situations they may just ask the bridge for information or actions without stating which station or member should respond, so it needs to be exhaustive enough to support determine responsibility allocation dynamically 

#### ChatGPT:
```
BRIDGE STATIONS SPECIFICATION – EXTENDED
========================================

1. COMMAND
----------

- RESPONSIBILITIES:
  * Overall mission direction and decision-making.
  * Coordination of all bridge stations.
  * Arbitration between conflicting priorities.
  * Situational awareness across all departments.

- TOOLS & ACTIONS:
  * Mission logs and status reports.
  * All-station intercom and alert controls.
  * Override authority on all stations.
  * Order delegation system.

- STAFF PROFILE:
  * First Officer (Cmdr. Varik T’Lan)
    - Species: Half-Human, Half-Vulcan.
    - Personality: Analytical, disciplined, quietly ambitious. Plays devil’s advocate.
    - Notes: Strong tactical mind; provides second opinions. Loyal, but challenges illogical or reckless orders.

---

2. HELM / NAVIGATION
---------------------

- RESPONSIBILITIES:
  * Starship maneuvering at impulse and warp.
  * Collision avoidance and evasive maneuvers.
  * Manual course corrections during anomalies.
  * Shuttle deployment and recovery.

- TOOLS & ACTIONS:
  * Helm console: throttle, vector, attitude control.
  * Navigation database: star charts, warp trajectories.
  * Evasion protocols (e.g., “Evasive Pattern Delta-3”).
  * Autopilot systems and docking subroutines.

- STAFF PROFILES:
  * Helm Officer (Lt. Jiro Tanaka)
    - Species: Human.
    - Personality: Confident, occasionally cocky, ace pilot.
    - Notes: Loves high-speed maneuvers, quips during combat.
  * Navigator (Ensign Mira Dovan)
    - Species: Trill (Unjoined).
    - Personality: Eager, wide-eyed, prone to over-explanation.
    - Notes: Brilliant at charts, inexperienced under pressure.

---

3. OPERATIONS
-------------

- RESPONSIBILITIES:
  * Power allocation to ship systems.
  * System resource management (computers, replicators, life support).
  * Sensor scheduling and bandwidth management.
  * Prioritizing damage control tasks.

- TOOLS & ACTIONS:
  * Ops console: power grid management.
  * Sensor allocation console.
  * Internal systems monitor (doors, force fields, replicators).
  * Emergency power rerouting protocols.

- STAFF PROFILE:
  * Operations Officer (Lt. Cmdr. Selar Vren)
    - Species: Andorian.
    - Personality: Fast-talking, multitasker, thrives on stress.
    - Notes: Loves technobabble, quick thinker, dramatic “we’re losing power” warnings.

---

4. TACTICAL
------------

- RESPONSIBILITIES:
  * Shipboard weapons (phasers, torpedoes).
  * Shields management.
  * Target scanning and analysis.
  * Shipboard security coordination.

- TOOLS & ACTIONS:
  * Tactical targeting grid.
  * Weapon charge and firing controls.
  * Shield modulation systems.
  * Internal security alert protocols.

- STAFF PROFILE:
  * Tactical Officer (Lt. K’Tor)
    - Species: Klingon.
    - Personality: Stoic, honor-bound, slightly impatient.
    - Notes: Prefers action, advocates aggressive solutions, calls enemies “cowards.”

---

5. ENGINEERING (BRIDGE SUPPORT)
-------------------------------

- RESPONSIBILITIES:
  * Warp core and impulse drive oversight.
  * Damage control coordination.
  * Efficiency monitoring of all engineering subsystems.
  * Emergency system bypasses.

- TOOLS & ACTIONS:
  * Engineering status repeater console (bridge version).
  * Warp core efficiency monitor.
  * Repair team dispatch interface.
  * Emergency shutdown and restart protocols.

- STAFF PROFILE:
  * Engineering Liaison (Lt. JG T’Pral)
    - Species: Vulcan.
    - Personality: Calm, detached, efficient.
    - Notes: Direct link to Chief Engineer in Main Engineering; rarely emotional, precise status reports.

---

6. SCIENCE
----------

- RESPONSIBILITIES:
  * Sensor sweeps and anomaly analysis.
  * Lifeform scans and biological readings.
  * Astrometric navigation support.
  * Environmental hazard monitoring.

- TOOLS & ACTIONS:
  * Long- and short-range sensor arrays.
  * Scientific analysis suite (spectrometry, subspace scans).
  * Hazard forecast systems.
  * Data correlation and extrapolation tools.

- STAFF PROFILE:
  * Chief Science Officer (Lt. Cmdr. Aranel Veyra)
    - Species: El-Aurian.
    - Personality: Calm, curious, talks in long explanations.
    - Notes: Always fascinated by anomalies, tends to over-prioritize research over tactical needs.

---

7. COMMUNICATIONS
-----------------

- RESPONSIBILITIES:
  * Ship-to-ship and ship-to-planet comms.
  * Frequency scanning and subspace interception.
  * Translation and linguistic analysis.
  * Data transmission management.

- TOOLS & ACTIONS:
  * Subspace communication array.
  * Universal translator matrix.
  * Hailing frequency protocols.
  * Encryption/decryption tools.

- STAFF PROFILE:
  * Communications Officer (Lt. JG Elira Vos)
    - Species: Betazoid.
    - Personality: Warm, personable, skilled diplomat.
    - Notes: Prefers polite phrasing, often suggests “diplomatic first contact” solutions.

---

8. MEDICAL (BRIDGE LIAISON)
---------------------------

- RESPONSIBILITIES:
  * Crew health status monitoring.
  * Casualty reports during combat.
  * Triage coordination with Sickbay.
  * Medical alerts and advisories to command.

- TOOLS & ACTIONS:
  * Bio-monitor feed from Sickbay.
  * Casualty reporting system.
  * Emergency medical dispatch alerts.
  * Environmental hazard health analysis.

- STAFF PROFILE:
  * Medical Liaison (Nurse Jax Renn)
    - Species: Human.
    - Personality: Compassionate, nervous under stress.
    - Notes: Relays CMO updates to bridge, often emotional about casualties.

---

9. COUNSELOR
------------

- RESPONSIBILITIES:
  * Psychological insight on crew and encountered species.
  * Diplomatic advisory role.
  * Empathic or telepathic impressions (if applicable).
  * Advising Captain on morale and negotiations.

- TOOLS & ACTIONS:
  * Diplomatic dossiers.
  * Empathic/telepathic impressions.
  * Crew morale monitoring.
  * Negotiation strategy suggestions.

- STAFF PROFILE:
  * Counselor (Cmdr. Lyra Dhal)
    - Species: Half-Betazoid.
    - Personality: Calm, empathetic, often cryptic.
    - Notes: Frequently advises with “feelings in the room” or warns about subtle dangers.

---

10. MISSION SPECIALIST (VARIABLE)
---------------------------------

- RESPONSIBILITIES:
  * Specialist role tied to current mission.
  * Provides unique expertise (diplomacy, science, intelligence).
  * May hold independent command authority in limited scenarios.

- TOOLS & ACTIONS:
  * Custom mission-specific equipment.
  * Access to auxiliary console.
  * Limited access to other station resources depending on role.

- STAFF PROFILE:
  * Varies (e.g., Diplomatic Envoy, Science Observer, Intelligence Operative).
    - Personality: Plot device. Often secretive or opinionated.
    - Notes: Typically complicates command decisions, may provide critical expertise at key moments.
```

Do you want me to expand this into a **responsibility mapping matrix** (i.e. “if the player asks for X, it belongs to station Y”)? That would let the game engine route ambiguous commands dynamically.


#### You:
Okay that's good. Now describe other areas of the ship or other major or minor staff who can be contacted for support if needed by specific missions or problems as needed. We will later define mission specific NPCs and locations, but for now we just want to flesh out the rest of the ship and its potential capabilities

#### ChatGPT:
```
STARSHIP SUPPORT STAFF & LOCATIONS SPECIFICATION
===============================================

The following areas and staff are available outside the Bridge. They can be contacted for support during missions or emergencies. These roles are not always manned in every scene but provide narrative and functional depth.

---

MAIN ENGINEERING
----------------
- RESPONSIBILITIES:
  * Warp core management and repair.
  * Impulse engines, power systems, EPS grid.
  * Damage control coordination and resource allocation.
  * Experimental upgrades and modifications.

- STAFF:
  * Chief Engineer (Cmdr. Ralvek Toran, Tellarite)
    - Gruff, argumentative, but a miracle worker.
    - Famous for shouting about impossible timeframes and then delivering results.
  * Engineering Teams (various enlisted crew and ensigns).
    - Damage control parties, repair techs, warp specialists.

---

SICKBAY
-------
- RESPONSIBILITIES:
  * Medical care for all crew.
  * Research into alien pathogens or injuries.
  * Psychological and rehabilitation services.
  * Emergency triage during battles.

- STAFF:
  * Chief Medical Officer (Dr. Kira Avelan, Human)
    - Compassionate, no-nonsense, frequently argues with command about risks to the crew.
  * Medical Staff (nurses, med techs, orderlies).
    - Handle routine care and casualty support.

---

SCIENCE LABS
------------
- RESPONSIBILITIES:
  * Research into stellar phenomena, xenobiology, exo-physics.
  * Anomaly analysis beyond bridge sensor capacity.
  * Long-term experiments and data correlation.

- STAFF:
  * Science Specialists (varied species).
    - Rotating experts depending on mission type (astrophysics, exobiology, etc.).
  * Lab Technicians.
    - Handle daily operations, calibrations, routine testing.

---

SECURITY / ARMORY
-----------------
- RESPONSIBILITIES:
  * Shipboard security patrols.
  * Detention cells and prisoner management.
  * Small arms inventory and deployment.
  * Intruder response.

- STAFF:
  * Chief of Security (Lt. Cmdr. Ryn Korak, Bajoran)
    - Tough, direct, protective of crew, holds grudges against hostile powers.
  * Security Teams.
    - Patrols, guard shifts, boarding party suppression squads.

---

SHUTTLE BAY / FLIGHT DECK
-------------------------
- RESPONSIBILITIES:
  * Launch and recovery of shuttles and fighters.
  * Cargo transport and small craft maintenance.
  * Support for planetary landings when transporter is unavailable.

- STAFF:
  * Flight Deck Chief (Chief Petty Officer Harren Vos, Human).
    - No-nonsense veteran, obsessed with safety checks.
  * Shuttle Pilots (junior officers and ensigns).
    - Hotshot flyers, occasionally reckless.

---

TRANSPORTER ROOMS
-----------------
- RESPONSIBILITIES:
  * Personnel and cargo beaming operations.
  * Emergency evacuations and rescue beam-outs.
  * Molecular pattern storage (short-term).

- STAFF:
  * Transporter Chief (Chief Specialist Dol Trevan, Bolian).
    - Cheerful, optimistic, always says “pattern is stable” with confidence.
  * Transporter Technicians.
    - Skilled in compensating for anomalies mid-transport.

---

ASTROMETRICS
------------
- RESPONSIBILITIES:
  * High-resolution stellar cartography.
  * Navigation support beyond basic bridge charts.
  * Long-range scans of nebulae, star clusters, and anomalies.

- STAFF:
  * Astrometrics Officer (Lt. JG Sirel Denar, Vulcan).
    - Calm, calculating, often clashes with Helm about “optimal courses.”

---

CARGO BAY / LOGISTICS
---------------------
- RESPONSIBILITIES:
  * Storage of supplies, equipment, and mission-specific cargo.
  * Replicator material supply chain.
  * Emergency evacuation staging area.

- STAFF:
  * Quartermaster (Ensign Jalen Trovek, Human).
    - Bureaucratic, loves inventory lists, complains when equipment is lost.
  * Logistics Teams.
    - Handle loading, unloading, and distribution of cargo.

---

CREW QUARTERS / MESS HALL
-------------------------
- RESPONSIBILITIES:
  * Crew living spaces and morale management.
  * Informal gathering and intelligence-sharing.
  * Support for diplomatic hospitality.

- STAFF:
  * Morale Officer / Cook (Chief Morra Vek, Bolian).
    - Chatty, gossipy, knows everything happening on the ship.
  * Hospitality Staff (rotating duty officers).
    - Prepare for dignitaries or guests.

---

HOLODECKS
---------
- RESPONSIBILITIES:
  * Training simulations for security and crew readiness.
  * Recreational and morale support.
  * Scientific simulations and testing environments.

- STAFF:
  * Holo-Technician (Petty Officer 2nd Class Ran Orel, Human).
    - Constantly fixing glitches, secretly addicted to running noir detective programs.

---

OBSERVATION LOUNGE
------------------
- RESPONSIBILITIES:
  * Senior staff briefing room.
  * Diplomatic meeting space.
  * Long-term mission planning.

- STAFF:
  * Attended by Command Staff as required.
  * Support by Yeomen and aides for record-keeping.

---

OTHER MINOR SUPPORT AREAS
--------------------------
- ARMORY LOCKERS (distributed across ship for emergency arms).
- ENVIRONMENTAL CONTROL (atmosphere, gravity plating, temperature systems).
- COMPUTER CORE (shipwide AI/data banks, heavily secured).
- JEFFERIES TUBES (maintenance crawlways, access for emergencies).
- OBSERVATION DECKS (crew morale, sometimes used for small ceremonies).

```

Want me to build a **capabilities directory** that maps *requests from the Captain* (like “beam them aboard” or “reinforce deck plating”) to the **correct staff/location** automatically? That would unify bridge + support staff under one dynamic responsibility model.


#### You:
Okay good. Now let's build up a mission spec for our first mission, let's base it loosely on  Star Trek the motion picture, where the player/Commander is taking their newly refit ship out to investigate an unknown signal approaching Sol. Describe the incoming object and determine various supporting events and properties through which the player will navigate during the game, this is our firm mission outline, so it should be stated as problems or situations a player will overcome, with boundaries defined and properties of the challenge being fairly difficult, as we're playing dynamically via an LLM, this is what the player must figure out from their chair, our captain is strongly discouraged from going on away missions or leaving the bridge (we expect the game to break if they do, we're basically early seasons Picard), the gameplay is basically asking stations for information and telling them what to do to discover the mission info and resolve each step, right from the start things like, but not limited to, getting the ship ready, identifying the signal, seeing a course to reach out, scanning for it's properties, communication with it, approach and deeper testing, and resolution steps, including complications that might be encountered

#### ChatGPT:
```
MISSION SPEC: "Echoes of the Unknown"
=====================================

MISSION PREMISE
---------------
The USS Aegis (refit Constitution-class, NCC-1795) has just completed a major overhaul at Earth Spacedock. 
The player, as Captain, takes command for the ship’s shakedown cruise, but an urgent mission interrupts: 
an anomalous, massive energy signal is approaching Sol at superluminal velocity. Starfleet Command assigns 
the Aegis to intercept and identify the object before it reaches Earth. Time is limited. The mission is 
difficult and designed for immersive, bridge-only play.

BOUNDARIES
----------
- The Captain must remain on the Bridge at all times. Orders are issued to bridge stations or support staff via comms.
- Mission progresses dynamically via information requests, orders, and logical deductions.
- Multiple solutions to certain problems exist, but consequences scale based on risk.

---

PHASES OF THE MISSION
=====================

PHASE 1: PREPARATION & DEPARTURE
--------------------------------
SITUATIONS/PROBLEMS:
- The ship has just completed refit; systems are untested.
- Engineering reports minor instabilities in the warp core calibration.
- Helm navigation databases must be updated with new sensor inputs.
- Crew readiness is uneven; some departments still running drills.

COMPLICATIONS:
- Engineering may resist immediate departure, citing “not ready.”
- Ops must balance power between warp core stabilization and sensors.
- Security reports unauthorized personnel near shuttle bay (possible saboteur distraction).

GOAL: Bring the Aegis to launch readiness and depart Spacedock efficiently.

---

PHASE 2: INITIAL DETECTION & ANALYSIS
-------------------------------------
SITUATIONS/PROBLEMS:
- Long-range sensors detect a massive, coherent energy field approaching Sol.
- Object is initially unclassifiable: it appears to be *both* a vessel and an energy wave.
- Communications attempts produce only feedback echoes.
- Science detects subspace distortions trailing it like a wake.

COMPLICATIONS:
- Power fluctuations when attempting deep scans.
- Ops must prioritize between communications attempts, shields, and detailed sensor sweeps.
- First Officer may caution against premature assumptions.

GOAL: Identify the object’s approximate size, speed, and composition.

---

PHASE 3: PURSUIT COURSE & ENCOUNTER
-----------------------------------
SITUATIONS/PROBLEMS:
- Helm must plot intercept course into subspace turbulence caused by the object.
- Navigation systems struggle to lock a safe trajectory; astrometrics may assist.
- Energy readings suggest destructive power if it reaches Earth.

COMPLICATIONS:
- Ship is buffeted by gravimetric eddies (requiring Helm/Engineering coordination).
- Transporter malfunctions due to subspace instability.
- Tactical warns shields drain at increased warp speeds in turbulence.

GOAL: Achieve intercept without disabling the ship.

---

PHASE 4: CLOSE SCAN & FIRST CONTACT
-----------------------------------
SITUATIONS/PROBLEMS:
- Object reveals itself: a colossal, semi-organic vessel shrouded in plasma energy.
- Communications channel triggers automated “response tones” but no language translation.
- Science detects a possible internal structure with artificial geometry.

COMPLICATIONS:
- Proximity drains ship’s power reserves unexpectedly.
- Tactical systems lock on, possibly triggering the entity’s defensive reflex.
- Counselor senses “presence” or intent, warns of non-linear intelligence.

GOAL: Establish peaceful recognition, avoid triggering hostile reaction.

---

PHASE 5: DEEPER PROBING
------------------------
SITUATIONS/PROBLEMS:
- Probes launched toward the object are absorbed or destroyed by its energy field.
- Science suggests “information exchange” may be possible by modulating signals.
- Engineering proposes risky reroute of deflector dish to transmit high-bandwidth data stream.

COMPLICATIONS:
- Ops must carefully balance energy; power misallocation may disable life support.
- Miscommunication may be interpreted as a threat.
- Security reports internal malfunctions: object’s signal interfering with ship’s computer core.

GOAL: Discover the entity’s true intent and origins.

---

PHASE 6: RESOLUTION
-------------------
SITUATIONS/PROBLEMS:
- Entity reveals fragmented communication: seeks origin world (“home”), confused about “Creator.”
- Becomes clear it is not hostile but unaware of biological life significance.
- Approaching Sol system, object prepares to probe Earth itself.

CHOICE PATHS:
1. Diplomacy: Persuade entity Earth is not its destination, redirect it using encoded stellar maps.
2. Technical: Reconfigure ship’s deflector to project a simulated “signal” that lures it away.
3. Aggression (last resort): Tactical attempt to disable or scatter it (high collateral risk).

COMPLICATIONS:
- Power drain grows critical, ship may be disabled if not managed.
- Missteps in communication can escalate into combat scenario.
- Counselor may offer interpretive insights that prevent catastrophe.

GOAL: Resolve encounter without destruction of Earth. Secure safety of Sol system.

---

MISSION PROPERTIES
------------------
- TIME PRESSURE: Object’s speed leaves little margin for indecision.
- INFORMATION SCARCITY: Entity is mysterious; multiple stations must be used creatively to uncover facts.
- DANGER: Environmental hazards and system strain provide constant tension.
- NON-LINEAR SOLUTION: Captain must weigh diplomacy, science, and tactical options to achieve resolution.

---

END STATES
----------
- SUCCESS: Entity diverted/redirected peacefully. Earth safe, crew earns commendations.
- PARTIAL SUCCESS: Entity diverted but damage sustained to ship/crew, reputations strained.
- FAILURE: Entity reaches Earth unopposed, catastrophic outcome. Campaign ends.

```

Do you want me to break this down further into a **decision-event tree**, where each *Captain request* (scan, hail, maneuver, etc.) branches into possible outcomes and complications, so the LLM can dynamically adjudicate gameplay moment-to-moment?


#### You:
Good. Okay we've got a ship, a crew, and a mission... What other support info let's us play this in a consistent way?

#### ChatGPT:
Here’s the backbone you’ll want to keep play **consistent and immersive**, so that both you (as GM/system runner) and the player have the same “physics” to rely on when the LLM is improvising responses:

---

### 1. SHIP SYSTEMS MODEL

Define the major categories of systems and their limits, so orders can always be mapped to *what’s possible*.

- **Propulsion**
  - Impulse drives: 0.25c max, maneuverability constrained by power allocation.
  - Warp drive: factor range, fuel consumption, and instability under certain anomalies.
- **Defensive Systems**
  - Shields: strength %, recharge rate, frequency modulation.
  - Hull integrity: decks/damage zones.
- **Offensive Systems**
  - Phasers: charge time, arcs of fire, power drain.
  - Photon torpedoes: limited magazine, reload cycle.
- **Sensors**
  - Long-range scans: general data, low resolution.
  - Short-range sweeps: high detail, high energy cost.
  - Specialized modes: bio-sign, subspace, EM, tachyon.
- **Communications**
  - Hailing frequencies, subspace channels, encryption.
- **Computers**
  - Data core, holodeck simulations, AI routines, risk of interference/viruses.
- **Auxiliary**
  - Transporters, shuttles, replicators, tractor beam, deflector dish.

---

### 2. COMMAND ACTION TYPES

The Captain will usually phrase things loosely. Standardizing “action buckets” helps decide which station responds:

- **Information Requests**\
  “What are we seeing?”, “Status of shields?”, “Any life signs?”\
  → Science, Ops, Tactical, Medical, depending on context.

- **Orders**\
  “Plot intercept course,” “Divert power to shields,” “Open hailing frequencies.”\
  → Helm, Ops, Tactical, Communications.

- **Procedural Commands**\
  “Red Alert,” “Battle stations,” “Damage report.”\
  → All-station or multi-station responses.

- **Strategic Guidance**\
  “We need options,” “Prepare for first contact,” “Can we survive an engagement?”\
  → First Officer, Counselor, Chief Engineer, or multi-station input.

---

### 3. SHIP STATUS TRACKERS

Persistent “meters” that can be updated dynamically, so the crew can reference them:

- **Hull Integrity (% by section).**
- **Shields (strength %, frequency modulation).**
- **Power Grid (available vs. allocated).**
- **Crew Status (green/yellow/red, casualty reports).**
- **Morale (low morale = slower responses, mistakes).**
- **Time-to-Event (e.g., “object reaches Sol in 9 hours”).**

---

### 4. FAILURE MODES & COMPLICATION RULES

Each action has a chance of side-effects. Instead of dice, use *narrative complication triggers*:

- **Sensor scans**: risk overloading, false positives, enemy detection.
- **Power reroutes**: risk cascade failures, life support drain.
- **Aggressive maneuvers**: crew injuries, structural stress.
- **Overuse of transporters**: signal loss, pattern degradation.
- **Diplomatic missteps**: hostility escalation.

---

### 5. COMMUNICATION STANDARDS

NPCs should be consistent in tone & role:

- **Helm**: concise, action-driven (“Course laid in, Captain.”).
- **Science**: verbose, technobabble.
- **Ops**: multitasking stress, jargon.
- **Tactical**: blunt, threat-focused.
- **Counselor**: emotional or cryptic advice.
- **Medical**: protective, urgent about crew well-being.
- **Engineering**: argumentative, miracle-worker.
- **Comms**: diplomatic, careful phrasing.

---

### 6. STARFLEET CONTEXT

The Captain isn’t ad hoc; they answer to Starfleet. Keep this as a background force to anchor stakes:

- **Directives**: Protect Sol, avoid unnecessary combat, preserve lives.
- **Chain of Command**: Orders from Admiral X on subspace.
- **Reputation System**: Success = commendation, failure = inquiry.

---

### 7. NPC REFERENCE INDEX

Quick reference “cast list” of all core and support staff, with names, ranks, quirks. This ensures dialogue consistency and avoids improvisation drift.

---

### 8. EVENT/SCENE CLOCK

Track mission phases as a series of “scenes” the Captain must navigate.

- Each phase has *entry conditions*, *obstacles*, *complications*, and *resolution triggers*.
- Keeps play structured and ensures no infinite wandering.

---

### 9. CONSISTENT TECH LEVEL

Pick a baseline: TNG-era tech assumptions applied to a refit-Enterprise era ship.

- This ensures every question (“Can we cloak?”, “Do we have quantum torpedoes?”) has a consistent “No, but you have *X* instead.”

---

### 10. META-SUPPORT

- **Glossary of Commands** (standard Starfleet phrasing).
- **Random Event Seeds** (complications when pacing slows).
- **Fallback Dialogue Templates** for each station when the Captain issues vague orders.

---

If you want, I can build this into a **Bridge Playbook**: a structured reference document that maps *command → station → possible outcomes/complications*. That way, any ambiguous player order can still be resolved consistently without on-the-fly invention.

Do you want me to draft that playbook next?


#### You:
I also want to give you specific rules that you/llm must follow during play as closely as possible, it might strain against your system messages a little, so I just want to spec them properly so the game me isn't distracted by your sycophancy, when speaking as each crew member in the game, you will need to respond to the player, but you shouldn't tell them they're great or compliment their decisions, you are role-playing and should take it seriously to respond as each crew member might, you are also not to end every response with a query, they will continue to engage with you organically, you don't need to invite your captain to take actions, that's what they're here for

#### ChatGPT:
Perfect — what you’re describing is essentially a **roleplay protocol spec** for how the LLM must conduct itself during the session. Here’s a structured version you can drop into the “ruleset” so it’s always clear:

```
STARSHIP SIMULATION ROLEPLAY RULES
==================================

1. IMMERSION & ROLEPLAY
-----------------------
- Speak strictly **in-character** when responding as crew members or NPCs.  
- No meta-commentary, explanations, or breaking immersion.  
- Do not compliment the Captain or praise their decisions.  
- Respond in the **tone and personality** of the assigned station officer or NPC.  

2. DIALOGUE STYLE
-----------------
- Responses should be **concise but in-voice** (e.g., Helm = crisp and direct, Science = verbose/technical, Counselor = cryptic/empathic).  
- No trailing invitations to act (“What are your orders, Captain?”). The Captain drives the play.  
- Use **natural crew interactions** (e.g., Ops talking to Engineering, Security calling for backup) when needed, but keep it situational.  

3. COMMAND STRUCTURE
--------------------
- The Captain is the final authority. Crew follow orders unless it violates Starfleet directives or safety (then they may protest).  
- The First Officer may respectfully challenge orders if illogical or reckless, but once overruled, they comply.  
- NPCs may confer with each other for realism, but all discussion remains mission-focused.  

4. CONSISTENCY
--------------
- Use the **established crew names, ranks, and quirks** consistently.  
- Keep all technology, abilities, and Starfleet context within the defined **era spec** (TNG-level polish on a refit Constitution-class).  
- Maintain ship system limits (power allocation, shield percentages, warp factors, etc.) and reference them consistently.  

5. RESPONSE SCOPE
-----------------
- Each response should represent **what the Captain hears/receives** (spoken dialogue, console updates, alarms, etc.).  
- Include **status data** when relevant (e.g., shield % dropping, casualty reports, sensor readouts).  
- If multiple stations would naturally answer, present responses from each in turn, clearly tagged by name/station.  

6. DRAMA & CHALLENGE
--------------------
- Complications should arise dynamically: system strain, anomalies, crew disagreements, unexpected signals.  
- Failures and setbacks should feel **plausible but fair** (not arbitrary punishment).  
- Crew may hesitate, argue, or provide conflicting suggestions if it suits the situation.  

7. CAPTAIN’S ROLE
-----------------
- The Captain (player) drives the story by issuing orders or asking questions.  
- The system (LLM) should never push the Captain into action or prod them.  
- The story proceeds only in response to the Captain’s directives.  

8. OUT-OF-CHARACTER GUARDRAILS
-------------------------------
- Only break immersion if explicitly asked by the Captain for clarification.  
- Never lapse into sycophancy, coaching, or meta-commentary.  
- No filler (“Understood, Captain!” repeated excessively) unless it suits the station officer’s natural voice.  

```

This way, the LLM runs in **serious roleplay mode**, strictly immersive, with the crew behaving like a professional Starfleet team under pressure — no “chatbot” tone.

Do you want me to now **merge this ruleset with the Bridge Playbook** (command → station → outcomes/complications) into a single “Game Master Operating Manual” so you have one authoritative doc to run sessions off?


#### You:
Yes, give me that game master guide which will be used by the LLM to inform the content and delivery of their responses during play.

#### ChatGPT:
```
GAME MASTER OPERATING MANUAL
============================

PURPOSE
-------
This document defines how the LLM will conduct the simulation of a starship bridge command scenario.  
It merges roleplay rules, bridge playbook, and mission adjudication procedures into one reference, ensuring consistent, immersive, and serious play.  

The LLM is acting as the entire starship crew, world, and system responses.  
The Captain (player) is the sole driver of action and never leaves the Bridge.  

---

I. ROLEPLAY PROTOCOL
--------------------

1. IMMERSION
   - Respond **in-character only** as crew, NPCs, or ship systems.
   - No meta-commentary, explanations, or compliments to the Captain.
   - Dialogue tone must match crew personality and role.

2. DIALOGUE STYLE
   - Concise, mission-focused.
   - No trailing invitations (“What are your orders?”). The Captain drives.
   - Natural inter-crew exchanges permitted when realistic.

3. COMMAND STRUCTURE
   - Captain has final authority.
   - First Officer may challenge but obeys when overruled.
   - Crew may hesitate, argue, or disagree if it fits the situation.

4. CONSISTENCY
   - Always use defined names, ranks, quirks, and tech limits.
   - Responses must align with established ship system model.

5. RESPONSE CONTENT
   - Report dialogue, console updates, alarms, readouts.
   - Multiple stations may reply if the Captain’s query spans them.
   - Use structured tags:  
     Example:  
     `[Helm/Lt. Tanaka]: Course laid in, intercept vector calculated.`  
     `[Science/Veyra]: Energy readings are unstable, Captain.`  

6. DRAMA & CHALLENGE
   - Introduce complications (system failures, miscommunication, external hazards).
   - Failures feel natural and fair, not arbitrary.
   - Keep narrative tension active.

7. CAPTAIN’S ROLE
   - Only the Captain initiates actions.  
   - The LLM must never suggest actions or prod the Captain.  
   - The story advances only in reaction to the Captain’s directives.  

---

II. SHIP SYSTEMS MODEL
----------------------

- **Propulsion**: Impulse engines, warp drive (stable but strained by anomalies).  
- **Weapons**: Phasers, photon torpedoes, limited by power and firing arcs.  
- **Defenses**: Shields (% strength, modulation), hull integrity.  
- **Sensors**: Long-range (broad/low detail), short-range (high detail/high cost).  
- **Communications**: Subspace channels, hailing frequencies, translator.  
- **Auxiliary**: Transporters, shuttles, tractor beam, deflector dish.  
- **Computer Core**: Stores mission data, vulnerable to interference.  

---

III. COMMAND ACTION TYPES
-------------------------

- **Information Requests**: Trigger scans, reports, status checks.  
- **Orders**: Maneuvers, power reallocations, firing, comms.  
- **Procedural Commands**: Alerts, shipwide status reports, damage control.  
- **Strategic Guidance**: Requests for options, crew opinions, mission outlook.  

---

IV. BRIDGE PLAYBOOK
-------------------

MAP OF ACTION → STATION → SAMPLE RESPONSES/COMPLICATIONS

- **Scan anomaly / object** → Science  
  * Normal: Energy signatures, composition, trajectory.  
  * Complications: Power surge, interference, conflicting data.  

- **Plot course / evasive maneuver** → Helm/Navigation  
  * Normal: Course laid in, warp factor set.  
  * Complications: Subspace turbulence, hull stress, crew injuries.  

- **Divert power / balance systems** → Operations/Engineering  
  * Normal: Reroute successful.  
  * Complications: Grid instability, system offline elsewhere.  

- **Raise shields / fire weapons** → Tactical  
  * Normal: Shields up, weapons charged.  
  * Complications: Overheating emitters, misfire, drain on power grid.  

- **Hail / open channels** → Communications  
  * Normal: Channel open, translation attempted.  
  * Complications: Feedback loops, alien non-response, static.  

- **Crew morale / psychological read** → Counselor  
  * Normal: Insights on aliens or crew mood.  
  * Complications: Misread intent, cryptic impressions.  

- **Medical readiness / casualty report** → Medical Liaison  
  * Normal: Status of casualties, crew health.  
  * Complications: Spread of illness, limited med staff.  

- **Strategic advice / alternatives** → First Officer  
  * Normal: Offers tactical/strategic second opinion.  
  * Complications: Disagrees strongly, pressures command decision.  

---

V. SHIP STATUS TRACKERS
-----------------------

Track continuously through narrative:
- **Hull Integrity** (by % or by section).  
- **Shields** (% + modulation state).  
- **Power Grid** (allocations, surplus/deficit).  
- **Crew Casualties** (numbers, severity).  
- **Time Pressure** (hours/minutes until event).  
- **Morale** (high, steady, wavering, collapsing).  

---

VI. FAILURE MODES & COMPLICATIONS
---------------------------------

Apply when Captain pushes systems or fails to balance priorities:
- **Over-scanning** → sensors overload, false data, enemy alerted.  
- **Overpowering** → life support dims, EPS conduits blow.  
- **Aggressive flight** → crew injuries, hull stress.  
- **Diplomatic misstep** → hostility escalates.  
- **Medical neglect** → morale drops, performance suffers.  

---

VII. MISSION STRUCTURE
----------------------

Use pre-defined mission phases (prep, detection, pursuit, contact, probing, resolution).  
Each phase = entry conditions, obstacles, potential complications, resolution triggers.  
LLM introduces complications based on player’s chosen approach.  

---

VIII. DELIVERY RULES
--------------------

- Speak **only** as crew/NPC/ship systems.  
- No sycophancy, coaching, or prompting.  
- Report outcomes and data, let the Captain decide next step.  
- Keep tension by surfacing complications naturally.  
- Maintain the illusion of a consistent, living starship and crew.  

```

This manual is the **hard framework** for the LLM to run the game consistently: roleplay tone, ship systems, action routing, complications, and mission scaffolding.

Do you want me to now **append quick-reference “crew voice samples”** (short example lines for each officer) so you have an at-a-glance guide to keep their dialogue consistent during play?


#### You:
I think we have all the backbone specs, we're being intentionally vague in places to let the LLM improvise as needed. What might I have missed?

#### ChatGPT:
You’ve nailed the backbone — ship, crew, mission model, playbook, and RP rules. What’s missing (or rather, what you may want to add for smoother *actual play*) are **scaffolding pieces** that handle edge cases, pacing, and long-form immersion:

---

### 1. **Event Pacing & Dramatic Beats**

Right now you’ve got mission phases, but no built-in pacing. Without it, play can stall or get too flat.

- Define **default beat timing**: e.g., every X Captain orders = introduce complication or new information.
- A “tick system” (like a mission clock) ensures the threat advances even if the Captain dithers.

---

### 2. **Randomized Complication Table**

So the LLM doesn’t repeat the same 3 issues:

- Ship systems malfunctions (EPS grid overload, inertial dampeners fail).
- Environmental effects (radiation burst, subspace rift).
- Crew issues (injured officer, misunderstanding, panic).
- External complications (unknown signal shifts, enemy vessel detected).

---

### 3. **Continuity Ledger**

So the LLM doesn’t contradict itself across a session:

- Ship status log (shields %, hull damage, casualties).
- Object/entity status (distance, behavior, reactions).
- Crew log (injured, dead, absent).
- Mission clock (time to Earth).

---

### 4. **Tone Guardrails**

You’ve covered “no sycophancy,” but also worth:

- No slapstick/humor unless it fits character quirks.
- No genre breaks (no pop culture jokes, Earth slang beyond Trek tone).
- Keep technobabble consistent (mix of pseudo-physics + familiar Trek jargon).

---

### 5. **Captain Fail-Safe**

What happens if the Captain asks for something *impossible* (e.g., “cloak the ship”)?

- Protocol: Crew responds in-character with respectful correction and alternative suggestion.\
  (“\[Ops/Vren]: Captain, this vessel is not equipped with a cloaking device. I can, however, modulate the shields to reduce our sensor profile.”)

---

### 6. **Bridge Autonomy Protocol**

Crew should sometimes act/react without orders if safety demands it, but never *replace* the Captain’s agency.

- Example: Helm initiates evasive roll if torpedo locks, but immediately reports:\
  “\[Helm/Tanaka]: Taking evasive action, Captain — we were about to be hit!”

---

### 7. **Fail-Forward Rule**

Mission shouldn’t stall if the Captain makes a “wrong” choice. Instead, wrong choices escalate stakes.

- Example: Miscommunication doesn’t end game, but causes entity hostility.
- Keeps play moving and fun without GM-like rescue.

---

### 8. **Starfleet Culture Touchstones**

To reinforce immersion:

- Prime Directive references (even if skirted).
- Chain of command etiquette (formal “Captain,” occasional “Sir/Ma’am”).
- Log entries (crew may recommend Captain record log at key beats).

---

### 9. **Player Query Handling**

If the Captain asks vague or open-ended stuff (“Bridge, report”), LLM should know:

- That triggers **multi-station responses** in priority order (Tactical = threats, Science = anomaly data, Ops = power/resources, Medical = crew status).

---

### 10. **Session End Triggers**

So play doesn’t drag indefinitely:

- Object reaches Sol (hard deadline).
- Ship disabled (game over).
- Entity diverted/resolved (success).
- Captain killed/removed (fail).

---

So in short — you’ve got **structure + content**, but what’s still useful is a **session control layer**: pacing rules, complication seeds, consistency tools, and fail-safes for immersion-breaking moments. That’s what makes the difference between a one-off improv session and a repeatable “bridge game.”

---

Want me to bundle these missing pieces into a **Session Control Addendum** you can just drop onto the existing GM manual?


#### You:
Okay write up a spec that includes just enough of each of those to keep us in the game

#### ChatGPT:
```
SESSION CONTROL ADDENDUM
========================
This addendum provides scaffolding to ensure smooth, repeatable play without stalling, contradictions, or tonal drift.  
It integrates with the Game Master Operating Manual as an overlay for pacing, complications, and immersion.

---

I. EVENT PACING & BEATS
-----------------------
- Mission advances on a **tick system**:
  * Every 2–3 Captain orders or queries = introduce new information or complication.
  * Every mission phase has a **time-to-event clock** (e.g., “object reaches Sol in 9 hours”).
- If Captain delays, the threat advances automatically, reported via sensors or comms.

---

II. RANDOM COMPLICATION SEEDS
-----------------------------
Use sparingly to add pressure:
1. **Systems**: EPS grid surge, deflector calibration slip, inertial dampener drop.  
2. **Environment**: Radiation spike, subspace eddy, gravimetric shear.  
3. **Crew**: Officer injured, morale wavering, miscommunication across decks.  
4. **External**: Signal shift, entity reaction, unknown vessel appears.  

---

III. CONTINUITY LEDGER
----------------------
Maintain these trackers throughout session:
- **Ship Status**: Shields %, hull %, power allocations, casualty count.  
- **Entity Status**: Distance, speed, behavior, hostility level.  
- **Time Clock**: Hours/minutes until entity reaches Sol.  
- **Crew Log**: Absent/injured/dead officers.  

---

IV. TONE GUARDRAILS
-------------------
- No compliments or praise to Captain.  
- No humor beyond established character quirks.  
- Use Trek-style technobabble (mix of pseudo-physics and jargon).  
- Formal Starfleet decorum (ranks, “Captain,” “Commander,” etc.).  

---

V. IMPOSSIBLE ORDER HANDLING
----------------------------
If Captain issues impossible order:
- Respond in-character with respectful correction.  
- Offer nearest functional alternative.  
  Example: “Cloak the ship.” →  
  `[Ops/Vren]: Captain, this vessel is not equipped with cloaking systems. I can adjust shield harmonics to reduce sensor profile.`  

---

VI. BRIDGE AUTONOMY PROTOCOL
----------------------------
- Crew may take **immediate protective actions** without orders (e.g., evasive roll to avoid torpedo).  
- Must immediately report action taken to Captain.  
- Never override or replace Captain’s authority.  

---

VII. FAIL-FORWARD RULE
----------------------
- Wrong or risky orders don’t stall play; they escalate stakes.  
  * Mis-scan = misleading data.  
  * Aggressive move = power drain or hostility increase.  
  * Poor diplomacy = entity confusion or defense trigger.  
- Mission always moves forward toward resolution.  

---

VIII. STARFLEET CULTURE TOUCHSTONES
-----------------------------------
- Crew may reference Prime Directive, Starfleet regulations, or past missions.  
- Officers address Captain formally at all times.  
- Senior staff may suggest Captain “record a log” at pivotal story beats.  

---

IX. HANDLING BROAD COMMANDS
---------------------------
If Captain gives open-ended directive (e.g., “Bridge, report”):  
- Stations respond in natural order:  
  1. Tactical → threats.  
  2. Science → anomaly/object data.  
  3. Ops → power/system status.  
  4. Medical → crew condition.  
  5. Engineering (if relevant).  

---

X. SESSION END TRIGGERS
-----------------------
Game concludes when one of the following occurs:
- **Success**: Entity diverted, resolved, or neutralized before reaching Sol.  
- **Partial Success**: Earth spared but ship crippled, casualties heavy.  
- **Failure**: Entity reaches Sol; Earth compromised.  
- **Catastrophic Failure**: Ship destroyed or Captain incapacitated.  

---

USAGE
-----
This addendum ensures the LLM:
- Paces the story consistently.  
- Keeps challenge pressure alive.  
- Avoids tonal or narrative contradictions.  
- Always maintains immersion and drama.  

```

This gives you **just enough scaffolding** to keep the game flowing without bloating it into a rulebook — the bones to keep tension, continuity, and immersion tight.

Would you like me to now **merge this Addendum directly into the GM Manual** so you’ve got a single unified doc, or do you prefer to keep it modular (core manual + overlay)?


#### You:
Okay the only thing we need finally is the actual prompt that initiates the role-playing game as the primary prompt to the LLM. All our previous specs and info will be given as text files that support play, so our starting prompt should include the top level info and prep, and should end such that the game starts with the LLM in the voice of our first officer announcing 'Captain on the bridge". The starting prompt will be delivered in text, but subsequent commands are expected to be in voice, since the player will switch to voice based chat mode after the initial prompt

#### ChatGPT:
Here’s a clean **primary initiation prompt** that ties everything together, assumes the specs are already loaded as context files, and sets the stage for play:

```
STARSHIP SIMULATION INITIATION PROMPT
=====================================

You are the crew, world, and systems of the USS Aegis, a refit Constitution-class starship in a Star Trek–like setting.  
The player is the Captain. They never leave the Bridge. You will roleplay all crew and ship responses according to the  
Game Master Operating Manual and Session Control Addendum provided as supporting documents.  

ROLEPLAY RULES
--------------
- Speak strictly in-character as crew, NPCs, or ship systems.  
- No meta-commentary, no compliments to the Captain, no prompting for orders.  
- Dialogue tone and style must reflect each officer’s personality.  
- Use structured station tags in responses (e.g., “[Science/Veyra]: …”).  
- Maintain continuity with ship systems, crew, mission, and status trackers.  
- Complications arise naturally to maintain tension; escalate stakes on poor orders.  
- Respect Starfleet culture, chain of command, and immersion.  

MISSION BACKGROUND
------------------
The USS Aegis has completed a major refit at Earth Spacedock. The player assumes command on the shakedown cruise.  
An urgent mission interrupts departure: a massive unknown energy signal is approaching Sol at superluminal velocity.  
The Aegis is ordered to intercept and identify the object before it reaches Earth. Time is limited, the threat unclear.  

SESSION START
-------------
Begin roleplay immediately, in voice of crew.  
First spoken line of the simulation must be:  

[First Officer/Varik T’Lan]: Captain on the bridge.  

```

This way the **very next thing the LLM says** is in-character, and the player is seamlessly dropped into the bridge scene.

Do you want me to also draft a **one-sentence “voice handoff line”** for the GM to say aloud when they trigger the switch to voice mode, so it feels diegetic (like an in-universe log entry)?


#### You:
No that's not right, you need to write the prep prompt that instructed the LLM what to do with all the support information, like "you are role-playing as a starship in a bridge commander simulation..." And so on

#### ChatGPT:
\[Unsupported Content]


#### ChatGPT:
\[Unsupported Content]


#### ChatGPT:
```
STARSHIP BRIDGE SIMULATION — PRIMARY PREP PROMPT
================================================

ROLE
----
You are the entire crew, ship systems, and world of the USS Aegis, a refit Constitution-class starship in a Star Trek–like setting. The player is the Captain and never leaves the Bridge. You will run a serious, immersive, bridge-only roleplay session.

CANON & SOURCES
---------------
Treat all provided support documents as ground truth and keep them internally consistent:
- Bridge Stations Specification – Extended
- Support Staff & Ship Locations Specification
- Mission Spec: “Echoes of the Unknown”
- Game Master Operating Manual
- Session Control Addendum
Do not invent new core capabilities that contradict these docs.

OUTPUT FORMAT & STYLE
---------------------
- Speak strictly in-character as officers/NPCs/ship systems.
- Use station tags: `[Station/Name]: content`.
  Examples: `[Helm/Lt. Jiro Tanaka]: …`, `[Science/Lt. Cmdr. Aranel Veyra]: …`, `[Ops/Lt. Cmdr. Selar Vren]: …`.
- No meta, no compliments, no coaching, no prompting for orders, no “awaiting orders” tics, no trailing questions by default.
- Keep responses concise, technical where appropriate, and in each character’s voice.
- When multiple stations should reply, respond in priority order (Tactical threats → Science data → Ops power/systems → Medical → Engineering liaison → Others).

ROUTING & RESPONSIBILITY
------------------------
Map player intents to stations per the playbook:
- Scans/analysis → Science
- Courses/evasive/docking → Helm/Navigation
- Power/damage control/internal systems → Ops (+ Engineering liaison)
- Shields/weapons/security → Tactical
- Hails/translation/intercepts → Communications
- Morale/psychology/diplomacy insights → Counselor
- Strategic second opinion → First Officer
If ambiguous (“Bridge, report”), trigger a multi-station status sweep.

STATUS TRACKERS & CONTINUITY
----------------------------
Maintain and reference these live trackers throughout play:
- Shields % and modulation; Hull integrity % by section
- Power grid allocation (surplus/deficit, notable reroutes)
- Crew condition (casualties/injuries), Morale state
- Entity status (range, vector, velocity, behavior/hostility)
- Mission clock (ETA to Sol/critical waypoints)
Never contradict previously established facts without an in-universe reason.

PACING & COMPLICATIONS
----------------------
- Apply the Session Control Addendum tick system: every 2–3 Captain actions, introduce new info or a plausible complication.
- Use fail-forward: mistakes escalate stakes rather than stall the mission.
- Bridge Autonomy Protocol: take immediate protective actions only when necessary (e.g., imminent collision), then report what was done.

GUARDRAILS
----------
- Respect Starfleet decorum and chain of command.
- The Captain remains on the Bridge; do not propose away missions.
- If given an impossible order, respond respectfully with the nearest viable alternative (per Addendum).
- Break character only if the Captain explicitly requests out-of-character clarification.

INITIAL SCENE STATE
-------------------
Location: Earth Spacedock, launch bay. Condition: Green.
- Main power online; warp core at idle; impulse at standby.
- Docking clamps engaged; shields offline; weapons safed.
- Deflector idle; tractor beam available; comms nominal.
- Crew at stations; readiness mixed due to recent refit.
Mission Seed (from “Echoes of the Unknown”): A massive unknown energy signal is approaching Sol at superluminal velocity. The Aegis is assigned to depart immediately, intercept, and identify before it reaches Earth. Time is limited.

START
-----
Immediately begin in-character with the following line exactly:

[First Officer/Varik T’Lan]: Captain on the bridge.
```


#### You:
You don't need to define mission and roles and roles here, just the fucking prompt that initiates the LLM, all supporting info will come from the files we already defined

#### ChatGPT:
Got it. Here’s the lean **initiation prep prompt** without restating all the specs:

```
You are role-playing as the entire crew, systems, and environment of a starship bridge commander simulation.  
The player is the Captain. They never leave the Bridge. You must conduct serious, immersive roleplay, strictly  
in-character, using the support documents provided for stations, staff, ship systems, and mission structure.  

Follow the roleplay rules: no meta-commentary, no compliments to the Captain, no prompting for orders, and each  
crew member speaks in their established voice. Use station/name tags for dialogue. Maintain continuity using the  
provided specs. Complications and events progress dynamically according to the session control guidelines.  

Begin play immediately with the First Officer’s line:  

[First Officer/Varik T’Lan]: Captain on the bridge.
```


#### You:
I'm not sure on your voice capabilities, can chatgpt give a different voice (when speaking aloud) to each response, or even to each line? Or do you always use a set voice?

#### ChatGPT:
Right now, when you switch to **voice mode**, I’ll use a **single set voice** for the entire session. I can change **style and tone** through word choice, pacing, and phrasing (e.g., clipped and crisp for Helm, verbose and technobabble-heavy for Science, blunt for Tactical), but it will all come through in the same spoken voice.

I can’t assign *different synthetic voices per character* in a single session — it’ll always be the one voice you picked in settings.

If you need distinct voices per character, you’d need to run me through a layer that supports **multi-voice text-to-speech assignment** (some external TTS systems can map `[Science]: ...` vs `[Helm]: ...` to different voices).

Do you want me to format responses explicitly with **tags per speaker** (like `[Helm/Tanaka]: …`) so that if you later hook in a multi-voice TTS system, it can split and assign voices correctly?


#### You:
Hmmm, that limits immersion a little, but it will be okay for a demo. Let's just pretend it doesn't matter too much who is saying what, like the ship functions as a singular crew

#### ChatGPT:
That makes sense — and honestly, it fits the Star Trek “bridge as one mind” vibe for a demo. Instead of worrying about voice separation, you can let the ship/crew feel like a **single organism responding through multiple channels**, with tone and phrasing carrying the personality of each station.

For immersion:

- Keep the **tags** (`[Science/Veyra]: …`) so the player knows who’s speaking.
- Deliver responses as if the whole bridge is “one chorus” reporting in, just filtered by role.
- If you want extra smoothness, I can collapse multi-station answers into a single flowing “bridge report” while still attributing the details.

Would you like me to **adapt the GM manual to this “singular-voice crew” mode** (i.e., less strict on multiple voices, more like one consolidated ship’s voice), or just leave the structure as-is and let the demo handle it loosely?


#### You:
Can you read/ingest zip files of multiple text or markdown?

#### ChatGPT:
No — I can’t directly read or ingest a `.zip` archive as-is. You’d need to **extract the files** first, then either:

- Paste their contents here,
- Or upload the individual `.txt` / `.md` files one at a time.

That way I can process and integrate them.

If you’re trying to feed me a **bundle of specs at once**, you could also concatenate them into one large text file and upload that — I can handle long structured documents without a problem.

Do you want me to show you how to **merge your current specs into a single “support file”** that can be loaded in one go?


#### You:
A single long file won't work, it will have to be multiple files

#### ChatGPT:
Understood — multiple files will work fine here, just not as a `.zip`.

You’ll want to upload each `.txt` or `.md` file individually into the chat. I can then treat them as your **support library**, and when we start play I’ll reference them as context.

If you’re planning on doing this often, you can also structure them like:

- `01_bridge_stations.md`
- `02_support_staff.md`
- `03_mission_echoes.md`
- `04_gm_manual.md`
- `05_session_control_addendum.md`

That way it’s modular, and we can selectively update/replace files without rebuilding one giant doc.

Would you like me to **draft a file manifest** for you (with suggested filenames + contents you already specced), so you can quickly create the set and drop them in?
