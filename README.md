# OS Parameters Display Program

This Python program retrieves and displays essential parameters of the operating system. It provides information such as OS name and version, processor details, memory and disk space, current user, IP address, system uptime, CPU usage, running processes, disk partitions, system architecture, and environment variables.

## Information Available

- **Operating System Details:** Includes OS name, version, and processor information.
- **System Resources:** Displays memory and disk space availability.
- **User Information:** Shows the current user logged into the system.
- **Network Information:** Retrieves the IP address of the system.
- **System Uptime:** Provides the duration the system has been running since the last boot.
- **CPU Usage:** Shows the current CPU usage as a percentage.
- **Running Processes:** Displays information about currently running processes, including their process ID, name, and memory usage.
- **Disk Partitions:** Provides information about the disk partitions on the system, including device name and mount point.
- **System Architecture:** Shows the architecture of the system (e.g., 32-bit or 64-bit).
- **Environment Variables:** Lists the environment variables set on the system.

## How to Use

1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Open a terminal or command prompt.
4. Navigate to the directory where the `os_parameters.py` file is located.
5. Run the program by executing the command `python os_parameters.py`.
6. The program will display the OS parameters in the terminal/command prompt.

## Dependencies

This program requires the following Python libraries:
- `platform`
- `psutil`
- `os`
- `subprocess`
- `datetime`
- `socket`

These dependencies can be installed via pip if not already installed:
