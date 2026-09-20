# MFi-Controller-Lab-App

<img width="1024" height="768" alt="ipad 8bitdo" src="https://github.com/user-attachments/assets/2295d583-e0c9-40cc-a2e8-574885e43b41" />



<img width="1024" height="768" alt="4F2B6514-BE4B-4971-BB62-D8D16B694F5B_1_105_c" src="https://github.com/user-attachments/assets/4a27fda4-26dc-42ac-a6f9-fdf686da9348" />

# 🇪🇸 Español

**MFi Controller Lab** es una aplicación para dispositivos iOS con jailbreak orientada a ampliar, gestionar y probar el soporte de mandos de juego.

Esta distribución contiene la aplicación compilada y los componentes necesarios para el funcionamiento de la app y del driver encargado de proporcionar soporte a los mandos, sin publicar el código fuente del proyecto.

> **Versión actual:** 1.0.97 Build 205  
> **Plataforma objetivo:** iOS 9.3.5 con jailbreak · armv7  
> **Distribución:** binaria (`.deb`)

---

## Advertencia y responsabilidad

MFi Controller Lab se proporciona sin garantías expresas o implícitas sobre su funcionamiento, compatibilidad o adecuación para un dispositivo concreto.

La instalación y el uso de este software se realizan bajo la responsabilidad exclusiva del usuario.

El autor no se hace responsable, en la medida permitida por la legislación aplicable, de daños, pérdidas de datos, fallos del sistema, incompatibilidades, problemas derivados del jailbreak, daños al dispositivo o al hardware, pérdida de configuraciones u otras consecuencias derivadas directa o indirectamente de la instalación, modificación o uso de MFi Controller Lab.

Cada usuario es libre de decidir si desea instalar, probar o utilizar el software y debe realizar previamente las copias de seguridad que considere necesarias.

Se recomienda no instalar MFi Controller Lab en dispositivos que contengan información importante sin disponer antes de una copia de seguridad y de un método de recuperación.

---

## ¿Qué es MFi Controller Lab?

MFi Controller Lab permite trabajar con diferentes tipos de mandos en dispositivos iOS antiguos con jailbreak, proporcionando una capa adicional de compatibilidad entre los controladores físicos, las aplicaciones compatibles con mandos MFi y otras aplicaciones como RetroArch.
Permite ademas conectar dos mandos simultaneos diferentes.

El proyecto incluye, entre otros componentes:

-Un driver que hace que los mandos importados se reconocan como MFi. Los que ya estan importados simplemente se enlazan o bien por Ajustes>Bluetooth o bien dentro de la app en Emparejar / Preparar mando en caso de que no aparezca en el primer lugar.

-Una App que permite Importar Mandos, Remapear botones, hacer shortcuts para retroarch y un test de botones de mandos. 
La distribución pública contiene **binarios precompilados**.

El código fuente del proyecto no se distribuye actualmente.

---

## Compatibilidad

Esta versión ha sido desarrollada para:

**iOS 9.3.5 · jailbreak · armv7**

El desarrollo y las pruebas originales se han realizado principalmente en un **iPad 3 con iOS 9.3.5**.

No se garantiza actualmente el funcionamiento en otras versiones de iOS, otras arquitecturas, otros dispositivos o configuraciones de jailbreak diferentes.

---

## Instalación

Descarga el archivo:

```text
com.davidfores.mficontrollerlab_1.0.97-205_iphoneos-arm.deb
```

desde la sección **Releases** de este repositorio.

El paquete puede instalarse mediante herramientas compatibles con paquetes Debian en dispositivos con jailbreak, por ejemplo:

- Filza.
- iFile.
- `dpkg`.
- Otros gestores de paquetes compatibles.

### Instalación mediante terminal

```sh
dpkg -i com.davidfores.mficontrollerlab_1.0.97-205_iphoneos-arm.deb
```

Dependiendo de la configuración del dispositivo, puede ser necesario realizar un respring o reiniciar determinados servicios después de la instalación.

### Instalación desde Cydia

Añade la siguiente fuente en Cydia:

`https://davidfores-dev.github.io/MFi-Controller-Lab-App/`

Después busca **MFi Controller Lab** e instala el paquete.

---

## Antes de instalar

Se recomienda realizar una copia de seguridad del dispositivo y de cualquier configuración importante antes de instalar MFi Controller Lab.

