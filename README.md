# MultiClinNER enigma

Task: https://temu.bsc.es/MultiClinAI/
Train Data v1.1: https://zenodo.org/records/18772832

Base Models:
- **ClinicalBERT** (emilyalsentzer/Bio_ClinicalBERT) — fine-tuned token classification

Results:
| Model                     | Entity Precision | Entity Recall | Entity F1 |
|---------------------------|------------------|---------------|-----------|
| ClinicalBERT (fine-tuned) | 0.17             | 0.65          | 0.27      |