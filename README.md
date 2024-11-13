# Easy vulnerable Active-Directory environment Setup in Vmware

Are you looking to set up a local Active Directory environment with all virtual machines pre-configured?

To set up a local Active Directory environment with pre-configured virtual machines, please follow the steps outlined below. The environment includes three machines: one Domain Controller and two Workstations. All essential configurations have already been completed, including networking, IP assignments, user accounts, machine setup, and local administrative access.

The PDF file contains the links for the three VMware files, including the Domain Controller and the two workstations.

Simply download the "Vulnerable Active Directory in VMware Documentation" and follow the instructions provided. This documentation will guide you through the remaining setup steps, making the process straightforward and efficient. Once completed, you’ll have a vulnerable Active Directory environment at your disposal for testing and training on Active Directory vulnerabilities.

Detailed Description:

Vulnerable Active Directory in VMware Documentation
Prepared by Ahmed Hassan

This comprehensive document provides a detailed, step-by-step guide to deploying a vulnerable Active Directory environment locally using VMware. Follow the instructions below to set up and configure a test environment with ease.
Overview

The setup includes three virtual machines:

    Domain Controller (DC)
    Workstation 1
    Workstation 2

Each machine is fully pre-configured with essential settings such as networking, IP addresses, user accounts, machine names, and local administrative privileges.
Deployment Steps

    Download the Required Files
        Access the PDF file to obtain links to the VMware files for the Domain Controller and two workstations.
        Download each VMware file and confirm the file integrity.

    Set Up VMware Environment
        Open VMware and import each downloaded file to create virtual instances for the Domain Controller and the workstations.
        Verify that all machines are configured according to the network settings outlined in the documentation.

All these steps down below are already pre-configured and finished for you:

    Network Configuration
        Ensure that each virtual machine has the correct IP address, as specified in the guide.
        Check that networking settings are compatible across all three machines, facilitating domain communication.

    User Account Verification
        Confirm that all necessary user accounts are in place, and verify each account’s permissions and group memberships.
        Ensure administrative rights are correctly assigned as needed for training purposes.

    Initiate the Domain Controller
        Power on the Domain Controller, and follow the guide to initiate Active Directory services on this machine.
        Confirm that the domain is set up and accessible.

    Connect Workstations to the Domain
        Power on each workstation and connect them to the Active Directory domain created by the Domain Controller.
        Verify successful domain membership and connectivity.

    Testing and Validation
        Follow the testing scenarios provided in the documentation to identify and analyze vulnerabilities.
        Use the environment to explore and train in Active Directory security practices and common vulnerability exploitation techniques.

Final Verification

Once configured, validate the environment by running a few initial tests to ensure the setup is fully functional. You now have a locally deployed, vulnerable Active Directory environment to train and test AD vulnerabilities.

For additional assistance, refer to the documentation provided or reach out as specified in the contact details. This setup provides a controlled environment ideal for learning and training purposes.
