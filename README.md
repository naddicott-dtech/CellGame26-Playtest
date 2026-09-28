# CellGame26 playtest build

A test build of a cell-biology game in progress. The art is placeholder, and this isn't the game yet.

## Chromebook check (for TAs)

About 15 minutes per Chromebook.

**Before you start**
- Use a student Chromebook, plugged in, with every other tab closed.
- Note the model (**Settings → About ChromeOS**, or the label underneath) and the ChromeOS version.

**1. Graphics status.** Open `chrome://gpu` and photograph the **Graphics Feature Status** list. If the page is blocked, skip this step.

**2. Six measurements.** Open each link, keep the tab in front, and don't touch anything: the cell swims by itself. After about 35 seconds a black panel appears at the top right. **Photograph it.** If the panel starts with "The tab was hidden", reload and try again.

1. [Full load, tint effect](https://naddicott-dtech.github.io/CellGame26-Playtest/?scene=swarm&autoplay=1&fx=tint&measure=30)
2. [Full load, no effect](https://naddicott-dtech.github.io/CellGame26-Playtest/?scene=swarm&autoplay=1&fx=none&measure=30)
3. [Full load, blurred lens edge](https://naddicott-dtech.github.io/CellGame26-Playtest/?scene=swarm&autoplay=1&fx=blur&measure=30)
4. [Full load, capped at 30 fps](https://naddicott-dtech.github.io/CellGame26-Playtest/?scene=swarm&autoplay=1&fx=tint&fps=30&measure=30)
5. [Level 1 alone, for comparison](https://naddicott-dtech.github.io/CellGame26-Playtest/?scene=slice&autoplay=1&measure=30)
6. [Full load, tint effect, previous build](https://naddicott-dtech.github.io/CellGame26-Playtest/before/?scene=swarm&autoplay=1&fx=tint&measure=30): the same as link 1, on the build from before a speed-up, for a before-and-after

**2b. Optional: a typical-student tab load.** Open the tabs a student usually has open (Gmail, Docs, Classroom, 10 or more tabs), then repeat link 1 and photograph the panel. Chromebooks usually run short of memory before processor power, so this shows how the game fares on a busy machine.

**3. Task Manager.** While link 1 is running, press **Search + Esc** to open Chrome's Task Manager. Photograph the rows for the game's tab and for **GPU Process** (CPU and Memory footprint).

**4. Watch.** Open [link 1 without measuring](https://naddicott-dtech.github.io/CellGame26-Playtest/?scene=swarm&autoplay=1&fx=tint) and watch for a minute:
- Is the motion smooth, or does it stutter?
- Does the Chromebook get warm, or its fan get loud?

**Send back** all the photos and notes, labelled with the model.

## Level 1 prototype (for TAs)

About 10 minutes. This is a rough prototype of the first level. The text is placeholder: "[placeholder]" lines and grey demo boxes stand in for the real story and animations.

**[Play Level 1](https://naddicott-dtech.github.io/CellGame26-Playtest/level1.html)**

1. **Play it normally** to the "Level complete!" screen. Press on the cell's edge, drag outward and let go to move.
2. On the results screen, open **"Prototype measurements"**. Select all of its text and copy it into your notes, or photograph it.
3. **Play it again badly on purpose** (reload the page first):
   - spam long pulls until ATP runs out
   - ignore the glucose for a while
   - try dragging straight at far-away glucose when ATP is low

   Copy or photograph the measurements again.
4. **Note anything that confused you:** when you didn't know what to do, what a message meant, whether help arrived when you were stuck, and whether it felt slow anywhere.

**Send back** both measurement texts and your notes, labelled with the device (Chromebook model, or "own laptop").

