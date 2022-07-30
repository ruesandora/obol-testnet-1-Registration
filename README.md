<h1 align="center">Obol Network testnet başvuru </h1>

### Obol Türkiye Telegram Kanalı: [Obol Türkiye](https://t.me/ObolNetworkTurkish)

![image](https://user-images.githubusercontent.com/101149671/181920449-8aeb9c05-e068-415a-b42b-38f77f8d206c.png)

<h1 align="center">Selamlar, Obol Network testnet başvurucaz, sistem gereksinimi yok, herhangi bir sunucuda private key alabilirsiniz 2 dakikada. </h1>


## Sistem güncellemeleri:
```
sudo apt update && sudo apt upgrade -y
sudo apt install make clang pkg-config libssl-dev libclang-dev build-essential git curl ntp jq llvm tmux htop screen unzip -y
```

## Docker
```
curl -fsSL https://get.docker.com/ -o get-docker.sh
sudo sh get-docker.sh

curl -SL https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```

## Gerekli kurulumlar:
```
chmod o+w charon-distributed-validator-node
git clone https://github.com/ObolNetwork/charon-distributed-validator-node.git
cd charon-distributed-validator-node
```

## Son olarak bu komutu giriyoruz ve private key verecek, gözümüz gibi saklayalım:
```
docker run --rm -v "$(pwd):/opt/charon" ghcr.io/obolnetwork/charon:v0.8.1 create enr 
```
![image](https://user-images.githubusercontent.com/101149671/181920572-7a59a358-9774-40dd-9317-9dd07419d878.png)

## Form dolduralım: [form linki](https://obol.typeform.com/AthenaTestnet?typeform-source=blog.obol.tech)

* Obol discord: 

* İlk başları okuyarak evetliyoruz:

* Diğer cevaplar opsiyonel

![image](https://user-images.githubusercontent.com/101149671/181920731-4eab1539-3abf-475a-b23d-5f73905a108e.png)



