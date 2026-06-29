# Account registration

 Lightweight PHP-FPM account registration service to create login-server accounts in the L2J login database.
 
 Includes Caddy reverse proxy and obtains the Let's Encrypt certificate. 

1. Drag the module into *server* folder.
2. Use DOMAIN_REGISTER to set the public hostname, e.g. register.localhost
3. Run *make up* or *.\compose up*.
4. Navigate to https://register.localhost/
