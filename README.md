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


#### ARm64 Server Usage ( Netcup ARM64 - 10 Cpu - 16 Ram + 4 GB Swap Ram ) ; 

![image](https://github.com/user-attachments/assets/7f0cf1ea-ea91-45f0-834f-80bdc75798da)

![image](https://github.com/user-attachments/assets/a100aec7-1d03-4729-b823-a745aa08a3a5)


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
curl -fsSL https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
source ~/.bashrc
```

```bash
nvm install --lts
```

## 4. Python / Yarn / Git : 

```bash
sudo apt update && sudo apt install -y python3 python3-venv python3-pip git yarn && curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add - && echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list && sudo apt update && sudo apt install -y yarn
```

## HugginFace ; 

#### Crate Account : https://huggingface.co/

![image](https://github.com/user-attachments/assets/62af4936-bcd6-4f3b-8f92-4c34cfb0e388)


#### Access Token with Write permissions

![image](https://github.com/user-attachments/assets/dc54f075-915c-438c-a3b7-9c11b55d7c8f)


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

![image](https://github.com/user-attachments/assets/886d20a9-00d0-425f-ba52-6b601e581acb)


- Y , enter.

#### Visit This Link on Your Browser ; 

![image](https://github.com/user-attachments/assets/a5b3bbf6-f171-42e1-b41b-54d52fe2e0de)


#### Login With Email / Google etc.

![image](https://github.com/user-attachments/assets/181d5cc7-0e3c-417c-a335-26192021aab2)

![image](https://github.com/user-attachments/assets/0b100bc8-9bef-4326-b126-e3a5a4fdabf4)

![image](https://github.com/user-attachments/assets/a25090c5-2792-415f-a1d3-7cb66dee5f88)



## Y, Enter ; 

![image](https://github.com/user-attachments/assets/c0472fa2-19bb-4805-b5fa-5a96e9a0129e)

#### Paste Your HuggingFace Key ; 

![image](https://github.com/user-attachments/assets/556891b2-dfae-4edd-b07d-6057c2ce5f82)


![image](https://github.com/user-attachments/assets/45bb15f9-1f72-4b72-8a84-be8d1445a5fd)

- CTRL A + D


## Save .pem ; 

- /root/rl-swarm/swarm.pem 

![image](https://github.com/user-attachments/assets/48d21c7b-0eef-4a85-9732-41f1bc009f2a)


## OTP ; 

#### CC : https://x.com/Zun2025

#### Install NGROK


- For x86 Servers ; 

```bash
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz && tar -xvzf ngrok-v3-stable-linux-amd64.tgz && sudo mv ngrok /usr/local/bin/
```

- For Arm64 Servers ; 
```bash
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-arm.tgz && tar -xvzf ngrok-v3-stable-linux-arm.tgz && sudo mv ngrok /usr/local/bin/
```

- Link : https://ngrok.com/
- Sing UP
- Your AuthToken

![image](https://github.com/user-attachments/assets/4f317fd4-2715-4143-bcd2-5020fc5a8955)


#### Paste Command on Your Server ; 

![image](https://github.com/user-attachments/assets/18646475-4495-436c-92bc-b9df94bd39af)


```bash
screen -S ngrok
```

```bash
ngrok http 3000
```

#### Click This Link ; 

![image](https://github.com/user-attachments/assets/5cad13ae-2a42-49f0-ae0c-6669eb0225b6)


![image](https://github.com/user-attachments/assets/b20cf6c5-62b0-4701-9d7c-ac9a7a524213)

![image](https://github.com/user-attachments/assets/a73b6736-31fb-4fc3-84b6-ef81f2cace0d)

![image](https://github.com/user-attachments/assets/d787c7b9-1128-477c-8214-faf9a5aa140f)
