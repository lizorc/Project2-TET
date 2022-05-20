# Proyect2-TET

Diseñar, implementar y configurar una arquitectura para desplegar la aplicación BookStore hacia un ambiente escalable, robusto, flexible y confiable en el proveedor de nube publica AWS implementando conceptos de virtualización y contenerización. Ademas de, activar un servicio de monetoreo de disponibilidad y seguridad. 

## Diseño de la Implementación

<p align="center">
  <img width="861" alt="image" src="https://user-images.githubusercontent.com/79216103/169447643-430a3b5d-aeda-4cc6-8c9f-3c90f0e203c9.png">
</p>

Principalmente se necesita garantizar dos zonas de alta disponibilidad donde se creara un VPC que soporte el despligue de la aplicación proporcionando una subred publica y dos privadas por cada AZ. Para lograr un despliegue de alta disponibilidad se debe implementar servicios de balanceo de cargar y auto escalamiento.

En las subredes publicas se debe localizar los recursos Bastion Host (BH) y NAT Gateway. Teniendo en cuenta que el BH se define como una entidad que permite el acceso seguro a las instancias EC2 localizada en la subred privada de la VPC. el servicio de NAT Gateway es un dispositivo que permite la operación de NAT que permitira que las instancias EC2 que estan en las subredes privadas puedan conectarse por fuera de la VPC.

## Requisitos no funcionales 

## Configuración e inicialización (opcional)

## Configuración de DNS
<p align="center">
  <img width="316" alt="image" src="https://user-images.githubusercontent.com/79216103/169452067-bc921ede-9007-4c0c-a6f4-c595ea433118.png">
</p>

Ya que tenemos las IP elasticas de las máquinas, con el servicio de Freenom se puede solicitar un dominio gratuito. La configuración del DNS queda así:

## Servicios de AWS utilizados

#### VPC
#### EC2 Instance
#### Load Balancer
#### Bation Host 
#### NAT Gateway

## Herramientas utilizadas

#### nginx
#### no se 

## Analisis de costos de la solución

## Información extra

## Participantes 
| Nombre | |
|--------|---|
| Julian Ramirez | [GitHub](https://github.com/julianramirez2) |
| Liz Rodrigues | [GitHub](https://github.com/lizorc) |
