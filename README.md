# Data-Extraction-App
Data extraction UiPath Bot to prepare reports for the HR &amp; leadership teams


Encompasses all employees – 
  o	All employees have access to update the tracker 
  o	Final reporting includes all employees  
Not be sent to people on leave (if we can’t do this then need to add a question at the beginning of ‘I am out on short or long-term leave’)

Not redundant to other systems (and employees should update data into source system)
  o	For instance, employees should enter contact information into Workday which then will feed AD and be available for WellTrack
  o	Having conflicting data from WellTrack and WD would require downstream data reconciliation, creating more work and reducing quality of master data source
  
Accessibility via mobile preferred due to increased likelihood of capturing data

Able to create ELT-level corporate-wide dashboard from the data
  o	Also consider how to accomplish this with a phased approach (since will be 2 databases to manage)
  
Consider how HRBP team will be able to reconcile against their known cases and if we have taken action.

