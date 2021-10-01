# Convert Excel Files to CSV with OIC

This repository hosts the code required to setup an Oracle Function that will convert Excel files in xlsx and xls to CSV. It also stores the artefacts required to create an Oracle Integration (OIC) flow that will call this function to perform Excel to CSV file conversion. 

This code is accompanied by a blog article, available here: 
- XXXXX

**Function Artefacts**

- [requirements.txt](requirements.txt) specifies  the dependencies of the Excel2CSV conversion function
- [func.yaml](func.yaml) contains metadata about the function and declares associated properties
- [func.py](func.py) contains the Python function that converts a single Excel file to a CSV

sample file to call the function:
- [request.json](request.json)

to invoke the above function store the sample request in function folder within Cloud Shell and run:
  `fn invoke stv_FN_Demo convertexcelfiles < request2.json`
