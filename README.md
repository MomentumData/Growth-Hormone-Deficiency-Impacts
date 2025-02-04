# Growth-Hormone-Deficiency-Impacts
Codelists, exposure/outcome definitions and algorithms for the study titled "Potential impacts of adult growth hormone deficiency: A population-based study in England"

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate.

## Algorithms for identification

## Primary GHD case definition
GHD was identified in primary care in patients with either:
1. A clinical [GHD diagnosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)) recorded in primary care.
2. A diagnosis code for [hypopituitarism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Hypopituitarism) and the presence of [levothyroxine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Treatments/Thyroid%20Hormones) and steroid treatments ([oral hydrocortisone](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Treatments/Oral%20Hydrocortisone) **OR** [oral prednisolone](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Treatments/Oral%20Prednisolone)) within six months of the [hypopituitarism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Hypopituitarism) diagnosis code.

**AND** for patients 20 years old or less with [GHD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)) recorded, **no codes for an alternative indication for growth hormone treatment:**
1. [Turner Syndrome](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Turner%20Syndrome)
2. Chronic renal insufficiency
   evaluated using [Serum Creatinine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Measurements/Serum%20Creatinine) levels and a code for [Chronic Kidney Disease (CKD) Stage 5](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/CKD%20Stage%205%20(Chronic%20Kidney%20Disease%20Stage%205)) (eGFR < 60 **OR** CKD Stage 5)
4. [Children born small for gestational age (SGA)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/SGA%20(Small%20for%20Gestational%20Age))
5. [Prader-Willi Syndrome (PWS)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Prader-Willi%20Snydrome)

Patients diagnosed with childhood onset GHD (prevalent cases only) were only included if they:
1. Had a code for a recognised cause of ongoing GHD - [genetic GHD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)/Genetic%20GHD), [genetic hypopituitarism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Hypopituitarism/Genetic%20Hypopituitarism), [congenital tumor](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/CAPG%20(Congenital%20Anomaly%20of%20Pituitary%20Gland)) **or** [pituitary tumour](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Pituitary%20Neoplasms)
2. Had an additional [GHD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)) diagnosis code or [somatropin](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Treatments/Somatropin) prescription during adulthood.
3. Had two or more pituitary hormone deficiencies in addition to GHD.

## Broader GHD case definition
This comprised; patients with a recorded diagnosis of [GHD](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/GHD%20(Growth%20Hormone%20Deficiency)) plus patients with a diagnosis of [hypopituitarism](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Conditions/Hypopituitarism) with or without recorded prescriptions for [levothyroxine](https://github.com/MomentumData/Momentum-Data-Codelists/tree/c0998ff70f0b96d5a5513556d80f141da01044c4/Treatments/Thyroid%20Hormones) and steroid treatments ([oral hydrocortisone](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Treatments/Oral%20Hydrocortisone) **OR** [oral prednisolone](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Treatments/Oral%20Prednisolone)).

## Outcomes

### Cardiovascular event
Any of:
- Patients identified with a diagnosis code for [myocardial infarction](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Conditions/MI%20(Myocardial%20Infarction)) in primary or secondary care.
- Patients identified with a diagnosis code for [hemorrhagic stroke](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Conditions/Hemorrahagic%20Stroke) in primary or secondary care.
- Patients identified with a diagnosis code for [ischaemic stroke](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Conditions/Ischaemic%20Stroke) in primary or secondary care.

### Fractures
Any of:
- Patients identified with a diagnosis code for [lower limb fractures](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Conditions/Lower%20Limb%20Fracture) in primary or secondary care.
- Patients identified with a diagnosis code for [spinal fractures](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Conditions/Spine%20Fracture) in primary care.

### Osteoporosis
- Patients identified with a diagnosis code for [osteoporosis](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Conditions/Osteoporosis) in primary or secondary care.

### Time-off work
- Patients identified with a code for [time off work for illness (issuing of Med 3 certificates)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Care%20Use/MED3%20Certificate) in primary care.
- Patients identified with a code for [sick leave](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e72e210b76fc09607124dfe4833d64098d2e524e/Care%20Use/Sick%20Leave) in primary care.

### Unemployment
- Patients identified with a code for [unemployment](https://github.com/MomentumData/Momentum-Data-Codelists/tree/ee0f37fe7ff624dbf8a4aac9016d29ef9cce8938/Conditions/Unemployment) in primary care.

### Depression
Any of:
- Patients identified with a diagnosis code for [recurrent depressive disorder](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/RDD%20(Recurrent%20Depressive%20Disorder)) in primary care.
- Patients identified with a diagnosis code for [depressive episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Depressive%20Episodes) **AND** any coded depression treatment* after 365 days in primary care.
- Patients identified with a diagnosis code for [depressive episode](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Conditions/Depressive%20Episodes) **AND** any coded depression treatment* within 6 months in primary care.

*List of depression treatments:
- [Selective Seratonin Reuptake Inhibitors (SSRIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/SSRIs%20(Selective%20Serotonin%20Reuptake%20Inhibitors))
- [Tricyclic Antidepressants (TCAs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/TCAs%20(Tricyclic%20Antidepressants))
- [Monoamine Oxidase Inhibitors (MAOIs)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/MAOIs%20(Monoamine%20Oxidase%20Inhibitors))
- [Counselling](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Counselling)
- [Psychotherapy](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/Psychotherapy)
- [Cognitive Behavioural Therapy (CBT)](https://github.com/MomentumData/Momentum-Data-Codelists/tree/e324df8109e26e9bebd1f891340a12cf711dfa02/Treatments/CBT%20(Cognitive%20Behaviour%20Therapy))
