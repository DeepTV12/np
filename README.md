# Nodepay BOT
Nodepay BOT

- Register Here : [Nodepay](https://app.nodepay.ai/register?ref=2K9Y1KXieUAKN96)
- Use Code : 2K9Y1KXieUAKN96

## Features

  - Auto Run  Multi Accounts
  - Auto Run With Free Proxy [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) - Choose [ 1 ]
  - Auto Run With Private Proxy - Choose [ 2 ]
  - Auto Run Without Proxy - Choose [ 3 ]
  - Auto Complete Available Tasks
  - Auto Get Account Information
    
Note: auto connects 3 connections if u using proxies choose [ 1 ] or [ 2 ] and only 1 connection if choose [ 3 ].

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/DeepTV12/np.git
   ```
   ```bash
   cd np
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Configuration

- **tokens.txt:** You will find the `tokens.txt` inside the project directory. Make sure contains data that matches the format expected by the script. Here are examples of file formats:

   Single account
  ```bash
    eyj...xyz
  ```
  Multi Accounts
  ```bash
    eyj...xyz1
    eyj...xyz2
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```

