# Growth-Hormone-Deficiency
Codelists, exposure/outcome definitions and algorithms for the study titled "The epidemiology of growth hormone deficiency in adults: A population-based study in the UK"

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification

## Primary GHD case definition
GHD was identified in primary care in patients with either:
1. A clinical [GHD diagnosis]() recorded in primary care.
2. A diagnosis code for [hypopituitarism]() and a diagnosis code in both [thyroid hormone]() and [glucocorticoids]().

**AND no codes for:**
1. [Turner Syndrome]()
2. Chronic renal insufficiency:
   [eGFR]() < 60 **AND** [Chronic Kidney Disease (CKD) Stage 5]()
3. [Children born small for gestational age (SGA)]()
4. [Prader-Willi Syndrome (PWS)]()

For patients 20 years old or less with GHD recorded.

## Broader GHD case definition
This will comprise; people with a recorded diagnosis of GHD plus patients with a diagnosis of hypopituitarism without GHD specifically recorded.


The index date will be set at the date of the earliest diagnosis code (for [GHD]() or [hypopituitarism]()) or the date of the earliest [somatropin]() issue date where the diagnosis post-dates the first somatropin issue date in the primary care record.
