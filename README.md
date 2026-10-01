# Finakids

**Simulación de vida en 3D para aprender a manejar el dinero tomando decisiones.**
Vive ocho semanas en la vida de Sofía: recibe dinero, ahorra, compra, usa crédito, trabaja, emprende e invierte... y vive las consecuencias.

## ▶ Jugar ahora en el navegador

**https://lelelilo-studios.github.io/Finakids/**

Funciona en Chrome, Edge, Safari y Firefox recientes (WebGPU, con respaldo WebGL2), también en celulares y tablets: gira el teléfono en horizontal. Con sonido (música y efectos; se ajustan en el menú de pausa).

## Descargas (versión 0.1.0)

| Plataforma | Descarga | Notas |
|---|---|---|
| Windows 10/11 (64 bits) | [Finakids-windows-x64.zip](https://lelelilo-studios.github.io/Finakids/downloads/Finakids-windows-x64.zip) | Descomprime y abre `finakids.exe`. Si SmartScreen avisa: *Más información → Ejecutar de todas formas*. |
| macOS 11+ (Apple Silicon e Intel) | [Finakids-macos-universal.zip](https://lelelilo-studios.github.io/Finakids/downloads/Finakids-macos-universal.zip) _(versión anterior)_ | App sin firma de Apple: clic derecho → *Abrir*, o `xattr -dr com.apple.quarantine Finakids.app`. |
| Linux x86_64 | [Finakids-linux-x64.tar.gz](https://lelelilo-studios.github.io/Finakids/downloads/Finakids-linux-x64.tar.gz) | Requiere drivers Vulkan u OpenGL. `./finakids` |
| Android 8+ (arm64) | [Finakids-android-arm64.apk](https://lelelilo-studios.github.io/Finakids/downloads/Finakids-android-arm64.apk) _(versión anterior)_ | Permite *instalar apps desconocidas* para tu navegador y abre el APK. |
| iOS / iPadOS 15+ | [Finakids-ios-unsigned.ipa](https://lelelilo-studios.github.io/Finakids/downloads/Finakids-ios-unsigned.ipa) _(versión anterior)_ | IPA sin firmar: instálala firmándola con tu Apple ID (AltStore / Sideloadly). También: [build para Simulador](https://lelelilo-studios.github.io/Finakids/downloads/Finakids-ios-simulator.zip) _(versión anterior)_. |

## Controles

| | Teclado y ratón | Pantalla táctil |
|---|---|---|
| **Mover** | WASD / flechas, o clic en el suelo | Toca el suelo |
| **Interactuar / hablar** | E, o clic en el objeto o personaje | Toca el objeto o personaje |
| **Teléfono** (banco, metas, crédito, inversiones...) | TAB o el botón inferior derecho | Botón inferior derecho |
| **Cámara** | Arrastrar, Q / R, rueda | Arrastra; pellizca para acercar |
| **Pausa** (volumen, calidad gráfica) | Esc o el botón ⏸ | Botón ⏸ |
| **Pantalla completa** | F | Automática al primer toque (Android) |

---
Hecho con Rust + wgpu. Todo el mundo 3D, los personajes y sus animaciones se generan proceduralmente en tiempo real.
