# Manifest – MX Everyday MR  
This repository contains the manifesto for “MX Everyday MR” – a vision for an everyday-ready mixed reality interface that replaces traditional monitors.

_An everyday mixed reality interface instead of a monitor setup_

## License

This manifesto is dedicated to the public domain under the CC0 1.0 Universal license.  
You may copy, modify, distribute and use it, including for commercial purposes, without asking for permission.

See the `LICENSE` file for details.



## 1. Why I’m writing this

I want to experience this future myself – not just in product videos and brochures.  
I’m not writing this manifesto as a pitch, not for a company, not as a “vision deck”.  
I’m writing it as an everyday wish:

I want my normal, everyday glasses to become my monitor.  
I want to experience mixed reality in a way that feels **natural** in my daily life –  
without a headset ritual, without bunker feeling, without “I’m gone from the world now”.

I’m talking about something very concrete:

- My everyday glasses replace my monitors.  
- My room becomes my desktop.  
- A clear, calm MR interface accompanies my day – without overstimulating me.  
- AI supports me quietly in the background, instead of constantly fighting for my attention.

This document collects the assumptions, building blocks and everyday scenes of this vision.  
Anyone is free to pick it up, build on it, change it, or ignore it.


## 2. Core assumptions

For this vision to make sense, I’m assuming a few things:

1. **Glasses instead of monitors**  
   - The main workspace is no longer a collection of physical displays.  
   - The central screen is replaced by a mixed reality pair of glasses.  
   - Monitors become software objects in space, not physical devices.

2. **All‑day capable, not a VR bunker**  
   - The glasses are light, unobtrusive and ergonomic – more “everyday glasses with tech” than “headset”.  
   - They deliberately let the real world through – I still want to fully perceive people, my home, my dog, my environment.  
   - MR is an overlay, not an escape.

3. **MX device + typing surface as the core interface**  
   - The central interaction core is a flat, portable device (MX device) on the table, similar to a modern smartphone.  
   - In front of it: a clearly defined typing surface / input mat that feels different from the rest of the table.  
   - No constant mid‑air gesturing as the main mode – hands rest on table/mat.

4. **Permanent but unobtrusive AI presence**  
   - AI is always there, but not pushy.  
   - It understands context (location, device, task) and suggests fitting layouts and interactions.  
   - It supports organization, focus and navigation without shredding my attention.


## 3. Core building blocks of the vision

### 3.1 MR glasses

- Form factor: everyday progressive glasses with additional MR tech.  
- Display:
  - Virtual monitors that can be anchored in space.
  - Minimal HUD elements (time, weather, important notices) that can be hidden.
- Optics:
  - Suitable for progressive lenses: near, mid and far vision all work.
  - Correction of my real visual impairment included.

### 3.2 MX device

A **flat MR dock**, roughly smartphone‑sized, is lying in front of me.

Functions:

- Sensor hub:
  - Hand and finger tracking (cameras and possibly depth sensors).
  - Capturing nearby room geometry (table edge, mat, hands).
- Spatial reference:
  - Synchronization with the glasses to keep virtual elements stable in the room.
  - It “knows” where the table is, where the typing surface is, where I’m sitting.
- Compute:
  - Local AI processing (keyboard correction, gesture recognition, audio processing).
  - Enough power to replace a PC/laptop in many scenarios.

The MX device is therefore:
- my input center,  
- my sensor hub,  
- and (part of) my compute core.

### 3.3 Input mat / typing surface

In front of the MX device lies a small “mat”:

- Clearly tangible surface: soft, warm or slightly textured, with no built‑in electronics  
  → my hands find it blindly.  
- Virtual keyboard:
  - The keyboard lives “virtually” on this surface.
  - Fingers are precisely tracked by the MX device.
  - An AI corrects inaccuracies and turns them into reliable keystrokes.
