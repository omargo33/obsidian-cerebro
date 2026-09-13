---
tags:
  - config
  - ficha
---
# Ficha de equipo # vps-qapaq.site.vps.ovh.ca

### Información del Servidor

| Valor                                                                             | Nombre     |
| --------------------------------------------------------------------------------- | ---------- |
| landigpage                                                                        | Propósito  |
| 142.44.241.249                                                                    | Ip         |
| 8022                                                                              | Puerto ssh |
| debian                                                                            | Usuario    |
| debian                                                                            | S.O        |
| https://manager.ca.ovhcloud.com/#/dedicated/vps/vps-65a90309.vps.ovh.ca/dashboard | KVM        |
| 4GB                                                                               | Memoria    |
| 40GB                                                                              | Disco      |
| 2 vCores                                                                          | Procesador |
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
- Mapa del sitio [[config-Qapaq.site]]

## 🏁 Tareas

Para ver las tareas pendiente de desarrollo y componentes [[Pendientes]]
Para las tareas de configuración, incluir a continuación:

- [ ] Quitar Password y pasarlos por Screts github  [ priority:: high]   [due:: 2026-09-13]
- [ ] Retirar JAVA y MAVEN para dejar solo por docker las instancias [priority:: low]  [due:: 2026-09-13]