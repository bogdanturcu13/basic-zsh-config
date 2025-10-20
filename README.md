# basic-zsh-config
<div align="center">

# 🚀 Automatización de ZSH para Parrot OS

<p>
  Un script Bash para configurar automáticamente un entorno de terminal ZSH moderno y potente en Parrot OS, incluyendo Oh My Zsh, Powerlevel10k y plugins esenciales de productividad.
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

## ✨ Características Principales

* **Instalación desatendida:** Ejecuta un solo comando y deja que el script haga todo.
* **Shell Moderna:** Instala y configura ZSH como shell predeterminada.
* **Gestión de Plugins:** Integra [Oh My Zsh](https://ohmyz.sh/) para facilitar la gestión.
* **Tema Visual Impactante:** Instala y activa [Powerlevel10k](https://github.com/romkatv/powerlevel10k), uno de los temas más potentes y visuales.
* **Productividad:** Incluye plugins esenciales:
    * `zsh-autosuggestions` (sugerencias basadas en el historial).
    * `zsh-syntax-highlighting` (resaltado de sintaxis en tiempo real).

---

## 📋 Requisitos Previos

* Un sistema **Parrot OS** (o una distribución basada en Debian 12+).
* Acceso a **Internet** (para descargar paquetes y repositorios).
* Privilegios de **Superusuario** (`sudo`).

---

## ⚙️ Instalación y Uso

Simplemente clona este repositorio y ejecuta el script como `root` o con `sudo`.

```bash
# 1. Clona el repositorio
git clone https://github.com/bogdanturcu13/basic-zsh-config.git

# 2. Entra en el directorio
cd basic-zsh-config

# 3. Da permisos de ejecución al script
chmod +x personalizar_zsh.sh

# 4. Ejecuta el script con sudo
sudo ./personalizar_zsh.sh
