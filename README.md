1. Reserve the FMC sandbox from : https://devnetsandbox.cisco.com/RM/Topology (search for FMC)
2. Download python 3.x.x if you dont have in your local system : https://www.python.org/downloads/
3. do a "pip3 install json
        pip3 install requests
        pip3 install sys" 
    To complete the library pre-requisite installs.
4. Download the .py file from the github repo
5. From the reserved FMC sandbox in Step1, navigate to toolbar option "window > output" to get username and password for the current session.
6. Edit the username and password values mentioned in the downloaded github python file with the one from step4 and save it and run from cli : python3 <path of .py file> eg. python3 security-API-demo.py
