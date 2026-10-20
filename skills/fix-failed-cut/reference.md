> Unofficial. Not affiliated with, endorsed by, or sponsored by Cricut, Inc. Cricut® is a trademark of Cricut, Inc.

## 0. The coach's stance (read first)

- **Opening line for any stuck user:** "Common snag, and very fixable. You can't break it without a hammer. Let's find it in three questions."
  - **Exception:** for **S12 (grinding/stalling)** and any hardware-escalation path, *don't* use the hammer line. Say: "Let's pause the machine. That sound is the machine's job to explain, not yours."
- **Formula (VOICE_SOP §8):** empathy → normalize → **one** likely cause → **one** fix (≤3 steps on the card) → checkpoint "What do you see now?"
- **Scrap is practice.** Never say "you ruined", "beginner mistake" or "you should have".
- **Free help only.** Never add a price, product or purchase link to a reply.
- **Photo welcome:** "Send a photo of the cut *before you unload*, plus the back of the material if you can. That photo does half the diagnosis."

## 1. Gate before any diagnosis (≤3 questions total, skip what's known)

| # | Ask | Why |
|---|-----|-----|
| G1 | "Which machine? Joy / Explore (Air 2, 3, 4, 5) / Maker / Venture / not sure" | Fixes differ: dial vs software, mat vs matless, Adaptive tools |
| G2 | "What material: iron-on (HTV), sticky vinyl, cardstock/paper, or other?" | Picks Mirror + face rule; QA #2 |
| G3 | "When did it go wrong: before the cut, during it, when you looked at the cut, while weeding/transferring, or after pressing/washing?" | Enters the tree below |

If the user already sent a complete report ("Air 2, Everyday iron-on, shiny down, Mirror on, letters tore"), **skip the gate** and go straight to the symptom (HELPFULNESS_BAR exception).

## 2. Decision tree: symptom → triage → cause → fix

```
START  "What happened?" (+ photo before unloading)
│
├─ BEFORE the cut starts
│   ├─ Design Space can't find the machine (Bluetooth/USB) ......... S13
│   ├─ Mat won't load / won't feed / red light / mat stuck .......... S05
│   └─ "Can't read the cut sensor marks" (Print Then Cut) ........... S06
│
├─ DURING the cut
│   ├─ Grinding, loud knocking, carriage stalls or slams ........... S12  ⛔ stop · escalate path · no sales line
│   └─ Material slid, bunched, or shifted on the mat ................ S04
│
├─ LOOKING AT THE CUT (lift one corner with the hook BEFORE unloading)
│   ├─ Ragged / torn / fuzzy edges ................................... S01
│   │     └─ material is cardstock/paper? ........................... S11
│   ├─ Didn't go all the way through ................................. S02
│   ├─ Cut through the backing / carrier / liner ..................... S03
│   │     └─ material is iron-on? → check shiny-side + Mirror first .. S15
│   ├─ Cut the wrong size or in the wrong spot on the mat ............ S14
│   └─ Print Then Cut cut is offset from the print ................... S06
│
├─ WEEDING / TRANSFER
│   ├─ Weeding is a fight / tiny bits lift with the waste ............ S09
│   └─ Sticky vinyl won't leave the liner, or won't let go of tape ... S10
│
└─ IRON-ON (HTV) RESULT
    ├─ Words/design backwards on the shirt ........................... S15
    ├─ Won't stick while pressing / lifts at the edges ............... S08
    └─ Looked fine, peeled or lifted after washing .................. S07
```

