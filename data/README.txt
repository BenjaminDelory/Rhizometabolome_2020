This README.txt file was generated on 20200826 by Benjamin Delory

-------------------
GENERAL INFORMATION
-------------------

1. Raw data used for the following paper: Delory et al (2020) The rhizosphere metabolome triggers species-specific and context-dependent root responses in later arriving plants.  

2. Author Information

  Principal Investigator Contact Information
        Name: Benjamin M. Delory
        Institution: Institute of Ecology, Leuphana University
        Address: Universitaetsallee 1, 21335 Lueneburg, Germany
        Email: benjamin.delory@leuphana.de; delory.benjamin@gmail.com

3. Date of data collection: from May 2018 to January 2019 

4. Geographic location of data collection: Lüneburg, Germany

5. Data collected by Benjamin M. Delory, Hannes Schempp, Sina Maria Spachmann, Laura Störzer, Nicole M. van Dam, Vicky M. Temperton, Alexander Weinhold

-----------------------------------------------
DATA-SPECIFIC INFORMATION FOR: Data_plants.csv
-----------------------------------------------

1. Number of variables: 44

2. Number of cases/rows: 60

3. Variable List
    A. Name: SampleID
       Description: the sample ID number (from 1 to 60)
       Type: integer

    B. Name: Species
       Description: the plant species name (Dd is Dianthus deltoides, Fr is Festuca rubra)
       Type: character

    C. Name: Treatment
       Description: the rhizosphere solution applied to the plant. Soil solution was collected from mesocosms in which a forb (Forbs) or a grass (Grasses) community was sown, as well as from unsown mesocosms containing only soil (Soil, referred to as CTL in the paper).
       Type: character

    D. Name: Replicate
       Description: the replicate number (from 1 to 10)
       Type: integer

    E. Name: F700
       Description: red chlorophyll fluorescence (700 nm)
       Type: numeric

    F. Name: F735
       Description: far red chlorophyll fluorescence (735 nm)
       Type: numeric

    G. Name: Chl50
       Description: Leaf chlorophyll concentration
       Type: numeric
       Unit: mg/m²

    H. Name: SFW
       Description: total shoot fresh weight
       Type: numeric
       Unit: g

    I. Name: LFW
       Description: total fresh weight of 10 young, healthy, and fully expanded leaves
       Type: numeric
       Unit: g

    J. Name: SDW
       Description: total shoot dry weight
       Type: numeric
       Unit: g

    K. Name: LDW
       Description: total dry weight of 10 young, healthy, and fully expanded leaves
       Type: numeric
       Unit: g

    L. Name: LA
       Description: total surface area of 10 young, healthy, and fully expanded leaves
       Type: numeric
       Unit: cm²

    M. Name: SLA
       Description: specific leaf area
       Type: numeric
       Unit: cm²/g

    N. Name: SDMC
       Description: shoot dry matter content
       Type: numeric
       Unit: %

    O. Name: LDMC
       Description: leaf dry matter content
       Type: numeric
       Unit: %

    P. Name: Nleaf
       Description: leaf nitrogen content
       Type: numeric
       Unit: %

    Q. Name: Cleaf
       Description: leaf carbon content
       Type: numeric
       Unit: %

    R. Name: CNleaf
       Description: leaf C:N ratio
       Type: numeric
       Unit: -

    S. Name: Nshoot
       Description: shoot nitrogen content (only available for Dianthus deltoides)
       Type: numeric
       Unit: %

    T. Name: Cshoot
       Description: shoot carbon content (only available for Dianthus deltoides)
       Type: numeric
       Unit: %

    U. Name: CNshoot
       Description: shoot C:N ratio
       Type: numeric
       Unit: -

    V. Name: Nroot
       Description: root nitrogen content
       Type: numeric
       Unit: %

    W. Name: Croot
       Description: root carbon content
       Type: numeric
       Unit: %

    X. Name: CNroot
       Description: root C:N ratio
       Type: numeric
       Unit: -

    Y. Name: RDWns
       Description: root dry weight (non-scanned roots)
       Type: numeric
       Unit: g

    Z. Name: RDWs
       Description: root dry weight (scanned roots)
       Type: numeric
       Unit: g

    AA. Name: RDW
       Description: total root dry weight (RDWns + RDWs)
       Type: numeric
       Unit: g

    AB. Name: PDW
       Description: total plant dry weight (RDW + SDW)
       Type: numeric
       Unit: g

    AC. Name: SMF
       Description: shoot mass fraction
       Type: numeric
       Unit: g/g

    AD. Name: RMF
       Description: root mass fraction
       Type: numeric
       Unit: g/g

    AE. Name: Nuptake
       Description: total N uptake
       Type: numeric
       Unit: g

    AF. Name: TRLs
       Description: total root length (scanned roots)
       Type: numeric
       Unit: cm

    AG. Name: TPSAs
       Description: total projected root surface area (scanned roots)
       Type: numeric
       Unit: cm²

    AH. Name: TSAs
       Description: total root surface area (scanned roots) 
       Type: numeric
       Unit: cm²

    AI. Name: TRVs
       Description: total root volume (scanned roots)
       Type: numeric
       Unit: cm³

    AJ. Name: SRL
       Description: specific root length
       Type: numeric
       Unit: cm/g

    AK. Name: SRA
       Description: specific root area
       Type: numeric
       Unit: cm²/g

    AL. Name: RTD
       Description: root tissue density
       Type: numeric
       Unit: g/cm³

    AM. Name: TRL
       Description: estimated total root length (SRL*RDW)
       Type: numeric
       Unit: cm

    AN. Name: TSA
       Description: estimated total root surface area (SRA*RDW)
       Type: numeric
       Unit: cm²

    AO. Name: TRV
       Description: estimated total root volume (RDW/RTD)
       Type: numeric
       Unit: cm³

    AP. Name: RLD
       Description: root length density in the soil (soil volume = 1826 cm³)
       Type: numeric
       Unit: cm/cm³

    AQ. Name: RSD
       Description: root surface density in the soil (soil volume = 1826 cm³). Used as a proxy for soil exploration in the paper.
       Type: numeric
       Unit: cm²/cm³

    AR. Name: D
       Description: length-weighted average root diameter
       Type: numeric
       Unit: mm

