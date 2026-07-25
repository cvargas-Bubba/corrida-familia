# Corrida Familia · Aventura en Río 🏃🇧🇷

Juego de plataformas estilo Mario protagonizado por la familia — **Cristóbal**,
**Fernanda** y **Javiera** (cabezones con sus caricaturas). Corre y salta por Río,
junta 🪙 y ⭐, vence cangrejos saltándoles encima, derrota al jefe 👑 y llega a la 🏁.

Construido con **[Phaser 3](https://phaser.io)** (motor de juegos). La librería va
incluida localmente (`phaser.min.js`), así que **funciona offline y sin CDN**.

## Jugar
Serví la carpeta (GitHub Pages) o abrí `index.html` en un navegador.
Necesita `phaser.min.js` al lado del `index.html`.

### Controles
- **← →** (o **A / D**): mover
- **Espacio / ↑ / W**: saltar (mantén = salto más alto)
- **M** no aplica aquí; usá el botón **🔊 Sonido**
- Móvil: botones táctiles ◀ ▶ y saltar

## Modos y detalles
- **Modo familia** 👨‍👧‍👧: los 3 corren juntos (elegís el líder; los otros lo siguen).
- **Mueca de festejo** 🎉: al superar el nivel o vencer al jefe, el héroe rebota,
  gira y suelta confeti con un "¡BIEEN!".
- **Caricaturas integradas**: las 3 caras van embebidas en `index.html` (data URI),
  iguales en todos los dispositivos. Las fotos/caras no dependen del navegador.

## Estructura
- `index.html` — juego completo (Phaser + escenas + niveles + caricaturas embebidas)
- `phaser.min.js` — motor Phaser 3 (local, ~1.2 MB)

## Roadmap
- [ ] Más niveles y mundos
- [ ] Power-ups (escudo, imán de estrellas, salto doble)
- [ ] Spritesheets animados de correr/saltar
- [ ] Ranking online entre la familia (Supabase)
- [ ] PWA instalable

---
Hecho en familia. ⚽
