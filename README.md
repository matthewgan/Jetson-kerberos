# JETSON KERBEROS

[Kerberos](https://kerberos.io/) instance deploy on Jetson NANO with docker-compose

## Installation

```
cd ~
git clone https://github.com/matthewgan/Jetson-kerberos
cd Jetson-kerberos
```

Make volumes for saving logs, captures, webconfigs

```
mkdir -p ~/Jetson-kerberos/ 
```

```
sudo docker-compose up -d --build
```

## Validate

```
sudo docker ps
```

kerberos-camera1
kerberos-camera2