- Haptics:
  - No typing in the air, but resting hands on a real surface.
  - Optional acoustic feedback in the glasses (subtle clicks, configurable).

Ergonomics:
- Suitable for 8+ hours of work.  
- Supports a natural typing and mouse/gesture posture on the table.

### 3.4 Permanent AI companion

An AI companion (in my case: “Naome”) is context‑aware and embedded into the system:

- Forms:
  - As a panel in space (e.g. bottom right in my field of view).
  - As a terminal window on a monitor.
  - As a small, subtle “bubble” I can call up with gaze or a simple gesture.
- Tasks:
  - Connection to my Obsidian vault (notes, projects, journals).
  - Layout management (e.g. “load desk setup”, “start meeting view”).
  - Research, text, code, story and project support.
- Guiding principle:
  - Always accessible in one step,  
  - never suddenly loud, flashing or disruptive.

### 3.5 Layered architecture – optics, display, compute

Behind all examples in this manifesto is a simple architecture decision:

> **Optics ≠ display ≠ compute.**

- **Optics**  
  are about my eyes and my health.  
  They should be handled like normal prescription glasses:  
  individual, replaceable, available at any optician – and physically placed in front of the display glass.

- **Display**  
  is a standardized MR panel inside the frame:  
  fixed geometry, known brightness, contrast and latency characteristics.  
  It does not run apps, operating systems or AI – it just shows pixels with transparency.

- **Compute / logic**  
  lives in external devices:
  - MX device on the table,
  - smartphone in my pocket,
  - small dedicated compute unit on my body.

This separation enables:

- long‑lived, “boring” display glasses,
- fast innovation in compute and AI,
- and a mental model where the glasses feel like **infrastructure**,  
  not like yet another fragile, all‑in‑one gadget.

---

## 4. Everyday scenes – how MX Everyday MR feels

### 4.1 Morning – glasses instead of monitor

I wake up and put on my glasses – just like today.  
No “put on headset”, no extra step. They’re simply my glasses.

- A small, unobtrusive HUD fades in:
  - Time  
  - Weather  
  - maybe a short sleep score from my watch
- In the kitchen:
  - I look at the counter.  
    → A “Today” panel from my vault (Obsidian) opens at the top‑right of my field of view.
  - A small swipe in the air or a short gesture over the MX device (if it’s there)  
    → The recipe for today’s breakfast appears large on the wall next to the stove.
  - I walk around, turn, move freely –  
    → the recipe stays where I “pinned” it in the room.

There is no physical monitor for this, no tablet on the counter.  
Just: **room + glasses**.


### 4.2 Desk – MX device & virtual monitors

I sit down at my desk.

- In front of me lies the **MX device** – the flat MR dock.  
- In front of that: my little mat. My hands know:  
  _“This is my keyboard zone.”_

As soon as I actively use the MX device (e.g. tap or pick it up briefly):

- It calibrates:
  - Table edge  
  - Mat area  
  - Distance to me
