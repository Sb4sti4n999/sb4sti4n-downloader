# sb4sti4n Download Manager 🚀

![GitHub Release](https://img.shields.io/badge/Version-8.0-blue)
![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Android-green)
![License](https://img.shields.io/badge/License-MIT-red)

Gestor de descargas universal desde terminal con soporte para **YouTube, Google Drive, SourceForge y más**. Descarga cualquier archivo o video con un solo comando.

![Demo](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdWtwY2Z5bHl6Y2FmM2RjY3Z5Z3J6d2h6eGx4N2VzZ2RmbjBqbmN6dyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3ohzdIuqJv6W9l8NtC/giphy.gif)

## 🌟 Características Principales
- ⚡ **Descarga ultra-rápida** en SourceForge (16 conexiones paralelas)
- ☁️ Soporte para **Google Drive/YouTube** con detección automática
- 📊 Sistema de **logging integrado** para diagnóstico de errores
- 🔄 **Auto-instalación** de dependencias (aria2c, yt-dlp, ffmpeg)
- 📱 Compatibilidad con **Android (Termux)**
- 🎨 Interfaz **colorida con animaciones**
- 🔍 **Detección de origen** (plataforma y URL original)
- 📈 Multi-plataforma y **multi-conexiones**

## 🚀 Instalación
```bash
# Método directo (sin instalación):
curl -sL https://raw.githubusercontent.com/sb4sti4n999/sb4sti4n/main/sb4sti4n | bash -s -- [https://github.com/sb4sti4n999/sb4sti4n]

# Instalación permanente:
sudo curl -L https://raw.githubusercontent.com/sb4sti4n999/sb4sti4n/main/sb4sti4n -o /usr/local/bin/sb4sti4n
sudo chmod +x /usr/local/bin/sb4sti4n
```

## 🛠️ Uso
```bash
# Descargar video de YouTube
sb4sti4n https://youtu.be/ID_DEL_VIDEO

# Descargar de Google Drive
sb4sti4n https://drive.google.com/file/d/ID_DRIVE/view

# Descarga turbo de SourceForge
sb4sti4n https://sourceforge.net/projects/nombre-proyecto/files/ruta/archivo/download

# Descarga genérica
sb4sti4n https://ejemplo.com/archivo.zip
```

## 🔍 Detección de Origen
El script identifica automáticamente la procedencia:
```bash
🔍 Detalles del origen:
 Plataforma: ☁️ Google Drive
 URL Original: https://drive.google.com/file/d/ID_DRIVE/view
```

## 📦 Dependencias Auto-instaladas
| Herramienta    | Función                          |
|----------------|----------------------------------|
| `aria2c`       | Descargas aceleradas             |
| `yt-dlp`       | Videos de YouTube                |
| `ffmpeg`       | Conversión de formatos           |
| `wget/curl`    | Descargas básicas                |

## 📱 Soporte Android (Termux)
```bash
pkg install git aria2 -y
termux-setup-storage
sb4sti4n [URL]
```

## 🐛 Solución de Problemas
Ver logs en:
```bash
~/sb4sti4n√Downloads/Logs/sb4sti4n.log
```

## 🤝 Contribuir
1. Haz fork del repositorio
2. Crea una rama: `git checkout -b nueva-funcionalidad`
3. Commit: `git commit -m 'Agrega funcionalidad'`
4. Push: `git push origin nueva-funcionalidad`
5. Abre un **Pull Request**

## 📜 Licencia
[MIT License](LICENSE) © 2023 [sb4sti4n999](https://github.com/sb4sti4n999)

---

**¡Descarga el mundo con un comando!** 🎉  