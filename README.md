# FitOS Desktop UI 🚀

**FitOS** es un proyecto divertido que crea un falso escritorio fitness en HTML, diseñado para motivarte a mantener hábitos saludables. ¡Y lo mejor! Puede ser lanzado directamente desde una **shell interactiva** personalizada en Bash.

## 📁 Contenido del Proyecto

- `fitos_desktop_ui.html`: Una interfaz de escritorio simulada, con accesos a:
  - Planes de entrenamiento
  - Meditación
  - Hidratación diaria
  - Nutrición
  - Modo avanzado (contabilidad de macros)
  - Retos diarios
- `shell_interactiva.sh`: Un script Bash que permite:
  - Lanzar la interfaz FitOS en el navegador (`launch`)
  - Instalar páginas auxiliares (`install`)
  - Desinstalar recursos (`uninstall`)
  - Ver fecha y hora actual (`time`)
  - Mostrar arte ASCII fitness (`fitness`)
  - Ver páginas de bienestar en modo texto (`salud`)
  - Ejecutar comandos en modo interactivo

## 🚀 Instalación y uso

1. **Clona este repositorio**:

```bash
git clone https://github.com/tu_usuario/fitos_desktop.git
cd fitos_desktop
```

2. **Dale permisos de ejecución al script**:

```bash
chmod +x shell_interactiva.sh
```

3. **Ejecuta la shell interactiva**:

```bash
./shell_interactiva.sh
```

4. **Comandos disponibles dentro de la shell**:

- `install` → Crea archivos HTML de prueba.
- `uninstall` → Borra archivos instalados.
- `launch` → Abre el escritorio FitOS en tu navegador (por defecto Firefox).
- `fitness` → Muestra arte ASCII motivacional.
- `salud` → Abre una guía de bienestar en modo texto (usa `lynx`).
- `time` → Muestra fecha y hora actual.
- `exit` → Salir de la shell.

---

## ⚡ Requisitos

- Linux o MacOS (puede adaptarse fácilmente a Windows WSL)
- Navegador Firefox (o adaptar el script para otro)
- `lynx` instalado para navegación en texto:

```bash
sudo apt install lynx  # En Debian/Ubuntu
```

---

## 🎯 Objetivo del proyecto

Este proyecto es principalmente educativo y recreativo:
- Practicar scripting en Bash.
- Simular entornos de escritorio ligeros.
- Divertirse creando pequeñas apps motivacionales.

---

## 📜 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

