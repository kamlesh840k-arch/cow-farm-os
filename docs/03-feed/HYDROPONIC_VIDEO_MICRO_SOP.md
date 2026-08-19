# Hydroponic Fodder — Video Micro-SOP & Visual Operating Notes

**Project:** Cow Farm OS  
**Farm context:** 10-cow Phase-1, Nepal  
**Primary video:** Indian Farmer — hydroponic fodder system  
**Video ID:** `g2SG_2_tJG8`  
**Prepared:** 2026-08-19  
**Purpose:** Capture small operating details from the reference video and convert them into a testable farm SOP.

> IMPORTANT EVIDENCE LABELS
>
> - **[VIDEO/USER OBSERVATION]** = detail noticed in the video by the project owner and preserved here for farm replication.
> - **[RESEARCH-CHECKED]** = supported by ICAR/NARC or peer-reviewed hydroponic-fodder research.
> - **[TO VERIFY FRAME-BY-FRAME]** = exact number, timing, spacing, material or sequence must be checked again from the original video before becoming a locked SOP.
>
> The video URL could not be reliably fetched frame-by-frame by the current research tools during this pass. Therefore, details reported from visual observation are preserved but not falsely presented as independently frame-verified.

---

## 1. The process shown is more than “put maize in trays”

The useful production chain appears to be:

```text
DRY GRAIN
   ↓
Sorting / removing bad grain
   ↓
WASHING
   ↓
SOAKING
   ↓
DRAINING
   ↓
PRE-GERMINATION / 2-DAY GERMINATION BED
   ↓
SPROUTED GRAIN
   ↓
SPREAD INTO HYDROPONIC TRAYS
   ↓
RACK + WATER/MIST + DRAINAGE + AIR
   ↓
ROOT MAT FORMS
   ↓
GREEN SHOOT GROWTH
   ↓
WHOLE MAT HARVEST
   ↓
FEED AS PART OF THE RATION
```

This pre-germination stage is operationally important. We should not design Cow Farm OS around a simplistic “soak → immediately put on rack” workflow until the reference method is fully verified.

---

# 2. Grain / crop selection by season

## Maize

**[VIDEO/USER OBSERVATION]** Maize is used as the principal hydroponic fodder grain in the demonstrated season.

**[RESEARCH-CHECKED]** ICAR recommends maize as a major choice grain for Indian hydroponic green fodder systems and reports successful production on a roughly 7-day cycle. Maize is also the crop used in Nepal NARC hydroponic-fodder work.

## Wheat — “gohu / gehun”

**[VIDEO/USER OBSERVATION]** The farmer says they use **wheat (gohu/gehun)** in another season.

This is a very important farm-design point: **the hydroponic structure is crop-flexible; the grain can change seasonally.**

**[RESEARCH-CHECKED]** ICAR literature and other livestock-hydroponic studies recognize wheat and barley as alternative cereal grains for hydroponic fodder.

### Cow Farm OS implication

Do not hard-code the system as a “maize machine.” It should be treated as a **cereal-sprouting fodder module**.

Candidate seasonal strategy to test:

```text
Warm / maize-appropriate period → maize
Cooler period / economics favor wheat → wheat
Other possible trial crop → barley
```

Selection each season must be based on:

1. grain price per kg,
2. germination percentage,
3. mold/rejection rate,
4. kg fresh fodder per kg grain,
5. dry-matter yield,
6. cow palatability,
7. local availability.

Do not choose the crop only because its green mat looks larger.

---

# 3. Maize cleaning and washing — do not omit this

**[VIDEO/USER OBSERVATION]** The farmer washes the maize before the germination stage.

This should become an explicit Cow Farm OS task, not a hidden step.

## Proposed operating sequence

```text
Container A: dry maize
       ↓
Hand-sort obvious stones / broken / damaged / moldy grain
       ↓
Add clean water
       ↓
Agitate grain by hand
       ↓
Remove floating debris / suspicious material
       ↓
Drain dirty water
       ↓
Repeat washing until wash water is acceptably clean
       ↓
Proceed to soaking
```

