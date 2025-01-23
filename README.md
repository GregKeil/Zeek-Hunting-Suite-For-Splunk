# Splunk-Zeek-Suite
This suite of dashboards is designed to provide an easier hunting enviroment for analysts through the use of Zeek logs.

## Important Notes:
- The Splunk CIM may be needed for proper operation.
- For proper operation, the datamodel must be uploaded & configured to utilize the correct indexes.
- A lookup file MUST be created under the name "Known_Scanners.csv" with the field "scannerip". It can be used to filter out all known scanners.

## App Links:
### Splunk App For Lookup File Editing:
- https://splunkbase.splunk.com/app/1724
