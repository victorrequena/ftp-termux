# ftp-termux

## INSTALACION

Inicia instalando python3 
```sh
pkg install python
```
FTP por python requiere un modulo pip llamado pyftpdlib 
```sh
python -m pip install pyftpdlib
```
```sh
termux-setup-storage
```
De permisos de ejecion al archivo ftpserver
```sh
chmod +x ftpserver.py
```
Inicie ftpserver.py
```sh 
python3 ftpserver.py
```
Para poner en segundo plano 
```sh
python3 ftpserver.py &
```
