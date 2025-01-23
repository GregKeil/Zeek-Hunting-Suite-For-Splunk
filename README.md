# Splunk-Zeek-Suite
This suite of dashboards is designed to provide an easier hunting enviroment for analysts through the use of Zeek logs.

## Note:
- The Splunk CIM may be needed for proper operation
- For proper operation, the datamodel must be configured to utilize the correct indexes
- A lookup file must be created under the name "Known_Scanners.csv" with the field "scannerip" must be used to filter out all known scanners
