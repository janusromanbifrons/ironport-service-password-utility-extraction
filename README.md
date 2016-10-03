# Ironport Vulnerability: Privilege Escalation through internal utility extraction.
_This is a follow-up to the previously explored pub-key injection exploit._ The requirements are the same; however we will extract two files from the virtual appliance.

The main file of interest is the `gen_pass` executable. This program uses the seed key and the serial number as inputs, and will output the password used for the `service` user.

The initial steps are much the same, but we will not be making any changes to the disk of the appliance, so it is technically _safer_ to do. However, I still do not recommend using this on production appliances.

##### Timeline:
__Disclosure to Vendor:__ 2016-10-03

__Vendor Response:__ TBA

__Vendor Fix/Patch:__ TBA

__Public Disclosure:__ TBA

##### Meta:
__Cisco Bug IDs:__ TBA

## Instructions
_This section will be populated after the `Public Disclosure` date._

## Comments:
_This section will be populated after the `Public Disclosure` date._
