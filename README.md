<h1 align="center">Obol Network testnet başvuru </h1>

### Obol Türkiye Telegram Kanalı: [Obol Türkiye](https://t.me/ObolNetworkTurkish)

![image](https://user-images.githubusercontent.com/101149671/181920449-8aeb9c05-e068-415a-b42b-38f77f8d206c.png)

<h1 align="center">Selamlar, Obol Network testnet başvurucaz, sistem gereksinimi yok, herhangi bir sunucuda private key alabilirsiniz 2 dakikada. </h1>


<h1 align="center">Obol kurulu sunucunuzu sıfırlamadayısanız altta vereceğim komutu kullanarak private keyi alabilirsiniz. </h1>

* Private keyi not edin ve kimseyle paylaşmayın.
* ENR adresinizi [discord kanalı](discord.gg/ruescommunity) #obol-enr-adres odasına enr adresinizi gönderin.

```
nano ~/charon-distributed-validator-node/.charon/charon-enr-private-key
```

<h1 align="center">Obol kurulu sunucunuzu sıfırladıysanız altta vereceğim komutları kullanarak enr adresi ve private keyi alabilirsiniz. </h1>


## Sistem güncellemeleri:
```
sudo apt update && sudo apt upgrade -y
sudo apt install make clang pkg-config libssl-dev libclang-dev build-essential git curl ntp jq llvm tmux htop screen unzip -y
```

## Docker
```
curl -fsSL https://get.docker.com/ -o get-docker.sh
sudo sh get-docker.sh
```
```
curl -SL https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```

## Gerekli kurulumlar:
```
git clone https://github.com/ObolNetwork/charon-distributed-validator-node.git
chmod o+w charon-distributed-validator-node
cd charon-distributed-validator-node
```

## Son olarak bu komutu giriyoruz ve private key verecek, gözümüz gibi saklayalım:
```
docker run --rm -v "$(pwd):/opt/charon" ghcr.io/obolnetwork/charon:v0.8.1 create enr 
```
![image](https://user-images.githubusercontent.com/101149671/181920572-7a59a358-9774-40dd-9317-9dd07419d878.png)


## Private key alma:

* Private keyi not edin ve kimseyle paylaşmayın.
* ENR adresinizi [discord kanalı](discord.gg/ruescommunity) #obol-enr-adres odasına enr adresinizi gönderin.

```
nano ~/charon-distributed-validator-node/.charon/charon-enr-private-key
```

## SORUN YAŞARSANIZ: https://t.me/ObolNetworkTurkish


