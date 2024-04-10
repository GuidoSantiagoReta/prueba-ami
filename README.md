# aws EC2 - integración con terraform - terraform docs - github actions - Grafana

### Configuración AWS EC2 CON TERRAFORM 

- En este proyecto se realizó la configuracion de terraform y la EC2 de forma modularizada en varios archivos .tf
- Se creo la vpc, grupos de seguirdad, instancia y los diferentes secrets para el acceso ala EC2 DE AWS con github actions y la actualización automática de la ip publica porconexión por SSH.


### USO DE TERRAFORM DOCS
- Se instaló terraform docs con choco desde un ordenador windows por powershell.

![terraformdocs-chocolatey](https://github.com/GuidoSantiagoReta/prueba-ami/assets/46303885/42303295-0a60-4479-984f-816a65d58c23)


### EJECUTAR TERRAFORM DOCS EN EL PROYECTO Y CREAR EL DOCUMENTO

```
terraform-docs markdown . > Terraformdocs.md

```
