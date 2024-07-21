# Nmap-Automation
# Scripting and Automation for Threat Mitigation

This project contains a Python script for automating tasks related to threat mitigation. The script performs a port scan on an IP address, checks for common vulnerabilities on those ports, and generates a report with the results.

## Requirements

- Python 3.x
- nmap (must be installed and in the PATH)
- Python libraries: `python-nmap` and `requests`

## Installation

### Step 1: Install `nmap`

#### Windows

1. Download the `nmap` installer from [nmap.org](https://nmap.org/download.html).
2. Run the installer and follow the instructions to install `nmap`.
3. Ensure the `nmap` installation path is in the system PATH. You can add it manually if needed.

#### macOS

1. If you have `Homebrew` installed, you can install `nmap` with the following command:

    ```sh
    brew install nmap
    ```

2. If you don't have `Homebrew`, you can download the installer from [nmap.org](https://nmap.org/download.html) and follow the instructions.

#### Linux

1. On Debian/Ubuntu-based distributions, you can install `nmap` with the following command:

    ```sh
    sudo apt-get install nmap
    ```

2. On Red Hat/Fedora-based distributions, use the following command:

    ```sh
    sudo yum install nmap
    ```

### Step 2: Install Python Libraries

Run the following command to install the required libraries:

pip install python-nmap requests

## Usage

### Step 1: Clone the Repository

Clone this repository to your local machine:
```sh
git clone https://github.com/wh0arew3/-Scripting-and-Automation-for-Threat-Mitigation-
```
```sh
cd -Scripting-and-Automation-for-Threat-Mitigation-
```
Step 2: Install Python Libraries

Run the following command to install the required libraries:
```sh
pip install python-nmap requests
```
Step 3: Run the Script

Run the script from the command line (cmd on Windows or terminal on macOS/Linux):
```sh
python threat_mitigation.py
```
Step 4: Enter the IP Address

When prompted, enter the IP address you want to scan:

Enter the IP address to scan:

Step 5: View the Results

The script will scan open ports on the specified IP address, check for common vulnerabilities, and generate a JSON report named report.json.
```sh
Example Output
plaintext
Copiar código
Enter the IP address to scan: 192.168.1.1
Scanning open ports on 192.168.1.1...
Open ports found: [22, 80, 443]
Scan and vulnerability check completed.
Report generated: report.json
```
