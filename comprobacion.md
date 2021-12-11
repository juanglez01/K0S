# Comprobación de la instalación


## Creamos un pod de ejemplo:

```
k0s kubectl run pod-nginx --image=nginx
```


## Vemos los elementos desplegados en k0s:

```
k0s kubectl get all
```


## Vemos la descripción del pod creado:

```
k0s kubectl describe pod/pod-nginx
```

