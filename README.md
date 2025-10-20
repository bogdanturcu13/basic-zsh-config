# basic-zsh-config
<div align="center">

# 🚀 Automatización de ZSH para Parrot OS

<p>
  Un script Bash para configurar automáticamente un entorno de terminal ZSH moderno y potente en Parrot OS, incluyendo Oh My Zsh, Powerlevel10k y plugins esenciales de productividad. Este script está pensado para aquellas personas que quieren tener una terminal útil, personalizada y productiva pero sin sobrecargar el sistema operativo con aplicaciones y plugins. Aún así, se pueden integrar todos los plugins que se deseen en el archivo ~/.zshrc.
  
  Al finalizar la instalación, reinicia el sistema, vuelve a abrir la consola y elige las opciones de personalización que más te gusten. Con click derecho + profiles + preferences cambia el color de la letra al que más te guste.
</p>

<p>
  <img src="https://img.shields.io/badge/OS-Parrot%20OS-blue.svg" alt="OS">
  <img src="https://img.shields.io/badge/Shell-ZSH-lightgreen.svg" alt="Shell">
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="Licencia MIT">
  <img src="https://img.shields.io/badge/Status-Estable-success.svg" alt="Estado">
</p>

</div>

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
chmod +x zsh-config

# 4. Ejecuta el script con sudo
sudo ./zsh-config
