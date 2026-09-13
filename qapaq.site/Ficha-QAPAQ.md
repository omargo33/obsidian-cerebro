---
tags:
  - config
  - ficha
---
# Ficha de equipo # vps-qapaq.site.vps.ovh.ca

### Información del Servidor

| Nombre     | Valor                                                                             |
| ---------- | --------------------------------------------------------------------------------- |
| Propósito  | landigpage                                                                        |
| Ip         | 142.44.241.249                                                                    |
| Puerto ssh | 8022                                                                              |
| Usuario    | debian                                                                            |
| S.O        | debian                                                                            |
| KVM        | https://manager.ca.ovhcloud.com/#/dedicated/vps/vps-65a90309.vps.ovh.ca/dashboard |
| Memoria    | 4GB                                                                               |
| Disco      | 40GB                                                                              |
| Procesador | 2 vCores                                                                          |
### Github Runners

| Nombre                    | Funcion       | Path                            |
| ------------------------- | ------------- | ------------------------------- |
| action-runner-database-v1 | base de datos | $HOME/action-runner-database-v1 |
| action-runner-manager-v1  | manager JAVA  | $HOME/action-runner-manager-v1  |
| action-runner-site-v1     | Web           | $HOME/action-runner-site-v1     |
## APP's S.O.
- **lolcat**: visualización arco iris. 
- **tree**: visualizar árbol 
- **htop**: visualizar procesos

### Config Files

- **$HOME/.customConfig**: para personalizar la configuración alterando lo menos posible los  servicios. 

## 🏁 Tareas

- [ ] Quitar Password y pasarlos por Screts github  [priority:: low]  [due:: 2026-09-13]
- [ ] Retirar JAVA y MAVEN para dejar solo por docke