### Why washing matters

Washing is not only cosmetic. Hydroponic grain is kept warm and wet at high density; dirt and contaminated grain increase mold and bacterial risk.

### What to reject during washing

- visibly moldy kernels
- rotten kernels
- insect-damaged grain
- stones / soil / husk / foreign matter
- strongly discolored kernels
- grain with foul smell

### Farm rule

**Never load questionable grain simply to avoid wasting seed.** One contaminated batch can spread mold into trays, rack surfaces, nozzles and neighboring batches.

### Video verification items still required

- exact number of washes shown
- whether any disinfectant is used or only water
- duration of washing
- whether floating maize is discarded in the video
- type/size of wash container

These should be timestamped when the video file is available for direct frame inspection.

---

# 4. Soaking stage

After cleaning/washing, the grain needs controlled hydration.

**[RESEARCH-CHECKED]** Hydroponic maize protocols vary. ICAR Goa reports that about **4 hours soaking can be sufficient for maize** in its standardized system, while other farm/research protocols use longer soaking or overnight soaking. Nepal NARC work reported overnight soaking before germination in a jute sack.

### Important conclusion

There is **no universal “always soak 12/24 hours” rule**. We should copy the reference farm only after verifying its exact timing and then run our own germination test under Nepal conditions.

### Cow Farm OS test variables

For each grain source, log:

- dry seed weight
- soak start time
- soak end time
- water temperature if practical
- final drained weight
- smell / fermentation signs
- germination % after pre-germination

### Failure warning

Too-long soaking + warm water + low oxygen can cause fermentation, sour smell and poor germination.

---

# 5. Two-day germination bed — critical detail

**[VIDEO/USER OBSERVATION]** The video appears to show a separate **bed / prepared area used for approximately 2 days of germination before the sprouted seed goes to the hydroponic trays**.

This is one of the most important details missed in the earlier summary.

## Working reconstruction of the observed sequence

```text
WASHED + SOAKED GRAIN
        ↓
Drain excess water
        ↓
Place grain in a dedicated germination bed / covered zone
        ↓
Keep batches physically separated
        ↓
Cover to maintain dark/moist germination conditions
        ↓
Approx. Day 1
        ↓
Approx. Day 2
        ↓
Roots / sprouts emerge
        ↓
Move germinated grain to hydroponic trays/racks
```

### Why a separate germination bed makes sense

During the first 1–2 days the grain mainly needs hydration, moisture and germination conditions; green-light exposure is not yet the main objective. A separate bed can:

- reduce rack space required for the earliest stage,
- allow batch identification,
- create more uniform sprouting,
- keep the production line continuous,
- simplify daily rotation.

### Cow Farm OS design implication

The hydroponic room should include a **dedicated pre-germination zone** rather than only tray racks.

Suggested layout concept:

```text
┌───────────────────────────────────────┐
│         HYDROPONIC WORK ROOM          │
│                                       │
│  [A] WASH / SOAK       [C] RACKS      │
│  buckets/tank           Day 3–7+      │
│       │                 █████████      │
│       ▼                 █████████      │
│  [B] GERMINATION BED    █████████      │
│  Day 1–2 batches        █████████      │
│  ───────────────        █████████      │
│                                       │
│  [D] HARVEST + TRAY-WASH AREA         │
└───────────────────────────────────────┘
```

The earlier 50 kg/day design should therefore reserve physical space for this pre-germination step.

---

# 6. “Four-finger gap” between germination batches

**[VIDEO/USER OBSERVATION]** The farmer appears to keep approximately a **four-finger gap** while laying out/covering germinating batches.

This detail must be preserved because it may serve one or more practical purposes:

- separation of batches loaded on different days,
- airflow between moist grain masses,
- preventing roots from interlocking between batches,
- allowing a hand to identify/lift individual batches,
- reducing cross-contamination,
- making the 2-day rotation visually obvious.

## Visual reconstruction

