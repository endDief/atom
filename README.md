# Atom

[![Build status](https://dev.azure.com/github/Atom/_apis/build/status/Atom%20Production%20Branches?branchName=master)](https://dev.azure.com/github/Atom/_build/latest?definitionId=32&branchName=master)

> Atom y todos los repositorios de Atom se archivarán en diciembre 15, 2022. Learn more in our [official announcement](https://github.blog/2022-06-08-sunsetting-atom/)

Atom es un editor de texto de código abierto para el siglo XXI, construido sobre [Electron](https://github.com/electron/electron), and based on everything we love about our favorite editors. We designed it to be deeply customizable, but still approachable using the default configuration.

![Atom](https://user-images.githubusercontent.com/378023/49132477-f4b77680-f31f-11e8-8357-ac6491761c6c.png)

![Atom Screenshot](https://user-images.githubusercontent.com/378023/49132478-f4b77680-f31f-11e8-9e10-e8454d8d9b7e.png)

Visita [atom.io](https://atom.io) para obtener más información o visita el [Atom forum](https://github.com/atom/atom/discussions).

Sigue [@AtomEditor](https://twitter.com/atomeditor) en Twitter para importantes
anuncios.

Este proyecto se adhiere al Pacto del Colaborador. [codigo de conducta](CODE_OF_CONDUCT.md).
Al participar, se espera que respete este código. Por favor reporte cualquier comportamiento inaceptable a atom@github.com.

## Documentation

Si desea leer sobre el uso de Atom o el desarrollo de paquetes en Atom, el [Manual de vuelo de Atom](https://flight-manual.atom.io) is free and available online. You can find the source to the manual in [atom/flight-manual.atom.io](https://github.com/atom/flight-manual.atom.io).

La [API reference](https://atom.io/docs/api) para desarrollar paquetes también está documentado en Atom.io.

## Instalacion

### Requisitos previos
- [Git](https://git-scm.com)

### macOS

~~Download the latest~~ ~~[Atom release](https://github.com/atom/atom/releases/latest).~~

~~Atom will automatically update when a new release is available.~~

### Windows

Descargar el último [Instalador de Atom](https://github.com/atom/atom/releases/latest). `AtomSetup.exe` es 32-bit. para sistemas de 64-bit, descarga `AtomSetup-x64.exe`.

Atom se actualizará automáticamente cuando haya una nueva versión disponible.

También puedes descargar `atom-windows.zip` (32-bit) o `atom-x64-windows.zip` (64-bit) desde la [releases page](https://github.com/atom/atom/releases/latest).
The `.zip` version will not automatically update.

Using [Chocolatey](https://chocolatey.org)? Run `cinst Atom` to install the latest version of Atom.

### Linux

Atom sólo está disponible para sistemas Linux de 64 bits.*

Configure el administrador de paquetes de su distribución para instalar y actualizar Atom siguiendo las instrucciones [Linux installation instructions](https://flight-manual.atom.io/getting-started/sections/installing-atom/#platform-linux) in the Flight Manual.  También encontrará instrucciones sobre cómo instalar los paquetes oficiales de Linux de Atom sin utilizar un repositorio de paquetes, aunque no obtendrá actualizaciones automáticas después de instalar Atom de esta manera.

#### Archive extraction

Hay un archivo disponible para las personas que no quieren instalar `atom` como root.

Esta versión le permite instalar varias versiones de Atom en paralelo. Ha sido construido en Ubuntu de 64 bits,
pero debería ser compatible con otras distribuciones de Linux.
1. Install dependencies (on Ubuntu):
```sh
sudo apt install git libasound2 libcurl4 libgbm1 libgcrypt20 libgtk-3-0 libnotify4 libnss3 libglib2.0-bin xdg-utils libx11-xcb1 libxcb-dri3-0 libxss1 libxtst6 libxkbfile1
```
2. Download `atom-amd64.tar.gz` from the [Atom releases page](https://github.com/atom/atom/releases/latest).
3. Run `tar xf atom-amd64.tar.gz` in the directory where you want to extract the Atom folder.
4. Inicie Atom usando el comando `atom` instalado desde el directorio recién extraído.

Actualmente, la versión de Linux no se actualiza automáticamente, por lo que deberá
repita estos pasos para actualizar a versiones futuras.

## Building

* [Linux](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-linux)
* [macOS](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-mac)
* [Windows](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-windows)

## Discussion

* Discuss Atom on [GitHub Discussions](https://github.com/atom/atom/discussions)

## License

[MIT](https://github.com/atom/atom/blob/master/LICENSE.md)

When using the Atom or other GitHub logos, be sure to follow the [GitHub logo guidelines](https://github.com/logos).
