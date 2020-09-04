ODIN is a simple **RAT** <br/> <br/>
ODIN uses **RSA-2048** with **AES-256** to keep your communication with infected machines secure.<br/>

[![Version](https://img.shields.io/badge/Version-v0.1.1-blue)]() 
[![Python](https://img.shields.io/badge/Python-v3.6%2B-blue)]() 
<br/><br/>

# Requirements

- Python **3.6.x** | **3.7.x** | **3.8.x**

# Servers Tested

- Windows 10
- Kali Linux

# Bots Tested

- Windows 10

# Payload Generator Tested

- Windows 10

# Features

- Upload & Download
- Chrome Launching
- Persistence
- Screenshare
- Screenshot
- Keylogger
- SFTP
- SSH


# Installation

```shell
$> pip install -r requirements.txt
```

# Server Side

1. Open `/lib/const.py` & configure your private and public IP's
2. Start ODIN.py
3. Navigate to http://localhost:5000
4. Login

    ```
    Username: odin
    Password: nido
    ```

5. Start the server on the same IP as your private IP

# Generate Payload

Navigate to agent directory and run the following command

```shell
$> python builder.py -h
```

**It will not compile inside a virtual environment**

# After Connection

-   You can click the id of the bot once it connects

# FYI

-   The bot will call the server using the Public IP, not the private IP
-   The bot will call the server using the port specified on the server tab
