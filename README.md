<p style="font-size:14px" align="right">
<a href="https://t.me/autosultan_group" target="_blank">Join our telegram <img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
</p>

<p align="center">
  <img height="150" height="auto" src="https://user-images.githubusercontent.com/38981255/185994172-0b4e4ea8-f81a-48db-8020-9be619f485b7.png">
</p>

# ALEO INCENTIVE TESTNET
***Sebelum jalankan ini biasakan sedia kopi biar kgk puyeng***

## SPEK VPS
|  Komponen |  Persyaratan Minimum |
| ------------ | ------------ |
| CPU  | 6 or more physical CPU cores  |
| RAM | At least 16GB of memory (RAM) |
| Penyimpanan  | At least 400GB of SSD disk storage |
| Internet | At least 10mbps network bandwidth |

## INSTALL NODE (PROSES EMANG LAMA KUDU SABAR)
```
wget -O aleo.sh https://raw.githubusercontent.com/sipalingnode/Aleo/main/aleo.sh && chmod +x aleo.sh && ./aleo.sh
```

## RUNNING NODE
```
cd snarkOS
screen -S aleo
```

```
./run-prover.sh
```
***Masukkan Privatekey kalian kemudian enter dan CTRL+AD***
***Untuk mengecek lagi bisa gunakan command ini*** `screen -rd aleo`

## Perintah Berguna
## Uinstall Node (ini hanya untuk yang mau menghapus node)
```
rustup self uninstall
rm -rf prover.sh
rm -rf snarkOS
```

## Explorer Aleo : https://aleo123.io/
