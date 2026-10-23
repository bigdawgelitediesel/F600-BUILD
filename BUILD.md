# 1959 Ford F600, 7.3 Powerstroke 4x4 Build

Core decisions captured 2026-10-16. Specific part numbers, vendors, and pricing are the next phase.

## The truck

1959 Ford F600. Medium-duty, 2-ton class, 2WD from the factory. Only the **cab and frame** are kept. Everything else is replaced.

## Engine

7.3 Powerstroke, Dealers Diesel reman core rated 215 hp. Jacob's read 2026-10-23: likely a 94-97 OBS engine, not yet confirmed. Full custom rebuild with a 99-03 fuel and electronics package (split-shot HEUI injectors, HPOP, IDM, PCM, harness). OBS core adds: block off the mechanical lift pump drive on the front cover, oil cooler matched to the housing on the block.

- Check the build date. Pre-2001 have forged rods, 2001+ have powdered-metal rods. Moot now, since new forged rods are going in either way.
- Photograph the casting date and build sticker while it is apart.
- Engine history and mileage: not yet recorded.

## Target

400-450 hp and bulletproof. Reliability is non-negotiable. 450 keeps it in Stage 1.5/2 injector and S300-class single-turbo territory, not a race build. Don't over-turbo at the expense of low-end drivability.

## Transmission

Automatic. **Soft-locked on the 4x4 4R100** (Jacob 2026-10-16: "soft stick with 4R100"). Plan around it but open to revisiting. Jacob does not have a transmission yet.

