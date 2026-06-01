# P02 - Implantación de Máquina Virtual Ubuntu Server

## 1. Descripción

En esta práctica se ha realizado la instalación y configuración de una máquina virtual con Ubuntu Server LTS.  
El objetivo ha sido disponer de un sistema base funcional para trabajar posteriormente con servicios de red y administración de sistemas a lo largo del curso.

Se ha priorizado una correcta planificación y documentación del proceso, siguiendo una metodología profesional que permita repetir la instalación sin errores.

---

## 2. Requisitos aplicados

Se han cumplido todos los requisitos indicados en la práctica:

- Memoria RAM: 4 GB  
- Disco duro: 20 GB  
- Adaptador de red 1: NAT  
- Adaptador de red 2: Red puente  
- Dirección IP: 192.168.X.X /24  
- Usuario: usuario  
- Contraseña: usuario  
- Servicio SSH: instalado  

<h2>Prueba de implementación</h2>

<p>
A continuación se muestra evidencia de la máquina virtual creada en VirtualBox, donde se pueden observar 
las características de hardware configuradas según los requisitos del proyecto.
</p>

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1O8AeUEnUpqeLCHMZCbZojhwPWzAwBbhf" 
       alt="Máquina virtual Ubuntu Server en VirtualBox" 
       width="600">
</p>

<p align="center">
  <em>Visualización de la máquina virtual con los recursos asignados (RAM, disco y adaptadores de red).</em>
</p>


---

## 3. Proceso de instalación

### 3.1 Creación de la máquina virtual  
Se ha creado una nueva máquina virtual utilizando un software de virtualización.  
Se ha seleccionado Linux como sistema operativo y Ubuntu Server como versión.

### 3.2 Asignación de recursos  
Se han asignado los siguientes recursos:

- 4 GB de memoria RAM  
- 20 GB de disco duro en formato dinámico  

### 3.3 Configuración de red  
Se han configurado dos interfaces de red:

- La primera en modo NAT, para disponer de acceso a Internet  
- La segunda en modo puente, para permitir la comunicación en red local  

---

## 4. Instalación del sistema operativo

Durante la instalación del sistema se han configurado los siguientes parámetros:

- Idioma del sistema  
- Usuario: usuario  
- Contraseña: usuario  
- Instalación sin entorno gráfico  
- Instalación del servidor SSH durante el proceso  

Se ha completado la instalación correctamente sin errores.

---

## 5. Configuración de red

Se ha configurado la red mediante Netplan para asignar una dirección IP estática en el adaptador de red puente.

Se ha editado el archivo de configuración del sistema para definir:

- Dirección IP  
- Puerta de enlace  
- Servidor DNS  

Una vez aplicada la configuración, se ha verificado la conectividad correctamente.

---

## 6. Configuración del servicio SSH

Se ha comprobado que el servicio SSH está correctamente instalado y en ejecución.

Se ha verificado el acceso remoto mediante conexión desde otro equipo utilizando la dirección IP asignada.

El servicio funciona correctamente, permitiendo la administración remota del sistema.

---

## 7. Exportación de la máquina virtual

Una vez finalizada la configuración, la máquina ha sido exportada en formato OVA.

Esto permite reutilizar el sistema rápidamente en el futuro sin necesidad de repetir la instalación completa.

---

## 8. Resultados obtenidos

El sistema ha quedado completamente funcional:

- Sistema operativo instalado correctamente  
- Configuración de red operativa  
- IP estática configurada  
- Acceso remoto mediante SSH activo  
- Máquina virtual exportada en formato OVA  

---

## 9. Problemas encontrados y solución

Durante la práctica se han identificado algunos problemas:

- Error en la configuración de la red  
  Solución: revisión de la sintaxis del archivo de configuración  

- Problemas de conectividad  
  Solución: comprobación de la configuración del adaptador puente  

- SSH no accesible inicialmente  
  Solución: instalación y verificación del servicio  

---

## 10. Conclusión

Esta práctica ha permitido comprender el proceso completo de instalación y configuración de un servidor Linux.

Se han trabajado aspectos clave como:

- Configuración de red  
- Acceso remoto  
- Virtualización de sistemas  

Además, se ha demostrado la importancia de la documentación para poder reproducir el entorno de forma fiable y profesional.

Este sistema servirá como base para el desarrollo de futuras actividades del curso.
``
