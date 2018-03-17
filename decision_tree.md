~~~~
# Decision tree

On each step a decision is taken, all but one options are eventually rejected and all further decision are based on taken decision.

Independent decision that do not follow from previous ones are shown as separate branches, with their own title and branch numbers.

## Structure

1) Material
	50$/m3 40Mpa pallets
		+20$ 40h dismantle, +200$ 40h treatment
	100$/m3 4Mpa concrete
		+30$ 3h rebar/fibre, +30$ 3h mold
	200$/m3 80Mpa bamboo
		+200$ 40h treatment
	1k$/m3 60Mpa timber
		+200$ 40h treatment
	200$/m3 50Mpa plastic recycled
		+160h, +100k$ capital investments
	500$/m3 50Mpa plastic secondary
		+1000h, +5k$ capital investments
	1.2k$/m3 100Mpa plastic granules
		+1000h, +3k$ capital investments
	4k$/m3 100Mpa aluminium
		+200$ 3h paint anti rust
	4k$/m3 400Mpa steel
		+200$ 3h paint, +200$ 10h zinc protection
	4k$/m3 500Mpa plastic fibre
	4k$/m3 2Gpa fiberglass
		+4k$ 20h epoxy, +100$ 5h mold, +200$ 3h paint
Decision: Steel
Reason: price, capital investments, time

2) Fasteners to join beams/slabs together
	material*3 h $/m3 wedge locks
	100$/m3 30h polyprop strapping
	30$/m3 20h glass fiber strapping
	1k$/m3 10h bolts
	100$/m3 4h welding
Decision: Weld
Reason: Price, well tested, creep, time, hermetical seal
Decision: bolts
Reason: simplicity, creep, time

3) Protection (per 1m3 of main material)
	10$/m3 paint, PS+toluene
	100$/m3 oil derivatives
	300$/m3 epoxy
	4$/m3 zinc anodes
	40$/m3 zinc electroplating
Decision: paint + zinc anodes
Reason: price, well tested, environment, time

4) Bouyoncy
	75$/t plastic barrels
		+standard
	100$/t single hull
		-expensive facilities -cant be done small
	150$/t prestressed sphere on rebar mold 1/2
		-very expetimental
	150$/t prestressed sphere with rebar struct
		-very expetimental, +more strength
	20$/t welded steel floats
		-need perfect rust protection
Decision: plastic barrels, later welded floats
Reason: quick start, price, time, work, facilities

5) Superstructure
	sierpinski pyramid
		+rebuild, +best strength, +price, -aesthetic
	inflatable dome
		+best price, +mirror/transparent, -waves
	geodesic dome
		+strength, +aesthetic, -price
	monolithic simple shape
		+build, -logistics, -repair, -worst price
	flat, modules with flexible joints
		+best rebuild, -waves
		-storm-proof 8-12 flex joints per module
Decision: sierpinski pyramid
Reason: price, wave protection

6) Wave protection
	elevated sttucture with exposed trusses
		+replacable, +waves, +mobility, -aesthetics
		10k$/person
	structure wall
		+collision protection, +mobility
		30k$/person
	separate fragmented truss breakwater
		30k$/person, +rebuild
	separate monolithic truss breakwater
		100k$/person, -aesthetics
	separate solid wall breakwater
		1kk$/person
	pneumatic active breakwater
		10k$/person, 100$/person per day of storm
	moonpools as absorbers
		10k$/person, generate energy 10$/person/day
	no wave protection
		-30% population	and their relatives
Decision: elevated structure
Reason: price, rebuild, mobility
Decision: separate fragmented truss breakwater
Reason: aestetics, rebuild
Decision: pneumatic + structure wall
Reason: best protection, mobility

7) Floats type
	hermetically sealed deep floats
		No wave reaction, no wave hits, cost x4
	hermetically sealed surface floats
		direct wave reaction, cost x2
	deep moonpools
		reverse wave reaction, no wave hits, cost x1
	surface moonpools
		weak direct wave reaction, cost x1
Decision: 100% deep moonpools, with dynamic control
Reason: best wave cancellation, rebuild
Decision: 90% deep floats 10% surface floats
Reason: best static stability
Decision: 33% deep moonpools and 67% surface moonpools
Reason: best price, static stability, rebuild, energy

8) Landing gear
	Paw: separate upside down truss pyramids and flat bottom floaters
		+can use standard barrels	
	Rib: united with upside down pyramids floaters
		+price, +backup bouyoncy
