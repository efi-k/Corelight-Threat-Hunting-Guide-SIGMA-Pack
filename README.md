# Corelight-Threat-Hunting-Guide-SIGMA-Pack
Corelight Threat Hunting Guide SIGMA Pack - Added TH searches and dashboard to the splunk app

The included .conf and xml file will add the Corelight+SOC Prime splunk searches and dashboard to the splunk Corelight app.

Please follow the below instructions for installation:

1. Make sure you have the splunk Corelight app or get it from https://splunkbase.splunk.com/app/3884
2. Save the corelight_security_corelight_threat_hunting_guide_sigma_pack.xml file to Splunk\etc\apps\CorelightForSplunk\local\data\ui\views.
   Create the local\data\ui\views folders structure that does not exist already
3. Append the content of savedsearches.conf to the savedsearches.conf file already in Splunk\etc\apps\CorelightForSplunk\local or just put it
   there is no savedsearches.conf file already exists.
4. You should see the "Corelight Threat Hunting Guide SIGMA pack" under the "Security Workflows" menu of the app

Happy Hunting!

Efi
