# Instalación

Vamos a proceder a la instalación de Kubernetes en nuestro servidor:

### 1. Lo primero que debemos hacer es actualizar los repositorios:

```
apt update
```

### 2. Descargamos k0s:

```
curl -L https://get.k0s.sh |sh
```
![Descargak0s](https://github.com/juanglez01/K0S/blob/3619ff4ecabace088040c3e6e0578486955ae19c/Imagenes/descargak0s.png)

### 2. Le proporcionamos permisos de ejecutable:

```
chmod 777 /usr/local/bin/k0s
```
![Permisosk0s](https://github.com/juanglez01/K0S/blob/c43e5e1fbc970a7f57c42a69e2acb44697482646/Imagenes/permisosk0s.png)

### 3. Lo instalamos con un único nodo:

```
k0s install controller --single
```
![k0snodos](https://github.com/juanglez01/K0S/blob/9aac6a19fc9a1e5d72baf08e4e36a50d346ddfe5/Imagenes/k0snodos.png)

### 4. Iniciamos K0S:

```
k0s start
```
![Clouding.io]()

### 5. Comprobamos si eel servicio está funcionando correctamente:

```
systemctl status k0scontroller.service
```
![Clouding.io]()
