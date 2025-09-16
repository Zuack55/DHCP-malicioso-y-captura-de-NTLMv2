![Banner](./DHCPBanner.png)

# Laboratorio: DHCP malicioso y captura de NTLMv2 (educativo)

## Resumen
Este repositorio contiene documentación para un **laboratorio controlado** que demuestra cómo un atacante en una red local puede desplegar un servidor DHCP malicioso y herramientas de respuesta (por ejemplo, *Responder*) para capturar **hashes NTLMv2** y, a partir de ahí, probar técnicas de obtención de credenciales y acceso remoto en un entorno aislado.  
El objetivo es **educativo**: entender vectores de ataque, técnicas de detección y estrategias de mitigación.

---

## 🔒 Aviso legal / Disclaimer
Este material **es solo para fines educativos y de investigación en entornos controlados**. No uses estas técnicas contra redes o sistemas para los que no tengas permiso explícito por escrito. Cualquier mal uso es responsabilidad del usuario.

---

## 🎯 Objetivos del laboratorio
- Mostrar la interacción entre un **servidor DHCP legítimo** (Windows Server) y un **servidor DHCP malicioso** (Kali).  
- Demostrar cómo servicios de respuesta y envenenamiento (LLMNR/NBT-NS/mDNS + Responder) pueden facilitar la captura de **hashes NTLMv2**.    
- Enseñar buenas prácticas para montar un entorno **seguro y aislado** para pruebas.