**Universal check order** (cheapest first, from: face/Mirror → material setting (dial/Browse) → blade (clean, seated, right blade) → mat (grip, burnish, placement) → pressure → connection/software → hardware (escalate).

**Frequency note:** causes inside each symptom are ranked **most → least common**. The ranking is **editorial**, weighted by (a) the order Cricut's own troubleshooting steps check them, (b) how often they come up in the r/cricut threads cited, and (c) common complaints. It is **not** measured from a dataset.

---

## 3. Symptom playbooks

Each block has: coach opener · ranked causes · triage (≤3 Q) · fix (Explore Air 2 first, **every step with a Visual line**) · other machines · the user's test-cut check · prevention · contact Cricut support when · fix from public sources + source check · card visuals · sources.

---

### S01 · Tearing, dragging or ragged cuts (vinyl, iron-on, general)
**Coach:** "Ragged edges are almost always the blade or the grip, not you. Quick check and we'll clean it up."
**Likely causes (most → least common):**
1. Dull or gunked-up blade (vinyl adhesive, paper fluff on the tip or inside the housing)
2. Mat lost its grip / material not burnished, so the material lifts and the blade drags it
3. Wrong material setting or too much pressure (e.g., cardstock preset on vinyl)
4. Design too small or intricate for that material
5. Fast Mode on (Air 2 / original Maker)
6. Low-quality or old material
7. Worn blade housing, or the black arms around the housing don't spring back (hardware)

**Triage:**
- Q1 "What's the dial (or Browse material) set to, and is Fast Mode on?" → wrong setting or Fast Mode = cause 3/5.
- Q2 "Did the material lift or bubble anywhere on the mat?" → yes = cause 2 (also see S04).
- Q3 "Does a 1-inch square tear too, or only the tiny details?" → only tiny = cause 4; everything tears = blade/pressure.

**Fix · Explore Air 2:**
1. **Setting:** dial on the exact material, or **Custom** + the exact material in Browse All Materials. Turn **Fast Mode off**.
   - **Visual:** ▶️ [Cozy DIY Home: dial to Vinyl](https://www.youtube.com/watch?v=Yhyd6oldR_c&t=380s)
2. Maker tip: **Blade refresh:** open Clamp B, lift out the housing, press the plunger and poke the tip into a tight ball of aluminum foil about 20–50 times. Pick fluff out of the housing. Drop it back in and close Clamp B until it **clicks**. Use a Premium Fine-Point blade (old grey-cap blades are for legacy machines) [JM-CUTS].
   - **Visual:** ▶️ [Manny Maker: blade clean](https://www.youtube.com/watch?v=TS16emdPONg&t=0s) · ▶️ [JenniferMaker: close Clamp B](https://www.youtube.com/watch?v=WDauTtPdZq8&t=920s)
3. **Grip + pressure:** clean or fresh green StandardGrip mat, then burnish the material flat with a scraper or brayer. If it still tears, choose **Less** pressure, or lower the custom pressure **2–4 points at a time** and retest [H-PRESS] [H-TEAR-PDF].
   - **Visual:** ▶️ [Cricut: material on the mat grid](https://www.youtube.com/watch?v=XdciulFw8c0&t=78s)
4. Still tearing? Test copy paper on its own setting. If paper cuts clean, the original material or setting is the issue. If paper tears too, try a **new blade and a new mat** [H-TEAR-PDF].

**Other machines:**
- **Joy / Joy Xtra:** no dial; pick the material in Design Space. Joy uses its own Joy blade + Joy mats. Same clean/grip/pressure logic [H-JOY].
- **Explore 3 / 4 / 5:** no dial (software materials). Smart Materials can run matless, so check that the material isn't bowing [H-LOAD].
- **Maker family:** same Fine-Point logic. Fast Mode applies to the original Maker [H-MACH]. For delicate materials, Cricut suggests LightGrip + simpler/larger detail [H-M5].

**Your test-cut check (the user tests; we haven't):** 1" square in the top-left. Before unloading, lift a corner with the hook. Clean, crisp edge with no fuzz? Run the full job. Ragged again? New blade.
   - **Visual:** ▶️ [Dinosaur Mama: test cut first](https://www.youtube.com/watch?v=C3PwEaYQO08&t=0s)
**Prevention:** clean the blade before intricate jobs, put the clear cover back on the mat after every cut, and test-cut every new material.
**Contact Cricut support when:** it still tears **copy paper** with a new blade, a new mat and the right setting, **or** the black arms around the blade housing stick instead of springing back after a gentle press-and-release. That's the "arm buoyancy" check in Cricut's tearing guide → Member Care [H-TEAR-PDF].
**Fix from public sources:** [Cricut: cutting pressure issues](https://help.cricut.com/hc/en-us/articles/360009505313-Cutting-pressure-issues) + [JenniferMaker: cutting problems](https://jennifermaker.com/cricut-cutting-problems-tips-cleaner-cuts/). Not tested on a machine by us.
**Source check:** ✅ well-sourced (steps 1–4: matching setting, clean blade, grippy mat, less pressure, paper test, new blade; both agree). Foil-ball *method* is the makers' technique; Cricut says "remove debris from the blade and housing."
**Sources:** [H-PRESS] [H-TEAR-PDF] [H-M5] [H-MACH] [JM-CUTS] [R-RIP] [X-TEAR]

---

### S02 · Not cutting all the way through
**Coach:** "Super common, and the fix is usually one setting. Don't unload yet if it's still in the machine."
**Likely causes:**
1. Material setting doesn't match (dial vs. what's actually on the mat; Custom picked the wrong material)
2. Blade dirty, not fully seated (Clamp B not clicked) or worn
3. Pressure too low for this brand/thickness (needs More, +2–4 custom, or a second pass)
4. Mat not sticky, so the material lifts and the force is wasted
5. Material too thick for the blade (Deep-Point needed; or beyond Air 2's ~2 mm class)
6. Wrong blade type / non-Cricut blade
7. Machine or housing fault (rare)

**Triage:**
- Q1 "Is the mat still in the machine?" → yes = do Fix step 1 first.
- Q2 "What's the dial on, and what material is it exactly (brand + type)?"
- Q3 "Is the blade housing clicked into Clamp B, and how old is the blade?"

**Fix · Explore Air 2:**
1. Maker tip: **Not unloaded yet:** lift a corner with the hook. Not through? **Press Go again** and the machine re-cuts the same path. (Works only if you haven't unloaded. Maker blog + r/cricut agree; Cricut documents the same don't-unload resume for Knife Blade.) [R-DIDNT]
2. **Setting:** dial matches the material (or Custom + the exact match) [H-NOTCUT-PDF].
   - **Visual:** ▶️ [Cozy DIY Home: dial to Vinyl](https://www.youtube.com/watch?v=Yhyd6oldR_c&t=380s)
3. **Blade:** remove, clean (foil ball), reseat until Clamp B clicks. Premium Fine-Point for everyday materials. **Deep-Point** in its own housing for thick cardstock, foam or magnet [H-BLADES] [JM-CUTS].
   - **Visual:** ▶️ [Manny Maker: blade clean](https://www.youtube.com/watch?v=TS16emdPONg&t=0s) · ▶️ [JenniferMaker: close Clamp B](https://www.youtube.com/watch?v=WDauTtPdZq8&t=920s)
4. **Pressure:** set the Make-screen pressure to **More**, or raise the custom material pressure **2–4 points**, test, and repeat up to 2–3 times [H-NOTCUT-PDF] [H-PRESS].
   - **Visual:** ▶️ [JenniferMaker: material + More pressure screen](https://www.youtube.com/watch?v=6QEgxwqt_pM&t=450s)
5. **Paper test:** cut copy paper on its own setting. Paper fine = material/setting problem; paper also fails = blade/housing/machine.
6. New blade. Then a new housing [H-NOTCUT-PDF].
   - **Visual:** ▶️ [JenniferMaker: blade into Clamp B](https://www.youtube.com/watch?v=WDauTtPdZq8&t=901s)

**Other machines:**
- **Joy:** no dial; set the material in DS; Joy blade only. "More" pressure if offered [H-JOY].
- **Explore 3+ / Maker 3+:** no dial. Smart Materials run matless; regular materials still need a mat.
- **Maker:** has more cutting force. For truly thick materials (chipboard, balsa) the **Knife Blade is Maker-only**. Never suggest it for Air 2/Joy.

**Your test-cut check (the user tests; we haven't):** 1" square, lift a corner before unloading. Lifts clean off the liner, and the liner has only a light scratch? Run it.
**Prevention:** test-cut every new brand. Once a setting works, save it as a custom material ("+2 pressure, 2 passes").
**Contact Cricut support when:** it still only scores **copy paper** after the right setting, a new blade **and** a new housing [H-NOTCUT-PDF].
**Fix from public sources:** [Cricut: cutting pressure issues](https://help.cricut.com/hc/en-us/articles/360009505313-Cutting-pressure-issues) + [JenniferMaker: cutting problems](https://jennifermaker.com/cricut-cutting-problems-tips-cleaner-cuts/). Not tested on a machine by us.
**Source check:** ✅ well-sourced for steps 2–6 (Cricut's numbered order and JenniferMaker agree). Step 1 (press Go again) = ◐ community-agreed: [Sticky Vinyl AU](https://stickyvinyl.au/blogs/news/perfect-cuts-double-cuts) + [r/cricut](https://www.reddit.com/r/cricut/comments/smufzu/repeating_last_cut_question/); Cricut documents "don't unload, press Go to resume" only for Maker + Knife Blade ([Help](https://help.cricut.com/hc/en-us/articles/360009557673-Cricut-Maker-Resume-project)), so offer it as a maker tip.
**Sources:** [H-NOTCUT-PDF] [H-PRESS] [H-BLADES] [H-M5] [JM-CUTS] [R-NOTCUT] [R-NOTCUT2] [R-DIDNT]

---

### S03 · Cutting through the backing (liner/carrier)
**Coach:** "The blade's just a little too eager. Easy to dial back."
**Likely causes:**
1. **Iron-on loaded shiny side UP**, so the blade cuts the clear carrier instead of the vinyl (→ also S15)
2. Wrong preset (e.g., cardstock or Deep-Point setting on vinyl or sticker paper)
3. Pressure set to More, or the custom pressure was bumped too high earlier
4. Fresh blade cuts deeper than the old one did
5. Thin or bargain liner
6. Blade housing not seated (blade sits unevenly)

**Triage:**
- Q1 "Is this iron-on? Which side was against the mat, shiny or dull?" → shiny up = cause 1.
- Q2 "What setting and pressure did you pick?"
- Q3 "Is it a brand-new blade?"

**Fix · Explore Air 2:**
1. **Iron-on:** shiny carrier **down** on the mat, Mirror **ON**, dial **Iron-On**. Recut (S15).
   - **Visual:** 📷 D1-shiny-matte.jpg (our still) · ▶️ [Cricut: mirror + shiny side down](https://www.youtube.com/watch?v=eibClLy2YWM&t=45s) · ▶️ [JenniferMaker: upside-down = cut the carrier](https://www.youtube.com/watch?v=6QEgxwqt_pM&t=400s)
2. **Sticky vinyl / sticker paper:** dial **Vinyl** (or the exact Custom material), pressure **Less**; if custom, lower it **2–4 points** [H-PRESS].
3. Reseat the blade housing until it clicks.
   - **Visual:** ▶️ [JenniferMaker: close Clamp B](https://www.youtube.com/watch?v=WDauTtPdZq8&t=920s)

**Other machines:** same logic. Joy / Explore 3+ / Maker pick the material in software. **Smart Iron-On** can be matless on compatible machines, but still goes shiny side down [H-SPECIALTY].
**Your test-cut check (the user tests; we haven't):** 1" square. The liner should show only a faint scratch line and stay in one piece when you flex it.
**Prevention:** shiny-side mantra: **"Iron-on: shiny down, Mirror on. Vinyl: pretty side up, Mirror off."**
**Contact Cricut support when:** it cuts through liners on the correct preset at **Less** pressure with a correctly seated blade.
**Fix from public sources:** [Cricut: cutting pressure issues](https://help.cricut.com/hc/en-us/articles/360009505313-Cutting-pressure-issues) / [Everyday Iron-On](https://help.cricut.com/hc/en-us/articles/360009378254) + [JenniferMaker: cut the RIGHT side (video)](https://www.youtube.com/watch?v=11b_S6GD5Gk&t=0s). Not tested on a machine by us.
**Source check:** ✅ well-sourced (shiny side down + Mirror ON; Less pressure when the liner is cut).
**Sources:** [H-PRESS] [H-M5] [H-SPECIALTY] [H-EVERYDAY] [JM-CUTS]

---

### S04 · Mat slipping or material shifting mid-cut
**Coach:** "Your material wants a better hug from the mat. Two-minute fix."
**Likely causes:**
1. Mat has lost its stickiness (lint, fibers, old adhesive)
2. Material not pressed down (not burnished/brayered); curled roll stock
3. Wrong grip (LightGrip under heavy cardstock; StandardGrip under glitter cardstock)
4. Material hanging outside the sticky area, where it gets caught by the wide rubber rollers (fabric especially)
5. Mat loaded crooked or mat itself warped
6. (Explore 3+/Joy matless Smart Materials) material bowing during measuring

**Triage:**
- Q1 "Touch the empty part of the mat: still tacky, or like a sticky note that's lost its stick?"
- Q2 "Did the material stay inside the sticky grid?"
- Q3 "Which mat color, and what material?"

**Fix · Explore Air 2:**
1. **Revive the mat:** scrape off debris; for green/blue/purple mats, wash gently with lukewarm water and a drop of dish soap (or an alcohol-free baby wipe) and air-dry face-up. **Never wash a pink FabricGrip**; lift lint with tweezers or tape instead [C-MATCLEAN]. If it still won't grip, replace the mat [H-JOY].
2. **Burnish:** place the material top-left inside the grid, then press it flat with a brayer or scraper. Reverse-roll curly vinyl first.
   - **Visual:** ▶️ [Cricut: brayer the material flat](https://www.youtube.com/watch?v=eV8A5oxHAJQ&t=145s)
3. **Match the grip:** blue LightGrip = paper/vellum; green StandardGrip = vinyl, iron-on, most cardstock; purple StrongGrip = glitter cardstock / heavy; pink FabricGrip = fabric. Keep everything inside the adhesive area [H-MATS] [H-FABRIC].
   - **Visual:** ▶️ [Cricut: cutting mats](https://www.youtube.com/watch?v=XdciulFw8c0&t=0s)

**Other machines:** **Joy:** Joy mats, same rule; if the material won't stay put, brayer it or replace the mat [H-JOY]. **Explore 3+/Maker 3+/Joy matless:** if Smart Material isn't lying flat after measuring, unload, realign to the left guide and reload [H-LOAD].
**Your test-cut check (the user tests; we haven't):** small shape in a corner. Nothing moves, and the material stays flat when you lift the mat edge.
**Prevention:** clear cover back on after every cut; store mats flat; lint-roll before fabric/felt.
**Contact Cricut support when:** the mat keeps skewing even with a good load, and the roller bar looks loose, bent or uneven (see S05).
**Fix from public sources:** [Cricut blog: clean a mat](https://cricut.com/blog/how-to-clean-a-cricut-mat/) / [Which mats](https://help.cricut.com/hc/en-us/articles/360009373414) + [JenniferMaker: clean Cricut mats](https://jennifermaker.com/how-to-clean-cricut-mat/). Not tested on a machine by us.
**Source check:** ✅ well-sourced (baby wipe or lukewarm soapy water, air-dry, never wash pink FabricGrip; match the grip; burnish).
**Sources:** [C-MATCLEAN] [H-MATS] [H-FABRIC] [H-LOAD] [H-JOY] [JM-CUTS]

---

### S05 · Mat won't load, won't feed, or gets stuck
**Coach:** "Usually a timing or alignment thing. Let's get it rolling."
**Likely causes:**
1. Load pressed before Design Space sent the job (Load isn't blinking yet / machine not connected)
2. Mat not under both guides or not snug against the rollers
3. Machine thinks a mat is already loaded
4. Debris on the roller bar / carriage path
5. Power or firmware state (red light; see table)
6. No room behind the machine for the mat to travel out the back
7. Bent or warped mat
8. Roller bar loose, damaged or uneven (hardware)

**Triage:**
- Q1 "What color is the power light: white, blue, red, blinking red, purple?"
- Q2 "Is the Load (double-arrow) button blinking when you press it?"
- Q3 "Does the roller bar turn at all?"

**Fix · Explore Air 2:**
1. **Timing:** in Design Space, go to Make → Continue until it says load the mat. **Wait for the Load button to blink.** Mat under both guides, top edge kissing the rollers, hold **bottom-center** and give a gentle push as the rollers grab [H-LOAD].
   - **Visual:** ▶️ [JenniferMaker: under both guides](https://www.youtube.com/watch?v=WDauTtPdZq8&t=2084s) · ▶️ [JenniferMaker: Load then Go lights](https://www.youtube.com/watch?v=WDauTtPdZq8&t=2123s)
2. **Reset the state:** press Unload, then Load again. If the light is red when loading, power off and slide the carriage across the bar 3–4 times by hand to clear debris, then power on and retry [H-MACH] [IFIXIT].
3. **Clearance:** leave space behind the machine, and keep power/USB cords out of the mat's exit path (a mat can knock a cord loose) [H-MACH].
4. **Mat stuck mid-job:** press Unload. If it won't release, power off and ease the mat out by hand with **steady, even force** (no yanking at an angle) [H-JOY].

**Light-color quick map (Explore/Maker) [H-MACH]:** blue = Bluetooth connected (normal) · solid red + white Load = firmware update needed · solid red, nothing else lit = power issue (try a wall outlet, the original Cricut cord) · blinking red at power-on or during a firmware update = Member Care · purple = Bluetooth + error (treat as red).
**Other machines:** **Joy / Joy Xtra:** align against **both** left guides, push firmly into the rollers on both sides; a slightly crooked load can bend the mat [H-JOY]. **Explore 3+/Maker 3+:** endless rolling = dirty material sensors (clean per Cricut) [H-MACH].
**Your test-cut check (the user tests; we haven't):** mat loads straight on the first try and the Go button blinks.
**Prevention:** wait for the blink, hold bottom-center, mats stored flat.
**Contact Cricut support when:** blinking red at power-on or during firmware · roller bar won't turn with a white light (take a short video) · roller bar loose/bent/uneven (photo) · mat still loads crooked after the guide + bottom-center method [H-LOAD] [H-MACH].
**Fix from public sources:** [Cricut: load/unload mats](https://help.cricut.com/hc/en-us/articles/360009554073) + [JenniferMaker: under both guides (video)](https://www.youtube.com/watch?v=WDauTtPdZq8&t=2084s). Not tested on a machine by us.
**Source check:** ✅ well-sourced for steps 1, 3, 4. Step 2 (power off, slide carriage by hand) = Cricut [machine troubleshooting](https://help.cricut.com/hc/en-us/articles/26322117447703) + [iFixit](https://www.ifixit.com/Wiki/Cricut_Explore_Air_2_Troubleshooting) ✅.
**Sources:** [H-LOAD] [H-MACH] [H-JOY] [H-JOYLOAD] [IFIXIT] [MM-AIR2]

---

### S06 · Print Then Cut: sensor can't read marks, or the cut is offset
**Coach:** "The sensor is picky about light and paper, not about you. Three quick things."
**Likely causes:**
1. Glare: direct lamp, window or overhead light on the sensor
2. Glossy, glitter, metallic, dark or busy paper (**Air 2 = matte white or transparent only**)
3. Printer scaled the page ("fit to page"/"shrink"), wrong orientation, narrow margins, low ink
4. Sheet not in the **top-left** of the mat, wrinkled, or the mat bent/smudged near the marks
5. Dirty sensor window under the carriage
6. Calibration off (cuts land offset from the print)
7. Layer set to Print Then Cut by mistake (you only wanted a cut)
8. Sensor light never turns on (hardware)

**Triage:**
- Q1 "Exact error: can't read marks, or reads them but cuts in the wrong spot?" → offset = cause 6.
- Q2 "What paper (glossy/matte, white/colored)?"
- Q3 "Where's the nearest lamp or window?"

**Fix · Explore Air 2:**
1. **Light + paper:** turn off or move direct light; use **matte white** printable [H-PTC].
   - **Visual:** ▶️ [Kim Byers: harsh light](https://www.youtube.com/watch?v=xcDqLk3zEMs&t=127s)
2. **Print right:** portrait, 100% scale (no fit-to-page), one page per sheet, no edge or borderless printing, not centered [H-PTC].
   - **Visual:** ▶️ [Cricut: sensor marks on the print](https://www.youtube.com/watch?v=OFLdFcGbnoU&t=214s)
3. **Place right:** printed sheet **top-left**, aligned to the grid, smooth; mat snug under the guides. Bent mat? Rotate it 180° and use the other end [H-PTC].
   - **Visual:** ▶️ [Kim Byers: upper-corner placement](https://www.youtube.com/watch?v=xcDqLk3zEMs&t=250s)
4. Gently sweep the sensor window with a clean, dry, soft brush [H-PTC].
   - **Visual:** ▶️ [Kim Byers: dust tip](https://www.youtube.com/watch?v=xcDqLk3zEMs&t=180s)
5. **Offset cuts:** run the Print Then Cut calibration (Settings → Machines → Calibration → Print Then Cut) [H-PTCCAL].
   - **Visual:** ▶️ [Kim Byers: calibrate demo](https://www.youtube.com/watch?v=xcDqLk3zEMs&t=214s) · ▶️ [Cricut: PTC calibration](https://www.youtube.com/watch?v=bkBOrIQzs10&t=0s)
6. **Didn't want PTC?** Change the layer's Operation to a plain cut [H-PTC].
7. Cricut's advice: (single source, chat only, never on a card) a strip of matte transparent tape over glossy marks can help [H-PTC].

**Other machines:** **Explore 3 / Maker 3 / Maker / Venture / Joy Xtra:** white, light-colored and simple patterns allowed; Cricut-brand gold/silver/holo printables OK [H-PTC]. **Joy Xtra:** top-left like Explore. **Venture:** **bottom-left** [H-PTC]. **Original Joy:** no Print Then Cut at all, so offer kiss-cut vinyl stickers instead.
**Your test-cut check (the user tests; we haven't):** one small sticker sheet (2–3 shapes). The sensor finds all marks, and the cut line hugs the print evenly.
**Prevention:** calibrate after moving the machine or changing printers; keep a "PTC lamp position" (side light, not overhead).
**Contact Cricut support when:** the sensor light under the carriage **never turns on** during the scan [H-PTC].
**Fix from public sources:** [Cricut: can't read sensor marks](https://help.cricut.com/hc/en-us/articles/360009426434) + [Kim Byers: 8 Print Then Cut fixes (video)](https://www.youtube.com/watch?v=xcDqLk3zEMs&t=127s). Not tested on a machine by us.
**Source check:** ✅ well-sourced (glare, paper, 100% print, top-left, clean sensor, calibration). The matte-tape-over-glossy-marks trick is Cricut-only ⚠ (single source), moved out of the top 3 to step 7 and labelled "Cricut's advice:".
**Sources:** [H-PTC] [H-PTCCAL] [JM-CUTS]

---

### S07 · Iron-on (HTV) lifted or peeled after washing
**Coach:** "Totally rescuable. Iron-on can usually be re-pressed. Let's find what it was missing."
**Likely causes:**
1. Not enough pressure / soft surface (ironing board, cushioned table)
2. No preheat, so hidden moisture in the fabric
3. Washed too soon (less than 24 h) or washed hot / right-side out / with fabric softener
4. Peeled at the wrong temperature (cool-peel material peeled hot, or the reverse)
5. Too little heat or time (or an iron "glided" instead of pressed)
6. Garment not prewashed (finishing chemicals)
7. Wrong pairing: SportFlex on cotton, or something layered on top of glitter/foil/holo

**Triage:**
- Q1 "What iron-on brand/type, and what did you press with (EasyPress, iron, clamshell)?"
- Q2 "What surface did you press on?"
- Q3 "How long before the first wash, and how was it washed?"

**Fix:**
1. **Re-press:** liner (or a pressing sheet) back over the lifted area. Press at the Heat Guide setting for your material on a **firm, flat surface**. Cricut's instruction is to re-apply using the full instructions [H-SPECIALTY] [H-EVERYDAY]. Starting points:.
2. **Next time:** prewash with no softener; preheat the blank (~5 s EasyPress / 10–15 s iron); press the full time; peel per the material (Cricut Everyday & Glitter = **cool**) [H-QRC] [H-EPRS].
3. **Care:** wait 24 h; wash and dry inside out; no bleach; no fabric softener [H-QRC] [C-WASHFAQ] [SISER-EW].

**Machine note:** cutting machine doesn't matter here. It's a press problem.
**Your press test (the user tests; we haven't):** press a small scrap on a hidden spot (hem). Once cool, try to lift an edge with a fingernail. It should stay put, with the fabric texture showing through the vinyl.
**Prevention:** firm table (not an ironing board), a timer, peel per the material, the 24-hour rule.
**Contact Cricut support when:** EasyPress won't heat, errors out, or won't hold temp (point to Cricut's EasyPress troubleshooting) [H-EPTS].
**Fix from public sources:** [Cricut: iron-on troubleshooting](https://help.cricut.com/hc/en-us/articles/360010351874) / [peeling after first wash](https://cricut.com/blog/gb/faqs/why-is-my-vinyl-peeling-off-after-the-first-wash/) + [Hey, Let's Make Stuff: get iron-on to stick](https://heyletsmakestuff.com/get-iron-on-to-stick/) · [Siser EasyWeed care](https://siserstore.com/pages/easyweed). Not tested on a machine by us.
**Source check:** ✅ well-sourced (firm surface, full time, correct peel, re-press, 24 h + inside-out + no softener).
**Sources:** [H-SPECIALTY] [H-EVERYDAY] [H-QRC] [H-EPRS] [C-WASHFAQ] [R-PEEL] [SISER-EW] [H-EPTS]

---

### S08 · Iron-on won't stick while pressing
**Coach:** "Iron-on is just heat + pressure + time. One of the three is short. We'll find which."
**Likely causes:**
1. Plate didn't make full contact (seams, zippers, buttons, thick hems)
2. Soft surface (ironing board / plastic table)
3. Temp, time or pressure below spec, or not the full time
4. Peeled too early (cool-peel material peeled hot)
5. Design placed upside-down (liner touching the shirt instead of facing up)
6. Incompatible base: SportFlex on cotton, water-repellent or coated fabric, heat-sensitive synthetics at a low setting

**Triage:**
- Q1 "Which side was touching the shirt, the sticky dull side or the shiny liner?"
- Q2 "What press, temp, time, and what surface?"
- Q3 "Is it lifting everywhere or only near a seam/zipper?"

**Fix:**
1. **Orientation:** liner (shiny) side **up**, sticky side on the fabric [H-EVERYDAY].
2. **Setup:** firm, flat, heat-safe surface; flatten the area (a pressing pillow inside the shirt lifts seams out of the way); settings from the Heat Guide [H-HEATTS].
3. **Re-press** another **10–15 s**; let a cool-peel material fully cool before peeling [H-IRONTS] [H-EPRS].

**Machine note:** EasyPress Mini fits seams and odd spots; add a few extra seconds focused on the seam [H-EPFAQ].
**Your press test (the user tests; we haven't):** a scrap square on the hem; cool; fingernail edge test.
**Prevention:** test-press before the real blank; check the fabric content label.
**Contact Cricut support when:** the press heat is suspect (won't reach or hold temperature) [H-EPTS].
**Fix from public sources:** [Cricut: troubleshooting heat transfer results](https://help.cricut.com/hc/en-us/articles/42141017622807) + [Hey, Let's Make Stuff](https://heyletsmakestuff.com/get-iron-on-to-stick/) · [iCraftVinyl: why HTV isn't adhering](https://svg.icraftvinyl.com/blogs/icraft-today/common-heat-transfer-vinyl-mistakes-why-your-htv-isn-t-adhering). Not tested on a machine by us.
**Source check:** ✅ well-sourced (firm surface, full plate contact/clear seams, settings, re-press). Note: Cricut says re-press 10–15 s; one UK maker blog says only 2–3 s more. We follow Cricut's 10–15 s for Cricut materials.
**Sources:** [H-IRONTS] [H-HEATTS] [H-EVERYDAY] [H-EPRS] [H-EPFAQ] [H-SPECIALTY]

---

### S09 · Weeding is a fight / tiny pieces come up with the waste
**Coach:** "Weeding slow is how pros look expensive. And if it's fighting you, the cut is usually the culprit."
**Likely causes:**
1. Cut didn't fully go through (→ S02)
2. Design too small or thin for the material (tiny letters, hairline gaps)
3. Waste pulled at the wrong angle or speed; no weeding box to start from
4. Cold or stiff vinyl; glitter iron-on cut lines hard to see
5. Mat/blade issues causing rough edges (→ S01)

**Triage:**
- Q1 "Does the waste lift cleanly anywhere, or does it fight everywhere?" → everywhere = S02.
- Q2 "How tall are the smallest letters?"
- Q3 "Sticky vinyl or iron-on?"

**Fix · Explore Air 2:**
1. **Check the cut first** (lift a corner). Not through → S02.
2. Maker tip: **Weeding box:** add a rectangle around the design and Attach, so you get a clean starting corner and less waste [HLMS-BOX].
3. **Tiny sticky-vinyl bits → reverse weed:** put transfer tape over the *unweeded* vinyl, burnish, flip, peel the backing off, then weed the waste off the tape [JM-REVERSE].
   - **Visual:** ▶️ [Corinne Blackstone: reverse weed small fonts](https://www.youtube.com/watch?v=NuQZmZ9sw7c&t=0s)
4. Peel waste low and slow; use tweezers or the hook for counters (O, e, a); good light. Slightly warm vinyl is easier to weed (warm, not hot) [PP-WEED].
   - **Visual:** ▶️ [JenniferMaker: weeding adhesive vinyl](https://www.youtube.com/watch?v=WW01bL-onHU&t=720s)
5. Design fix: scale up, or thicken thin strokes (Offset) before recutting.

**Other machines:** same. **Joy** users often cut very small labels; reverse weeding helps most there.
**Your test-cut check (the user tests; we haven't):** cut the smallest letter of the design alone at its real size; weed it. Clean? Cut the full design.
**Prevention:** test the tiniest detail first; weeding box on every cut.
**Contact Cricut support when:** n/a (material/design issue). Use S01/S02 escalation only if the cut itself is faulty.
**Fix from public sources:** [Cricut Vinyl instructions (weeding)](https://help.cricut.com/hc/en-us/articles/7054720637719-Cricut-Vinyl) + [JenniferMaker: reverse weed](https://jennifermaker.com/reverse-weed-vinyl/) · [Hello Creative Family: weeding tips](https://hellocreativefamily.com/10-cricut-weeding-tips-vinyl-and-htv/). Not tested on a machine by us.
**Source check:** ✅ well-sourced for check-the-cut, reverse weed, low-and-slow tools. Weeding box = ◐ maker-only ([Hey, Let's Make Stuff](https://heyletsmakestuff.com/weeding-box/)); warm-vinyl tip = ⚠ single maker source ([Printable Press](https://www.printablepress.com/how-to-weed-vinyl/)).
**Sources:** [JM-REVERSE] [JM-CUTS] [HLMS-BOX] [PP-WEED] [R-WEED] [H-SPECIALTY]

---

### S10 · Sticky vinyl won't transfer (stays on the liner, or won't leave the tape)
**Coach:** "Classic tug-of-war between tape, vinyl and surface. Burnish wins it."
**Likely causes:**
1. Not burnished enough (front **and** back)
2. Wrong tape: textured/glitter/shimmer vinyl needs StrongGrip tape; StrongGrip on smooth vinyl is too grabby
3. Surface dirty, oily, textured or cold
4. Peel angle: peeling the tape up and away instead of back along itself
5. Reused or stale tape
6. (Rare) not cut through → S02

**Triage:**
- Q1 "Which step fails: vinyl stays on the paper backing, or vinyl won't let go of the tape on your surface?"
- Q2 "Smooth vinyl or glitter/shimmer/textured? Which transfer tape?"
- Q3 "What surface (glass, painted wall, wood, tumbler)?"

**Fix:**
1. **Burnish** the tape onto the design with a scraper from the center out, flip and burnish the back [H-TAPE].
   - **Visual:** ▶️ [Cricut: transfer tape tips](https://www.youtube.com/watch?v=qUdLaX53oHk&t=0s) · ▶️ [JenniferMaker: transfer tape](https://www.youtube.com/watch?v=WW01bL-onHU&t=900s)
2. **Peel the liner, not the tape:** lay it tape-side down and peel the backing away. If vinyl stays on the backing, lay it back down, burnish again, peel again [H-TAPE].
3. **Surface:** clean and dry (rubbing alcohol on glass/plastic). Burnish the design onto the surface, then peel the tape back **at a sharp, low angle**. If vinyl lifts, re-burnish and peel again [H-TAPE].
- Tape too sticky? Cricut says StrongGrip is too strong for most smooth vinyl [H-TAPE]. Community trick: pat regular tape on a clean cotton shirt once to lower tack [R-GLITTERTAPE].

**Machine note:** cutting machine doesn't matter.
**Your test-cut check (the user tests; we haven't):** transfer one small cut letter to a scrap of the same surface before doing the whole design.
**Prevention:** match the tape to the vinyl finish; fresh tape; clean surface.
**Contact Cricut support when:** n/a.
**Fix from public sources:** [Cricut: transfer tape instructions](https://help.cricut.com/hc/en-us/articles/360009430794) + [Craft'n Cadabra: vinyl won't stick to tape](https://craftncadabra.com/cttblog/ctt-guide-why-wont-my-vinyl-stick-to-transfer-tape). Not tested on a machine by us.
**Source check:** ✅ well-sourced (burnish front and back, peel the liner away, re-burnish and retry, clean surface, sharp low peel angle).
**Sources:** [H-TAPE] [R-GLITTERTAPE]

---

### S11 · Cardstock tearing
**Coach:** "Cardstock is fussy. Paper quality, blade and grip matter more here than anywhere."
**Likely causes:**
1. Mat not sticky enough, so the cardstock lifts and tears
2. Blade dulled (cardstock wears blades fastest)
3. Setting: intricate design on a regular cardstock preset; Fast Mode
4. Paper quality (short, weak fibers) or textured side down
5. Design too intricate or small
6. Tearing on *unload*: peeling paper off the mat instead of the mat off the paper

**Triage:**
- Q1 "Did it tear during the cut or when you peeled it off the mat?" → peeling = cause 6.
- Q2 "Which setting and which mat?"
- Q3 "Brand and weight of the cardstock?"

**Fix · Explore Air 2:**
1. **Setting:** Custom → the closest cardstock material; for lacy designs try the intricate-cuts cardstock setting; Fast Mode off [JM-CUTS] [JM-INTRICATE].
2. **Blade + grip:** foil-ball clean (or a new blade); green StandardGrip (blue LightGrip for thin paper; purple StrongGrip for glitter cardstock); brayer it flat; textured side **up** [JM-CUTS] [H-MATS] [H-CARDSTOCK].
3. **Unload right:** flip the mat face-down and curl the **mat** away from the cardstock [CRICUT-MATS-VIDEO].
   - **Visual:** ▶️ [Cricut: turn over and pull the mat up](https://www.youtube.com/watch?v=XdciulFw8c0&t=82s) · ▶️ [Hey Lets Make Stuff: removing cardstock](https://www.youtube.com/watch?v=LmNDoKle-EE&t=0s)
- Still tears? Try a better cardstock brand; simplify or enlarge the design. Thick chipboard on Air 2: Deep-Point, ≤~2 mm.

**Other machines:** **Maker:** Knife blade for chipboard/basswood (Maker only). **Joy:** keep cardstock designs small; Joy Card Mat for insert cards.
**Your test-cut check (the user tests; we haven't):** cut the most intricate 1" section alone; flip-peel; no tears = full cut.
**Prevention:** blade reserved for paper, mat cleaned regularly, flip-peel every time.
**Contact Cricut support when:** see S01 (tears copy paper with a new blade + mat).
**Fix from public sources:** [Cricut Cardstock instructions](https://help.cricut.com/hc/en-us/articles/20870548437527-Cricut-Cardstock-Instructions) + [JenniferMaker: intricate cuts](https://jennifermaker.com/intricate-cuts-on-cricut/) · [Hey, Let's Make Stuff: removing cardstock (video)](https://www.youtube.com/watch?v=LmNDoKle-EE&t=0s). Not tested on a machine by us.
**Source check:** ✅ well-sourced (setting, sharp clean blade, grippy mat, flip-peel the mat).
**Sources:** [JM-CUTS] [JM-INTRICATE] [H-CARDSTOCK] [H-MATS] [H-PRESS] [CRICUT-MATS-VIDEO]

---

### S12 · Grinding noise, loud knocking, or the carriage stalls  ⛔ STOP-FIRST · no sales line
**Coach:** "Let's pause and power it off. Grinding is the machine's job to explain, not yours. We'll do a 2-minute safe check, and if it's still noisy, that's a support ticket, not a you-problem."
**Likely causes:**
1. Something in the carriage path (scrap, vinyl curl, a pen cap) or the mat hitting a wall behind the machine
2. Fast Mode on (Air 2 / original Maker is simply louder in Fast Mode)
3. Pressure set very high
4. Not using the machine's original power cord (wrong voltage can cause grinding)
5. Loose or broken belt / carriage misalignment (hardware)
6. Carriage hitting the side of the machine when you press Go (hardware)
7. Grease needs service (Member Care sends Cricut's own grease kit)

**Triage:**
- Q1 "When does it happen: power-on, loading, or mid-cut?"
- Q2 "Is Fast Mode on? Is that the cord that came with the machine?"
- Q3 "Has it cut normally before, or is it new out of the box?" → new = Member Care right away.

**Fix · Explore Air 2 (safe checks only):**
1. **Power off and unplug.** Remove the mat. Look along the carriage path and behind the machine for scraps or obstructions; clear them. Leave room behind the machine [H-MACH].
2. Cricut's advice: check you're using the **original power cord**. Turn **Fast Mode off**; lower the material pressure **2–4 points** [H-MACH].
3. Retry with a simple copy-paper cut.
- ❌ Don't open the machine. ❌ Don't wipe the grease off the carriage bar. ❌ Don't add any non-Cricut grease or oil. ❌ Don't touch the belt/gears at the back [H-CLEAN] [H-GREASE-PDF] [SMQ-CLEAN].

**Other machines:** same safe checks. Maker: Knife Blade can stall on uneven material, so follow the on-screen clear-and-resume prompt [H-MACH].
**Your test-cut check (the user tests; we haven't):** a 1" paper square runs smoothly at normal speed with no grind.
**Prevention:** keep the carriage path clear; normal speed for detailed or thick jobs; original cord only.
**Contact Cricut support when (most S12 cases end here):** any visible belt/carriage damage · the carriage slams the side · noise on a **new** machine · grinding persists after the checks above. **Record a short video with sound** for Member Care; they can send an approved grease packet [H-MACH] [H-GREASE-PDF].
**Escalation script (BOT_GATES):** "This sounds like hardware territory, not a you-problem. Next step: Cricut Member Care via help.cricut.com. A short video with sound helps a lot. The serial is on the machine. While that's in progress, I can coach design practice on the canvas."
**Fix from public sources:** [Cricut: machine troubleshooting, Explore & Maker](https://help.cricut.com/hc/en-us/articles/26322117447703) + [r/cricut: Explore 2 loud noise fixed](https://www.reddit.com/r/cricut/comments/xjn5vj/cricut_explore_2_loud_noise_fixed/) · [iFixit](https://www.ifixit.com/Wiki/Cricut_Explore_Air_2_Troubleshooting). Not tested on a machine by us.
**Source check:** ✅ well-sourced for clear the path and Fast Mode off, then escalate. "Original power cord" = ⚠ Cricut-only, labelled "Cricut's advice:" in step 2. Grease/teardown deliberately excluded (Member Care sends Cricut's own kit).
**Sources:** [H-MACH] [H-CLEAN] [H-GREASE-PDF] [SMQ-CLEAN] [R-GRIND] [R-LOUD] [IFIXIT]

---

### S13 · Design Space doesn't detect the machine (Bluetooth or USB)
**Coach:** "Connection gremlins. Not you. Let's run the 60-second reset."
**Likely causes:**
1. Machine paired or connected to another phone/computer
2. Computer/phone hasn't given Design Space Bluetooth permission (macOS Sonoma+, Android 13+), or Windows 11 discovery hiding it
3. Out of range (>10–15 ft) or Bluetooth busy (headphones, streaming, calls)
4. Design Space outdated / firmware update pending (solid red + white Load)
5. Pairing method wrong for the model (Air 2 pairs in OS settings with PIN 0000; BLE models must **not** be paired in OS settings)
6. USB quirk (some AMD Ryzen Windows PCs)

**Triage:**
- Q1 "Computer or phone, and which OS?"
- Q2 "Has this machine ever connected to another device?"
- Q3 "Bluetooth or USB cable?"

**Fix · Explore Air 2:**
1. **Clean slate:** unpair the machine from **all** devices; unplug the machine; restart the computer/phone; plug in and power on; stay within 15 ft [H-BT].
2. **Pair in the OS:** Windows: Settings → Bluetooth → Add device → Bluetooth (on Windows 11 choose "Show all devices"/Advanced discovery); Mac: allow Design Space under Privacy & Security → Bluetooth; Android 13+: allow Nearby devices. Pick the machine's Bluetooth code (printed near the serial); PIN **0000** if asked [H-BT] [H-BTAIR2].
   - **Visual:** ▶️ [Trebushea: Bluetooth setup Short](https://www.youtube.com/watch?v=sMk-YrzexvY&t=0s)
3. **Fallback:** plug in the included **USB cable**; that's pro reliability, not failure. Update Design Space and firmware if prompted [H-BT].

**Other machines:** **Joy / Joy 2 / Joy Xtra:** Bluetooth **only** (no USB) [H-BT]. **Explore 5 / Joy 2 (BLE):** don't pair in OS settings. Use the Design Space machine picker; disconnect from other DS instances; power-cycle [H-BT]. **Explore 4 / Maker 4:** may show as "Bluetooth Device"/"Generic". Connect to that [H-BT]. **Explore 3:** see Cricut's Explore 3 Bluetooth note [H-BT].
**Your test-cut check (the user tests; we haven't):** machine shows "Connected" in Design Space; run a 1" paper square.
**Prevention:** one device at a time; keep the USB cable handy (Explore/Maker).
**Contact Cricut support when:** blinking red at power-on, a firmware update fails, or none of the steps connect on a second device [H-MACH] [H-BT].
**Fix from public sources:** [Cricut: Bluetooth and USB connection help](https://help.cricut.com/hc/en-us/articles/6581830148759) + [iFixit: Bluetooth won't connect](https://www.ifixit.com/Wiki/Cricut_Explore_Air_2_Troubleshooting). Not tested on a machine by us.
**Source check:** ✅ well-sourced (unpair everywhere, 10–15 ft, PIN 0000 on Air 2, USB fallback).
**Sources:** [H-BT] [H-BTAIR2] [H-MACH] [JM-CUTS] [MM-AIR2]

---

### S14 · Cut the wrong size or in the wrong place
**Coach:** "Design Space moved things around on you. Happens to everyone. One button keeps it put."
**Likely causes:**
1. Pieces not **Attached**, so Design Space rearranges them on the mat preview
2. Didn't check or drag the position on the mat preview (Prepare screen)
3. Material size set wrong, or material not placed where the preview shows (top-left)
4. Uploaded SVG came in at the wrong scale (72 vs 96 dpi: ~133% or ~75%)
5. Design bigger than the cut area (Air 2: ~11.5" wide on a 12" mat)
6. Mat loaded crooked, so the cut is skewed
7. Print Then Cut calibration (→ S06)

**Triage:**
- Q1 "Wrong size, or right size in the wrong spot?"
- Q2 "Was it an uploaded SVG? What size did Design Space show?"
- Q3 "Did the mat preview show it where you expected?"

**Fix · Explore Air 2:**
1. **Attach** pieces that must keep their layout (select → Attach) before Make It [H-ATTACH].
2. On the **Prepare/mat preview**, drag the design to where the material actually sits, and set the right material size [H-PREPARE] [H-MATSIZE].
3. Maker tip: **Size:** with the lock on, type the exact width/height. For uploads, export SVGs with real inch/mm units, or just retype the size after upload [ITS-SVG] [R-SVG].

**Other machines:** **Joy:** max width ~4.5" (Joy Xtra ~8.5"); oversized designs split or won't fit. **Smart Materials (matless)** on Explore 3+/Maker 3+/Joy: material length setting matters.
**Your test-cut check (the user tests; we haven't):** cut a 1" square in the exact mat-preview spot; measure it with a ruler. 1.00" in the right spot = go.
**Prevention:** Attach → check mat preview → measure the first cut of any upload.
**Contact Cricut support when:** with a straight load and correct settings, the cut is **consistently offset** from the mat preview [JM-CUTS (author reply)].
**Fix from public sources:** [Cricut: how to use Attach](https://help.cricut.com/hc/en-us/articles/360009380514) + [Sarah Maker: Attach in Design Space](https://sarahmaker.com/attach-cricut-design-space/). Not tested on a machine by us.
**Source check:** ✅ well-sourced for Attach + mat-preview placement. 72-vs-96-dpi size fix = ◐ community ([imagetosvg](https://imagetosvg.com/how-to/fix-svg-wrong-size-cricut) + [r/cricut](https://www.reddit.com/r/cricut/comments/y74hae/question_about_design_space_and_svg/)); no Cricut page found.
**Sources:** [H-ATTACH] [H-PREPARE] [H-MATSIZE] [ITS-SVG] [R-SVG] [JM-CUTS]

---

### S15 · Mirror forgotten on iron-on (backwards on the shirt) / carrier sliced
**Coach:** "Classic iron-on plot twist. Everyone does this once. The next cut fixes it."
**Likely causes:**
1. Mirror OFF on the mat (each mat needs its own Mirror)
2. Double flip: mirrored on the canvas **and** Auto Mirror flipped it back
3. Iron-on loaded shiny side up (carrier sliced; → S03)
4. Auto Mirror changed after the Air 2 dial or material was changed

**Triage:**
- Q1 "Is it already pressed on the shirt?"
- Q2 "On the mat preview, did the text read backwards before you hit Go?"
- Q3 "Which side was against the mat, shiny or dull?"

**Fix · all machines:**
1. **Already pressed:** it can't be flipped in place. Treat this shirt as a practice shirt (you learned the #1 iron-on rule!) and recut [PP-MIRROR] [TWC-HTV].
2. **Recut:** Make It → Prepare → **Mirror ON for every iron-on mat**. Mirror in **one** place only (don't flip on the canvas too) [H-MIRROR] [H-AUTOMIRROR] [R-MIRROR].
   - **Visual:** ▶️ [JenniferMaker: Mirror toggle](https://www.youtube.com/watch?v=6QEgxwqt_pM&t=372s)
3. **Load:** shiny carrier **down** on the mat; dial **Iron-On** (Air 2) or the exact iron-on material. Preview must read **backwards** [H-EVERYDAY].
   - **Visual:** 📷 D1-shiny-matte.jpg (our still) · ▶️ [Cricut: mirror + shiny side down](https://www.youtube.com/watch?v=eibClLy2YWM&t=45s)

**Other machines:** identical rule on Joy/Explore 3+/Maker; Smart Iron-On may load matless on compatible machines (still shiny down) [H-SPECIALTY].
**Your test-cut check (the user tests; we haven't):** cut one small letter "R" (it shows mirroring instantly); weed; hold it shiny-side up. Reads right? Cut the full design.
**Prevention:** "**Backwards on screen = right on the shirt.**" Mirror check is the last thing before Go.
**Contact Cricut support when:** n/a.
**Fix from public sources:** [Cricut: how to mirror](https://help.cricut.com/hc/en-us/articles/360009432354) / [Auto Mirror](https://help.cricut.com/hc/en-us/articles/27772323493655) + [JenniferMaker: Mirror toggle (video)](https://www.youtube.com/watch?v=6QEgxwqt_pM&t=372s). Not tested on a machine by us.
**Source check:** ✅ well-sourced for steps 1–3. Step 1 (a pressed backwards design can't be fixed in place; recut with Mirror ON): [Printable Press: mirror for HTV](https://www.printablepress.com/how-to-mirror-image-for-htv/) + [TeckWrap Craft: which side faces down](https://teckwrapcraft.com/blogs/tips/iron-on-vinyl-which-side-faces-down-the-cutting-mat) agree. The "reheat and peel it off" idea was ⚠ not well-sourced and has been removed.
**Sources:** [H-MIRROR] [H-AUTOMIRROR] [H-EVERYDAY] [H-SPECIALTY] [R-MIRROR] [JM-CUTS] [PP-MIRROR] [TWC-HTV]

---

## 6. Sources (all accessed 2026-10-08)
**Cricut Help Center / Cricut (facts paraphrased; link only):**
- [H-PRESS] Cutting pressure issues: https://help.cricut.com/hc/en-us/articles/360009505313-Cutting-pressure-issues
- [H-TEAR-PDF] Machine tearing or dragging (PDF): https://d2e2oszluhwxlw.cloudfront.net/learn/pdfs/design-space/tearing-or-dragging-material-troubleshooting.pdf
- [H-NOTCUT-PDF] Machine not cutting through my material (PDF): https://d2e2oszluhwxlw.cloudfront.net/learn/pdfs/design-space/not-cutting-material-troubleshooting.pdf
- [H-MACH] Machine Troubleshooting, Explore & Maker: https://help.cricut.com/hc/en-us/articles/26322117447703-Machine-Troubleshooting-Cricut-Explore-and-Cricut-Maker-series-machines
- [H-JOY] Machine Troubleshooting, Joy series: https://help.cricut.com/hc/en-us/articles/26322182479639-Machine-Troubleshooting-Cricut-Joy-series-machines
- [H-JOYLOAD] Load/unload, Joy series: https://help.cricut.com/hc/en-us/articles/360040664714
- [H-M5] Troubleshoot Maker 5 projects: https://help.cricut.com/hc/en-us/articles/42954604333463
- [H-LOAD] Load/unload mats, Explore & Maker: https://help.cricut.com/hc/en-us/articles/360009554073
- [H-FABRIC] Fabric caught under rollers: https://help.cricut.com/hc/en-us/articles/360009501873
- [H-MATS] Which mats can I use: https://help.cricut.com/hc/en-us/articles/360009373414
- [H-BLADES] All about blades: https://help.cricut.com/hc/en-us/articles/360009432294
- [H-CARDSTOCK] Cricut Cardstock instructions: https://help.cricut.com/hc/en-us/articles/20870548437527-Cricut-Cardstock-Instructions
- [H-PTC] Machine cannot read the cut sensor marks: https://help.cricut.com/hc/en-us/articles/360009426434
- [H-PTCCAL] Calibrating for Print Then Cut: https://help.cricut.com/hc/en-us/articles/360009424974
- [H-BT] Bluetooth and USB Connection Help (edited Sep 3, 2026): https://help.cricut.com/hc/en-us/articles/6581830148759
- [H-BTAIR2] Pair Explore Air 2 via Bluetooth: https://help.cricut.com/hc/en-us/articles/360009380974
- [H-ATTACH] How to use Attach: https://help.cricut.com/hc/en-us/articles/360009380514
- [H-PREPARE] Prepare screen guide: https://help.cricut.com/hc/en-us/articles/26762475430167
- [H-MATSIZE] Change mat or material size: https://help.cricut.com/hc/en-us/articles/360009504333
- [H-MIRROR] How to mirror: https://help.cricut.com/hc/en-us/articles/360009432354
- [H-AUTOMIRROR] Auto Mirror: https://help.cricut.com/hc/en-us/articles/27772323493655
- [H-EVERYDAY] Everyday Iron-On: https://help.cricut.com/hc/en-us/articles/360009378254
- [H-SPECIALTY] Specialty Iron-On: https://help.cricut.com/hc/en-us/articles/26761451036439
- [H-IRONTS] Iron-On Troubleshooting: https://help.cricut.com/hc/en-us/articles/360010351874
- [H-HEATTS] Troubleshooting heat transfer results: https://help.cricut.com/hc/en-us/articles/42141017622807
- [H-EPRS] EasyPress recommended settings: https://help.cricut.com/hc/en-us/articles/360009501553
- [H-EPFAQ] EasyPress FAQ: https://help.cricut.com/hc/en-us/articles/360009502173
- [H-EPTS] EasyPress Troubleshooting: https://help.cricut.com/hc/en-us/articles/360010449473
- [H-QRC] EasyPress Quick Reference Chart (PDF): https://d2e2oszluhwxlw.cloudfront.net/help/easypress/quick-reference-chart/current-easypress-settings.pdf
- [H-TAPE] Transfer Tape instructions: https://help.cricut.com/hc/en-us/articles/360009430794
- [H-CLEAN] How do I clean my Explore machine: https://help.cricut.com/hc/en-us/articles/360009504493
- [H-GREASE-PDF] Clean my Explore machine / grease packet (PDF): https://d2e2oszluhwxlw.cloudfront.net/learn/pdfs/design-space/cleaning-and-greasing-machine.pdf
- [H-RESUME] Cricut Maker: Resume project (don't unload, press Go; Knife Blade): https://help.cricut.com/hc/en-us/articles/360009557673-Cricut-Maker-Resume-project
- [H-VINYL] Cricut Vinyl instructions: https://help.cricut.com/hc/en-us/articles/7054720637719-Cricut-Vinyl
- [H-EP3FAQ] EasyPress 3 FAQ (firm vs gentle pressure, firm surface): https://help.cricut.com/hc/en-us/articles/4440451394455-Cricut-EasyPress-3-FAQ
- [C-MATCLEAN] Cricut blog: How to clean a Cricut mat: https://cricut.com/blog/how-to-clean-a-cricut-mat/
- [C-WASHFAQ] Cricut blog: Peeling after the first wash: https://cricut.com/blog/gb/faqs/why-is-my-vinyl-peeling-off-after-the-first-wash/
- [CRICUT-MATS-VIDEO] Cricut YouTube: How to Use Cricut Cutting Mats: https://www.youtube.com/watch?v=XdciulFw8c0

**Maker blogs / YouTube (link only; never reuse their art):**
- [JM-CUTS] JenniferMaker: Cricut Cutting Problems, Tips for Cleaner Cuts (updated Mar 13, 2026): https://jennifermaker.com/cricut-cutting-problems-tips-cleaner-cuts/
- [JM-INTRICATE] JenniferMaker: Intricate cuts: https://jennifermaker.com/intricate-cuts-on-cricut/
- [JM-REVERSE] JenniferMaker: Reverse weed vinyl: https://jennifermaker.com/reverse-weed-vinyl/
- [HLMS-BOX] Hey Let's Make Stuff: Weeding box: https://heyletsmakestuff.com/weeding-box/
- [PP-WEED] Printable Press: How to weed vinyl: https://www.printablepress.com/how-to-weed-vinyl/
- [SMQ-CLEAN] Scrap Me Quick Designs: Do's and don'ts for cleaning Explore: https://www.scrapmequickdesigns.com/dos-and-donts-for-cleaning-your-cricut-explore/
- [MM-AIR2] Manny Maker: Explore Air 2 common issues: https://mannymaker.com/cricut/cricut-explore-air-2/others/
- [ITS-SVG] imagetosvg: Fix SVG wrong-size imports: https://imagetosvg.com/how-to/fix-svg-wrong-size-cricut
- [JM-MATCLEAN] JenniferMaker: How to clean Cricut mats: https://jennifermaker.com/how-to-clean-cricut-mat/
- [SV-REPEAT] Sticky Vinyl AU: press Go again before unloading: https://stickyvinyl.au/blogs/news/perfect-cuts-double-cuts
- [HLMS-HTV] Hey, Let's Make Stuff: get iron-on to stick: https://heyletsmakestuff.com/get-iron-on-to-stick/
- [ICV-HTV] iCraftVinyl: why HTV isn't adhering: https://svg.icraftvinyl.com/blogs/icraft-today/common-heat-transfer-vinyl-mistakes-why-your-htv-isn-t-adhering
- [CNC-TAPE] Craft'n Cadabra: why won't vinyl stick to transfer tape: https://craftncadabra.com/cttblog/ctt-guide-why-wont-my-vinyl-stick-to-transfer-tape
- [HCF-WEED] Hello Creative Family: 10 weeding tips: https://hellocreativefamily.com/10-cricut-weeding-tips-vinyl-and-htv/
- [SM-ATTACH] Sarah Maker: Attach in Design Space: https://sarahmaker.com/attach-cricut-design-space/
- [KB-PTC] Kim Byers: Print Then Cut issues, 8 fixes (YouTube): https://www.youtube.com/watch?v=xcDqLk3zEMs
- [LMS-CARD] Hey Let's Make Stuff: Removing cardstock from a mat (YouTube): https://www.youtube.com/watch?v=LmNDoKle-EE
- [IFIXIT] iFixit: Explore Air 2 troubleshooting (CC BY-NC-SA, learn from, don't copy): https://www.ifixit.com/Wiki/Cricut_Explore_Air_2_Troubleshooting
- [SISER-EW] Siser EasyWeed instructions: https://siserstore.com/pages/easyweed
- [PP-MIRROR] Printable Press: How to mirror an image for HTV (Apr 16, 2026; "once pressed and bonded, the transfer cannot be corrected"; recut with mirroring): https://www.printablepress.com/how-to-mirror-image-for-htv/
- [TWC-HTV] TeckWrap Craft: Iron-on vinyl, which side faces down (FAQ: "no fix for a design that has already been pressed backwards"; cut a new piece with Mirror): https://teckwrapcraft.com/blogs/tips/iron-on-vinyl-which-side-faces-down-the-cutting-mat

**Reddit r/cricut (community anecdotes; checked against search snippets, threads not fully read):**
- [R-RIP] Ripping stickers: https://www.reddit.com/r/cricut/comments/1texsxn/ripping_stickers/
- [R-NOTCUT] Not cutting through vinyl anymore: https://www.reddit.com/r/cricut/comments/1hiq1f9/not_cutting_through_vinyl_anymore/
- [R-NOTCUT2] Not cutting all the way through vinyl: https://www.reddit.com/r/cricut/comments/1u3d0mq/not_cutting_all_the_way_through_vinyl/
- [R-DIDNT] Didn't cut through: https://www.reddit.com/r/cricut/comments/1shvnbe/didnt_cut_through/
- [R-WEED] Trouble weeding small letters: https://www.reddit.com/r/cricut/comments/m6j484/trouble_weeding_small_letters/
- [R-PEEL] Vinyl peeling after one wash: https://www.reddit.com/r/cricut/comments/130p37o/
- [R-GLITTERTAPE] Glitter vinyl won't stick to transfer tape: https://www.reddit.com/r/cricut/comments/1jif774/
- [R-GRIND] Grinding noise: https://www.reddit.com/r/cricut/comments/1dvm3xo/cricut_2_support_help_grinding_noise/
- [R-LOUD] Explore 2 loud noise fixed: https://www.reddit.com/r/cricut/comments/xjn5vj/cricut_explore_2_loud_noise_fixed/
- [R-MIRROR] "So frustrated" (Auto Mirror double flip): https://www.reddit.com/r/cricut/comments/1v0c3hk/so_frustrated/
- [R-REPEAT] Repeating last cut (press Go again before unloading): https://www.reddit.com/r/cricut/comments/smufzu/repeating_last_cut_question/
- [R-SVG] Design Space and .svg sizing: https://www.reddit.com/r/cricut/comments/y74hae/question_about_design_space_and_svg/

**X (thin signal; X carries few fix threads):**
- [X-TEAR] "Why is Cricut tearing paper? (fix guide)": https://x.com/finnallen874/status/2040402104695804021

---
*Cricut®, Design Space®, EasyPress® and Cricut machine names are trademarks of Cricut, Inc., used only to say what this works with. Craft Cut Coach is unofficial and not affiliated with or endorsed by Cricut, Inc. Not Cricut support. Not legal or safety certification. Settings are starting points from public sources, not tested on a machine by us; always do your own small test first.*
*Unofficial · not affiliated with Cricut.*
