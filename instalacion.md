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

### 2. Le proporcionamos permisos de ejecutable:

```
chmod 777 /usr/local/bin/k0s
```

### 3. Lo instalamos con un único nodo:

```
k0s install controller --single
```

### 4. Iniciamos K0S:

```
k0s start
```

### 5. Comprobamos si eel servicio está funcionando correctamente:

```
systemctl status k0scontroller.service
```
