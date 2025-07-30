https://github.com/user-attachments/assets/736639b6-81ab-4683-803a-a4e7605009f5

1. Identify medications (Korean) or active ingredients(ATC) (alphabet lowercase)
2. Review potential drug interactions:
   - MFDS(식약처) drug label (by LLMs; results are subject to error)
   - ["Flockhart table"](https://drug-interactions.medicine.iu.edu/MainTable.aspx)

Colors of medicine/ingredient:
- Blue: Ingredients were identified and MFDS drug label was reviewed
- Cyan: Ingredients were identified, but the MFDS drug label was not reviewed (yet)
- Green: Medication was identified, but the ingredient is not in identification list(e.g., herbal ingredients)
- Yellow: More than one medication or ingredient can be matched
- Red: No medication or ingredient can be matched

Colors of feedback:
- Yellow: Needs some alterations
- Green: Contains clinically insignificant information