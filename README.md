*This project has been created as part of the 42 curriculum by ayhammou.*

# NetPractice

## Description
NetPractice is a general practical exercise designed to introduce the fundamentals of computer networking. The primary goal of this project is to solve routing and addressing problems to make simulated small-scale networks function properly. Through 10 progressively difficult levels, this project focuses on configuring IP addresses, connecting devices through routers and switches, and understanding the critical role of default gateways in a network architecture.

## Instructions
**How to run the training interface:**
1. Download the project archive and extract it into a folder.
2. Open a terminal, navigate to the folder, and execute the run script:
   `./run.sh`
   *(This will launch a local web server and open the interface in your preferred web browser.)*
   *Fallback: If the script does not work, run `python3 -m http.server 49242` and open `http://localhost:49242` in your browser.*
3. On the homepage, enter your 42 intranet login to generate your personal configuration.
4. Solve the network puzzles. Once a level is complete, use the **Get my config** button to export the configuration file.

**Submission Requirements:**
As required, there are exactly 10 exported configuration files (one for each training level) located at the root of this Git repository.

## Resources
To successfully complete this project, I studied and applied the following core networking concepts:
- **TCP/IP addressing**
- **Subnet masks** (including CIDR notation and subnetting logic)
- **Default gateways**
- **Routers and switches** behavior
- **OSI layers** (specifically Layer 2 and Layer 3)

**Classic References:**
- IPv4 Subnetting logic and cheat sheets.
- Cisco documentation regarding basic routing and switching.

**Use of Artificial Intelligence (AI):**
AI tools were utilized strictly as a learning assistant and debugging partner during the training phase, in accordance with the pedagogical guidelines:
- **Conceptual understanding:** AI was used to explain the mathematical logic behind subnetting (e.g., how a /26 mask divides a network into 4 blocks of 64 addresses).
- **Log analysis:** AI helped decipher the exact meaning of specific interface error logs (such as "multiple interface match" or "destination does not match any route") to better understand which routing rules were being violated.
- AI was *not* used to directly generate or bypass the creation of the configuration files submitted in this repository.