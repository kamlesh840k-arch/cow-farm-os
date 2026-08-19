# Hydroponic Fodder Build Design — 50 kg/day, Nepal

Status: Phase-1 engineering concept for the 10-cow startup
Target output: 50 kg fresh hydroponic maize fodder/day
Design philosophy: low-cost, modular, easy to sanitize, scalable to 100 kg/day

## 1. Design basis

This design intentionally uses conservative biological assumptions rather than optimistic vendor claims.

- Target fresh fodder: 50 kg/day
- Crop cycle: 7 days
- Conservative fresh conversion: 5.32 kg fodder/kg seed (aligned with the Nepal NARC trial previously studied)
- Required maize seed: about 9.4 kg/day
- Daily trays harvested: 8
- Seed per tray: about 1.17–1.20 kg
- Required average fresh fodder per tray: 6.25 kg
- Active 7-day tray positions: 56
- Total trays procured: 64
- Spare/buffer trays: 8

A commercial 50 kg/day system example uses 40 trays, 7.5 kg maize/day, a 0.5 HP pump, a 200 L tank and roughly 50 L water/day. That configuration assumes about 6.7x fresh-weight conversion. For Cow Farm OS, we are deliberately sizing more tray capacity because a 5–6x conversion is safer for budgeting and operations.

## 2. Recommended room / shed footprint

Preferred internal clear size: approximately 10 ft x 9 ft (90 sq ft).

Minimum practical size if space is tight: about 10 ft x 8 ft, provided drainage and access remain adequate.

Recommended layout:

- Rack A along one side
- Rack B along opposite side
- Central working aisle: about 3 ft
- Side/rear clearances: 6–12 inches minimum where access is not required
- Front handling/work zone: about 2 ft
- Water tank and pump at the rear or outside the wet growing zone
- Floor drain on the lowest side of the room

The room should be shaded, insect-screened, washable, well ventilated, and protected from direct rain and direct strong sun.

## 3. Rack design

Build 2 identical GI/MS racks.

Each rack:

- Approx. width: 6 ft
- Approx. depth: 2.1–2.25 ft
- Approx. height: 6.5–7 ft
- Shelves: 8 levels
- Tray positions per shelf: 4
- Capacity per rack: 32 trays
- Total rack capacity: 64 trays

Tray orientation:

Use approximately 18 x 24 inch trays. Four 18-inch tray widths fit across a 6-ft shelf.

Shelf spacing:

- 9–10 inches clear vertical spacing for early levels
- Slightly larger clearance on final levels if needed
- Build shelf angles/support rails so trays remain level and do not pond water

Material recommendation:

- GI square tube preferred for corrosion resistance
- Painted MS can reduce upfront cost but requires excellent anti-rust coating and periodic repainting
- Avoid untreated mild steel in the wet zone

## 4. Tray specification

Target: 64 reusable food/agriculture-grade plastic trays.

Preferred dimensions: about 18 x 24 inches.

Required features:

- 2–3 inch wall height is generally adequate
- Multiple small drainage holes
- Smooth internal surfaces for easy cleaning
- Strong enough to carry a 6–7 kg wet fodder mat repeatedly
- Stackable when empty

Do not buy all trays until a 3–5 tray germination test confirms that the selected tray depth, hole size, drainage and seed loading work with the locally available maize.

## 5. Daily rotation

Use an 8-tray/day rotation.

Day 0:
- Clean and grade maize seed
- Germination test on every new seed lot
- Soak required seed

Day 1:
- Spread about 1.17–1.20 kg pre-soaked seed per tray
- Load 8 trays into the first production group

Days 2–6:
- Continue irrigation, inspection and tray rotation as required

Day 7:
- Harvest 8 oldest trays
- Target 50 kg total fresh output
- Wash and disinfect harvested trays
- Reload with the next seed batch

At steady state, 8 trays enter and 8 trays leave every day.

## 6. Water system

### Tank

Recommended: 200–300 L covered tank.

A 200 L tank is sufficient for the 50 kg/day biological requirement, but 300 L provides operational buffer during interruptions.

### Pump

Recommended: 0.5 HP clean-water surface/self-priming pump.

Current Nepal market examples found during research place common 0.5 HP surface pumps roughly around NPR 5,500–11,860 depending on brand and seller. A 0.5 HP pump is therefore both technically reasonable and locally obtainable.

### Filtration

Install a washable inline screen/disc filter before the irrigation laterals. Foggers/nozzles are very sensitive to sediment.

### Distribution

Suggested system:

Tank -> filter -> pump -> main header -> rack isolation valve -> 16 mm laterals -> micro-sprayers/foggers -> trays -> drainage gutter -> floor drain.

Use separate isolation valves for each rack. This allows maintenance of one rack while the other remains operational.

### Nozzles

