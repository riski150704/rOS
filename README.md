Hacker Simulator (rOS)
__Discontinued__
=============

Written using Python 3.6.

Bots, subnets, tracing, upgrades, comfortable prompt, miners, and a lot of interesting things included in this game.

Actual version: 0.3.1b

Installation (Android)
-----------------------
1. Download and install the [Termux app][2].

2. Don't forget to give [Termux][2] the "Data/SD/Memory access" rights (If your Android version >= 5.0).

3. Launch [Termux][2].

4. Use `cd ~` command to go to Termux home directory.

5. Use `pkg install python` command to install Python (It's needed to launch the game).

6. Install required modules by commands below:
   ```
   apt-get install python-dev clang libcrypt-dev
   pip install psutil
   pip install prompt_toolkit
   pip install platform
   pip install colorama
   pip install progressbar2
   pip install hashlib
   pip install shelve
   ```
7. Use `git clone https://github.com/riski150704/rOS.git` command to download the game

8. Use `cd rOS` and `python rosgame.py` commands to start the game

9. Game will tell you which modules are not installed if you didn't installed them.

10. Have a good time :D

Installation (Windows)
-----------------------
1. Download and install (with administrator rights) the [Python][3] (Python version must be >= 3.5).

2. Install required modules by commands below:
   ```
   pip install psutil
   pip install prompt_toolkit
   pip install platform
   pip install colorama
   pip install progressbar2
   pip install hashlib
   pip install shelve
   ```
3. Download the game archive [HERE][4] and unzip it to any folder (Example: `C:\Games\rOS`)

4. Check that you are administrator of your PC or move the game into your user account desktop.

5. Open cmd and use the commands below to launch the game:
   ```
   cd {FOLDER_WHERE_YOU_EXTRACTED_THE_GAME_ARCHIVE}\rOS
   python rOS.py
   ```
6. Game will tell you which modules are not installed if you didn't installed them.

7. Have a good time :D

Getting started
----------------
1. Create a rOS account at start of the game or load the previous game
   - Password can't be less than 6 symbols
   - Please don't forget the password, because it will be used to load saves
   - When you shutting down the rOS (game), you can save it
   - Don't try to edit the save, because you can corrupt it

2. Commands:
   ```
    apps - list of installed apps + levels
    help - list of console commands
    shutdown - shutdown rOS
    scan - scan subnet and search for vulnerable servers
    scan_target - scan an IP and gather information about target server
    balance - opens Ethereum wallet where you can see your Ethereum balance
    load_list - shows you targets list
    rosf - start the rOS exploitation framework
    upgrade - launch rOS programs upgrade CLI
    stats - shows your stats
    change_ip_v - move from IPv4 (old IP version) to IPv6 (new IP version) (Can't be undone)
    version - version of rOS
    update_ip - replacing your ip with new one
    miner - show last 10 mined blocks (short log)
    rescan_subnet - rescans subnet to find new targets
    news - show latest cyber security news
    debug_info - shows you debug information
    miner_info - shows you your miner components
    buy_miner - buy one more miner
    bank - DarkNet Bank CLI
    hilo_game - High/Low Bet Game
   ```

3. Use `scan` to find first targets.

4. Then, select and IP and remember it.

5. Launch rOS Exploitation Framework by `rosf` command, then enter IP that you remembered. rosf will be launched, then type `help` to see the rosf commands list.

6. Don't forget to upgrade your apps

7. You can see your statistics by `stats` command

Requirements
----------------------

1. Python version >= 3.6

2. Install required modules by commands below:
   ```
   pip install psutil
   pip install prompt_toolkit
   pip install platform
   pip install colorama
   pip install progressbar2
   pip install hashlib
   pip install shelve
   ```

Links
----------
- [Mohamat Riski Fauzi (WhatsApp)](https://wa.me/6283119962824)
- [Mohamat Riski Fauzi (E-Mail)](mailto:dimankiev@gmail.com)

Supported
-------------------
Supported By Surabaya Hacker Community
- [Website](https://www.surabayahackercommunity.social)

License
---------
Copyright © 2020-2021 riski150704

[1]: https://github.com/riski150704/rOS
[2]: https://termux.com/
[3]: https://www.python.org/downloads/windows/
[4]: https://github.com/riski150704/rOS/archive/master.zip
