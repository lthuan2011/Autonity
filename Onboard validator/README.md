
# Validator

## Install Autonity
```
sudo apt install curl -y && source <(curl -s https://raw.githubusercontent.com/lthuan2011/Autonity/main/Open%20the%20door/auto_install)
```
```
mkdir piccadilly-keystore && chmod +x piccadilly-keystore && cd $HOME
```
```
cp -r $HOME/autonity-client/autonity-chaindata/autonity/autonitykeys $HOME/piccadilly-keystore/
```
Upload wallet.key to folder: piccadilly-keystore

## Install Oracle

```
aut account new --keyfile ./piccadilly-keystore/oracle.key
```

