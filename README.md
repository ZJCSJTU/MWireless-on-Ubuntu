# Connect Ubuntu machine to MWireless at UM

## In Wi-Fi Settings, set the following

- Wireless security: ```WPA & WPA2 Enterprise```
- Authentication: ```Protected EAP (PEAP)```
- Anonymous identity: ```<leave blank>```
- CA certificate: ```<browse to the certificate file you downloaded>```
- PEAP version: ```Version 0```
- Inner authentication: ```MSCHAPv2```
- Username: ```<U-M email address>```
- Password: ```<UMICH password>```

## Run the following
```sh SecureW2_JoinNow.run```

## See if you can connect.
