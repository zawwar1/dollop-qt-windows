Getting started

Open your wallet, and make sure you are connected to another wallet. 

You are connected when you see the icon Wallet Connections in the lower right corner of your wallet.

Close your wallet and create the file credit.conf in the folder "%APPDATA%\credit\".

Paste the following text into credit.conf and save the file.

rpcuser=your_username
rpcpassword=your_password
rpcallowip=127.0.0.1
rpcport=43796
listen=1
server=1
addnode=206.189.195.40

Download the latest version of cpuminer from here and extract the zip file.

Create a .bat file named mine.bat and paste the following text into mine.bat.

minerd --url=http://127.0.0.1:43796 --userpass=your_username:your_password

Save the file inside the extracted cpuminer folder.

Open your wallet and execute mine.bat to start mining your first coins.
