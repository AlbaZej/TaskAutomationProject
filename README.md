Project Description
This script is an interactive Bash program designed to provide users with information about various security topics, check password strength, encrypt and decrypt files, and analyze network traffic. It is designed to be user-friendly and accessible, even for those with no hacking experience. Below is a detailed explanation of each function and its purpose, along with the tools used.

Tools Used
- Hydra: A network login cracker that supports multiple protocols.
- Zphisher: An automated phishing tool.
- GPG (GNU Privacy Guard): For file encryption and decryption.
- tcpdump: A network traffic analyzer.
- Main Menu
-The mainmenu function presents the user with a menu of options to choose from:

- Learn more about security and ethical hacking: Leads to a submenu for further information.
- Password Strength Check: Allows users to test the strength of a password.
- Encrypt and Decrypt a file: Provides options to encrypt or decrypt a file using GPG.
- Network Traffic Analyzer: Analyzes network traffic using tcpdump.
- EXIT: Exits the script.

Information
The Information function provides educational content about security topics. Users can choose from:

Password cracking: Information on methods and tools for password cracking.
Types of attack indicators: Details on various attack indicators.
Go back to main menu: Returns to the main menu.
Sinfo (Password Cracking Information)
The Sinfo function explains different methods of password cracking, such as brute force attacks and dictionary attacks. Users can further choose to learn about:

Tools (needed for hacking): Information about tools like Hydra.
Attack Vectors: Information about phishing attacks using tools like Zphisher.
BF (Brute Force Tools)
The BF function provides details on Hydra, a network login cracker, including installation and usage instructions.

DA (Dictionary Attack Tools)
The DA function describes phishing attacks and provides instructions for using the Zphisher tool.

Ethical
The Ethical function gives an overview of various types of attacks and malware, such as Trojans and worms.

Password
The password function tests the strength of a password entered by the user. It checks for the presence of both letters and numbers to determine if the password is strong or weak.

Anon (File Encryption and Decryption)
The anon function allows the user to encrypt or decrypt files using GPG:

Encrypt a file: Prompts the user for a file path and recipient, then encrypts the file.
Decrypt a file: Prompts the user for an encrypted file path, then decrypts the file.
E1 (Encrypt File)
The E1 function handles the encryption of a specified file using GPG.

D2 (Decrypt File)
The D2 function handles the decryption of a specified file using GPG.

T (Network Traffic Analyzer)
The T function provides an option to analyze network traffic using tcpdump. It captures and displays a specified number of packets from the network.
