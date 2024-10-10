# Configuracion servidor Debian como DHCP
---
### 1 Preparacion
### 2 vale
### 3 vale
### 4 vale
---

## 1. Aqui te muestro la configuracion de la ip del propio servidor.
![img1](/dhcp_debian/Ip_servidor.PNG)

## 2. Aqui te muestro la instalacion del servicio de DHCP.
![img2](/dhcp_debian/instalacion_servicio_dhcp.PNG)

## 3. Aqui te muestro el fichero de configuracion en el que indicamos cual es la interfaz de red que queremos utilizar.
![img3](/dhcp_debian/isc_dcp_server.PNG)

## 4. Aqui te muestro todos los apartados que tenemso que configurar red, rangos de ip, dns principal, el nombre del dominio, etc... Despues te muestro la reserva del Cliente de Ubuntu.
![img4](/dhcp_debian/dhcpd.conf.PNG)
![img5](/dhcp_debian/dhcpd2.conf.PNG)

## 5. Aqui te muestro como el servicio esta arrancado y funciona correctamente.
![img6](/dhcp_debian/restart_status.PNG)

## 6. Aqui te muestro la ip del Cliente de Windows y de Ubuntu.
![img7](/dhcp_debian/ip_windows.PNG)
![img8](/dhcp_debian/ip_ubuntu.PNG)

## 7. Aqui te muestro las concesiones del servidor y en este caso solo nos saldria la de windows porque la de ubuntu no es una concesion es una reserva.
![img9](/dhcp_debian/var_lib_dhcp_dhcpd.leases.PNG)

## 8. Aqui comprobamos que hay conexion entre los dos clientes haciendo un ping.
![img10](/dhcp_debian/ping.PNG)

## 9. Aqui te muestro como los dos hacen ping a google y tienen internet.
![img11](/dhcp_debian/ping_google.PNG)

## 10. Aqui te muestro los registros de acceso del cliente de windows al servidor.
![img12](/dhcp_debian/journal.PNG)
![img12](/dhcp_debian/journal2.PNG)