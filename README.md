# Release Audit

Small Python program for displaying support-ticket information.

## Requirements
- Python 3.12 or newer
- Git  
- Dependencies from requirements.txt

## Setup
First clone the repository  
```
git clone https://github.com/NMCameron/CPS310-ICA08-DevOps.git
```
Next create your own virtual environment with  
```
python -m venv .venv
```  
Then activate your virtual environment for Windows with  
```
.\venv\Scripts\Activate.ps1
```  
Finally, Install dependencies using  
```
python -m pip install -r requirements.txt
```

## Configuration
All project settings are contained within `config.json`  
- `data_file` - Contains the file read in for the tickets
- `report_title` - Provides the title displayed whent he program runs
- `high_priority_threshold` - sets the minimum level to make a ticket high priority 

## Run
To run the program, open the terminal and run  
```
python release_audit.py
```

## Tests
To run tests, open the terminal and run
``` 
python -m pytest -v
```
## Verification
To run verifications for the program, open the terminal and enter
```
.\verify.ps1
```

## Release-Readiness
This version is more ready for release as it has more guardrails and guidelines for ensuring that the program works as intended. With the requirements, we ensure each user or developer has an idea of what dependencies are required to run this project. Then by asking the user to clone our repository we ensure that they are working with the same version of the project. Finally our tests and verification scripts help us catch issues before release and confirm the program is functioning as we expect.