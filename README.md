# Convert Excel Files to CSV with OIC

This repository hosts the code required to setup an Oracle Function that will convert Excel files in xlsx and xls to CSV. It also stores the artefacts required to create an Oracle Integration (OIC) flow that will call this function to perform Excel to CSV file conversion. 

This code is accompanied by a blog article, available here: 
- XXXXX

**Function Artefacts**

- ../requirements.txt specifies all the dependencies for your function
- /func.yaml contains metadata about your function and declares properties
- ./func.py  which is your actual Python function 

to invoke function store sample request in function folder and run:
  fn invoke stv_FN_Demo convertexcelfiles < request2.json
