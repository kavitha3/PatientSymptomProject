# PatientSymptomProject
This is a tool that will ask the user to input patient ID and will produce a summary of key symptoms noted in chart notes for the patient of interest in the last year.

# Setup
1. Save the following files in the directory where you are running the source code.
  
  - symptoms.csv (list of key symptoms/conditions)
  
  - patient_list.csv (list of fictitious patients with basic demographics and chart notes)
  
  - negation.csv (list of negation words)

2.Install metapy
```bash
pip install --upgrade pip

pip install metapy pytoml
```

