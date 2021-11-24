# rootcertwithpowershell

Install a remote root certificate in ms windows using powershell

$FLAGDOWNLOAD = 0

$FLAGINSTALL = 0

$URL_PATH =  NETWORK path to download certificate e.g. "http://192.168.1.2:8000/ca.crt"

$CERT_LOCATION =  Where to download certificate e.g. "$env:public\firewallssl.cer"

$DONOTDELETE_FILE = flag to check if certificate is correctly installed - e.g. "DONOTDELETE_CERT_OK.txt"

$FLAGLOCATION = flag location - e.g. $env:public

$FLAGNAME = flag name "DONOTDELETE_CERT_OK.txt"
