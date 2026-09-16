**Installation & Setup**
Clone or download the project files into a local directory.
Ensure both ntfish.py and index.html are placed in the same working folder.
Open your terminal and navigate to the project directory.

**Usage**
Run the application using Python:
python ntfish.py

**Menu Options:**
Localhost Mode: Binds the HTTP server to a local interface (auto-selects a free port or prompts for a custom port) for local testing.

Cloudflared Mode: Automatically launches a local handler thread and provisions a temporary public tunnel via Cloudflare.

Exit: Safely terminates the application.

**Disclaimer**

This tool is intended strictly for authorized security testing, educational demonstrations, and administrative awareness training within
controlled environments. Unauthorized use against systems or individuals without explicit prior consent is strictly prohibited.


**Prerequisite:**
Install Cloudflared to use Cloudflared Tunnel.

Download the latest .deb package for your architecture (usually amd64):
#curl -L -o cloudflared.deb https://github.com/cloudflare/cloudflared/releases/latest/download/cloudflared-linux-amd64.

Install the package using dpkg:
#sudo dpkg -i cloudflared.deb

Verify the installation by checking the version:
#cloudflared --version
