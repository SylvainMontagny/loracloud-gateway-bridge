The Chirpstack Gateway Bridge permits to connect UDP Packet Forwarder GW to LoRaCloud Network Server

1. Clone this repo
2. Log on ns.loracloud.com
3. Register a new Gateway and create Certificate : Gateways > your_gateway > Certificate > Generate Certificate
4. Store CA certificate under ca.pem
5. Store TLS certificate under cert.pem
6. Store TLS key under key.pem
7. Copy ca.pem, cert.pem, key.pem to the /configuration/chirpstack-gateway-bridge/ folder
8. If you want to change UDP Packet forwarder port (default 1701 !) change 1701:1701 to whatever port you want in docker-compose.yml file.
9. sudo docker-compose up -d

