---
home: true
heroImage: /dortania-logo-clear.png
heroText: Dortania's OpenCore Install Guide
actionText: Getting Started→
actionLink: prerequisites.md

meta:
- name: description
  content: Version soportada actualmente 0.6.1
---

# Qué es OpenCore y para quién es esta guía

* **Advertencia**: Esta traduccion de la guia de OpenCore es no oficial ya que no está afiliada a [Dortania](https://github.com/dortania), por lo tanto esta guía puede quedar obsoleta rapidamente.

OpenCore es lo que referimos como un "gestor de arranque", esto es una compleja pieza de software que usamos para preparar nuestros sistemas para macOS. Especificamente, inyectando nuevos datos para macOS como SMBIOS, tablas de ACPI y extensiones del kernel (kexts). Esta herramienta es diferente a otras como Clover porque ha sido diseñado con security y calidad en mente, permitiendonos usar varias caracteristicas de seguridad encontradas en macs reales como SIP (Proteccion de la Integridad del Sistema) y FileVault. Mas informacion puede ser vista aquí: [Porque OpenCore y no Clover u otros](why-oc.md)

Esta guía especificamente se focaliza en 2 cosas principales:

* Instalar macOS en una PC basada en x86
* Enseñarte que hace que tu hackintosh funcione

Debido a esto, es muy necesario leer, aprender e incluso buscar en Google.
Esto no es una instalacion simple de 1 click.

Porfavor, acuerdese de que OpenCore es recién nuevo y en beta. Aunque sea un poco estable, mucho mas estable que Clover en varias maneras, sigue siendo actualizado frequentemente y varios chunks de configuracion cambian muy frequente. (Ejemplo: Nuevos Quirks replazando otros)

Finalmente, los que tienen problemas pueden visitar el [Subreddit r/Hackintosh (En Inglés)](https://www.reddit.com/r/hackintosh/) y el [discord de r/Hackintosh (También en Inglés)](https://discord.gg/u8V7N5C) para mas ayuda.

