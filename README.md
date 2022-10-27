## To set up bot you will need: 

### linux system
it have to be online so i recomend to run bot in remote server
<details> 
  <summary>If you don't know how to get one </summary> ㅤ
  
   • Digital Ocean is expencive, but by this link you will get 200$ trial for 2 months. So it up to 3 VPS free for 2 month - great choise to start, but i would not suggest to pay there.
   
   • Contabo is cheapest VPS - for bot absoulutelly ok
   
   • Hetzner - best quality/price balance (probably optimal for nodes) 
  
</details>


You will need some dependences to run bot. 
Run  command block below to update your system and install them

    cd $HOME
    sudo apt update && sudo apt upgrade -y
    apt install tmux python3-pip -y
    pip3 install getch loguru requests
