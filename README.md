# Growth-Hormone-Deficiency
Codelists, exposure/outcome definitions and algorithms for the study titled "The epidemiology of growth hormone deficiency in adults: A population-based study in the UK"

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification
All of the conditions and medications mentioned below will use diagnostic codes recorded in primary care only.

## Primary GHD case definition
GHD was identified in primary care in patients with either:
1. A clinical [GHD diagnosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)) recorded in primary care.
2. A diagnosis code for [hypopituitarism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Hypopituitarism) and a diagnosis code in both [thyroid hormone](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Treatments/Thyroid%20Hormones) and [glucocorticoids](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Treatments/Oral%20Steroids).

**AND** for patients 20 years old or less with [GHD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)) recorded, **no codes for:**
1. [Turner Syndrome](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Turner%20Syndrome)
2. Chronic renal insufficiency
   Evaluated using [Serum Creatinine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Measurements/Serum%20Creatinine) levels and a code for [Chronic Kidney Disease (CKD) Stage 5](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/CKD%20Stage%205%20(Chronic%20Kidney%20Disease%20Stage%205)) (eGFR < 60 **AND** CKD Stage 5)
4. [Children born small for gestational age (SGA)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/SGA%20(Small%20for%20Gestational%20Age))
5. [Prader-Willi Syndrome (PWS)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Prader-Willi%20Snydrome)

Patients diagnosed with childhood onset GHD were only included if they:
1. Had a code for a recognised cause of ongoing GHD - [genetic GHD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)/Genetic%20GHD), [genetic hypopituitarism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Hypopituitarism/Genetic%20Hypopituitarism), [congenital tumor](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/CAPG%20(Congenital%20Anomaly%20of%20Pituitary%20Gland)) **or** [pituitary tumour](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Pituitary%20Neoplasms)
2. Had an additional [GHD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)) diagnosis code or [somatropin](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Treatments/Somatropin) prescription during adulthood.
3. Had two or more pituitary hormone deficiencies in addition to GHD.

## Broader GHD case definition
This will comprise; patients with a recorded diagnosis of [GHD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)) plus patients with a diagnosis of [hypopituitarism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Hypopituitarism) without GHD specifically recorded.

