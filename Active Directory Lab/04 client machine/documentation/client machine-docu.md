# Joining a Client Workstation to the Active Directory Domain

## Objective

Configure a Windows client workstation to communicate with the Domain Controller and successfully join the **corp.local** Active Directory domain.

---

## Configuration

* Configured the client workstation to use the Domain Controller as its preferred DNS server.
* Verified network communication between the client workstation and Domain Controller.
     ![ADDS Installation and Config](https://github.com/stephanie-i234/active-directory-home-lab/blob/main/Active%20Directory%20Lab/07%20troubleshooting/screenshots/network-subnet-correction..PNG)
  
* Joined the workstation to the **corp.local** domain.
   ![ADDS Installation and Config](https://github.com/stephanie-i234/active-directory-home-lab/blob/main/Active%20Directory%20Lab/04%20client%20machine/screenshots/success_we_made_it.PNG)
* Restarted the client workstation to apply the domain membership.
* Authenticated using Active Directory domain credentials.
![ADDS Installation and Config](https://github.com/stephanie-i234/active-directory-home-lab/blob/main/Active%20Directory%20Lab/04%20client%20machine/screenshots/domain_change_creditentials_entry.PNG)

---

## Outcome

The client workstation successfully joined the **corp.local** Active Directory domain and authenticated using domain user accounts. The workstation was fully integrated into the lab environment and ready for centralized user management through Active Directory.

