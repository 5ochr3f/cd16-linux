# Install Counter-Strike 1.6 Server in Linux VPS (Ubuntu/Debian)




1. sudo apt-get upgrade -y
2. sudo apt-get update -y
3. sudo dpkg --add-architecture i386
4. sudo apt install curl wget file tar bzip2 gzip unzip bsdmainutils python util-linux ca-certificates binutils bc jq tmux netcat lib32gcc1 lib32stdc++6 -y
5. sudo dpkg --add-architecture i386
6. sudo apt-get install unzip
7. sudo apt-get install lib32gcc1
8. sudo apt-get install screen
9. mkdir cs-server
10. cd cs-server
11. chmod 777 *
12. wget https://www.sohaibxtreme.net/FDL/hlds/latest_rehlds_fresh2k21.zip
13. unzip latest_rehlds_fresh2k21.zip
14. rm latest_rehlds_fresh2k21.zip

15. ./hlds_run -game cstrike -console +maxplayers 32 +map de_dust2 -sv_lan 0 -port 27015