--------------------------------------------------
DATA-SPECIFIC INFORMATION FOR: Data_nutrients.csv
--------------------------------------------------

1. Number of variables: 4

2. Number of cases/rows: 30

3. Variable List
    A. Name: When
       Description: either Before (before addition of salts) or After (after addition of salts)
       Type: character

    B. Name: Treatment
       Description: plant community composition. Soil solution was collected from mesocosms in which a forb (Forbs) or a grass (Grasses) community was sown, as well as from unsown mesocosms containing only soil (Control, referred to as CTL in the paper).
       Type: character

    C. Name: Element
       Description: target macronutrient (N for nitrate, P for phosphate, K for potassium, Ca for calcium, Mg for magnesium)
       Type: character

    D. Name: Concentration
       Description: measured concentration in soil solution samples
       Type: character
       Unit: mg/l

---------------------------------------
DATA-SPECIFIC INFORMATION FOR: DOC.csv
---------------------------------------

1. Number of variables: 3

2. Number of cases/rows: 30

3. Variable List
    A. Name: Treatment
       Description: plant community composition. Soil solution was collected from mesocosms in which a forb (Forbs) or a grass (Grasses) community was sown, as well as from unsown mesocosms containing only soil (CTL).
       Type: character

    B. Name: Replicate
       Description: the replicate number (from 1 to 10)
       Type: integer

    C. Name: DOC
       Description: dissolved organic carbon concentration
       Type: numeric
       Unit: mg/l

-------------------------------------------------------------------
DATA-SPECIFIC INFORMATION FOR: dd_max_heuristic_SN50_bw3_neg_1.csv
-------------------------------------------------------------------

LC-MS data (negative ionisation mode)

1. Number of variables: 48

2. Number of cases/rows: 611