Esta es la **primera distribución pública binaria** del proyecto.

El paquete publicado ha pasado comprobaciones de:

- Estructura del paquete Debian.
- Integridad del contenido.
- Generación del repositorio de distribución.
- Exclusión del código fuente del proyecto.
- Exclusión de identidades físicas privadas de los mandos utilizados durante el desarrollo.
- Exclusión de datos temporales y estados privados del dispositivo de desarrollo.

La instalación en otros dispositivos y configuraciones de jailbreak debe considerarse actualmente experimental.

Si encuentras algún problema, puedes comunicarlo mediante la sección **Issues** de este repositorio.

---

## Uso básico

1. Instala MFi Controller Lab.
2. Empareja tu mando mediante Ajustes>Bluetooth. Si ya esta en la lista de mandos compatibles simplemente usalo.
3. Si no aparece entra en la app>añadir un nuevo mando>emparejar/preparar mando
4. Abre MFi Controller Lab.
5. Comprueba que el mando aparece correctamente.
6. Utiliza el TEST para comprobar sus controles.
7. Configura el perfil o remapeo si fuera necesario.
8. Utiliza el mando en una aplicación compatible.
9. Tambien puedes probar a importar un mando nuevo.
    
Los mandos genéricos pueden requerir un proceso inicial de identificación y configuración dentro de MFi Controller Lab.

---

## RetroArch

MFi Controller Lab incluye componentes destinados a facilitar su integración con RetroArch.

**RetroArch no se distribuye dentro de este paquete.**

Tampoco se incluyen:

- ROMs.
- Juegos.
- BIOS.
- Partidas guardadas.
- Otros contenidos protegidos pertenecientes a terceros.

---

## Código fuente

El código fuente de MFi Controller Lab **no se publica actualmente**.

Este repositorio público está destinado principalmente a:

- Distribución de versiones binarias.
- Documentación.
- Descargas.
- Publicación de nuevas versiones.
- Reporte de problemas mediante Issues.

El repositorio de desarrollo del proyecto permanece privado.

---

## Licencia y condiciones de uso

MFi Controller Lab es software propietario distribuido en formato binario.

Se permite descargar, instalar y utilizar las versiones binarias oficiales para uso personal y no comercial, de acuerdo con las condiciones indicadas en:

[`LICENSE-NOTICE.txt`](LICENSE-NOTICE.txt)

Los componentes, bibliotecas, marcas y programas de terceros continúan sujetos a las licencias y derechos de sus respectivos propietarios.

---

## Integridad de la versión 1.0.97 Build 205

### Paquete DEB

```text
com.davidfores.mficontrollerlab_1.0.97-205_iphoneos-arm.deb

SHA-256:
2662c8d33ad6fb3cd95a064e71716d2fbb0f4c46b99f58b875b71761b62d7513
```

---

## Reportar problemas

Si encuentras un error, puedes abrir un **Issue** en este repositorio.

Es recomendable indicar:

- Modelo de dispositivo.
- Versión de iOS.
- Jailbreak utilizado.
- Modelo del mando.
- Descripción del problema.
- Pasos necesarios para reproducirlo.

Por favor, no publiques:

- Direcciones Bluetooth.
- Identificadores privados.
- Datos personales.
- Archivos que puedan contener información sensible.

---

# 🇬🇧 🇺🇸 English

**MFi Controller Lab** is an application for jailbroken iOS devices designed to expand, manage, and test game controller support.

This distribution contains the compiled application and the components required for the app and the controller-support driver to function, without releasing the project's source code.

> **Current version:** 1.0.97 Build 205  
> **Target platform:** jailbroken iOS 9.3.5 · armv7  
> **Distribution:** binary (`.deb`)

---

## Disclaimer and liability

MFi Controller Lab is provided without any express or implied warranties regarding its operation, compatibility, or suitability for a specific device.

Installation and use of this software are entirely at the user's own risk.

To the extent permitted by applicable law, the author is not liable for damages, data loss, system failures, incompatibilities, jailbreak-related problems, damage to the device or hardware, loss of settings, or any other consequences arising directly or indirectly from the installation, modification, or use of MFi Controller Lab.

Each user is free to decide whether to install, test, or use the software and should create any necessary backups beforehand.

It is recommended not to install MFi Controller Lab on devices containing important information without first having a backup and a recovery method available.

---

## What is MFi Controller Lab?

