# Comprobación de la instalación


## Creamos un pod de ejemplo:

```
k0s kubectl run pod-nginx --image=nginx
```
![ CreacionPod ](https://github.com/juanglez01/K0S/blob/0db5fff76bd414052731280226c6ddf4a5ab59b4/Imagenes/describepod.png)

## Vemos los elementos desplegados en k0s:

```
k0s kubectl get all
```


## Vemos la descripción del pod creado:

```
k0s kubectl describe pod/pod-nginx
```

