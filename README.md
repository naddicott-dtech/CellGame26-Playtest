# CellGame26 playtest build

A test build of a cell-biology game in progress. Some art is still placeholder.

**Build:** Levels 1 to 4, classroom build of `b2fad7f2` (2026-10-16; the dialogue polish and the glossary). New since the last build: Level 4 (Cleanup Crew) complete; the characters speak in character, with the control instructions in the Objective pane's help line and the "well, actually" details in **ⓘ Science note** buttons; the dialogue box no longer flashes when a scene opens; the Encyclopedia is real, with 52 entries revealed as the game teaches them, each with a game picture and a real-cell picture.

## Student QA: the dialogue polish and the glossary (October 2026)

About 40 minutes on a Chromebook. **[Play](https://naddicott-dtech.github.io/CellGame26-Playtest/)** (the teacher opens the link for the session).

**What changed, and what we want your opinion on.** This week the game's words were reworked, and the Encyclopedia was built. We can test that the code works; only you can tell us whether it *feels* right. Five things to judge:

1. **The characters stay in character.** Aqua, R.Y.E. and the others talk about the cell, not about the game. Nobody should say "click", "press", "button", a price, or a game rule in a speech bubble.
2. **You always know what to do.** The Objective pane (top left) names the goal and, under it in smaller type, how to do it. During a story scene it already shows what comes next.
3. **Science notes.** Some lines have a small **ⓘ Science note** button beside Back and Next. It holds the "well, actually…" detail (for example, the real ATP count).
4. **The dialogue box doesn't jump.** When a scene opens, the picture and text should appear at once, with no flash or reflow.
5. **The Encyclopedia** (the button top right). Terms appear as the game introduces them, grouped by category; each has text, a picture from the game and a picture of the real thing, with "See also" links and an **Enlarge** button on the real picture.

### Before you start

- A classroom Chromebook, Chrome, the window full size. Nothing else open.
- On level select press **Reset all progress** and confirm, so you start as a new student. (If you want to keep your own progress, use a different Chrome profile.)
- Keep a notes doc open beside you (the teacher's form). For every note, write **where** (level, what was on screen) and, if it's about words, **the exact words**.

### Part A: Level 1 and Level 2 (about 15 minutes)

Play Level 1 to "Level complete!", then **Start Level 2: Gesundheit**, and play it through. While you play:

- **Stuck?** Any moment you didn't know what to do: write what the Objective pane said at that moment, and whether its small help line was enough. If the pane was empty or said something unhelpful, that's the note we most want.
- **Out of character?** Any speech bubble that sounded like an instruction manual (a button name, a price, a rule about what the game allows). Write the speaker and the exact line.
- **The box.** When a scene opened, did anything flicker, jump or re-wrap? Which scene?
- **Science notes.** Did you notice the ⓘ button? Open at least two. Was the note worth the click? Did it cover anything you needed to see? Did one open by itself (the first mitochondrion), and was that a help or a distraction?
- **Nudges.** If you stop for 30 seconds, a line appears under the pane and something is pointed out. Did it help you, nag you, or point at the wrong thing?

### Part B: the Encyclopedia (about 10 minutes, anywhere in Level 2 or later)

1. Open it from the top-right **Encyclopedia** button. Which term is highlighted? Is that the one you'd expect right now?
2. Click or tap something in the cell (the nucleus, a mitochondrion), and press the **Encyclopedia: …** button on its panel. Did it open on that thing?
3. Read one full entry. Rate it: too long, too hard, about right, too easy. Underline any sentence you'd rewrite for a 9th grader.
4. The two pictures: does "In the game" next to "In a real cell" make sense to you? Press **Enlarge** on the real picture, then **Back to the entry**. Could you read the labels when enlarged?
5. Follow one **See also** link, then find your way back to where you were (the list on the left). Was that easy?
6. Use the ↑ and ↓ keys in the list. Press **Escape**. Did it close, and did you land back in the game where you were?
7. At your screen size: anything cut off, overlapping, or needing a scroll you didn't expect?
8. Look for terms you expected to find but couldn't. Write them down (some are hidden until a later level teaches them; that's on purpose, but we want to know what you looked for).

### Part C: Level 3 or Level 4 (about 10 minutes, if time)

Start the next level you have open and play as far as you get. Same questions as Part A, plus: open **Pause → How to Play** once. Does it answer the question you had, in the order you'd want?

### Closing questions (5 minutes, everyone)

Rate 1 (bad) to 5 (great), with one sentence each:

| | Rating | Why |
|---|---|---|
| I always knew what to do next | | |
| The characters sounded like characters, not a manual | | |
| The science notes were worth opening | | |
| The Encyclopedia helped me understand the cell | | |
| The game ran smoothly on this Chromebook | | |

Then two short answers: **one thing you would change first**, and **one thing about cells you know now that you didn't before** (say it in your own words; we check whether the game taught it right).

### Known things, no need to report

The Pseudopod entry has no "real cell" picture yet. Some Encyclopedia terms are hidden until Level 5 exists. The Cytoskeleton's real picture is large and may load slowly. Levels 5 and up are not in this build.

### For the teacher

- Collect the notes in one sheet with columns: tester, device, level, where (pane text or scene), the exact words, the note, the rating. The closing table's five ratings go in their own columns, so the before/after against the next build is a glance.
- The three items we most want decided from this round: whether the help line under the Objective is enough on its own (or whether students still want a spoken instruction), whether the science notes should stay closed by default, and whether the Encyclopedia's entries read at grade level.
- A note that quotes a line lets us find it in the manuscripts; a note that says "the dialogue was confusing" doesn't. Please ask testers for the words.

## Level 4 work in progress (test build, for the teacher)

The **test build** of `3eb996dc` (2026-10-14), in its own folder; the root stays the classroom build of Levels 1 to 3.

**[Play the test build](https://naddicott-dtech.github.io/CellGame26-Playtest/test/?open=all)**: `?open=all` opens every level; choose **Start Level 4: Cleanup Crew**.

- **What's there so far:** the Start, Damage and Golgi holds and Objectives 1 and 2: the damaged mitochondrion floating in and engulfed, the Golgi arriving and claimed by a tap.
- **Where it stops:** after the Golgi hold there is no next Objective yet. Buying lysosomes comes with the next PR.
- **Look for:** whether the damaged mitochondrion reads as damaged at normal zoom, and whether the Golgi's size, place and orientation read well (its curved side toward the ER, its open side toward the membrane).

## Level 3 playtest (for testers)

About 12 to 15 minutes, after Levels 1 and 2 (Level 3 opens when Level 2 is complete).

**[Play](https://naddicott-dtech.github.io/CellGame26-Playtest/)**: choose **Start Level 3: Room to Grow**.

1. **Play it normally** until "Level complete!".
2. **Note where you got stuck, and whether you got going again.** This level is the hardest so far. Especially:
   - **Selecting and recycling:** did **Select all slicers** and **Recycle** make sense?
   - **The ER:** did you find **Make Membrane** and **Take Membrane** on the ER's panel? Was the vesicle demonstration clear?
   - **The peroxide:** did you understand what the small particles were doing to the nucleus? Were **Move** and **Switch off / Switch on** on the mitochondrion easy to use?
   - **Repair and peroxisomes:** did you understand what the repair enzymes and the peroxisomes do?
   - **The unit counts** under the membrane gauge: did you notice them? Did they help you see when you were running out of slicers or peroxisomes?
   - **The viruses:** did you have enough slicers ready?
   - **Anything else:** a moment you didn't know what to do, something slow or broken, or something fun.
3. **Known gaps (no need to report):** placeholder Encyclopedia and How to Play text.

**Send back** your notes, labelled with the device, how long the level took you (it's on the results screen), and where you got stuck.

## Chromebook control check (Level 2, for the teacher)

The camera bench is gone; the check is on Level 2 itself, on a classroom Chromebook, about 10 minutes.

1. **[Play](https://naddicott-dtech.github.io/CellGame26-Playtest/)** Level 1 to "Level complete!", then **Start Level 2: Gesundheit**.
2. After the first ribosomes are bought, the hold zooms to the nucleus by itself; then the zoom bar appears.
3. Try each across the whole range: the **two-finger scroll** (it zooms), a **pinch**, the **zoom bar** and its **− and +** ends, **WASD or the arrows**, a **drag on empty space** (pans), and **Follow the cell**.
4. Note: any **accidental zooming**; **near-miss presses** on the membrane that panned instead of pulling; whether each control is easy to control across the range; and anything clipped behind the story box or the panel at the classroom window size.

## Level 2 playtest (for testers)

About 10 minutes, after Level 1 (Level 2 opens when Level 1 is complete).

**[Play](https://naddicott-dtech.github.io/CellGame26-Playtest/)**: choose **Start Level 2: Gesundheit**.

1. **Play it normally** until "Level complete!".
2. **Note anything that confused you**, especially:
   - **Buying:** did you find **Buy Ribosomes** and **Buy Slicers** on the nucleus's panel? Were the costs and any "bought 3 of 5" messages clear?
   - **The new ribosomes:** did you notice them sliding out of the nucleus through a glowing pore?
   - **The viruses:** did you understand what the slicers do, and why the membrane lost health?
   - **Running low:** if the game said winning was no longer possible and offered **Restart level**, did that make sense?
   - **The story boxes and demonstrations:** too long, too short, or about right? Any line you didn't understand?
   - **Anything else:** a moment you didn't know what to do, something slow or broken, or something fun.
3. **Known gaps (no need to report):** placeholder Encyclopedia and How to Play text; some lines are placeholders.

**Send back** your notes, labelled with the device and how long the level took you (it's on the results screen).

## Level 1 playtest (for testers)

About 10 to 15 minutes. Use a Chromebook if you can, or your own laptop, with the browser window as large as it goes.

**[Play Level 1](https://naddicott-dtech.github.io/CellGame26-Playtest/)**: choose **Start Level 1: Wiggle Room**.

1. **Play it normally** until "Level complete!". Read the story boxes as you normally would: **Next** or **Continue**, or press **Enter**.
2. **Play it again:** press **Pause** (or **Esc**), then **Restart**. On parts you've already seen, try **Skip to gameplay**.
3. **Note anything that confused you**, especially:
   - **The story boxes:** did you read them, skim them, or skip them? Too long, too short, or about right? Any line you didn't understand?
   - **The demonstrations** (the animations above the story box): did you watch them while reading, or miss them?
   - **The first pseudopod:** how long did it take you to make the cell move for the first time? How many tries didn't work first?
   - **Refusals:** if a pull was refused (a red flash and a message), did you understand why, and what to do instead?
   - **The ATP numbers** (new): did you notice the green and red numbers floating up from the cell, and the meter glowing green? Did they help you see what makes ATP and what spends it, or get in the way?
   - **Anything else:** a moment you didn't know what to do, something slow or broken, or something fun.
4. **Known gaps (no need to report):** the Encyclopedia and How to Play text are placeholders, and there are no cutscenes yet.

**Send back** your notes, labelled with the device (the Chromebook model, or "own laptop") and how long the level took you (it's on the results screen).