MFi Controller Lab enables the use of different types of game controllers on older jailbroken iOS devices by providing an additional compatibility layer between physical controllers, MFi-compatible applications, and other applications such as RetroArch.
It also allows for the connection of two different controllers simultaneously.

The project includes, among other components:

-A driver that allows imported controllers to be recognized as MFi devices. Controllers that have already been imported can be paired either via Settings > Bluetooth or within the app under "Pair / Prepare Controller" if they do not appear initially.

-An app that allows you to import controllers, remap buttons, create shortcuts for RetroArch, and test controller buttons.
The public release includes **precompiled binaries**.

The public distribution contains **precompiled binaries**.

The project's source code is not currently distributed.

---

## Compatibility

This version was developed for:

**iOS 9.3.5 · jailbreak · armv7**

Original development and testing were performed primarily on an **iPad 3 running iOS 9.3.5**.

Compatibility with other iOS versions, architectures, devices, or jailbreak configurations is not currently guaranteed.

---

## Installation

Download:

```text
com.davidfores.mficontrollerlab_1.0.97-205_iphoneos-arm.deb
```

from the **Releases** section of this repository.

The package can be installed using Debian-package-compatible tools on a jailbroken device, for example:

- Filza.
- iFile.
- `dpkg`.
- Other compatible package managers.

### Terminal installation

```sh
dpkg -i com.davidfores.mficontrollerlab_1.0.97-205_iphoneos-arm.deb
```

Depending on the device configuration, a respring or restart of certain services may be required after installation.

### Installation via Cydia

Add the following source to Cydia:

`https://davidfores-dev.github.io/MFi-Controller-Lab-App/`

Then search for **MFi Controller Lab** and install the package.

---

## Before installing

It is recommended to create a backup of the device and any important configuration before installing MFi Controller Lab.

This is the **first public binary distribution** of the project.

The published package has passed checks covering:

- Debian package structure.
- Package integrity.
- Distribution repository generation.
- Exclusion of project source code.
- Exclusion of private physical controller identities used during development.
- Exclusion of temporary data and private development-device state.

Installation on other devices and jailbreak configurations should currently be considered experimental.

If you encounter a problem, please report it through the **Issues** section of this repository.

---

## Basic usage

1. Install the MFi Controller Lab app.
2. Pair your controller via Settings > Bluetooth. If it is already in the list of compatible controllers, simply use it.
3. If it does not appear, open the app > Add new controller > Pair/Prepare controller.
4. Open MFi Controller Lab.
5. Verify that the controller appears correctly.
6. Use the TEST function to check your controls.
7. Configure the profile or remap controls if necessary.
8. Use the controller in a compatible application.
9. You can also try importing a new controller.

Generic controllers may require an initial identification and configuration process inside MFi Controller Lab.

---

## RetroArch

MFi Controller Lab includes components intended to facilitate integration with RetroArch.

**RetroArch itself is not distributed as part of this package.**

The package also does not include:

- ROMs.
- Games.
- BIOS files.
- Save files.
- Other protected third-party content.

---

## Source code

The MFi Controller Lab source code is **not currently publicly distributed**.

This public repository is intended mainly for:

- Binary releases.
- Documentation.
- Downloads.
- New version announcements.
- Issue reporting.

The project's development repository remains private.

---

## License and terms of use

MFi Controller Lab is proprietary software distributed in binary form.

Official binary releases may be downloaded, installed, and used for personal, non-commercial use according to the terms described in:

[`LICENSE-NOTICE.txt`](LICENSE-NOTICE.txt)

Third-party components, libraries, trademarks, and software remain subject to the licenses and rights of their respective owners.

---

## Version 1.0.97 Build 205 integrity

### DEB package

```text
com.davidfores.mficontrollerlab_1.0.97-205_iphoneos-arm.deb

SHA-256:
2662c8d33ad6fb3cd95a064e71716d2fbb0f4c46b99f58b875b71761b62d7513
```

---

## Reporting problems

If you encounter an error, you can open an **Issue** in this repository.

When possible, please include:

- Device model.
- iOS version.
- Jailbreak used.
- Controller model.
- Description of the problem.
- Steps required to reproduce it.

Please do not publish:

- Bluetooth addresses.
- Private identifiers.
- Personal information.
- Files containing sensitive information.

---

Copyright © 2026 David Forés. All rights reserved.