Built to live at 450 hp: billet input and intermediate shafts, upgraded converter, better clutches, big trans cooler. Known builders: BTS (Brian's Truck Shop), Suncoast. Runs on the stock 7.3 PCM. BorgWarner 4407 bolts up.

Alternatives discussed and set aside:

- **5R110 TorqShift (2003-07):** stronger stock, 5 gears, shares the 7.3 bolt pattern. Needs a standalone controller (PCS TCM-2800, roughly $1.5-2k plus wiring), heavier and longer, costs more to build, fewer builders. Only worth it for 600+ hp or tighter highway ratios.
- **6R140:** possible but a one-off. Integral bellhousing cut for the 6.7 pattern, so it needs a custom adapter plate and flexplate/converter solution, standalone controller (PCS), and its 4x4 output does not mate to a 4407/1356 (Performance Adapters lists a 6R140/10R140-to-NP271/273 adapter). A 10R140 has been put behind a 2003 7.3 as a custom job.

Verdict: built 4R100 for this truck.

## Drivetrain and chassis

4x4 required, converting the original F600 frame (not a chassis swap onto a Super Duty frame).

- 4x4 4R100 tailhousing + BorgWarner 4407 or 1356 transfer case
- Front drive axle: Super Duty Dana 60 is the natural donor
- Rear axle swap: Sterling 10.5 or equivalent so hubs, brakes, and bolt pattern match the front
- Custom crossmember, engine and trans mounts
- Driveshafts built to length
- Front suspension redesign (leaf hangers or 4-link)
- Steering box and linkage to clear the front axle
- Brakes matched to the new axles
- Streetable gearing: 3.73-4.10 with modern tire size (tire size not chosen)

Axle sources not yet chosen.

## Sourcing

No donor Super Duty. Everything piece by piece, same approach as El Coyote. Shopping list to price individually: built 4x4 4R100, transfer case, front Dana 60, rear Sterling 10.5, steering box and linkage, brake system, standalone 7.3 PCM harness, radiator and intercooler, fuel system, A/C.

Industrial Injection is the shop partner and primary vendor (same as the F350 build). 307 has the in-house fab for the chassis work.

## Bed

Custom welded flatbed by Jacob (most likely, not 100% locked). Camper hitch/receiver built into the bed frame.

## Use

Show piece that must daily drive and tow a camper. Working A/C, reliable cold starts, highway manners.

## Budget and timeline

No deadline. Budget is flexible and worked out as the build goes. Buy right once rather than cheap twice.

---

## 450 hp bulletproof game plan

Laid out 2026-10-16. Not yet approved part by part.

**Foundation**
- Bake, blast, magnaflux block. Torque-plate bore and hone. Deck.
- Polish and balance crank.
- **Decided:** Industrial Injection forged rods + coated pistons, new rings. Replaces the Crower idea and settles forged-vs-PMR regardless of what the old rods are.
- Speed of Air dimpled pistons: dropped.
- Cam: stock if the lobes check out at Family Machine, Colt Stage 2 ($749, Rudy's/Dale's 2026-10-22) if he wants more. Decide after the shop sees it.
- Lifters: NEW regardless (2026-10-22). 7.3 runs hydraulic roller lifters, needle bearings are the known failure. KDD Gen 2 set of 16 $395 (killdevildiesel.com) is the pick; Power Stroke Products set $214 (dieselpowerproducts.com) is the budget option.
- Pushrods: NEW chromoly (2026-10-22). XDP 3/8 $270, KDD $299, PSP $324.
- Valve covers: BILLET ALUMINUM, decided 2026-10-22. Options priced that day: Choate Performance $1,395, SKU CEP73BVC, https://choateperformance.com/products/7-3-powerstroke-billet-valve-covers, 901-553-9847 (94-03, raw/black/blue/red powder coat, 1-3 wk lead, uses stock gaskets and hardware; Jacob sent this link 2026-10-22, it is the front-runner), G&R Diesel $1,499 (99-03, machined finish), UDP $2,000 (polished or any anodize, custom engraving). Lean Choate, UDP if he wants engraving. Before ordering confirm: pair vs each, passenger-side CCV mount, stock gasket (UVCH connectors live in the gasket so electrical stays stock). New gaskets either way: Alliant AP0014 set with UVCH option ~$176-245.
- Rocker arms: reuse after shop inspection (fulcrum galling, tip pitting). No street-grade new set exists, aftermarket is Jesel race hardware. Replace only what the shop flags.
- ARP head studs. The number one bulletproof item.
- New valves, guides, seals, springs. Brass injector cups.
- **No O-rings at this level.** O-ring/fire-ring is a 40+ psi, 600+ hp item. On a street truck it compromises coolant sealing and makes future head gasket jobs pickier. ARP studs + quality stock-style gasket + flat decks is the fix at 450. O-ring later if he goes compounds/550+. Machine work is the same either way.
- Rings: standard replacement set gapped to bore, torque-plate hone, real break-in under load.
- New LPOP, oil cooler o-rings.

**Fuel**
- Stage 1.5 hybrid injectors 238cc/80% (250/100 is the step up). See II catalog below for the single-shot alternative.
- HPOP upgrade required: Terminator T500 or Adrenaline. Not available from II.
- Regulated return fuel system (Driven Diesel or Riff Raff) to stop #8 starvation.
- FASS or AirDog lift pump.

**Air**
- Wastegated S300-class turbo: KC300x 63/68 or Riff Raff S366 kit. Stock GTP38 maxes around 350.
- Bellowed up-pipes.
- 4" downpipe and exhaust, non-EBPV pedestal.
- Stock 99-03 intercooler is fine to 500.
- Expect mid-30s boost.

**Tuning**
- Hydra chip, custom tunes. Roughly 350 daily tune + 450 hot tune.

**Electrical refresh**
- UVCH, glow plugs and relay, new CPS plus a spare in the glovebox.

**Gauges**
- EGT, boost, trans temp, ICP.

**Cooling**
- New radiator sized to the F600, HD fan clutch, new water pump, 190 t-stat, big trans cooler.

---

## Machine shop: Family Machine LLC, Denver CO

Status 2026-10-16: Jacob is tearing the 7.3 down and sending it to Family Machine for a full like-new job.

**Work order given to Jacob:**
- Bake, blast, magnaflux block
- Torque-plate bore and hone to supplied pistons
- Deck
- Line hone mains
- Cam bore check
- Crank magnaflux, polish, balance with rods + pistons + flexplate + damper
- Heads pressure-tested, resurfaced, new guides, seats, valves, springs, injector cups
- Cam bearings and freeze plugs
- All clearances in writing

**Bore size rule:** do NOT order pistons until the shop measures the bores. Stock is 4.11", but **this block is already .030 over (4.140)**: the reman pistons are stamped .030 (found 2026-10-23, photos in `reference/photos/`). II coated pistons are std/.020/.040 only, so .040 is the only II option and it leaves .010 of cleanup. If a hole needs more than .010, sleeve it back or look at a piston brand with more oversize options. Tell Family Machine before they pick a bore target.

**Important:** Industrial Injection coated pistons come in **standard / .020 / .040 only, no .030.** Tell Family Machine before they pick a bore target. The shop needs the piston oversize spec and the rod set in hand before boring and balancing.

---

## Industrial Injection 7.3 catalog (web list prices, pulled 2026-10-16)

**Pistons**
- X-Series Piston Kit SKU 34D106, from $1,499.95. Coated & Chamfered variant: thermal barrier crown, anti-scuff skirts, chamfered edges, 17.3:1, .015" reduced comp height, rings/pins/clips included. Oversizes: standard, .020, .040 only.

**Injectors (99.5-03 AD)**
- New Performance $483.95 base; Reman Performance $259.95 base + core.
- Stage 1: 120cc/15%, ~325 hp
- Stage 2: 160cc/20%, ~380 hp
- Stage 3: 230cc/20% **single-shot**, ~450 hp, needs HPOP upgrade and more air. Matches the target but loses split-shot pilot injection (more cackle, rougher cold idle).
- Stage 4: 285cc exchange hybrid
- Alternative: aftermarket 238cc/80% split-shot hybrids. **Jacob to decide.**

**Turbos**
- XR1 Series SKU 706447-0003-XR1, $1,685.95 (66mm/88mm billet wheel, .84 A/R, modified stock GTP38 drop-in)
- Garrett PowerMax GTP38R ball-bearing kit, $2,101.36
- BorgWarner S300 SX-R 68/68 super-core, $1,049.97 (core only; pedestal kit from Riff Raff or KC)
- Reman stock $1,029.95; reman hybrid billet $1,202.95
- Blank no-EBPV pedestal $199.44; blank EBPV outlet $113.86; install kit $66.55

**Fuel / oil**
- FASS Titanium Signature 140GPH $784; FASS sump $179
- IPR valve $277.88; IPR seal kit $20.85; HPOP seal kit $99.39
- HPOP is OE reman only ($1,280.50), not an upgrade. Terminator/Adrenaline must come from elsewhere.

**Electrical**
- Reman IDM $596.64; UVCH $106.51; glow plug relay $57.02; ICP/EBP pigtail $49.60; EBP sensor $106.69; starter $380

**Gaskets**
- Oil cooler o-ring kit $102.93; valve cover gasket kit $188.67; injector cup sleeve $27.10 ea; HEUI injector seal kit $12.57

**Not at II (source elsewhere)**
- Connecting rods for 7.3 (site lists Cummins/Duramax only; Jacob says II is supplying rods, **confirm brand**, likely drop-shipped Crower/Carrillo)
- ARP head studs, cam and lifters, bearings, HPOP upgrade, regulated return kit, up-pipes, exhaust, Hydra chip and tunes, radiator

---

## Reference

Dave's Auto Center (Utah), "FULL Rebuild on a 7.3L Powerstroke: An Iconic Workhorse Resurrected", Aug 2024, ~28 min: https://youtu.be/sa7WUEIFpKo

What they did: block oven-baked ~700F for 1 hr then shot blasted (stress relief), magnafluxed, every bore re-centered (factory bores off-center); Crower forged rods; balanced crank; upgraded cam; Speed of Air dimpled pistons (claimed ~200F lower EGT, ~150 ft-lb gain); heads O-ringed; new valves (old ones tuliped); new injector cups via tap-and-pull tool. No turbo, injector, or trans content. Copied into this plan: bake + blast, bore centering, balance, forged rods. Not copied: O-rings, Speed of Air.

---

## Fasteners: ARP everywhere it can be (Jacob, 2026-10-21)

Rule: any fastener on this engine that ARP makes a kit for gets ARP. Anything they don't make a kit for gets ARP bulk 12-point hardware in the right thread and length, except where OEM is the right call (noted below). Prices are web list, 2026-10-21.

### Application-specific ARP kits for the 94-03 7.3 Powerstroke

| Fastener | ARP p/n | Notes | Price seen |
|---|---|---|---|
| Head studs | **250-4201** | ARP2000, 12pt nuts, washers, Ultra-Torque lube included. The number one item. Torque per the ARP card in three passes, not the Ford spec. | $670 to $790 |
| Main studs | **250-5801** | 8740 chromoly, nuts and washers. **Family Machine must line-hone the mains with these studs installed and torqued.** Studs load the caps differently than bolts. Tell the shop before they touch the mains and send the studs with the block. | $425 |
| Flexplate bolts | **150-2802** | 10 bolts, 12pt, 8740 black oxide. Blue Loctite on threads, ARP lube under heads, torque per ARP card (Ford stock spec is 85-89 ft-lb; XDP's equivalent kit says 115; use ARP's number for ARP bolts). | $78 |
| Rod bolts | 250-6303 | **Do not order.** That kit is for 94-00 factory forged rods. The new II forged rods come with their own bolts. Confirm with II that the rod bolts are ARP (most aftermarket forged rods ship with ARP2000). |  |
| Damper bolt | none found | The 7.3 damper is one center bolt at 212 ft-lb. ARP 150-2505 is the 4-bolt kit for 6.0/6.4, does not fit. Use a new OEM bolt. If a Fluidampr (720211) or ATI (918889) goes on, use what they supply. |  |

### Generic ARP hardware (bulk 12-point, pick thread and length)

ARP sells metric 12-point bolts in 5-packs, 8740 black oxide or stainless. Measure the old bolt (thread, pitch, length under head) as each comes off today and write it on the bag. Then the order is just a list.

| Location | Approx. thread | Qty | Material | Notes |
|---|---|---|---|---|
| Exhaust manifolds to heads | M10 x 1.5 | 16 | Stainless | The classic 7.3 breakage point. Stainless with anti-seize on the threads. Ford torque 45 ft-lb, use ARP's figure for stainless. |
| Up-pipes to manifolds and collector | M10 x 1.5 | 8 | Stainless | Bellowed up-pipe kits usually include hardware, check before ordering. |
| Turbo pedestal to block, turbo to pedestal | M10 | 6 | Black oxide | Non-EBPV pedestal may come with its own. |
| Valve covers | M8 x 1.25 | 20 | ARP studs + 12pt nuts, or Dieselsite 7.3 stud kit | Back on the list now that billet aluminum covers are going on (2026-10-22). Still low torque, follow the cover maker's number. |
| Oil pan to block | M6 x 1.0 (10mm head, Jacob confirmed 2026-10-21) | ~24 | Black oxide | Ford WSM: 11 Nm / 8 ft-lb. The Riff Raff sheet says 18, that is wrong for an M6 into the rear cover flange. Use 8. |
| Front cover, rear cover | M8 | ~30 | Black oxide | 15 ft-lb. |
| Water pump | M8 | 4 | Black oxide | |
| Oil cooler headers, HPOP, reservoir | M8 | ~14 | Black oxide | 18 ft-lb. |
| Intake Y-bridge and intake cover | M8 | ~12 | Black oxide | |
| Bellhousing (4R100 to block) | M12 x 1.75 (confirm) | 8 | Black oxide | Measure one of the bolts in the pile. |
| Starter | M10 or M12 | 3 | Black oxide | |
| Engine mounts to block | M12 | 8 | Black oxide | Custom mounts for the F600, so these get sized when the mounts are built. |

### Leave OEM

- **Injector hold-down bolts.** 120 in-lb, they clamp the injector into the cup and o-rings. New Ford or II bolts.
- **Rocker pedestal bolts.** 20 ft-lb, OEM is fine. ARP if he wants, it buys nothing.
- **Glow plugs, sensors, fittings.** Not fasteners.
- **Cam thrust plate, lifter guide bolts, oil jet bolts.** Low torque, OEM.

### Rules that come with ARP

- ARP torque values assume ARP Ultra-Torque lube. Don't use oil or moly and the ARP number together. One lube, one number, from the card in the box.
- Chase every threaded hole in the block and heads before studs go in. Clean dry threads, hand-tight studs, torque the nuts.
- Stainless galls. Anti-seize on every stainless exhaust bolt.
- Keep the ARP instruction cards. Put them in `reference/arp/` when they arrive.

---

## Open items

- Engine is a Dealers Diesel reman (tag found 2026-10-22, reman serial 440469, rated 215 hp). Jacob believes it is a 94-97 OBS core. Navistar serial hunt is over. Rod type to be confirmed by eye when the rods come out. History and mileage unknown.
- **Generation check:** 215 hp is the 96-97 rating. Confirm 99-03 vs 94-97 from injector codes (AB/AD split-shot vs AA single-shot) and EBPV pedestal. No injectors came with the engine, so use the front cover (94-97 mechanical lift pump pad), EBPV pedestal, oil cooler style, head castings. **Either way the fuel and electronics package is bought as 99-03** (injectors, HPOP, IDM, PCM, harness); the generation only changes the oil cooler and whether a lift pump boss gets plugged.
- Bore size after Family Machine measures (then order pistons). Block is already .030 over, so .040 II pistons only if every hole cleans at .010; otherwise sleeve or change piston brand.
- Confirm rod brand coming through II
- Injector choice: 238/80 split-shot hybrid vs II Stage 3 single-shot
- Fastener sizes: measure thread, pitch, and length of flexplate, bellhousing, manifold, pan, and cover bolts during teardown so the ARP bulk order can be placed
- Confirm the II rod bolts are ARP
- Axle sources and gear ratio
- Tire size
- Engine mounts and radiator fitment in the F600
- Wiring harness vendor (standalone 7.3 PCM)
- Transmission purchase and builder
- Flatbed design
- Billet valve covers: call Choate (pair vs each, CCV provision), pick color, order with the engine parts
