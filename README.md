 # Gensyn-testnet


![image](https://github.com/user-attachments/assets/9a714d4c-645d-49b3-a3ce-c2a3095058cc)


| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | arm64 / amd64 |
| **RAM**          | 16++ GB                     |
| **GPU** **CUDA**     | RTX 3090, RTX 4090, A100, H100                 |
| **Python**     | Python >= 3.10 (For Mac, you may need to upgrade)                 |
| **Storage**      | x+ GB SDD                   |
| **Network**      | 100 Mbps (1 Gbps+ recommended) |

| Server Provider        | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Cheap / Paypal  |
| **PQ**      | [Link](https://pq.hosting/?from=627713)                  | Cheap / Crypto Payment |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Cheap / Paypal |

## Project : 
- Twitter : https://x.com/gensynai
- Discord : https://t.co/esOQ059S7q


## 1. Server Update : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Install Packages:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y
```

## 3. NPM :
```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs
```

## 4. Python / Yarn / Git : 

```bash
sudo apt update && sudo apt install -y python3 python3-venv python3-pip git yarn && curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add - && echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list && sudo apt update && sudo apt install -y yarn
```

## 5. Install RL-Swarm Repo ; 

```bash
git clone https://github.com/FurkanL0/rl-swarm.git && cd rl-swarm
```

## 6. Screen ; 

```bash
screen -S gensynrlswarm
```
## 7. Run The SWARM :) 
```bash
python3 -m venv .venv && source .venv/bin/activate && ./run_rl_swarm.sh
```

![image](https://github.com/user-attachments/assets/230a556a-fb87-42e9-9c79-33742d178f9a)

- Y , enter.


![image](https://github.com/user-attachments/assets/230675d9-71f1-434e-85d7-a685e2d73dbf)