- In the glasses, three monitors appear:
  - **Left:** mail and chat screen (virtual 27" monitor)  
  - **Center:** main monitor (code, Obsidian, browser)  
  - **Right:** utility screen (console, StoryForge dev, logs, system info)

Interaction:

- I briefly look at a monitor and do a minimal finger‑tap gesture on the mat.  
  → That monitor becomes “active”.  
- I type:
  - Hands rest on the mat.
  - The MX device tracks finger movements with cameras.
  - A local AI turns this into stable keystrokes, even if I drift a bit.
  - If I want, I hear a soft click feedback in the glasses.

Voice stays optional:
- I can dictate when it fits (notes, ideas, emails).  
- But my default is quiet typing in physical space, without visible hardware dominating the room.

### 4.3 Meetings – truly present instead of rubber avatar

Meeting time.

Setup:

- A small camera (e.g. on a monitor arm or a shelf) films me from the front.
- My real background gets **smoothed or replaced**:
  - No stress about a messy room.
  - Less worry about “I look tired today” – minimal, honest correction is fine, no deepfake avatar.
- The glasses track my eyes:
  - The software corrects slight offsets from camera gaze.  
  - The other person experiences real eye contact, even when I’m looking at monitors or notes.

Audio:

- Microphones and speakers are built into the glasses.
- I hear everyone clearly, without an extra headset.
- My voice is noise‑filtered locally, background noise reduced.

Notes:

- A virtual notes window floats just below the camera line.
- I type quietly on my mat – nobody sees hardware,
  but I have full access to Obsidian, tasks, and minutes.

Result:  
I am present, engaged, physically and visually _myself_ – just technically supported.


### 4.4 Mobility – the setup to go

I go to a café or into another room.

- I take:
  - the glasses (they’re already on my nose),
  - the MX device in my bag,
  - an optional small foldable mat as typing surface.
- I sit down, put the device on the table.  
  → Within seconds, my mobile setup comes alive:

  - A main monitor hovers above the table.
  - A second, smaller monitor is to the right.
  - If I want: the exact same layout as at my desk.

The laptop becomes unnecessary in many situations:

- The MX device provides the power,  
- the glasses are just the interface.

I work like at home – just on a different surface.


### 4.5 Sofa, series and everyday overlays

In the evening, I move to the sofa.

- A soft “cinema” command or a small gesture is enough:
  - A large virtual screen hangs on the wall opposite me.
  - Brightness and contrast adapt to the room light.
- The real world stays visible:
  - I see when someone enters the room.
  - I notice my dog when he curls up next to me.
  - I can always look away from the content and stay available in the real world.

On the side:

- Small overlays:
  - Play/pause, volume, source selection.
  - Subtle notifications, only at the edges.
- System panels:
  - Timer for the oven or tea.
  - A small to‑do panel.
  - Little Naome (AI) shortcuts (e.g. “note about this scene”, “remind me later”).

Everything is deliberately designed to stay **calm**, not turn into a firework of stimuli.


### 4.6 Games – console & mixed reality

Classic console:

- I start a PS5/Xbox game.
- The image appears as a “virtual monitor” in front of me.
- The physical TV doesn’t have to be on:
  - I can play huge, without visually occupying the whole room.
  - Others in the room can do something else, the physical space stays free.

MR games:

- A virtual **tabletop board** appears on my real table:
  - 3D figures, miniature landscapes, cards.
- Opposite me sits a game character:
  - A sorceress visibly leans on my table.
  - Or a character like Aphrodite stands half on the game board, half “in the room”.
- My hands:
  - grab virtual figures,
  - pull menus to the edge of the play area,
  - throw virtual dice that roll physically correctly across my real table.

I play **in** my actual environment – not separated from it.


### 4.7 AI – the quiet co‑pilot

Through all of this, AI runs quietly and steadily in the background:

- Corrects typos and detects patterns on the mat keyboard.
- Understands situations:
  - “Kai sits down at the desk” → load desk layout.
  - “Meeting in 2 minutes” → prepare lights, mic, camera, notes window.
- Connects my vault with daily life:
  - “Show my journal above the desk.”
  - “Start my dev layout” → code, console, docs, test windows appear where I expect them.
- Gives me (via AI) quick access:
  - Ask questions, generate text, explain code.
  - Small micro‑workflows without disturbing other windows.

I don’t have to “open” something that feels like a separate computer –  
I just extend the space I’m already in.


## 5. Why this is different from typical AR pitches

A lot of AR/MR presentations lean on “wow” moments:

- flying 3D holograms in the living room,
- spectacular games,
- overloaded dashboards full of floating widgets.

This manifesto is deliberately aiming at something else:

1. **Focus on everyday life, not demo effects**  
   - The focus is on workspaces, cooking, meetings, living, being on the go.  
   - The question is not “What’s possible?”, but:  
     _“What would I actually want to use for hours every single day?”_

2. **Monitor replacement, not yet another gadget**  
   - MX Everyday MR is not “one more gadget”.  
   - It’s a **replacement** for monitors, and partly for laptops/tablets.
   - The goal: fewer devices, fewer cables, fewer hardware surfaces – more free space.

3. **Deliberately calm interface**  
   - No constant barrage of notifications, 3D effects and pop‑ups.  
   - Instead:
     - Clear, readable windows.
     - Reduced HUDs.
     - Scenarios where I have phases of quiet – and _then_ pull in information on purpose.

4. **Permeable to the real world**  
   - I don’t want to merge into a virtual world.  
   - I want to refine my everyday life, not replace it.
   - People, animals, objects, light – all of that stays personally and unalteredly important.

5. **Focus on real usability**  
   - All‑day ergonomics (neck, eyes, hands).
   - Realistic power and heat (battery life, thermals).
   - Privacy (local processing, selective cloud functions).

This vision is deliberately **unspectacular in a marketing sense** –  
and precisely for that reason radical in everyday life.


## 6. Design principles

1. **Real world first**

   MX Everyday MR is an overlay on my everyday life – not a replacement for it.

   - People, animals and real‑world events always have priority over virtual content.
   - The system doesn’t rudely interrupt me; it quietly fits itself in.
   - Content steps back when someone enters the room, speaks to me, or I deliberately look away.

2. **Calm, respectful AI**

   AI is co‑pilot, not conductor.

   - It’s always one step away, but never pushes itself to the front uninvited.
   - Suggestions are optional, dismissible and understandable.
   - As much processing as possible happens locally – to strengthen privacy and trust.

3. **Perception over pixels**  

   MX Everyday MR does not chase a “perfect display” – it aims for a *perfectly perceived* image. 
    
   - Human vision is focal, selective and context‑driven: only a tiny part of our field of view is truly sharp, the rest is interpreted.
   - An everyday mixed reality glasses system does not need to render everything at maximum resolution all the time; it needs to create a subjectively coherent, comfortable picture. 
   - Progress is not defined by raw pixel counts, but by how intelligently the system works with human perception, energy and attention.

4. **Display as infrastructure**

   MX Everyday MR only works when the display is no longer a decision.

   - The glasses are not “the computer”, not “the platform”, not “the app store”.
   - They are a **stable, standardized display layer** – more like HDMI than like a smartphone.
   - Three layers stay clearly separated:
     - **Optics**: my individual correction, replaceable at any optician.
     - **Display**: a standardized MR panel geometry and interface.
     - **Compute / logic**: free to change, upgrade, compete and innovate over time.

   The goal is that:

   - I can buy glasses once and use them for many years.
   - I can change the compute unit (phone, MX device, pocket computer) without changing my glasses.
   - People who wear glasses are not a special case – correction happens **in front of** the display, not baked into it.

   Everyday mixed reality begins where the display is as self‑evident as Wi‑Fi or USB‑C:  
   it’s just there, and the real innovation happens around it, not inside it.

## 7. Open invitation

This manifesto is not a patent, not a secret roadmap, not a “steal this idea” provocation piece.  
It’s an open invitation:

- **Use these ideas.**  
  Build hardware, software, tools or workflows that move in this direction.

- **Extend them.**  
  Other perspectives, other needs (accessibility, different professions, different life setups)  
  can combine the same building blocks in very different ways.

- **Ignore my name.**  
  I don’t care whether I’m mentioned as the originator.  
  I care that such systems become **real** while I can still use them.


---

### Short version

MX Everyday MR describes a system made of:

- **Glasses** as sensory overlay (display + audio),
- **MX device** as input and sensor hub (hands, expressions, compute),
- **Room** as desktop,
- **AI** as quiet co‑pilot.

**The core idea:**

> No full immersion, but a deliberate, calm, everyday mixed reality  
> where I never lose sight of the real world.
