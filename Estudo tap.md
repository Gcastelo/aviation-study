## Falha de Comms
* VFR
    * Remain VMC
		1. Set transponder 7600
		1. Land nearest airfield
		1. Inform ATC of current position and situation

* IFR
    1. 7600. If total failure then 121.50
    * ATC airspace
        * Remain on assigned FL and speed for 20min after the failing the next report point then adjust FL and speed according to FP.
    * ATS airspace
        * Mantain last FL and speed for 7 min since
            * achieved last assigned altitude OR		
            * 7600 was set OR
            * failing the last mandatory report
            whichever is later
        * then adjust FL and speed according to FL
    1. If being vectored, proceed as direct as possible to FP route never later than next significant point, considering Minimum flight altitude
    1. Proceed according to FL to navaid serving destination airfield and execute a hold before descending
    1. Start descending at last ETA given or close as possible. If no ETA was given, before comm failure, descend at ETA of FP.
    1. Init and execute published procedure for navaid (how to know active runway if no comm?)
    1. Land if possible < ETA + 30min
				

## ICAO Annexes
    18 annexes


## Flight Plan
FP required for
* Any flight or part of flight requiring ATC
* Any IFR flight
* Any flight inside designated areas or routes providing information and SAR
* Any flight inside designated areas or routes that by ATS request require coordination with military areas to avoid interception
* Any flight crossing country borders

> 1h < Submitted time < 120h. If delay for EOBT+30, report delay. Otherwise submit new.


## RVSM
* 1000ft separation between FL290 and FL410
* Requires TCAS2-RA and qualified crew
* Non complaint aircraft cannot use RVSM FLs or must avoid RVSM zone

## Load factor
	N = Total lift / Total Mass => 1 / cos O

## Circling minimums
	
    		A	B	C	D
	MDH		400ft	500ft	600ft	700ft
	Min Met Vis	1500m	1600m	2400m	3600m


## VFR Rules
    Alt                         Airspace            Flight Visibility   Distance from cloud
    >= 10000ft                  A B C D E F G       8km                 1500m horizontal, 1000ft vertical
    
    3000AGL < alt < 10000ft
    or                          A B C D E F G       5km                 1500m horizontal, 1000ft vertical
    > 1000ft AGL
    whichever higher

    < 3000 MSL
    or                          A B C D E           5km                 1500m horizontal, 1000ft vertical
    > 1000ft AGL                
    whichever higher                F G             5km                 Clear of clouda and with surface in sight

## Alternates

### Takeoff alternate max distance of:

    2 engine airplane     1h flight INOP engine
    +2 engine airplane    2h

### Route alternate
    No need for alternate unless contigency is 3%

### Landing alternate

    Mandatory for IFR unless:
    * total flight, or replanning is < 6h
    * Destination airfield has 2 separated operational runways and TAF states that 1h < ETA < 1h has at least 2000' or 500' for circling whichever higher and VIS >= 5km
    * Isolated airfield (>2h from any other airfield)

### RNP
    Based on PBN (Performance based-navigation) and allows fix to fix nav. Similar to RNAV but with onboard monitoring and alert.

    Also refers to demanded accuracy for a sector. I.e RNP 0.3 requires the aircraft to be within 0.3Mn of the segment.

    ANP - Actual navigation performance

### RNAV

    Fix to Fix nav
    navaid or radial based from a VOR/DME
    5 letter ids

### GPS 
    24 Satellites

### Altitudes
* MAA - Maximum authorized altitude
* MCA - Minimum crossing altitude
* MCL - Minimum cruising level
* MEA - Minimum enroute altitude - Ensures radio coverage between two radio aids and maintains separation for obstacles
* MHA - Minimum holding altitude - Ensures radio coverage, comms and obstacle clearance
* MGA - Minimum* Grid Altitude - For offroute. Separation of obstacle+100 and:
    * +1000 - for altitudes below 6000
    * +2000 - for altitudes above 6000
* MSA - Minimum sector altitude - Min alt around a navaid or reference point, default 25mn, of at least 1000' above obstacles. Can be slip in segments
* MOA - Minimum Operating Altitude - Minium altitude for operating a flight considering:
    * Operational procedures
    * Aircraft performance
    * Weight
    * Weather conditions

* MORA - Minimum Off Route Altitude - min altitude 10mn each side of obstacle
* GRID MORA - same as MORA but defined by lat and long
* MTCA - Minimum terrain Clearance Altitude - Min altitude on air corridor, SIDS and STARS. Based on:
    * For SID and STAR - horizontly 5Mn to each side
    * For air corridors - 10 Mn each side
    * Vertically - 1000' if < 6000;  2000' if > 6000
* MOCA - Minimum obsctacle clearance altitude - Min altitude for any segment of the flight. Published for each route
* MDA (H) - Non precision min altitude. Not allowed to desced if no visual references to airport. MDH for circling is based on airfield elevation
* DA (H) - Altitude for precision approach at which go around is initiated if no visual refrences to continue approach.

* ILS Mininmus

Category        DH      RVR                 VIS

CAT I           200'    550m                800m
CAT II          100'    >= 300m
CAT IIIA        < 100'  >= 175m
CAT IIIB        < 50'   50m < RVR < 175m
CAT IIIC        -       -                   -

### Fuel

#### Contigency

The bigger of:
* 5% of planned fuel, or 5% of remaining fuel if replanning
*     
#### Final Reserve
    Jets - 30 min at 1500ft above airfield elevation
    Props - 45 min



### GPWS 

Mandatory for > 5700kg

7 modes

* Mode 1 - excessive rate of descend
* Mode 2 - min terrain distance
* Mode 3 - Sink rate
* Mode 4 - Flaps or landing gear not set for landing
* Mode 5 - Too low ILS
* Mode 6 - Below mininums
* Mode 7 - Windshear

#### Priorities

Max priority:

* Whoop whoop pull up (1,2,3,4)
* Terrain, terrain (2)
* Too low gear (4a)
* Too low terrain (4b)
* Minima, Minima (6)
* Sink rate, Sink rate (1)
* Don't sink, don't sink

Low priority:
* Glide slope, glide slope

#### Inputs
* Baro altitude
* Landing gear position
* Flap position
* Throttle position
* Radio altimeter
* Glideslope

#### Captain can ignore warnings if:
* 1000' vertical and 1km horizontally clear of clouds
* 8.5km Vis
* Daylight
* Not in danger

### Point of No return

Distance = speed * time

O = GS out
H = GS home
E = safe endurance
D = total sector distance

* TimeToPNR = (E * O) / (O + H)

* Distance to PNR = timeToPnr * O

### Point of Equal time / Critical Point

* PeTDist = (D * H) / (O + H)

* time to CP = CPDist / O


