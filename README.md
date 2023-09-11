# DRASTIC Database Repository

###### :exclamation: Current Obj: Fixing "statewide" bug :exclamation:


</br>


#### :boom: Announcements :boom:
💥 BUG FOUND: "statewide" FEMA affected counties did not receive +1 freq, when prev. unaffected. Total "statewide" affected datasets ~ 20. Solution found. Need to re-run datasets.

</br>
</br>

---

#### 👉 Pipeline of Current Objectives 👈
✨ ***Article Prep***
- [X] All nursing schools in the US  ![](https://geps.dev/progress/100)
- [X] All violent crime NM  ![](https://geps.dev/progress/100)
- [X] Households under 18 in 2020  ![](https://geps.dev/progress/100)
- [X] Lifelong learning – less than high school 2020  ![](https://geps.dev/progress/100)
- [X] FEMA – fire in NM  ![](https://geps.dev/progress/100)

</br>

---

✨ ***Datasets affected by FEMA "statewide" Bug***
- [X] FEMA Severe Storm(s) 2000-2005 (2000), statewide = ND  ![](https://geps.dev/progress/100)
- [X] FEMA Severe Storm(s) 2000-2005 (2000), statewide = AZ  ![](https://geps.dev/progress/100)
- [X] FEMA Severe Storm(s) 2000-2005 (2002), statewide = IN  ![](https://geps.dev/progress/100)
- [X] FEMA Severe Storm(s) 2000-2005 (2003), statewide = PA  ![](https://geps.dev/progress/100)
- [X] FEMA Fire 2000-2005 (2001), statewide = OR  ![](https://geps.dev/progress/100)
- [X] FEMA Fire 2000-2005 (2002), statewide = CO  ![](https://geps.dev/progress/100)
- [X] FEMA Fire 2000-2005 (2003), statewide = NM  ![](https://geps.dev/progress/100)
- [X] FEMA Fire 2006-2014 (2009), statewide = TX  ![](https://geps.dev/progress/100)
- [X] FEMA Fire 2006-2014 (2009), statewide = OK  ![](https://geps.dev/progress/100)
- [X] FEMA Fire 2006-2014 (2009), statewide = TX  ![](https://geps.dev/progress/100)
- [X] FEMA Fire 2006-2014 (2012), statewide = OK  ![](https://geps.dev/progress/100)
- [X] FEMA Other 2000-2005 (2003), statewide = NY  ![](https://geps.dev/progress/100)
- [X] FEMA Hurricane 2000-2005 (2005), statewide = WI  ![](https://geps.dev/progress/100)
- [X] FEMA Hurricane 2000-2005 (2005), statewide = TX  ![](https://geps.dev/progress/100)
- [X] FEMA Severe Ice Storm 2006-2014 (2007), statewide = MO  ![](https://geps.dev/progress/100)
- [X] FEMA Hurricane 2006-2014 (2012), statewide = PA  ![](https://geps.dev/progress/100)
- [X] FEMA Biological 2015-2022 (2020), statewide = LA  ![](https://geps.dev/progress/100)
- [X] FEMA Hurricane 2006-2014 (2011), statewide = RI  ![](https://geps.dev/progress/100)
- [X] FEMA Fire 2015-2022 (2016), statewide = CO  ![](https://geps.dev/progress/100)
- [X] FEMA Fire 2015-2022 (2021), statewide = WA  ![](https://geps.dev/progress/100)


<!---
✨ ***ArcGIS Online, Known Bugs or Issues***
- [ ] UnOptimized Performance Loading Maps
- [ ] Fix Religious Orgs Lat/Long Coordinates. Invalid coordinate values.
- [ ] Air quality datasets needs standardizing.
- [ ] Employment dataset is still RAW, need parsing + standardizing.
- [ ] Misc. Datasets not uploaded (Fault Lines, Nuclear Power Plants, etc.)
- [ ] (Not-a-bug) Double check FBI Agencies Lat/Long Coordinates.
- [ ] (Not-a-bug) Spot-check all datasets once uploaded to ArcGIS Online.

</br>

✨ ***FEMA Disasters***
- [X] Pull FEMA Declaration Summaries data, to now include years 2000-2022.  ![](https://geps.dev/progress/100)

  - [X] Split old FEMA .shp files into 3 separate files w/ data from 2000 - 2022  ![](https://geps.dev/progress/100)
  
    - [X] Assigned FEMA 2000-2009 Data  ![](https://geps.dev/progress/100)
    
    - [X] Assigned FEMA 2010-2019 Data  ![](https://geps.dev/progress/100)
    
    - [X] Assigned FEMA 2020-2022 Data  ![](https://geps.dev/progress/100)

- [X] Map all 114 FEMA Disaster Datasets w/ Years (2000-2009, 2010-2019, 2020+) ![](https://geps.dev/progress/100)
      
    - [X] Create all 19 FEMA disaster types (bio,hurricane,etc.) in each FEMA grouped dataset.  ![](https://geps.dev/progress/100)

        - [X] Assign datapoints to all 19 FEMA disaster types, for group 2000-2009  ![](https://geps.dev/progress/100)
  
        - [X] Assign datapoints to all 19 FEMA disaster types, for group 2010-2019  ![](https://geps.dev/progress/100)
  
        - [X] Assign datapoints to all 19 FEMA disaster types, for group 2020+  ![](https://geps.dev/progress/100)
  
    - [X] Identify Reservations vs. Counties in our datasets  ![](https://geps.dev/progress/100)

    - [X] Split data into Counties & Reservations  ![](https://geps.dev/progress/100)
  
    - [X] Build a Frequency Counter to count how many of each type of disaster (19 types) occurred, per county (per reservation), and per group year.  ![](https://geps.dev/progress/100)
  
    - [X] Map, all 19 disasters from group 2000-2009  ![](https://geps.dev/progress/50)
  
    - [X] Map, all 19 disasters from group 2010-2019  ![](https://geps.dev/progress/50)
    
    - [X] Map, all 19 disasters from group 2020+  ![](https://geps.dev/progress/100)

- [X] Re-group FEMA Data into groups: 2000-2005, 2006-2014, 2015-2022  ![](https://geps.dev/progress/100)

- [X] Upload new re-grouped FEMA Data  ![](https://geps.dev/progress/100)

- [ ] Map new re-grouped FEMA Data  ![](https://geps.dev/progress/50)

</br>


✨ ***Census*** 
- [X] 2020 Census (w/ %-Values)  ![](https://geps.dev/progress/100)

    - [X] Assign IDs to all 3,000+ U.S. Counties + Find any missing counties  ![](https://geps.dev/progress/100)
  
    - [X] Fix the "Income" .csv Bug when mapped to ArcGIS Pro Software  ![](https://geps.dev/progress/100)

    - [X] Convert whole values -> percent  ![](https://geps.dev/progress/100)
  
    - [X] Map all 30 Census Database Attributes  ![](https://geps.dev/progress/100)

- [x] 2010 Census (w/ %-Values)  ![](https://geps.dev/progress/100)
    - [ ] Find & Add "Employment" figures, for all counties.  ![](https://geps.dev/progress/00)

    - [ ] Find & Add "Insurance" figures, for all counties.  ![](https://geps.dev/progress/00)
    
    - [X] Convert Estimates -> Percents  ![](https://geps.dev/progress/100)
    
- [X] 2000 Census (w/ %-Values)  ![](https://geps.dev/progress/100)
    - [ ] Find & Add "Employment" figures, for all counties.  ![](https://geps.dev/progress/00)

    - [ ] Find & Add "Insurance" figures, for all counties.  ![](https://geps.dev/progress/00)
    
    - [X] Convert Estimates -> Percents  ![](https://geps.dev/progress/100)

- [ ] Language Proficiency  ![](https://geps.dev/progress/00)
    - [ ] 2000s   ![](https://geps.dev/progress/00)

    - [ ] 2010s    ![](https://geps.dev/progress/90)
        * Need to standardize

    - [ ] 2020s    ![](https://geps.dev/progress/00)

</br>


✨***7 Pillars of Health and Well-Being***
- [ ] Compile a list of sources for the 7 Pillars for Health and Well-Being  ![](https://geps.dev/progress/90)

    - [ ] Still need data for "Thriving and Natural World"...suggestions welcomed! 

- [X] Pull all *possible* 7-Pillars Datasets  ![](https://geps.dev/progress/100)

- [X] FBI Crime Statistics  ![](https://geps.dev/progress/100)

    - [X] 2000 FBI Statistics  ![](https://geps.dev/progress/100)

    - [X] 2010 FBI Statistics  ![](https://geps.dev/progress/100)
     
    - [X] 2020 FBI Statistics  ![](https://geps.dev/progress/100)

</br>


✨***Miscellaneous***
- [X] Upload Census Datasets (2000, 2010, 2020) as both Estimates & Whole Values.  ![](https://geps.dev/progress/100)

- [ ] Clean up DRASTIC repository w/ better README's & Folder Structures  ![](https://geps.dev/progress/00)

</br></br>


-->


#### :point_right: Cheat Sheets
- MD Syntax: <https://www.markdownguide.org/basic-syntax/>
  - Quick Reference: <https://www.markdownguide.org/cheat-sheet/>
- GitHub Emojis: <https://gist.github.com/rxaviers/7360908>
- Progress Bars: <https://github.com/gepser/markdown-progress>
- Link to Zip any folder from this Repository: <https://kinolien.github.io/gitzip/>
    * *Just open link, copy/paste URL into "GitHub repo root URL or sub-folder URL", & press "Download"*
