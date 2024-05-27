# traefik-proxy
Traefik configuration

##### On Windows:
- Open Cert Manager
- Expand Trusted Root Certification Authorities
- Right click on Certificates and select All Tasks > Import
- Import the `ca.crt` file from the certs folder

#### Firefox Special Instructions:
Firefox uses its own certificate manager
- Go to settings
- Search for certs
- Click View Certificates
- Select the Authorities tab
- Select import
- Import the `ca.crt` file from the certs folder