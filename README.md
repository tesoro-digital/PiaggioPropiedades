# PiaggioPropiedades
on:
push name:
Publish
Website jobs:
FTP-Deploy-Action:

name: FTP-Deploy-Action
runs-on: ubuntu-latest steps: - uses:

actions/checkout@v2.1.0 with: fetch-depth: 2
- name: FTP-Deploy-Action
uses:
SamKirkland/FTP-Deploy-Action@3.1.1
with: ftp-server: ftp://ftp.piaggiopropiedades.com:21/public_html
ftp-username: adagracielapiaggio
ftp-password: ${{ secrets. PiaggioPropiedades36 }}
