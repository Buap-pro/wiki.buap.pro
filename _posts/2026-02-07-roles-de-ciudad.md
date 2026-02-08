---
layout: post
title: Roles de Ciudad
date: 2026-02-07 18:14 -0600
description: Información sobre roles útiles en ciudades
author: galleta
categories:
- Tutorial
- Towny
tags:
- tutorial
- towny
- dudas
- roles
last_modified_at: 2026-02-07 19:42 -0600
---

## ¿Qué son los roles de ciudad?

Para permitir que ciertos ciudadanos puedan realizar acciones específicas (invitar a nuevos ciudadanos, cambiar permisos, modificar configuraciones de la ciudad, etc.) se utilizan los **roles de ciudad**.

Cada rol tiene un **conjunto fijo de permisos**. No es posible asignar permisos individuales a una persona: los permisos siempre se otorgan en grupo según el rol que tenga el ciudadano.

## Todos los permisos y sus significados

En la lista de roles aparecen los permisos incluidos en cada rol.
Puedes poner el mouse encima de cada permiso para ver qué acción permite realizar.

## ¿Qué roles hay?

---

## Roles de Ciudad

### Asistente

Rol de confianza con permisos administrativos generales dentro de la ciudad.

* <span data-bs-toggle="tooltip" title="Exime al ciudadano de pagar impuestos de la ciudad.">towny.tax_exempt</span>
* <span data-bs-toggle="tooltip" title="Permite administrar chunks de la ciudad y outposts.">towny.command.town.claim.*</span>
* <span data-bs-toggle="tooltip" title="Permite expandir la ciudad usando /town claim.">towny.command.town.claim.town</span>
* <span data-bs-toggle="tooltip" title="Permite reclamar outposts de la ciudad.">towny.command.town.claim.outpost</span>
* <span data-bs-toggle="tooltip" title="Permite reclamar parcelas en masa usando el comando /town claim fill.">towny.command.town.claim.fill</span>
* <span data-bs-toggle="tooltip" title="Permite reclamar múltiples parcelas a la vez usando /town claim auto, rect o circle.">towny.command.town.claim.town.multiple</span>
* <span data-bs-toggle="tooltip" title="Permite invitar nuevos jugadores a la ciudad.">towny.command.town.invite.add</span>
* <span data-bs-toggle="tooltip" title="Permite gestionar parcelas (vender, asignar, cambiar permisos, etc.).">towny.command.plot.*</span>
* <span data-bs-toggle="tooltip" title="Permite gestionar parcelas como alcalde dentro de la ciudad: recuperar parcelas de jugadores para la ciudad, cambiar permisos y configuraciones de cualquier parcela, y poner o quitar parcelas en venta.">towny.command.plot.asmayor</span>
* <span data-bs-toggle="tooltip" title="Permite realizar tareas similares a las del alcalde, pero solo en parcelas que pertenecen a la ciudad y no tienen residente. Incluye gestionar grupos de parcelas, poner o quitar parcelas en venta, modificar celdas de la cárcel y usar /plot perm y /plot trust para añadir o quitar permisos.">towny.command.plot.asmayorinunowned</span>
* <span data-bs-toggle="tooltip" title="Permite cambiar si la ciudad es pública o no.">towny.command.town.toggle.public</span>
* <span data-bs-toggle="tooltip" title="Permite interactuar con bloques (cofres, puertas, trampillas, etc.) en parcelas dentro de la ciudad (incluso de ciudadanos).">towny.claimed.owntown.switch.*</span>
<!-- * <span data-bs-toggle="tooltip" title="Permite asignar el rango VIP a ciudadanos.">towny.command.town.rank.vip</span> -->
* <span data-bs-toggle="tooltip" title="Permite asignar el rango Ayudante a ciudadanos.">towny.command.town.rank.ayudante</span>
* <span data-bs-toggle="tooltip" title="Permite asignar el rango Sheriff a ciudadanos.">towny.command.town.rank.sheriff</span>
* <span data-bs-toggle="tooltip" title="Permite encarcelar a jugadores marcados como forajidos.">towny.outlaw.jailer</span>

---

### Ayudante

Rol con permisos básicos de gestión territorial.

* <span data-bs-toggle="tooltip" title="Permite interactuar con bloques (cofres, puertas, trampillas, etc.) en parcelas que pertenecen a la ciudad.">towny.claimed.townowned.switch.*</span>

---

### Sheriff

El Sheriff es el encargado de hacer cumplir la ley dentro de la ciudad.
Puede encarcelar **incluso a miembros de la propia ciudad**.

* <span data-bs-toggle="tooltip" title="Permite encarcelar jugadores.">towny.command.town.jail</span>
* <span data-bs-toggle="tooltip" title="Permite liberar jugadores de la cárcel.">towny.command.town.unjail</span>
* <span data-bs-toggle="tooltip" title="Permite ver la lista de jugadores encarcelados.">towny.command.town.jail.list</span>
* <span data-bs-toggle="tooltip" title="Permite encarcelar forajidos.">towny.outlaw.jailer</span>

---

## Roles de Nación

### Asistente

Rol administrativo a nivel nación, con control diplomático y de gestión.

* <span data-bs-toggle="tooltip" title="Permite asignar el rango Ayudante dentro de la nación.">towny.command.nation.rank.ayudante</span>
* <span data-bs-toggle="tooltip" title="Permite invitar ciudades a unirse a la nación.">towny.command.nation.invite.add</span>
* <span data-bs-toggle="tooltip" title="Permite gestionar alianzas con otras naciones.">towny.command.nation.ally.*</span>
* <span data-bs-toggle="tooltip" title="Permite gestionar (agregar, quitar, aceptar, rechazar) invitaciones de alianza de la nación.">towny.command.nation.ally.manage.*</span>
* <span data-bs-toggle="tooltip" title="Permite ver las solicitudes de alianza enviadas por la nación.">towny.command.nation.ally.sent</span>
* <span data-bs-toggle="tooltip" title="Permite ver las solicitudes de alianza recibidas por la nación.">towny.command.nation.ally.received</span>
* <span data-bs-toggle="tooltip" title="Permite declarar enemigos de la nación.">towny.command.nation.enemy</span>
* <span data-bs-toggle="tooltip" title="Permite depositar dinero en el banco de la nación.">towny.command.nation.deposit.other</span>

---

### Ayudante

Rol básico para la expansión de la nación.

* <span data-bs-toggle="tooltip" title="Permite añadir ciudades a la nación.">towny.command.nation.add</span>