3. Variable List
    A. Name: PC
       Description: pseudo compound (PC) group
       Type: integer

    B. Name: mz
       Description: mass to charge ratio of the feature representing the PC group
       Type: numeric

    C. Name: mzmin
       Description: minimum mass to charge ratio of the PC group
       Type: numeric

    D. Name: mzmax
       Description: maximum mass to charge ratio of the PC group
       Type: numeric

    E. Name: rt
       Description: retention time of the feature representing the PC group
       Type: numeric

    F. Name: rtmin
       Description: minimum retention time of the PC group
       Type: numeric

    G. Name: rtmax
       Description: maximum retention time of the PC group
       Type: numeric

    H. Name: npeaks
       Description: number of times this PC group was detected across all samples (Forbs, Grasses, CTL, Mix, Tap)
       Type: integer

    I. Name: Forbs
       Description: number of times this PC group was detected in samples collected from forb communities
       Type: integer

    J. Name: Grasses
       Description: number of times this PC group was detected in samples collected from grass communities
       Type: integer

    K. Name: Mix
       Description: number of times this PC group was detected in composite samples obtained by mixing equal amounts of CTL, Grasses, and Forbs samples
       Type: integer

    L. Name: CTL
       Description: number of times this PC group was detected in samples collected from unsown mesocosms
       Type: integer

    M. Name: Tap
       Description: number of times this PC group was detected in tap water samples
       Type: integer

    N. Name: Forbs_1
       Description: peak intensity value in Forbs 1
       Type: numeric

    O. Name: Forbs_2
       Description: peak intensity value in Forbs 2
       Type: numeric

    P. Name: Forbs_3
       Description: peak intensity value in Forbs 3
       Type: numeric

    Q. Name: Forbs_4
       Description: peak intensity value in Forbs 4
       Type: numeric

    R. Name: Forbs_5
       Description: peak intensity value in Forbs 5
       Type: numeric

    S. Name: Forbs_6
       Description: peak intensity value in Forbs 6
       Type: numeric

    T. Name: Forbs_7
       Description: peak intensity value in Forbs 7
       Type: numeric

    U. Name: Forbs_8
       Description: peak intensity value in Forbs 8
       Type: numeric

    V. Name: Forbs_9
       Description: peak intensity value in Forbs 9
       Type: numeric

    W. Name: Forbs_10
       Description: peak intensity value in Forbs 10
       Type: numeric

    X. Name: Grasses_1
       Description: peak intensity value in Grasses 1
       Type: numeric

    Y. Name: Grasses_2
       Description: peak intensity value in Grasses 2
       Type: numeric

    Z. Name: Grasses_3
       Description: peak intensity value in Grasses 3
       Type: numeric

    AA. Name: Grasses_4
       Description: peak intensity value in Grasses 4
       Type: numeric

    AB. Name: Grasses_5
       Description: peak intensity value in Grasses 5
       Type: numeric

    AC. Name: Grasses_6
       Description: peak intensity value in Grasses 6
       Type: numeric

    AD. Name: Grasses_7
       Description: peak intensity value in Grasses 7
       Type: numeric

    AE. Name: Grasses_8
       Description: peak intensity value in Grasses 8
       Type: numeric

    AF. Name: Grasses_9
       Description: peak intensity value in Grasses 9
       Type: numeric

    AG. Name: Grasses_10
       Description: peak intensity value in Grasses 10
       Type: numeric

    AH. Name: CTL_1
       Description: peak intensity value in CTL 1
       Type: numeric

    AI. Name: CTL_2
       Description: peak intensity value in CTL 2
       Type: numeric

    AJ. Name: CTL_3
       Description: peak intensity value in CTL 3
       Type: numeric

    AK. Name: CTL_4
       Description: peak intensity value in CTL 4
       Type: numeric

    AL. Name: CTL_5
       Description: peak intensity value in CTL 5
       Type: numeric

    AM. Name: CTL_6
       Description: peak intensity value in CTL 6
       Type: numeric

    AN. Name: CTL_7
       Description: peak intensity value in CTL 7
       Type: numeric

    AO. Name: CTL_8
       Description: peak intensity value in CTL 8
       Type: numeric

    AP. Name: CTL_9
       Description: peak intensity value in CTL 9
       Type: numeric

    AQ. Name: CTL_10
       Description: peak intensity value in CTL 10
       Type: numeric

    AR. Name: Tap_1
       Description: peak intensity value in Tap 1
       Type: numeric

    AS. Name: Tap_2
       Description: peak intensity value in Tap 2
       Type: numeric

    AT. Name: Tap_3
       Description: peak intensity value in Tap 3
       Type: numeric

    AU. Name: Tap_4
       Description: peak intensity value in Tap 4
       Type: numeric

    AV. Name: Tap_5
       Description: peak intensity value in Tap 5
       Type: numeric

-------------------------------------------------------------------
DATA-SPECIFIC INFORMATION FOR: dd_max_heuristic_SN50_bw3_pos_1.csv
-------------------------------------------------------------------

LC-MS data (positive ionisation mode)

1. Number of variables: 48

2. Number of cases/rows: 3163

