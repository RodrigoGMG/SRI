
# Configuración servidor Debian como DHCP
# Índice
 
- [Configuración servidor Debian como DHCP](#configuración-servidor-debian-como-dhcp)
- [Índice](#índice)
  - [1. Configuración de la IP del propio servidor](#1-configuración-de-la-ip-del-propio-servidor)
  - [2. Instalación del servicio de DHCP](#2-instalación-del-servicio-de-dhcp)
  - [3. Configuración de la interfaz de red en el fichero](#3-configuración-de-la-interfaz-de-red-en-el-fichero)
  - [4. Configuración de red, rangos de IP, DNS y reserva del cliente Ubuntu](#4-configuración-de-red-rangos-de-ip-dns-y-reserva-del-cliente-ubuntu)
  - [5. Verificación del servicio DHCP activo](#5-verificación-del-servicio-dhcp-activo)
  - [6. IP del cliente Windows y Ubuntu](#6-ip-del-cliente-windows-y-ubuntu)
  - [7. Concesiones del servidor DHCP](#7-concesiones-del-servidor-dhcp)
  - [8. Comprobación de conectividad entre los dos clientes](#8-comprobación-de-conectividad-entre-los-dos-clientes)
  - [9. Conectividad a Internet (ping a Google)](#9-conectividad-a-internet-ping-a-google)
  - [10. Registros de acceso del cliente Windows al servidor](#10-registros-de-acceso-del-cliente-windows-al-servidor)
 
## 1. Configuración de la IP del propio servidor
![img1](/dhcp_debian/Ip_servidor.PNG)
 
## 2. Instalación del servicio de DHCP
![img2](/dhcp_debian/instalacion_servicio_dhcp.PNG)
 
## 3. Configuración de la interfaz de red en el fichero
![img3](/dhcp_debian/isc_dcp_server.PNG)
 
## 4. Configuración de red, rangos de IP, DNS y reserva del cliente Ubuntu
![img4](/dhcp_debian/dhcpd.conf.PNG)
![img5](/dhcp_debian/dhcpd2.conf.PNG)
 
## 5. Verificación del servicio DHCP activo
![img6](/dhcp_debian/restart_status.PNG)
 
## 6. IP del cliente Windows y Ubuntu
![img7](/dhcp_debian/ip_windows.PNG)
![img8](/dhcp_debian/ip_ubuntu.PNG)
 
## 7. Concesiones del servidor DHCP
![img9](/dhcp_debian/var_lib_dhcp_dhcpd.leases.PNG)
 
## 8. Comprobación de conectividad entre los dos clientes
![img10](/dhcp_debian/ping.PNG)
 
## 9. Conectividad a Internet (ping a Google)
![img11](/dhcp_debian/ping_google.PNG)
 
## 10. Registros de acceso del cliente Windows al servidor
![img12](/dhcp_debian/journal.PNG)
![img12](/dhcp_debian/journal2.PNG)