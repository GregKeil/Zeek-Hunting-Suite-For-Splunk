# Zeek Hunting Suite For Splunk
This suite of dashboards is designed to provide an easier hunting enviroment for analysts through the use of Zeek logs.

## Requirements & Recommendations:
### Requirements:
- **Splunk Common Information Model (CIM)**
  - https://splunkbase.splunk.com/app/1621
- **TA For Zeek**
  - https://splunkbase.splunk.com/app/5466
- **Known_Scanners.csv** Lookup File
- **Zeek_Suite_Datamodel.json** must be configured and installed (Datamodel ID: Zeek_Suite)
- **All Zeek____.xml Files** are the source code for the individual dashboards
### Recommendations: 
- **Splunk App For Lookup File Editing**
  - https://splunkbase.splunk.com/app/1724

## Current Version Notes:
- Version 3 has integrated drilldowns and base searches to minimize overall load

##Other Notes:
- Any modifications to a CSV file will not be automatically applied to the datamodel when in accelerated mode. To integrate changes, you must rebuild the datamodels
