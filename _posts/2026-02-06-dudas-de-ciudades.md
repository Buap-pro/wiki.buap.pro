---
layout: post
title: Dudas de Ciudades
date: 2026-02-06 22:01 -0600
description: Algunas respuestas frecuentes relacionadas a las ciudades de Towny
author: galleta
categories:
- Tutorial
- Towny
tags:
- tutorial
- towny
- dudas
- granjas
---

## Niveles

Las ciudades tienen un sistema de niveles para alcanzar ciertos beneficios, entre los cuales se incluyen:

1. Más chunks (claims)
2. Más espacio en el banco
3. Cambia el título de ciudad
4. Cambia el título de líder
5. Mayor tolerancia de deuda
6. Más outposts

Si una ciudad sube de nivel, también sube su capacidad económica, así que hay algunas desventajas, al subir de nivel:

1. Mayor costo de mantención
2. Mayor costo de paz

> En desarrollo: una tablita con todas los niveles, ventajas y desventajas.
{: .prompt-info}

### ¿Cómo sube de nivel mi ciudad?

Simplemente invita a amigos a tu ciudad... más ciudadanos = más nivel de ciudad.

### ¿Puede bajar de nivel mi ciudad?

Ya que, más ciudadanos = más nivel de ciudad...

También: menos ciudadanos = menos nivel de ciudad...

Solo no pierdas ciudadanos :)

## Impuestos

Todos los impuestos, desde impuestos de nación hasta impuestos de ciudadanos, se pagan **_diario_ a las 12:00 PM (medio día) hora México**.

> Seas lider de nación, lider de ciudad o solo ciudadano, puedes ver costos de todo usando los comandos `/towny prices` y `/town`.
{: .prompt-tip}

### Impuesto diario de ciudad

Las ciudades pagan impuestos por... existir (como en la vida real 🥳), puedes saber cuánto paga tu ciudad usando `/town`, este comando te muestra información de tu ciudad, en la cual hay un texto que dice "Mantención diaria" (en inglés "Daily upkeep"), junto a este texto está la cantidad que tu ciudad debe pagar.

El impuesto diario sube de acuerdo al nivel de ciudad, así que en algún punto querrás [cobrarle impuestos a tus ciudadanos](#impuestos-de-ciudadano) para que aporten a la mantención de la ciudad.

#### ¿Cómo pago este impuesto?

Solo deposita dinero al banco de tu ciudad usando `/t deposit cantidad` (por ejemplo `/t deposit 500`) y el servidor tomará el dinero automáticamente cuando se requiera.

#### ¿Qué pasa si no pago?

*NADA :D*

Solo pierdes tu ciudad... algo así, si quieres toda la explicación sigue leyendo, pero simplemente no quieres que pase eso.

Si tu ciudad no tiene suficiente dinero para pagar el mantenimiento, entra primero en bancarrota. En este estado ya no puede hacer casi nada útil. Si el problema continúa, la ciudad pasa a ruina, donde empiezan a perderse protecciones y todo se vuelve un poco caótico. Y si aun así nadie paga… bueno, RIP ciudad 💀: la ciudad se elimina y sus terrenos quedan libres para cualquiera que la encuentre.

#### ¿Cómo reduzco el impuesto?

No se puede :)

### Paz

#### ¿Cómo que paz?

La paz es un impuesto relacionado a épocas de guerra. [Las guerras](/posts/guerras) no siempre están activas, por lo que no siempre vale la pena estar pagando este impuesto.

#### ¿Cuándo pagar el impuesto?

Básicamente si un día es _posible_ que haya guerra, pagar el impuesto protegerá a tu ciudad de cualquier declaración de guerra.

Dentro del [post relacionado a guerras (click aquí)](/posts/guerras) se explica cuándo son las épocas de guerras, básate en eso para saber cuándo SÍ quieres pagar este impuesto.

#### ¿Cómo NO pagar el impuesto?

Simplemente quita el estado de paz en tu ciudad, puedes hacerlo con el comando `/t toggle peaceful off`.

#### ¿Cómo volver a pagar el impuesto?

Similar a quitar el estado de paz, puedes volver a habilitarlo con `/t toggle peaceful on`.

> Si no tienes el estado de paz activo durante época de guerras, estás en riesgo de que cualquier ciudad o nación enemiga te declare guerra.
{: .prompt-danger}

#### ¿Qué pasa si no pago por paz?

Solo pierdes la protección contra guerras, pero _podría_ registrarse como que tampoco pagaste tu impuesto diario... y eso no es bueno.

