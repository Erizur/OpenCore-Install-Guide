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

OpenCore es lo que referimos como un "gestor de arranque", esto es una compleja pieza de software que usamos para preparar nuestros sistemas para macOS. Especificamente, inyectando nuevos datos para macOS como SMBIOS, tablas de ACPI y extensiones del kernel (kexts). Esta herramienta es diferente a otras como Clover porque ha sido diseñado con security y calidad en mente, permitiendonos usar to use many security features found on real macs such as SIP and FileVault. A more in-depth look can be found at here: [Why OpenCore over Clover and others](why-oc.md)

This guide specifically focuses on 2 main things:

* Installing macOS on an X86 based PC
* Teaching you what makes your hack work

Because of this, you will be expected to read, learn and even google. This is not a simple 1-click install setup.

Please remember that OpenCore is still new and currently in beta. While quite stable, and arguably much more stable than Clover in pretty much every way, it is still being frequently updated and so chunks of configuration change quite often(ie. New quirks replacing old ones)

Lastly, those having issues can visit both the [r/Hackintosh subreddit](https://www.reddit.com/r/hackintosh/) and [r/Hackintosh discord](https://discord.gg/u8V7N5C) for more help.
