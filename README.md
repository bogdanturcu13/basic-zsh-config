<div align="center">

# Automatización de ZSH para Parrot OS

<p>
  Un script Bash para configurar automáticamente un entorno de terminal ZSH moderno y potente en Parrot OS.
</p>

<p>
  <img src="https://img.shields.io/badge/OS-Parrot%20OS-blue.svg" alt="OS">
  <img src="https://img.shields.io/badge/Shell-ZSH-lightgreen.svg" alt="Shell">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="Licencia MIT">
  <img src="https://img.shields.io/badge/Status-Estable-success.svg" alt="Estado">
</p>

</div>

---

## 📝 Explicación

Este script está pensado para aquellas personas que quieren tener una terminal útil, personalizada y productiva sin sobrecargar el sistema operativo con aplicaciones y plugins, aunque permite integrar todos los plugins que desees directamente en el archivo `~/.zshrc` (más información sobre cómo hacerlo en https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)

**Instrucciones importantes:**
- Al finalizar la instalación, reinicia el sistema y vuelve a abrir la consola.
- Elige las opciones de personalización que más te gusten.
- Para cambiar el color de la letra: clic derecho → Profiles → Preferences → selecciona tu color favorito.

---

## 📸 Vista Previa del Resultado

Aquí puedes ver cómo queda la terminal después de ejecutar el script:

![Zsh Function](https://raw.githubusercontent.com/bogdanturcu13/basic-zsh-config/main/assets/zsh-function.png)

---

## Características Principales

* **Shell Moderna:** Instala y configura ZSH como shell predeterminada.
* **Productividad:** Incluye plugins esenciales:
    * `zsh-autosuggestions` (sugerencias basadas en el historial).
    * `zsh-syntax-highlighting` (resaltado de sintaxis en tiempo real).
* **Configuración de teclado:** Cambia automáticamente el idioma del teclado al español.

---

## Requisitos

* Un sistema **Parrot OS** (o una distribución basada en Debian 12+).
* Acceso a **Internet** (para descargar paquetes y repositorios).
* Privilegios de **Superusuario** (`sudo`).

---

## Instalación y Uso

Simplemente clona este repositorio y ejecuta el script como `root` o con `sudo`.

```bash
# 1. Clona el repositorio
git clone https://github.com/bogdanturcu13/basic-zsh-config.git

# 2. Entra en el directorio
cd basic-zsh-config

# 3. Da permisos de ejecución al script
chmod +x zsh-config-debian   Ó   chmod +x zsh-config-macOS

# 4. Ejecuta el script con sudo
sudo ./zsh-config-debian   Ó   sudo ./zsh-config-macOS
