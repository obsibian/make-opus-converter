# Make Opus Converter

**Make Opus Converter** es una aplicación moderna con interfaz gráfica para convertir archivos de video al formato MKV con audio Opus a 96 kbps.

<img width="582" height="509" alt="makeOp" src="https://github.com/user-attachments/assets/aacb0dc9-6008-4927-86b4-b9aefe7ba4c9" />

---

## ✨ Características

- **Soporte de Arrastrar y Soltar** - Manejo intuitivo de archivos con retroalimentación visual
- **Entrada de Múltiples Formatos** - Soporta MP4, AVI, MOV, MKV, WMV, FLV, WEBM
- **Codificación de Audio Opus** - Convierte al eficiente audio Opus de 96 kbps
- **Preservación del Video** - La pista de video original se copia sin pérdida de calidad
- **Optimizado para MKV** - Contenedor MKV con audio Opus para la mejor compatibilidad
- **Persistencia de Configuración** - Recuerda tus preferencias

## 🎯 ¿Por qué Opus a 96 kbps?

Opus es un códec de audio moderno y muy eficiente que ofrece:
- **Excelente calidad** con bajas tasas de bits (96 kbps es transparente para la mayoría del contenido)
- **Baja latencia**, perfecto para edición de video
- **Archivos pequeños** en comparación con audio PCM
- **Estándar abierto**, libre de regalías y ampliamente soportado

### Comparación:
- **Audio PCM**: ~1.5 Mbps, archivos grandes, calidad sin pérdidas
- **Opus 96 kbps**: ~0.1 Mbps, archivos pequeños, calidad casi transparente
- **Ahorro de espacio**: flujos de audio ~90% más pequeños

## 🖥️ Uso

### Conversión Simple
1. **Inicia** la aplicación
2. **Selecciona el video** mediante:
   - Hacer clic en el botón "Examinar"
   - Arrastrar y soltar en la zona púrpura
3. **Elige la carpeta de salida** (predeterminada: `~/Videos`)
4. **Haz clic en "Crear MKV con Opus"**
5. Espera a que finalice la conversión

### Formatos Soportados
**Formatos de Entrada:**
- 📹 MP4 (.mp4)
- 📹 AVI (.avi)
- 📹 MOV (.mov)
- 📹 MKV (.mkv)
- 📹 WMV (.wmv)
- 📹 FLV (.flv)
- 📹 WEBM (.webm)

**Formato de Salida:**
- 🎬 Contenedor MKV
- 🎵 Audio Opus (96 kbps, 48 kHz, estéreo)
- 🎥 Códec de video original (sin recodificar)

---

## 📦 Instalación

Instala el paquete `.deb` en Debian 13 con:

```bash
sudo dpkg -i ./*.deb
sudo apt install -f
```
---

## 🧰 Requisitos

* Sistema operativo: **Debian 13**.
* Dependencias estándar incluidas en el paquete `.deb`.

---

## 📜 Licencia

Este proyecto está bajo la **Licencia Pública General de GNU v3.0**.
---

## 📧 Contacto

Opcional: telegram @geinux
