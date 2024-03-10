
# Validator

## Install Autonity
```
sudo apt install curl -y && source <(curl -s https://raw.githubusercontent.com/lthuan2011/Autonity/main/Onboard%20validator/auto_install)
```
```
mkdir piccadilly-keystore && chmod +x piccadilly-keystore && cd $HOME
```
```
cp -r $HOME/autonity-client/autonity-chaindata/autonity/autonitykeys $HOME/piccadilly-keystore/
```
```
aut account new --keyfile ./piccadilly-keystore/wallet.key
```
If you already have wallet before
**Upload wallet.key to folder: piccadilly-keystore**

## Install Oracle

```
aut account new --keyfile ./piccadilly-keystore/oracle.key
```
change xxx is pass of oracle
```
pass_oracle="xxx" && sudo apt install curl -y && source <(curl -s https://raw.githubusercontent.com/lthuan2011/Autonity/main/Onboard%20validator/oracle_install)
```
