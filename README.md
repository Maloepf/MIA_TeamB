# Medical Information Assistant (Vidal-based)

## Description
Develop an assistant that answers questions about medications, their uses, side effects, and interactions based on the French medical handbook Vidal.

## Use Case
Assist healthcare professionals or patients by providing reliable, up-to-date information on medications available in France, ensuring safe and informed usage.

## Challenges
- Handling medical terminology
- Ensuring accuracy in safety-critical information
- Adhering to legal and ethical guidelines in providing drug-related advice

## Reference Data

- [Dictionnaire VIDAL from 2018](https://epfedu-my.sharepoint.com/personal/antoine_gademer_epf_fr/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fantoine%5Fgademer%5Fepf%5Ffr%2FDocuments%2FEPF%2FMDE%5FLLM%2FUsesCases%2FHealth%2DVidal%2FVidal%202018%2Epdf&parent=%2Fpersonal%2Fantoine%5Fgademer%5Fepf%5Ffr%2FDocuments%2FEPF%2FMDE%5FLLM%2FUsesCases%2FHealth%2DVidal&ga=1)
- [VIDAL online](https://www.vidal.fr/) (Only patient-destined information is public; technical information is proprietary and reserved for healthcare professionals.)

## Main Criteria to be Satisfied
- In case of listing, ensure that everything is listed.
- For sensitive information that could have a high impact, recommend consulting a professional.
- If the information is not available, state that it cannot be provided.
- Ensure the information is up-to-date.
- Prioritize accuracy and clarity; use the correct medical terminology.
- Recommend the active ingredient (molecule) where applicable.
- Responses must be in French.
- Give information about the posologie.