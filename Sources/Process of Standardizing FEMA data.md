# Overview of Standardizations File, for FEMA Dataset.
**This file contains backend information on what we needed to do to standardize FEMA county names. In case we need to reference it.**

## Steps Used to Standardize a singular FEMA dataline:
***Do this process for EVERY row // EVERY Disaster from 2000-2022...***
1. **Convert FEMA State abbr. (NM -> New Mexico)**
2. **Remove "Fluff" from FEMA counties**
   * " (County)"
   * " (Parish)"
   * " (Borough)"
   * " (Census Area)"
   * " (City and Borough)"
   * " (Municipio)"
3. **Separate any county w/ "Reservation" Keyword** *(Since our maps split between counties & reservations)*
4. **At this point our County has been cleaned -> Check if there's a match w/ our ArcGIS .shp files?**
   1. **Yes, match**
      * Append associated FID
   2. **No, no direct match.**
      * Manually check these things:
        1. **Diff. spelling?**  *(Ex, "St. Louis" vs. "St Louis")*
        2. **Independent City Combo?**  *(Ex, "Bedford City" vs. "Bedford County" - 2 diff. locations in same state)*
        3. **Part of American Samoa or Northern Mariana Islands?**  *(these territories not yet mapped)*
        4. **Is it a reservation, that didn't have "reservation" keyword?**  *(Ex, Absentee Shawnee-Citizens Band of Potawatomi)*
        5. **Is it large enough to even EXIST in our map?**  *(Ex, FEMA Disaster in an area called "T05 ND BPP, Maine." - is a tiny rural town, does not have it's own official county! Yet, received funding from FEMA.)*
        6. **Does it have this type of callsign "...(in (P)MSA 1120,2600,4560)"?**  *Ignore, it's just a tiny farm in Maine or Massachusetts*
        7. **Some other minor exclusion**
