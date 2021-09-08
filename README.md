# ReStaking script - auto claiming and delegating rewards for OmniFLix Network

1. Download the script from my repository:

```bash
wget https://raw.githubusercontent.com/nook0ne/OmniFLix/main/restakingOmniFLix.sh
```

2. Give the permissions to this file:

```bash
chmod +x restakingOmniFLix.sh
```

3. Edit this script with your credentials -> change these parameters: 
DELEGATOR='Your delegator address' ;
VALIDATOR='Your validator address' ;
PASWD='pass phrase from cli' ;
DELAY=3600 #in secs - how often restart the script ;
ACC_NAME=YourWalleName 
 
 ```bash
nano restakingOmniFLix.sh
```
4. Open the screen or tmux session:
 
 ```bash
sudo apt install screen
screen -S scriptOmniFLix
```
5. Run auto claiming and delegating rewards:

 ```bash
bash restakingOmniFLix.sh
```
6. Enjoy it :)

<a href="http://manticore.team/">www.manticore.team</a> <br>
<a href="https://medium.com/@MantiCore.Team">medium.com</a>  <br>
<a href="https://t.me/MantiCoreTeam">Telegram</a>
