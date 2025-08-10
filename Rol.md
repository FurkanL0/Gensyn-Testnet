# ROL

#### Hali Hazırda Olan Gensyn Sunucumuzdan Devam Ediyoruz ; 

- Screen ; 

```bash
screen -S gswarm
```

- Go ; 

```bash
cd /tmp
wget -q https://go.dev/dl/go1.21.5.linux-amd64.tar.gz
rm -rf /usr/local/go
tar -C /usr/local -xzf go1.21.5.linux-amd64.tar.gz
echo 'export PATH=$PATH:/usr/local/go/bin:$HOME/go/bin' >> ~/.bashrc
source ~/.bashrc
```
<img width="759" height="166" alt="image" src="https://github.com/user-attachments/assets/484bf7d8-b94a-4ee9-83c0-de668436ea53" />


- Swarm CLI ; 

```bash
/usr/local/go/bin/go install github.com/Deep-Commit/gswarm/cmd/gswarm@latest
export PATH=$PATH:/usr/local/go/bin:$HOME/go/bin
```

<img width="787" height="219" alt="image" src="https://github.com/user-attachments/assets/1f4fc2db-e60a-488f-9e06-c49a1f8452e9" />

```bash
gswarm --version
```

<img width="500" height="61" alt="image" src="https://github.com/user-attachments/assets/55db8f31-36cc-4e4f-a021-2aee71b563ae" />


## Telegram ; 

- Telegramda BotFather'a gidip /newbot yazıp enterliyoruz. Link https://t.me/BotFather
- İsim veriyoruz
- Sonrasında kullanıcı adı tarzında isim seçtiriyor diyelim zattirizort koyacaksınız zattirizort_bot yazacaksınız bot olduğunu göstermek için.

<img width="624" height="628" alt="image" src="https://github.com/user-attachments/assets/52d22013-ab35-4406-9de4-d999190019d6" />

- Sonrasında botunuza tıklayın ve bir tane mesaj atın nokta olur random olur.

#### Chat ID Alalım ; 


- Aşağıdaki Linki düzenliyip tarayıcımızdan gireceğiz.
- Örnek : https://api.telegram.org/bot1234567890:ABCdefGHIjklMNOpqrsTUVwxyz/getUpdates
- Bot üzerinden aldığımız API'yi yazıyoruz - örnekteki gibi başında bot olacak onu değiştirmeyin.

<img width="396" height="436" alt="image" src="https://github.com/user-attachments/assets/9731bbfd-8752-452a-9963-29445fac63e0" />

- Chat ID Kaydedelim.

### EOA Adresini Alalım ; 

- Link : https://dashboard.gensyn.ai/

<img width="862" height="334" alt="image" src="https://github.com/user-attachments/assets/c348d2c4-345c-4798-8bbb-49a5e0f50261" />

## Rolümüzü Alalım ; 

```bash
screen -S gswarm
```

```bash
gswarm
```
<img width="671" height="296" alt="image" src="https://github.com/user-attachments/assets/5b18907b-1b39-4f56-8dcf-b4cc4d577597" />

- 1. İstediği Telegram Botfather'dan aldığımız Use this token to access the HTTP API:'nin altındaki key.
- 2. Tarayıcıdan girip aldığımız chat id.
- 3. Dashboard'dan Aldığımız EAO adress.

#### Discord'a Gidiyoruz ve Link To Access Kanalına Giriyoruz ; 

- /link-telegram Yazıp Yukarıdan Bot'u seçip enterliyoruz.

<img width="605" height="341" alt="image" src="https://github.com/user-attachments/assets/d153f710-43af-4b45-9d07-307d905a1ad7" />

- Telegramda Oluşturduğunuz Bot'a gelin - Discord üzerinde verilen /verify 13435454 yazanı yapıştırıp yollayın.

<img width="483" height="172" alt="image" src="https://github.com/user-attachments/assets/a9de83fa-0d22-49e7-8277-efa98bc5027b" />

- Bitti Rolünüz tanımlandı DC üzerinden kontrol edebilirsiniz.
