Issue:
Client could not locate Domain Controller.

![Network ping](https://raw.githubusercontent.com/stephanie-i234/active-directory-home-lab/refs/heads/main/Active%20Directory%20Lab/07%20troubleshooting/screenshots/25%25%20network%20ping.PNG)


Symptoms:
DNS timeout errors during domain join.

Investigation:
- Verified network settings
- Checked DNS configuration
- Tested connectivity with ping
- Verified name resolution using nslookup

 ![NSlookpup Results](../screenshots/network-subnet-correction..PNG)

Root Cause:
Subnet mismatch between Domain Controller and VMware NAT network.

Resolution:
Updated Domain Controller static IP configuration to match VMware NAT subnet.

#### Refer to HD-005 Network Connectivity Troubleshooting

Outcome:
Client successfully joined domain.