```text
TOP VIEW — GERMINATION BED

┌───────────────────────────────────────────┐
│ Batch A (Day 1)                           │
│ ███████████████████████████████████       │
│                                           │
│ <---- about FOUR FINGERS gap ---->        │
│                                           │
│ Batch B (Day 2 / next batch)              │
│ ███████████████████████████████████       │
└───────────────────────────────────────────┘
```

### Do not convert “four fingers” into centimeters yet

Finger width varies. Before construction we should frame-check the original video and, ideally, measure practically. Until then the farm note should retain the farmer’s **visual measurement language** rather than inventing a precise 6 cm / 8 cm figure.

---

# 7. Covering the germination bed

**[VIDEO/USER OBSERVATION]** The germinating grain/batches are covered.

Likely functional goals:

- retain humidity,
- protect the grain from direct light during initial germination,
- reduce surface drying,
- maintain a stable micro-environment.

### What must be checked from the video

- covering material: cloth / jute / sack / plastic / other
- whether cover touches grain or is suspended
- whether the cover is wetted
- whether it is opened for watering/inspection
- exact number of days covered
- ventilation around the covered bed

### Safety rule

The covering must **not create anaerobic, overheated, sour conditions**. If there is fermentation smell, sliminess, excessive heat or mold, the process is wrong even if the grain is technically sprouting.

---

# 8. Moving sprouted grain from bed to trays

After pre-germination, the sprouted grain is moved into shallow hydroponic trays.

## Operational care

- handle gently so new roots are not crushed excessively
- spread uniformly
- avoid deep heaps
- do not leave dry corners
- do not block drainage holes
- label or position by production day

**[RESEARCH-CHECKED]** ICAR research found seed density affects optimal output; one study recommended about **7.6 kg seed/m²** for hydroponic maize under its conditions. This is more reliable than saying “fill the tray thickly.”

### Cow Farm OS tray-loading formula

`Seed per tray = tray growing area (m²) × target seed rate (kg/m²)`

Then adjust using our actual germination and mold results.

---

# 9. Rack/day rotation — the system is a pipeline

The operation should be visualized as a daily production line, not a one-time crop.

Example if the farmer uses 2 days pre-germination + 5–7 rack days:

```text
DAY 1   Germination bed — Batch A
DAY 2   Germination bed — Batch A continues
DAY 3   Move A to rack; start Batch B
DAY 4   A grows on rack; B germinates
DAY 5   A grows; B moves forward; new batch enters
...
EVERY DAY: one batch enters, one batch advances, one batch harvests
```

Exact day count must be locked to the video + our Nepal trial.

### Farm identification rule

Every batch should have either:

- day-numbered rack position,
- colored tag,
- waterproof date tag,
- or fixed FIFO (first-in-first-out) physical flow.

This avoids harvesting the wrong age mat.

---

# 10. Watering after tray loading

The rack system uses frequent light irrigation/misting rather than keeping the grain submerged.

**[RESEARCH-CHECKED]** Low-cost hydroponic systems can use micro-sprinklers, automated sprayers or manual knapsack spraying. Tap water alone can be sufficient; nutrient solution is not inherently required for a short cereal-fodder cycle.

## Correct visual condition

```text
GOOD
roots/grain = moist
tray = draining
air = moving
no puddle

BAD
roots/grain = sitting in stagnant water
tray = waterlogged
air = hot/stale
mold smell
```

### Video verification items

- watering frequency stated by farmer
- duration per irrigation event
- manual or automated timing
- nozzle type
- whether water is recycled
- drainage slope
- whether older/younger trays receive different watering

---

# 11. Light and shade

The first germination stage is covered/darker; later rack growth requires enough light for green shoots but should not be treated like a field crop in harsh direct sun.

The system should provide:

- diffuse daylight / appropriate light exposure,
- protection from intense heat,
- strong ventilation,
- no stagnant humid pockets.

For Nepal we must adapt this to farm altitude and season rather than copying an Indian ambient-temperature setup blindly.

---

# 12. Whole-mat harvest

Hydroponic fodder is harvested as a combined mat:

