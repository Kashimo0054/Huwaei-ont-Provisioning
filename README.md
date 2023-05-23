Huawei ONT Provisioning Script
This Python script automates the provisioning of Huawei ONTs on a Huawei OLT, eliminating the need for manual registration. It significantly reduces provisioning time and minimizes the risk of mistakes that would require re-registering the ONT.

The script utilizes the Paramiko module for establishing an SSH connection with the OLT. It also incorporates the Time and Getpass modules to ensure password encryption when entering your credentials.

Key Features:

Efficient Provisioning: By automating the ONT registration process, the script saves considerable time and effort compared to manual registration.
Easy-to-Understand Modules: The script utilizes Paramiko for SSH connectivity, Time for time-related operations, and Getpass for secure password input, making it easy to comprehend and modify.
SN and ONT Number Extraction: The script employs an index method to locate the SN and ONT numbers, storing them in variables for further use during the provisioning process.
Flexible VLAN Registration: Using simple if-else conditions, the script enables ONT registration in different VLANs, providing flexibility to suit various network configurations.
Straightforward Registration Functions: The script includes functions that streamline the registration process, making it easy to follow and modify according to specific requirements.
Suitable for Python Beginners: The script is designed with straightforward concepts, making it accessible to those with basic Python knowledge. It is compatible with Python 3 and above.
This script significantly simplifies and accelerates the Huawei ONT provisioning process, reducing the chance of errors and the need for manual intervention. Its clear and concise implementation, combined with user-friendly modules, makes it a valuable tool for network administrators.









