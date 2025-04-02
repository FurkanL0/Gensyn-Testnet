# Gensyn Testnet Kurulumu

![Gensyn Testnet](https://github.com/user-attachments/assets/9a714d4c-645d-49b3-a3ce-c2a3095058cc)

## Sistem Gereksinimleri

| Bileşen        | Minimum Gereksinim              |
|----------------|----------------------------|
| **CPU**       | arm64 / amd64 |
| **RAM**       | 16+ GB                     |
| **GPU**       | RTX 3090, RTX 4090, A100, H100 |
| **Python**    | Python >= 3.10 (Mac için güncelleme gerekebilir) |
| **Depolama**  | SSD (Tavsiye edilir) |
| **Ağ Bağlantısı** | 100 Mbps (1 Gbps+ önerilir) |

### ARM64 Sunucu Kullanımı (Netcup ARM64 - 10 CPU - 16 GB RAM + 4 GB Swap RAM)

![Netcup Sunucu](https://github.com/user-attachments/assets/7f0cf1ea-ea91-45f0-834f-80bdc75798da)

![Sistem Kaynakları](https://github.com/user-attachments/assets/a100aec7-1d03-4729-b823-a745aa08a3a5)

## Uygun Sunucu Sağlayıcıları

| Sağlayıcı        | Link              | Özellikler |
|------------------|------------------|------------|
| **Contabo**     | [Bağlantı](https://www.dpbolvw.net/click-101330552-12454592) | Uygun fiyatlı, PayPal destekli |
| **PQ**          | [Bağlantı](https://pq.hosting/?from=627713) | Uygun fiyatlı, Kripto ödeme desteği |
| **NetCup**      | [Bağlantı](https://www.netcup.com/en/?ref=261820) | Uygun fiyatlı, PayPal destekli |

## Proje Bağlantıları

- **Twitter**: [Gensyn AI](https://x.com/gensynai)
- **Discord**: [Katıl](https://t.co/esOQ059S7q)

## 1. Sunucu Güncelleme

```bash
sudo apt update -y && sudo apt upgrade -y
```

## 2. Gerekli Paketleri Yükleme

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y
```

## 3. NPM Kurulumu

```bash
curl -fsSL https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
source ~/.bashrc
```
```bash
nvm install --lts
```

## 4. Python / Yarn / Git Kurulumu

```bash
sudo apt update && sudo apt install -y python3 python3-venv python3-pip git yarn && curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add - && echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list && sudo apt update && sudo apt install -y yarn
```

## 5. Hugging Face Hesabı Oluşturma

[Hugging Face](https://huggingface.co/) sitesine girip hesap oluşturun.

![Hugging Face Hesap](https://github.com/user-attachments/assets/62af4936-bcd6-4f3b-8f92-4c34cfb0e388)

**Write İzinli Tokeni Alın Tek Seferlik verir Kayıt Edin**

![Token Alma](https://github.com/user-attachments/assets/dc54f075-915c-438c-a3b7-9c11b55d7c8f)

## 6. RL-Swarm Deposu Kurulumu

```bash
git clone https://github.com/FurkanL0/rl-swarm.git && cd rl-swarm
```

## 7. Screen Başlatma

```bash
screen -S gensynrlswarm
```

## 8. SWARM Çalıştırma

```bash
python3 -m venv .venv && source .venv/bin/activate && ./run_rl_swarm.sh
```

![SWARM Çalıştırma](https://github.com/user-attachments/assets/886d20a9-00d0-425f-ba52-6b601e581acb)

Terminalde `Y` tuşuna basın ve `Enter` yapın.

#### Tarayıcınızdan bu linke ulaşın yada Sunucu IP'niz sunucuip:3000 ile erişebilirsiniz ; 

![image](https://github.com/user-attachments/assets/a5b3bbf6-f171-42e1-b41b-54d52fe2e0de)

![Giriş](https://github.com/user-attachments/assets/181d5cc7-0e3c-417c-a335-26192021aab2)

![Oturum Açma](https://github.com/user-attachments/assets/0b100bc8-9bef-4326-b126-e3a5a4fdabf4)

![Token Yapıştırma](https://github.com/user-attachments/assets/556891b2-dfae-4edd-b07d-6057c2ce5f82)

## 9. `.pem` Dosyasını Kaydetme

- `/root/rl-swarm/swarm.pem` konumunda bulunuyor pc'nize kaydedin.

![PEM Dosyası](https://github.com/user-attachments/assets/48d21c7b-0eef-4a85-9732-41f1bc009f2a)

##  OTP Doğrulama - Mail Doğrulaması Hata Alanlara

- **CC**: [Zun2025](https://x.com/Zun2025)

##  Ngrok Kurulumu

**x86 Sunucular İçin:**

```bash
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz && tar -xvzf ngrok-v3-stable-linux-amd64.tgz && sudo mv ngrok /usr/local/bin/
```

**ARM64 Sunucular İçin:**

```bash
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-arm.tgz && tar -xvzf ngrok-v3-stable-linux-arm.tgz && sudo mv ngrok /usr/local/bin/
```

Ngrok hesabı oluşturun: [Ngrok](https://ngrok.com/)

![Ngrok Auth Token](https://github.com/user-attachments/assets/4f317fd4-2715-4143-bcd2-5020fc5a8955)

##  Ngrok Başlatma

```bash
screen -S ngrok
```
```bash
ngrok http 3000
```

##  Tarayıcıda Açın

![Ngrok Link](https://github.com/user-attachments/assets/5cad13ae-2a42-49f0-ae0c-6669eb0225b6)


![image](https://github.com/user-attachments/assets/b20cf6c5-62b0-4701-9d7c-ac9a7a524213)

![image](https://github.com/user-attachments/assets/a73b6736-31fb-4fc3-84b6-ef81f2cace0d)

![image](https://github.com/user-attachments/assets/d787c7b9-1128-477c-8214-faf9a5aa140f)


Bu adımları takip ederek Gensyn Testnet'e başarılı şekilde katılabilirsiniz. 🎯
