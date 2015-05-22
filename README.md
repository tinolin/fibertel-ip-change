# Cambiar ip de fibertel

Script para forzar el cambio de ip en el modem Fibertel
Lo bueno es que no tenes que reiniciar, ni desenchufar ni nadad de eso...

Editar: ENET_IFACE="eth0"

por la interfaz conectada al modem.

## Dependencias

  - dhcpcd

### USO

```bash
$ git clone https://github.com/tinolin/fibertel-ip-change.git
$ cd cambiar-ip-fibertel && chmod +x cambiar-ip-fibertel
$ cp  cambiar-ip-fibertel /usr/bin/
$ cambiar-ip-fibertel
```
 
### Version
0.1.1
