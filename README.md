# Maven Setup Script

This Bash script automates the setup of a Maven environment on an Ubuntu system. It performs the following tasks:

- Sets the system hostname to 'maven.'
- Updates and upgrades system packages.
- Installs default JDK and Git.
- Downloads and installs Apache Maven.
- Adds Maven to the PATH in the user's .bashrc file.
- Logs the process with a timestamp.

## Usage

1. Clone the repository: `git clone https://github.com/chriscloudaz/maven-setup-script.git`
2. Run the script: `./maven_setup.sh`
3. Restart the .bashrc file for changes to take effect: `source ~/.bashrc`

## Notes

- Ensure you have sudo privileges to execute certain commands.
- Check the log file (`maven-log.txt`) for detailed information about the installation process.
