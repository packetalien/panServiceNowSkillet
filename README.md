# Service Now Server Profile Skillet
Simple Skillet for adding a HTTP ServiceNow pre-defined payload Incident 
Logger to PanOS. First version.

#### Purpose of this Skillet:
Skillet can be used to both Demo creation of a Service Now HTTPS Logging 
Server Profile and or operational creation of said profile.

#### Usage
This skillet is designed to implement an HTTP logger that sends messages to
a ServiceNow instance. It currently configures everything except the
pre-defined payload itself, an issue with that is being researched. Once
the object is created, you will need to select the pre-defined format.


Please see the [PanOS Admin Guide](https://docs.paloaltonetworks.com/pan-os/9-0/pan-os-admin.html) for more details.



### Support Policy
The code and templates in the repo are released under an as-is, best effort,
support policy. These scripts should be seen as community supported and
Palo Alto Networks will contribute our expertise as and when possible.
We do not provide technical support or help in using or troubleshooting the
components of the project through our normal support options such as
Palo Alto Networks support teams, or ASC (Authorized Support Centers)
partners and backline support options. The underlying product used
(the VM-Series firewall) by the scripts or templates are still supported,
but the support is only for the product functionality and not for help in
deploying or using the template or script itself. Unless explicitly tagged,
all projects or work posted in our GitHub repository
(at https://github.com/PaloAltoNetworks) or sites other than our official
Downloads page on https://support.paloaltonetworks.com are provided under
the best effort policy.