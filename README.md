# OpenMic

**Karaoke online multijugador inspirado en los open mics de bar.** Crea una sala, comparte el código con tus amigos, elijan canciones y ¡a cantar! Sin registro, sin complicaciones, solo tú y el micrófono.

> ⚠️ Este proyecto está en desarrollo activo. ¡Contribuye!

## Características

- **Multiplayer en tiempo real**: Canta con amigos desde cualquier lugar
- **Letras sincronizadas**: Las letras se resaltan conforme avanza la canción
- **Sistema de puntuación**: Evalúa tu actuación como en los concursos de karaoke
- **4 modos de juego**: Solo, Parejas, Grupos y Versus 1v1
- **Sin registro**: Crea sala, comparte código y listo
- **Responsive**: Funciona en PC, tablet y móvil

## Modos de Juego

| Modo | Descripción |
|------|-------------|
| **Open Mic** | Cada quien canta solo. Gana el que más puntos saque. |
| **Parejas** | Equipos de 2. Cantan juntos, puntaje combinado. |
| **Grupos** | Equipos de 3+. Modo colaborativo. |
| **Versus 1v1** | Dos cantantes, misma canción. |

## Stack de Desarrollo

| Capa | Tecnología |
|------|------------|
| Frontend | React + Vite + Tailwind CSS |
| Backend | Node.js + Express |
| Tiempo real | Socket.io |
| Letras | [lrclib.net](https://lrclib.net) API |

## Instalación

### Prerrequisitos

- Node.js 18+
- npm o yarn

### Clonar e instalar

```bash
# Clonar
git clone https://github.com/TU_USUARIO/open-mic.git
cd open-mic

# Instalar dependencias del servidor
cd server
npm install

# Instalar dependencias del cliente
cd ../client
npm install****