```text
GREEN SHOOTS
^^^^^^^^^^^^^
|||||||||||||
SEED / CROWN LAYER
ooooooooooooo
DENSE WHITE ROOT MAT
####################
```

The cow can consume shoots + germinated grain + root mat, subject to ration formulation and cleanliness.

ICAR describes hydroponic maize fodder as a mat containing **roots, germinated seed and plants**.

### Reject the mat if

- visible mold colonies
- strong sour/fermented odor
- slimy root zone
- black/rotten areas
- abnormal heating
- contaminated with dirty water/chemicals

---

# 13. The hidden workstation requirements learned from the video

Because washing + soaking + a 2-day germination bed occur before rack loading, Cow Farm OS needs more than racks.

## Required functional zones

1. **Dry grain storage** — protected from rodents and moisture
2. **Sorting/washing station** — drain nearby
3. **Soaking containers** — batch-sized and washable
4. **Draining station** — no standing dirty water
5. **2-day germination bed** — cleanable, covered, separated batches
6. **Tray loading table** — ergonomic working height
7. **Hydroponic rack zone** — mist + drainage + airflow
8. **Harvest zone**
9. **Dirty tray wash/disinfection zone** — preferably separated from clean tray loading
10. **Record board / batch log**

## Better room-flow visual

```text
DIRTY / RAW SIDE                         CLEAN / GROW SIDE

Grain store
    ↓
Sort & wash
    ↓
Soak
    ↓
Drain
    ↓
2-day germination bed
    ↓
Clean tray loading  ───────→  Growing racks
                                  ↓
                               Harvest
                                  ↓
                                Cows

Dirty harvested trays ─────→ Wash / sanitize ─────→ Clean tray store
```

The tray-washing direction should not send dirty wash splash back toward newly germinating grain.

---

# 14. Seasonal crop-switch SOP

If the video farm changes maize to wheat by season, Cow Farm OS should use a **crop-specific recipe card**.

| Variable | Maize recipe | Wheat recipe |
|---|---|---|
| Grain source | record | record |
| Price/kg | record | record |
| Germination % | test | test |
| Washing method | verify | verify |
| Soak time | trial/verify | trial/verify |
| Germination-bed time | verify | verify |
| Seed rate/tray | measure | measure |
| Rack days | measure | measure |
| Water cycle | measure | measure |
| Fresh yield/kg seed | measure | measure |
| DM % | sample | sample |
| Mold rejection % | record | record |
| Palatability | record | record |
| Cost/kg DM | calculate | calculate |

Do not assume the maize timing automatically applies to wheat.

---

# 15. Daily micro-checklist for the operator

## Before handling seed

- Wash hands / use clean gloves if appropriate.
- Confirm correct grain batch.
- Check grain for odor, insects and mold.
- Confirm wash and soak containers are clean.

## Washing

- Sort obvious bad grain.
- Wash/agitate.
- Drain dirty water.
- Repeat as required.
- Record rejected grain if material.

## Soaking

- Record seed weight.
- Record start time.
- Use clean water.
- Do not mix yesterday's and today's batches.
- Drain at scheduled time.

## Germination bed

- Place batch in its designated position.
- Keep intended gap between batches — video reference: about four fingers.
- Cover with the correct clean material.
- Check moisture; avoid waterlogging.
- Check odor/heat/mold at least daily.

## Tray transfer

- Use only clean trays.
- Spread sprouted grain uniformly.
- Do not compact excessively.
- Make sure drain holes/channels are open.
- Put tray in correct age/day position.

## Rack

- Confirm all nozzles operating.
- Confirm no standing water.
- Check older and younger trays separately.
- Remove any moldy tray immediately.
- Maintain airflow.

## Harvest

- Verify batch age.
- Inspect underside/root mat closely.
- Smell before feeding.
- Weigh harvest.
- Record yield.
- Feed only clean material.

## After harvest

- Remove remaining root/seed residue.
- Wash tray.
- Sanitize according to approved farm procedure.
- Dry/store clean tray without dirty-water recontamination.

---

# 16. Data that must be captured when we inspect the original video frame-by-frame

