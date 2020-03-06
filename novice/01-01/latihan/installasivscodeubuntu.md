# instalasi vs-Code untuk Distribusi linux berbasis Debian dan Ubuntu

**Cara termudah untuk menginstal Visual Studio Code** 
untuk distribusi berbasis Debian / Ubuntu adalah dengan mengunduh dan menginstal paket .deb (64-bit) >> https://go.microsoft.com/fwlink/?LinkID=760868, 
Atau
melalui baris perintah dengan:

```terminal
curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
sudo install -o root -g root -m 644 packages.microsoft.gpg /usr/share/keyrings/
sudo sh -c 'echo "deb [arch=amd64 signed-by=/usr/share/keyrings packages.microsoft.gpg]
https://packages.microsoft.com/repos/vscode stable main" > /etc/apt/sources.list.d/vscode.list'
```
Lalu update paket nya dan install paket menggunakan
```linux
sudo apt-get install apt-transport-https
sudo apt-get update
sudo apt-get install code # or code-insiders
```