Target 50–64 fogger/micro-spray points initially, then adjust after spray-uniformity testing.

The goal is not to continuously soak the crop. The target is short, frequent wetting with fast drainage and air movement between cycles.

## 7. Irrigation control

Use a programmable 220 V timer controlling the pump through a correctly rated contactor/relay.

Current Nepal listings show basic programmable timers around NPR 890–1,275, while higher-current/weather-protected models are more expensive.

Do not run a 0.5 HP motor directly through a small low-quality timer unless its motor-load rating is explicitly adequate. Preferred electrical architecture:

MCB/RCD -> timer -> contactor -> pump.

This protects the timer contacts and improves electrical safety.

Initial irrigation programming should be treated as a commissioning variable, not a fixed recipe. Start with brief pulses and observe tray moisture, drainage, room humidity and root condition. Increase or decrease interval length based on actual climate.

## 8. Water requirement

Research literature commonly reports approximately 1.5–3.0 L water per kg fresh hydroponic maize fodder, while a commercial 50 kg/day low-cost system example states about 50 L/day.

For design purposes:

- Biological irrigation planning range: 50–150 L/day
- Provide 200–300 L storage so the system remains robust
- Track actual water added to the tank daily

Water consumption KPI:

litres of makeup water / kg fresh fodder harvested.

If consumption becomes excessive, check drainage loss, nozzle size, run time and leaks.

## 9. Ventilation and climate control

The single biggest small-farm failure risk is mold caused by excess moisture, poor airflow and poor sanitation.

Required:

- Cross ventilation
- Insect/shade net openings
- At least one exhaust or circulation fan if natural airflow is weak
- No standing water on floor
- No continuously dripping nozzles
- Fast drainage from every tray

Do not initially install expensive air conditioning. First design the structure for passive ventilation and shade. Add forced ventilation if temperature/humidity observations show a need.

## 10. Drainage

Floor should be smooth concrete with a deliberate slope toward a drain.

Minimum requirements:

- No puddles under racks
- Drainage channels/gutters under racks where practical
- Wastewater routed away from the cow shed drinking-water area
- Entire floor washable daily

A dirty wet floor is a mold and pathogen reservoir.

## 11. Electrical safety

Because water and 230 V AC equipment share the same room:

- Use an RCD/ELCB
- Use an MCB sized for the pump and fan circuit
- Keep control panel above splash height
- Use weather-resistant electrical boxes
- Properly earth pump/frame
- Do not place loose extension boards on the floor
- Have final wiring completed by a competent electrician

## 12. Preliminary BOM and budget

These are procurement planning allowances, not quotations.

| Item | Qty | Planning range (NPR) |
|---|---:|---:|
| Hydroponic trays | 64 | 22,400–38,400 |
| Fabricated GI/MS racks | 2 | 28,000–40,000 |
| 0.5 HP pump | 1 | 6,000–12,000 |
| 200–300 L water tank | 1 | 3,000–5,000 |
| Timer + contactor + MCB/RCD box | 1 set | 3,000–6,000 |
| Water filter | 1 | 800–2,000 |
| PVC/PE pipe, valves, fittings | 1 lot | 3,000–6,000 |
| Foggers/nozzles | 50–64 | 4,000–8,000 |
| Gutters/drainage accessories | 1 lot | 2,500–5,000 |
| Shade/insect net + ventilation items | 1 lot | 5,000–12,000 |
| Wiring and electrical installation | 1 lot | 2,500–5,000 |
| Scale, buckets, cleaning/sanitation tools | 1 lot | 2,500–5,000 |
| Installation/contingency | — | 8,000–15,000 |
| **Preliminary equipment total** | | **~90,700–159,400** |

This excludes a new masonry room or major civil construction. If an existing washable, ventilated room can be adapted, the system can remain near the earlier NPR 120k–150k target.

## 13. Practical CAPEX rule

Cow Farm OS procurement rule for the 10-cow startup:

- Target installed cost: <= NPR 150,000 if an existing structure is used
- Preferred: NPR 100,000–130,000 after competitive local fabrication quotes
- Do not approve > NPR 160,000 for a 50 kg/day low-tech system without a clear justification

At higher capital cost, it becomes harder for hydroponics to compete with ordinary green fodder and silage.

## 14. Seed handling SOP

1. Buy only untreated feed-grade/germination-grade maize suitable for sprouting.
2. Reject visibly moldy, broken, insect-damaged or chemically treated seed.
3. Test germination before accepting a large lot.
4. Target >90% germination; lower germination can destroy the economics and increase mold risk.
5. Wash seed thoroughly.
6. Use a farm-approved sanitation procedure if needed.
7. Soak consistently.
8. Drain before spreading into trays.
9. Do not overload trays.

The seed is the dominant operating-cost driver, so seed procurement quality and price matter more than most mechanical optimizations.