This is the extraction checklist for the next direct-video pass.

| Detail | Exact value/observation needed |
|---|---|
| Maize washing | number of rinses / visual method |
| Floating grains | discarded or retained? |
| Soak container | material and approximate volume |
| Soak duration | exact hours stated |
| Post-soak draining | duration / method |
| Germination bed | dimensions/material |
| Bed surface | floor/tarpaulin/tray/other |
| Grain depth on bed | approximate cm / kernels thick |
| Four-finger gap | exactly between what items/batches? |
| Cover material | cloth/jute/plastic/etc. |
| Cover moisture | dry/wet |
| Pre-germination duration | exactly 2 days? |
| Root length before tray | visual estimate |
| Wheat season | exact months/temperature reason stated |
| Maize season | exact months stated |
| Tray dimensions | estimate/reference |
| Seed quantity/tray | kg stated |
| Tray perforations | number/layout |
| Rack dimensions | shelves, spacing, material |
| Water source | direct/filtered/recycled |
| Irrigation | frequency + duration |
| Nozzle type | fogger/mister/sprayer |
| Drainage | gutter/floor/open drainage |
| Light | shade net/room/direct daylight |
| Ventilation | open sides/fans/natural |
| Harvest age | exact day |
| Harvest yield | kg/tray or seed-to-fodder ratio |
| Feeding quantity | kg/cow/day if stated |
| Root mat handling | whole/chopped/torn |
| Cleaning | tray/rack sanitation method |
| Mold discussion | prevention/remedy if mentioned |
| Labour | persons and time if stated |

---

# 17. What is already research-supported vs what remains video-specific

## Research-supported

- maize is highly suitable for hydroponic fodder
- wheat/barley are valid alternatives
- short cycle around one week is common
- whole root-seed-shoot mat is harvested
- shallow tray density matters
- frequent light irrigation + drainage is standard
- clean seed / hygiene / mold prevention are critical
- low-cost/semi-automatic racks are technically viable
- pre-germination is used in many protocols, though exact duration varies

## Video-specific and NOT yet locked

- exact maize washing procedure
- exact soaking duration
- exact two-day bed procedure
- precise meaning/position of the four-finger gap
- exact covering material
- exact seasonal switch timing between maize and wheat
- tray/rack dimensions
- daily water schedule
- precise harvest age and yield for this farmer

These must not be invented.

---

# 18. Cow Farm OS design correction from this deeper pass

The previous rack-only concept is incomplete.

**Revised design must explicitly include:**

```text
WASH → SOAK → DRAIN → 2-DAY GERMINATION BED → TRAYS → RACK → HARVEST → TRAY WASH
```

This means the eventual BOM needs:

- seed wash tubs/buckets,
- soaking vessels,
- draining baskets/perforated containers,
- clean germination-bed platform,
- washable covering material,
- batch dividers/labels,
- tray-loading bench,
- drainage provision,
- separate clean/dirty tray flow.

The 50 kg/day room sizing and labour model should be revised after exact video dimensions/timings are extracted.

---

# 19. Primary technical cross-checks

- ICAR Goa standardized hydroponic maize production reports maize soaking can be as short as 4 hours in its system, tray loading and roughly 7-day production; therefore soak duration must be system-specific rather than assumed.
- ICAR *Indian Farming* describes hydroponic fodder as a ~7-day soilless cereal production method using tap water, with low-cost structures and manual/automatic micro-irrigation.
- ICAR seed-rate research found about 7.6 kg seed/m² a useful optimum under the study conditions.
- Nepal NARC hydroponic maize work used clean maize, overnight soaking, jute-sack germination, tray transfer and later harvest, confirming that a distinct pre-germination stage is a legitimate production approach.
- ICAR notes wheat/barley can also be used in hydroponic fodder systems.

---

## Working decision

The farmer's **washing + separate pre-germination + seasonal grain-switching** method is important enough that Cow Farm OS should replicate and test it before finalizing the 50 kg/day build.

**Do not purchase the full rack system until the micro-SOP is tested with 5–10 trays and both candidate grains.**
