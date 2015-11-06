# workstation-setup-checklist
-----------------------------

Workstation setup checklist for the Center for Community Engagement at the University of Arkansas.

Why?
----
Because it's the right thing to do.

Purpose:
--------
To help you setup workstations within the UARK domain painlessly, regardless of OS or network configuration.

Requirements:
-------------
Install CD/DVDs for Windows, as well as any supplementary software to be installed.
An internet connection (ethernet required to assign workstation to UARK Active Directory Domain).

 - Ensure that pc is plugged into the LAN via ethernet
  - add MAC (also called physical address) to DHCP self-registration database (ensure that the MAC address belongs to Ethernet adapter Local Area Connection ONLY)
- Update computer inventory table (still don’t have access to active directory, ticket not resolved)
  - Make the computer name “[position]-[service tag ID]
- Make the computer description the position of the user (e.g. CCE Graduate Assistant)
  - make the admin password

  - set the first user as admin, and set the password as the same in step 7
  - Register Microsoft Windows Registration under the office manager’s name and address
  - Network Setup
  - Network Registration (too ambiguous, what exactly does this entail?)
  - GACL (too ambiguous, what exactly does this step entail?)
- log in as local admin ( [computer_name]/admin ) ( not sure if applicable in all cases? )
  - My Computer >> Properties >> Computer Name >> Change >> Domain name: “UARK.EDU”
  - Add users that need admin / power user privileges (Control Panel >> User Accounts >> “give other users access to this computer"
      - If wireless, choose windows to select wireless instead of Intel (instructions unclear, are we referring to wireless as in battery powered, or wireless as in WiFi?)
      - If wireless, make sure it’s not on power save mode (unclear instructions, same as above)
      - Enable hidden administrator account
      - Login using local admin account ([computer_name]/admin)
      - launch cmd prompt as administrator
      - enter the following commands to change the password to match local admin password:
      - “net user administrator new_password_here”
      - “net user administrator /active:yes”
      - test the activated administrator by switching user or logging off, then logging on as Administrator with password that was just entered at command prompt
      - once activated, you can view the Administrator account in Control Panel >> Users Accounts
      - Get MAC address and IP address (cmd >> “ipconfig /all”)
      - Update computer inventory table with this info (Gizmo\\Sade\Computer\Computer Inventory.xls) (cannot access this drive, says it doesn’t exist)
      - Set up printers (control panel >> hardware and sound >> devices and printers >> add printer)
      - Set up printer to print on both sides (duplex mode), and eco-friendly ink setting within printer preferences.
      - Install windows updates
      - schedule auto windows updates (control panel >> system and security >> windows update >> change settings )
      - activate windows firewall (start >> control panel >> security >> windows firewall > toggle on/off )
      - install 3rd party applications
      - Symantec Antivirus (http://its.uark.edu/internet/antivirus/)
      - Firefox, Chrome, Adobe Reader
- “Save as PDF” browser extension (if not included)
  - Runtime Environments: Java, .NET, Silverlight, Flash, Shockwave, Air
  - Latest version of MS Office
  - configure Outlook / Exchange for primary users
  - Configure extended applications as needed:
  - Adobe Creative Suite
  - BASIS Client
  - Exchange Account
  - UARK Holidays ( I have never heard of this)
- UA Directory Access ( I have never done this before )
