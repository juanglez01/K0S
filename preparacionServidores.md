# Preparación del Servidor

## 1. Verificamos que nuestra máquina tiene instalado el paquete ssh:

```
apt policy ssh
```
![aptpolicyssh](https://github.com/juanglez01/K0S/blob/658e4646ec5cef1b7a1de0a4e801e32e525b7d79/Imagenes/policyssh.PNG)

```
apt policy openssh-server
```
![aptpolicyssh](https://github.com/juanglez01/K0S/blob/b2a182eb263a5aba5fe084efba29de96f611f8cf/Imagenes/policysshserver.PNG)

## 2. Configuración clave pública servidor:

1. Entramos en nustro servidor de Cloudin.io

```
ssh root@Ip_Servidor
```
Nos pedirá si estamos seguro de conectarnos a esa máquina y respondemos: **yes**
![conexionsevidor](https://github.com/juanglez01/K0S/blob/8b8a3f6a42366e3360b21f67aa36281b7fc6aa3f/Imagenes/conexion.PNG)