Si no quieres pagar el impuesto de paz, mejor deshabilitalo.

### Impuestos de ciudadano

El único impuesto para los ciudadanos _puede ser_ (no todas las ciudades lo tienen/quieren) el impuesto de residencia, el cual, al igual que todos los otros impuestos, se cobra diario automáticamente del dinero del ciudadano (los ciudadanos no necesitan hacer nada para pagar).

#### Impuesto fijo

Las ciudades pueden cobrar una cantidad específica, fija e igualitaria para todos los ciudadanos. Esta suele ser la forma más justa de cobrar a todos, pero si una ciudad tiene algunos ciudadanos pertenecientes al 0.1%, quizá quieran usar [impuestos porcentuales](#impuesto-porcentual).

##### ¿Cómo pongo un impuesto fijo?

1. Asegúrate de que tienes los impuestos _porcentuales_ DEShabilitados con `/t toggle taxpercent off`
2. Ajusta la cantidad fija que cobrarás a tus ciudadanos con `/t set taxes cantidad`, por ejemplo `/t set taxes 100` para cobrar $100 diarios.

#### Impuesto porcentual

Las ciudades pueden cobrar impuestos dinámicos relativos al dinero que cada ciudadano tenga, estos son impuestos porcentuales, cobrando un porcentaje del dinero total del ciudadano.

Por ejemplo, si una ciudad tiene impuestos porcentuales al 5% y tiene 2 ciudadanos, ciudadanoA tiene $100 y ciudadanoB tiene $1000, ciudadanoA pagará solo $5, mientras que ciudadanoB pagará $50.

##### ¿Cómo pongo un impuesto porcentual?

1. Asegúrate de que tienes los impuestos _porcentuales_ **habilitados** con `/t toggle taxpercent on`
2. Ajusta el porcentaje que cobrarás a tus ciudadanos con `/t set taxes cantidad`, por ejemplo `/t set taxes 5` para cobrar 5% a tus ciudadanos.

> Puedes usar `/t set taxpercentcap cantidadFija` para definir un máximo que se le cobrará a cualquier ciudadano, usando el ejemplo de antes, si tienes A con $100, B con $1000 y 5% de impuestos, pero pones `/t set taxpercentcap 20`, A seguirá pagando $5, pero B solo pagará $20, en vez de los originales $50 por el 5%
{: .prompt-tip}

## Granjas

### 💞 Granjas de Aldeanos 💞

Los aldeanos **NO** se pueden reproducir dentro de ciudade, ¿qué hacer? sigue leyendo.

**Opción 1:** Quitar tu claim del chunk donde tus aldeanos se reproducen. (Para hacerlo, similar a reclamar terreno, párate en el chunk y usa `/t unclaim`)

**Opción 2:** Mover tu granja afuera de tu ciudad.

**Opción 3:** No tener granjas de aldeanos :D

> ##### ¿Por qué no se pueden reproducir dentro de ciudades?
> 1. Para evitar lag. Permitir granjas de aldeanos protegidas hace que algunos jugadores decidan hacer trading halls enormes, esta limitación evita eso... o lo intenta.
> 2. Para hacerlo competitivo.
> 3. Para no hacer que todos los aldeanos estén 1000% seguros por la protección de ciudad (no grief + no monstruos + no explosiones = aldeanos inmortales), esto es algo más entretenido.
{: .prompt-info}


### 🧌 Granjas con mobs 🧌

Por defecto, por seguridad de jugadores nuevos, las ciudades están protegidas contra mobs, provocando que estos despawneen automáticamente al entrar a la ciudad.

**Solución 1 (más segura)**: Ponle una etiqueta al mob que quieres que no despawnee, esto evitará que solo ese mob desaparezca, manteniendo la protección contra todos los demás.

**Solución 2**: el lider de ciudad (o un asistente con permisos) tiene que habilitarlos con `/plot toggle mobs on`, esto deshabilia la protección contra mobs en el plot (chunk) donde se ejecuta el comando.

**Solución 3 (menos segura)**: el lider de ciudad (o un asistente con permisos) tiene que habilitarlos con `/t toggle mobs on`, esto deshabilia la protección contra mobs **en toda la ciudad**, lo cual puede ser peligroso, ten cuidado.

> Un chunk es un espacio de 16 x 16 bloques, puedes ver más información en [la wiki de Minecraft](https://es.minecraft.wiki/w/Chunk)
{: .prompt-info}
