This shell script automates the installation and setup of the Ollama service on a Linux system. Here’s a brief overview of its functionality:

Welcome Message: Displays a welcome message with an animation.
Update and Install Utilities: Updates the package lists and installs the curl utility.
Download and Install Ollama: Downloads the Ollama binary and installs it to /usr/bin/.
User Creation: Creates a dedicated system user for running the Ollama service.
Systemd Service Configuration: Sets up a systemd service to manage the Ollama service.
Service Management: Reloads the systemd daemon, enables the Ollama service to start on boot, and starts the service.
Usage Instructions
Save the script to a file, for example, install_ollama.sh.
Make the file executable