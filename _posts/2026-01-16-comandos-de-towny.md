---
layout: post
title: Comandos de Towny
date: 2026-01-16 13:48 -0600
description: Comandos esenciales (y más que esenciales) para tu experiencia como ciudadano o líder en BUAP.pro
author: galleta
categories:
- Tutorial
- Towny
tags:
- tutorial
- towny
- comandos
---

Los comandos son la base fundamental de la experiencia en Towny, esta guía está pensada para ayudarte a **vivir, proteger y mejorar tu experiencia dentro de una ciudad Towny**, ya seas un ciudadano o el líder de una gran ciudad o nación.

---

## 📌 Conceptos básicos (antes de usar comandos)

Antes de entrar en comandos, es importante entender algunos conceptos clave:

* **Ciudadano (Resident)**: jugador que pertenece a una ciudad.
* **Ciudad (Town)**: grupo de ciudadanos que reclaman terreno.
* **Residencia (Plot)**: terreno dentro de una ciudad.
* **Alcalde/Rey (Mayor)**: líder de una ciudad.
* **Nación (Nation)**: conjunto de ciudades.
* **Terreno salvaje (Wilderness)**: zonas sin reclamar (más peligrosas).

> Si todavía no lo has leído, te recomiendo que empieces leyendo el post *[Introducción a Towny](/posts/introducción-a-towny)*
{: .prompt-tip}

---

## 🧭 Comandos esenciales

### Para todos

Los jugadores que no pertenecen a ninguna ciudad igualmente pueden usar algunos comandos relacionados a su "perfil" de residente:

`/res` - Muestra información sobre tu residencia actual (incluso si no tienes una).

`/res friend add <jugador>` - Permite que un jugador tenga acceso a tu residencia.

### 👤 Para ciudadanos

Estos comandos son los que usarás **todos los días** como jugador perteneciente a una ciudad.

`/town` - Muestra información básica de tu ciudad: alcalde, impuestos, bancos y residentes.


`/town here` - Te dice **en qué ciudad o terreno estás parado**.

`/res set home` - Establece tu residencia como punto de aparición.

#### Quitar PVP, Fuego y Explosiones

`/res toggle pvp` - Activa o desactiva **PvP** dentro de tu residencia (si tienes permisos).

`/res toggle fire` - Activa o desactiva **fuego** dentro de tu residencia (si tienes permisos).

`/res toggle explosion` - Activa o desactiva **explosiones** dentro de tu residencia (si tienes permisos).

#### Permisos de residencia

Para configurar quién puede **construir, abrir cofres o usar puertas** en tu terreno, usa `/res set perm`

Ejemplo común:

- `/res set perm friend build on`


`/town deposit <cantidad>` - Deposita dinero en el banco de la ciudad (ayuda a pagar mantenimiento de tu ciudad, para que no quede en ruinas... literalmente).

---

### 🏛️ Para líderes (alcaldes)

Si eres alcalde, estos comandos son 100% necesarios:

`/town new <nombre>` - Crea una nueva ciudad.

`/town claim` - Reclama el chunk donde estás parado.

`/town unclaim` - Libera un terreno reclamado.

`/town invite <jugador>` - Invita jugadores a tu ciudad.

`/town kick <jugador>` - Expulsa a un ciudadano.

`/town set taxes <cantidad>` - Define el impuesto diario para los ciudadanos.

`/town set spawn` - Define el punto de spawn de la ciudad.

`/town set board <mensaje>` - Mensaje que verán todos los ciudadanos al entrar.

---

## 🚀 Comandos avanzados

### 👤 Para ciudadanos avanzados

Estos comandos mejoran **tu seguridad y calidad de vida** dentro de la ciudad.


`/res set perm outsider off` - Evita que jugadores externos interactúen con tu terreno.

`/res toggle explosion off` - Clave para protegerte contra **creepers y TNT**.

`/towny map` - Muestra el mapa de terrenos reclamados alrededor tuyo.

`/plot forsale <precio>` - Pone tu residencia a la venta.

`/plot notforsale` - Quita tu residencia del mercado.

---

### 🏛️ Para líderes avanzados

Aquí empieza la **gestión real de una ciudad**.

`/town set plottax <cantidad>` - Impuesto por residencia (muy útil para grandes ciudades).

`/town set perm` - Define permisos por defecto para toda la ciudad.

- Ejemplo recomendado:
  - `/town set perm outsider build off`

`/town claim outpost` - Crea un **outpost** (zona lejana útil para granjas o minas).

`/town set outpost` - Define el spawn del outpost.

`/town toggle pvp` - Activa o desactiva PvP en toda la ciudad.

`/town withdraw <cantidad>` - Retira dinero del banco de la ciudad.

---

> ## 🛡️ Cómo cuidar tu residencia
> 
> * 🔒 **Desactiva explosiones** siempre.
> * 🚪 Usa puertas y cofres con permisos bien configurados.
> * 🤝 Solo agrega como amigos a jugadores de confianza.
> * 🧭 Usa `/towny map` antes de construir para evitar errores.
> * 💰 Asegúrate de poder pagar impuestos diarios.
{: .prompt-info}

---

> ## 🌆 Cómo mejorar la experiencia de los ciudadanos (tips para líderes)
> 
> * Crea **barrios temáticos** (comercial, residencial, industrial).
> * Usa **impuestos bajos al inicio** para atraer jugadores.
> * Define normas claras en `/town set board`.
> * Mantén terrenos abandonados limpios (unclaim).
{: .prompt-tip}
