# [MahDiRoO](https://telegram.me/TELE_ELEMENT_TM)


* * *


# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/Parhamtrol/TELE-ELEMENT
cd TELE-ELEMENT
chmod +x matador.sh
chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh
./matador.sh install
./matador.sh 
# Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/Parhamtrol/TELE-ELEMENT && cd TELE_ELEMENT && chmod +x matador.sh && chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh && ./matador.sh install && ./matador.sh
```

* * *

### launch Bot

```
killall screen
cd TELE_ELEMENT && screen ./matador.sh
```

* * *


### auto launch 
```
killall screen
cd TELE_ELEMENT && screen ./auto.sh
```

* * *


### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    377450049,
    0,
    YourID
  }
