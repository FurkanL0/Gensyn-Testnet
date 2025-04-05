## Hata ; 

![image](https://github.com/user-attachments/assets/c81b19f0-60b1-4a01-8239-a26ea7afd05d)

#### ÇÖzüm ; 

- CTRL C ile nodenizi durdurun.

```bash
cd /root/rl-swarm/modal-login/
yarn upgrade
yarn add next@latest
yarn add viem@latest
cd ..
```


## Hata ; 

#### Mail Gelmilyor.

![image](https://github.com/user-attachments/assets/c101cd60-0e84-4148-9fdd-000e612552c4)

#### Çözüm :

- Ngrok ile mail gelmeme sorununu çözebiliriz.

- Ngrok İndir 

- X86 ( amd64 ) Serverlar İçin Ngrok İndirme ; 
```bash
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz && tar -xvzf ngrok-v3-stable-linux-amd64.tgz && sudo mv ngrok /usr/local/bin/
```
- Arm64 Serverlar için Ngrok İndirme ; 
```bash
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-arm.tgz && tar -xvzf ngrok-v3-stable-linux-arm.tgz && sudo mv ngrok /usr/local/bin/
```

- Link : https://ngrok.com/
- Kayıt oluyoruz.
- Your AuthToken'a basın soldan önünüze açılan sayfada göz işaretine basıp keyinizi gördün. 

![428863754-4f317fd4-2715-4143-bcd2-5020fc5a8955](https://github.com/user-attachments/assets/e837875d-31aa-49f9-a3e1-659885dc8d66)

- Komutu sunucunuzda yapıştırın.

![428867019-18646475-4495-436c-92bc-b9df94bd39af](https://github.com/user-attachments/assets/9528da85-3515-4827-9f7a-be181369fe48)

```bash
screen -S ngrok
```

```bash
ngrok http 3000
```

#### Gösterdiği Linke tıklayıp onay verin - sizi giriş sayfasına yönlendiricek.

![image](https://github.com/user-attachments/assets/5cad13ae-2a42-49f0-ae0c-6669eb0225b6)


![image](https://github.com/user-attachments/assets/b20cf6c5-62b0-4701-9d7c-ac9a7a524213)