3. Variable List
    A. Name: PC
       Description: pseudo compound (PC) group
       Type: integer

    B. Name: mz
       Description: mass to charge ratio of the feature representing the PC group
       Type: numeric

    C. Name: mzmin
       Description: minimum mass to charge ratio of the PC group
       Type: numeric

    D. Name: mzmax
       Description: maximum mass to charge ratio of the PC group
       Type: numeric

    E. Name: rt
       Description: retention time of the feature representing the PC group
       Type: numeric

    F. Name: rtmin
       Description: minimum retention time of the PC group
       Type: numeric

    G. Name: rtmax
       Description: maximum retention time of the PC group
       Type: numeric

    H. Name: npeaks
       Description: number of times this PC group was detected across all samples (Forbs, Grasses, CTL, Mix, Tap)
       Type: integer

    I. Name: Forbs
       Description: number of times this PC group was detected in samples collected from forb communities
       Type: integer

    J. Name: Grasses
       Description: number of times this PC group was detected in samples collected from grass communities
       Type: integer

    K. Name: Mix
       Description: number of times this PC group was detected in composite samples obtained by mixing equal amounts of CTL, Grasses, and Forbs samples
       Type: integer

    L. Name: CTL
       Description: number of times this PC group was detected in samples collected from unsown mesocosms
       Type: integer

    M. Name: Tap
       Description: number of times this PC group was detected in tap water samples
       Type: integer

    N. Name: Forbs_1
       Description: peak intensity value in Forbs 1
       Type: numeric

    O. Name: Forbs_2
       Description: peak intensity value in Forbs 2
       Type: numeric

    P. Name: Forbs_3
       Description: peak intensity value in Forbs 3
       Type: numeric

    Q. Name: Forbs_4
       Description: peak intensity value in Forbs 4
       Type: numeric

    R. Name: Forbs_5
       Description: peak intensity value in Forbs 5
       Type: numeric

    S. Name: Forbs_6
       Description: peak intensity value in Forbs 6
       Type: numeric

    T. Name: Forbs_7
       Description: peak intensity value in Forbs 7
       Type: numeric

    U. Name: Forbs_8
       Description: peak intensity value in Forbs 8
       Type: numeric

    V. Name: Forbs_9
       Description: peak intensity value in Forbs 9
       Type: numeric

    W. Name: Forbs_10
       Description: peak intensity value in Forbs 10
       Type: numeric

    X. Name: Grasses_1
       Description: peak intensity value in Grasses 1
       Type: numeric

    Y. Name: Grasses_2
       Description: peak intensity value in Grasses 2
       Type: numeric

    Z. Name: Grasses_3
       Description: peak intensity value in Grasses 3
       Type: numeric

    AA. Name: Grasses_4
       Description: peak intensity value in Grasses 4
       Type: numeric

    AB. Name: Grasses_5
       Description: peak intensity value in Grasses 5
       Type: numeric

    AC. Name: Grasses_6
       Description: peak intensity value in Grasses 6
       Type: numeric

    AD. Name: Grasses_7
       Description: peak intensity value in Grasses 7
       Type: numeric

    AE. Name: Grasses_8
       Description: peak intensity value in Grasses 8
       Type: numeric

    AF. Name: Grasses_9
       Description: peak intensity value in Grasses 9
       Type: numeric

    AG. Name: Grasses_10
       Description: peak intensity value in Grasses 10
       Type: numeric

    AH. Name: CTL_1
       Description: peak intensity value in CTL 1
       Type: numeric

    AI. Name: CTL_2
       Description: peak intensity value in CTL 2
       Type: numeric

    AJ. Name: CTL_3
       Description: peak intensity value in CTL 3
       Type: numeric

    AK. Name: CTL_4
       Description: peak intensity value in CTL 4
       Type: numeric

    AL. Name: CTL_5
       Description: peak intensity value in CTL 5
       Type: numeric

    AM. Name: CTL_6
       Description: peak intensity value in CTL 6
       Type: numeric

    AN. Name: CTL_7
       Description: peak intensity value in CTL 7
       Type: numeric

    AO. Name: CTL_8
       Description: peak intensity value in CTL 8
       Type: numeric

    AP. Name: CTL_9
       Description: peak intensity value in CTL 9
       Type: numeric

    AQ. Name: CTL_10
       Description: peak intensity value in CTL 10
       Type: numeric

    AR. Name: Tap_1
       Description: peak intensity value in Tap 1
       Type: numeric

    AS. Name: Tap_2
       Description: peak intensity value in Tap 2
       Type: numeric

    AT. Name: Tap_3
       Description: peak intensity value in Tap 3
       Type: numeric

    AU. Name: Tap_4
       Description: peak intensity value in Tap 4
       Type: numeric

    AV. Name: Tap_5
       Description: peak intensity value in Tap 5
       Type: numeric