## 15. Daily operating SOP

Morning:

- Inspect every tray for mold/odor
- Check pump, filter and nozzles
- Weigh and harvest 8 Day-7 trays
- Record total harvested kg
- Feed only clean, fresh-smelling fodder
- Clean harvested trays

Midday:

- Inspect temperature, humidity/airflow and tray moisture
- Check for standing water
- Remove any suspect tray from the production room immediately

Evening:

- Prepare next seed batch
- Record seed kg used
- Check tank makeup water
- Inspect timer operation

## 16. Minimum records

Daily log fields:

- Date
- Seed lot
- Seed kg loaded
- Number of trays loaded
- Number harvested
- Fresh kg harvested
- Yield ratio (fresh kg / seed kg)
- Water added (L)
- Electricity estimate/meter reading
- Molded/rejected trays
- Labor minutes
- Cows fed
- Milk litres/cow
- Remarks

Weekly KPIs:

- Fresh yield ratio
- Cost/kg fresh fodder
- Cost/kg dry matter
- Rejection/mold rate
- Labor minutes/kg
- Water L/kg
- Change in milk yield versus ration baseline

## 17. Go/no-go thresholds after pilot

Scale up only if most of the following are achieved over at least 30–60 days:

- Yield >=5.0 kg fresh fodder/kg seed
- Target >=5.3 where possible
- Mold/rejection <3% of trays
- Labor <=60 minutes/day at 50 kg output
- Reliable daily output without frequent mechanical failures
- Actual cost/kg fresh fodder within approved feed budget
- No negative effect on dry matter intake or cow health
- Measurable ration or fodder-security benefit

If yield falls below 4.5x or mold loss is persistent, stop scaling and correct the process first.

## 18. Feeding strategy for the 10 cows

Do not treat 50 kg hydroponic fodder as 50 kg of normal green forage on a dry-matter basis.

Target use at full 50 kg/day:

- approximately 5 kg fresh hydroponic fodder/cow/day for 10 cows

This remains supplemental. Base ration should continue to include adequate conventional roughage, silage/hay/green fodder, concentrates, mineral mix and clean water according to milk production and animal nutrition requirements.

## 19. Scaling to 100 kg/day

The system is intentionally modular.

To double output:

- Increase daily tray harvest from 8 to 16
- Increase seed from about 9.4 kg/day to about 18.8 kg/day
- Total active tray positions: 112 for a 7-day cycle
- Recommended total trays with buffer: 120–128
- Add two more identical racks (4 racks total)
- Increase room area to roughly 150–180 sq ft depending on aisle layout
- Retain or upgrade pump only after checking pressure/flow; a 0.5 HP pump may remain adequate for zoned irrigation, while simultaneous irrigation of all racks may justify 1 HP
- Tank should increase to roughly 400–500 L
- Irrigation should be zoned rack-by-rack to avoid unnecessary pump oversizing

The key design principle is to duplicate proven 50 kg/day modules instead of replacing the whole installation with expensive automation.

## 20. Procurement sequence

Do not purchase everything simultaneously.

Stage A — seed/tray validation:
- Buy 5–10 candidate trays
- Buy several candidate maize lots
- Run germination and 7-day yield tests

Stage B — rack prototype:
- Fabricate one shelf/rack section
- Validate tray fit, drainage and working height

Stage C — water system:
- Install pump, filter, timer and test uniformity

Stage D — full 64-tray commissioning:
- Ramp 2 -> 4 -> 8 trays/day

Stage E — 30–60 day measured pilot:
- Make scale/no-scale decision from real farm data

## 21. Current source checks used for this engineering concept

- ICAR literature describes hydroponic fodder as a ~7-day crop, states nutrient solution is not essential, and supports low-cost structures made from bamboo, wood, MS/GI pipes or masonry.
- ICAR review reports 5–6x fresh yield as common, approximately 11–14% dry matter and 1.5–3.0 L water/kg fresh hydroponic maize fodder; it recommends hydroponic fodder primarily where conventional green fodder is difficult to grow reliably.
- A current commercial 50 kg/day design example specifies 40 trays of about 18 x 24 inches, 7.5 kg maize/day, 0.5 HP pump, 200 L tank and about 50 L water/day. Cow Farm OS deliberately adds tray/seed capacity to avoid depending on that more optimistic conversion.
- Current Nepal listings confirm ready availability of 0.5 HP pumps and programmable timer hardware in the approximate ranges used above.

## 22. Decision

APPROVE AS A PILOT DESIGN, NOT YET AS A LARGE CAPITAL PURCHASE.

For the 10-cow farm, build only the 50 kg/day modular unit after local tray, seed, GI fabrication and plumbing quotations are collected. The highest-priority procurement test is not the pump — it is finding clean, inexpensive maize with consistently high germination and measuring the actual 7-day yield ratio.
