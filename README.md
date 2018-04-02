# Description
- Axway Service Broker for Pivotal Cloud Foundry tile

## Prerequisites
- Install Pivtoal Cloud foundry tile - Reference : https://docs.pivotal.io/tiledev/2-0/tile-generator.html
- Check out https://github.com/Axway-API-Management-Plus/Cloud-Foundry-Service-Broker-Sample
- Goto the folder ( Cloud-Foundry-Service-Broker-Sample )
- mvn clean install
- Copy axway-apim-service-broker-x.x.x.jar to axway-apim-sb-tile/resources

# Build Tile

```bash
tile build
 ```
 
 The above command generate a file axway-x.x.x.pivotal under products folder. 
 
 # Import Tile to Pivotal Ops Manager
 - Import axway-x.x.x.pivotal file on PCF ops manager. 
 - Enter  enviroment variables
 - Click Apply changes 