Decision: Paw initially, then rib 
Reason: same height, but rib is cheaper because no need to double structure for floating and sitting support 

9) module shape, for non-flexible layer
	rectangle
		+0% sheeting, -20% strength, +0% usage
	triangle 60*60*60*
		-20% sheeting, +0% strength, -50% usage
	hexagon prism
		-20% sheeting, -40% strength, -20% usage
	vertical cylinder
		-40% sheeting, -100% strength, -30% usage
	horizontal cylinder
		-40% sheeting, -1000% strength, -40% usage
Decision: rectangle
Reason: best usage(for rectangle items) per strength and cost

10) floaters shape with nose and tail, side cx
	rectangle
		+0% sheeting, -50% strength, cx=1.4
	triangle 60*60*60*
		-20% sheeting, -50% strength, cx=1
	hexagon prism
		-20% sheeting, -50% strength, cx=1
	vertical cylinder
		-40% sheeting, +0% strength, cx=0.8
	horizontal cylinder
		-40% sheeting, -30% strength, cx=0.3
Decision: horizontal cylinder
Reason: best cx(drag) for given strength and cost

11) anchors
	big chunk of concrete
		30$/t, x1 weight to holding force, 10$/drop
	steel anchor
		100$/t, x4 weight to holding force, 10$/drop
	piles
		10$/t, x40 weight to holding force, 100$/drop
	suction caissons
		30$/t, x20 weight to holding force, 30$/drop
Decision: suction caissons
Reason: pile hammering is too expensive and prohibited in populated areas, concrete needs too heavy machinery and anchor is too expensive and also needs too much machinery

12) angle sensors
	pipe with fluid
		-wave interaction causes bad readings
	accelerometer
		-a bit more expensive
Decision: accelerometer
Reason: increase in price is way smaller than saved cost of risk of bad reading from mechanical sources of angle data

## Infrastructure

1) Potable water, capital investments(>3m3/mo) 
	30$ 3kj/kg reverse osmosis
		+100kj/kg price equivalent for filters
		+10kj/kg when rain water is used
	1k$ 400kj/kg membrane distillation
	1k$ 100kj/kg water compression evaporator
		+gives almost free waste disposal
	10k$ atmospheric water net condenser
	1k$ 0.1kj/kg wedge wire screen
		1kt per day, 75 micron solids, 30k people
	30$ rain collection
		50sqm per person, roof already exists
	1k$ 400j/kg acid/base + ionexchange buffer
Decision: Rain collection and osmosis 
Reason: they compensate each other minuses, both are well tested

2) Energy
Sun 
	10$ 1w/$ PV
	100$ 0.1w/$ 10wHeat/$ evacuated tubes
	1k$ 3w/$ 10wHeat/$ PV + mirrors + cooling
	1k$ 0.3w/$ 3wHeat/$ through+mirrors+turbine
	10k$ 0.1w/$ 3wHeat/$ algae grown for fuel
	100k$ 1w/$ 3wHeat/$ tower+mirrors+turbine
Wind
	1k$ 0.3w/$ vertical axis windmill
	1k$ 0.1w/$ drag-based vertical axis windmill
	1k$ 1w/$ classical windmill
	10k$ 3w/$ flying windmill
Waves
	1k$ 0.3w/$ pneumatic, moonpool + turbine
	1k$ 0.3w/$ mechanical, bending joint
Decision: PV, classical windmill, pneumatic
Reason: well tested, diversity, capital cost

3) Roads
	1-10% of modules fully designated as roads
	1-10% of surface of every module for roads
Decision: designated modules
Reason: more flexibility, same cost

4) Electric network
	220v 50hz
		99% compatibility, generator cost x3
	220v 0hz
		80% compatibility, generator cost x1
		cheap network joining/balancing
	220v 400hz
		10% compatibility, generator cost x2
		needs minimal shielding of a wire from iron
	220v 2khz
		10% compatibility, generator cost x1
		needs heavy shielding of a wire from iron
	1kv 2khz
		0.1% compatibility, generator cost x1
		wire cost x0.2, death risk, needs shielding
	1kv 0hz
		0.1% compatibility, generator cost x1
		wire cost x0.2, death risk, cheap balancing
	12v 0hz
		wires cost x20, 10% compatibility
		generator cost x1, invertors cost x20
Decision: 220v 0hz
Reason: low health risk, cheap network joining, reasonable compatibility, cheap generators, cheap invertors

~~~~
