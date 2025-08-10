# ROL

#### Hali Hazırda Olan Gensyn Sunucumuzdan Devam Ediyoruz ; 

- Screen ; 



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


```bash
screen -S gswarm
```



