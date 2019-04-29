# open-mongodb-release

##1. Mongodb Configuration
- PaaS-TA-mongodb-broker :: 1 machine
- Mongos :: 1 machine
- Mongo Config :: 1 machine
- Mongod :: 1 machine

##2. Download
- $ wget -O download.zip http://45.248.73.44/index.php/s/fjzyMqDCAgzjiFA/download
- $ unzip download.zip

##3. Deploy
>`$ cd $BOSH_RELEASE_DIR`<br>
>`$ bosh deployment mongodb-vsphere-1.yml`<br>
>`$ bosh deploy`
