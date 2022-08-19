+++
title= "Crear Laboratorio de Practicas (MetaSploitable2)"
description = "Pendiente"
author = "Juankar"
date = "2022-08-19"
tags = ["seguridad", "ejemplo"]
categories = ["windows"]
draft = false
+++


Instalar [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

Instalar [MetaSploitable2](https://sourceforge.net/projects/metasploitable/files/Metasploitable2/)
- User: msfadmin
- Contraseña: msfadmin

Instalar [Kali_Linux](https://www.kali.org/get-kali/#kali-virtual-machines)

Crear Red NAT en VirtualBox para las 2 máquinas (Preferencias/Red/new[NAT1])

Meter las 2 VM en la misma NAT (Config/Red/NAT1 / Avanzado/Modo promiscuo:Permitir todo/Actualizamos MAC y Aceptar)

Abrir las 2 VM

`ifconfig` en #Metasploit para ver la IP (ej: `10.0.2.4`)

Metemos esa IP en Kali/Firefox

