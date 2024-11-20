# Configuring a self-hosted CircleCI Runner on MacOS.

Initial Setup:

Provision MacMini into Jamf as normal

User account should be Distiller and generate a new password.

Password should be stored in 1Password in Dev Vault - Circle CI Office Machines. and Circel CI - Local Computer Accounts

Configure Auto-Login for Distiller Account

Configure Auto-Startup after a Power Outage in Energy Saver Setting in System Preferences.

Add to “CircleCI Machines“ Static Group in Jamf

This should remove Configuration Profiles like Screen Saver.

