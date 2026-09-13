---
description: >-
  Guía, consejos y recopilación sobre la crianza
---

# 💘 Crianza

## 💻 Interfaz de Crianza
![Aplicación de Crianza](../../images/cobblemon/crianza/crianzaapp.png)

El sistema de Crianza de Universo PokéNet se realiza a través de la **Aplicación Crianza de la Poké-Tablet**. También puedes usar el comando `/crianza` para abrir la Aplicación.

![Guarderías](../../images/cobblemon/crianza/crianza1.png)

Desde esta interfaz podrás manejar tus Guarderías, comprar otras guarderías e incluso **leer una guía resumida de como funciona el sistema.**

En esta entrada de la Wiki explicaremos una Guía más extensa, pero la que se encuentra dentro de la Aplicación sería más que suficiente.

## 🛍 Requisitos

Para empezar, vas a necesitar:
- Dos Pokémon de sexos opuestos ![male](../../.gitbook/assets/male.png) ![female](../../.gitbook/assets/female.png).
- Esos dos Pokémon deben pertenecer al mismo [Grupo Huevo](https://bulbapedia.bulbagarden.net/wiki/Egg_Group)
- Una Guardería libre en `/crianza`.

Existe también la posibilidad que uno de los dos Pokémon sea un Ditto ![ditto](../../.gitbook/assets/ditto.png). En ese caso, solo necesitarás:
- Ditto ![ditto](../../.gitbook/assets/ditto.png)
- Pokémon que pueda criar, da igual que sexo.
- Una Guardería libre en `/crianza`.

{% hint style="danger" %}
Si uno de los Pokémon está castrado, no podrá ser usado para criar. Al intentar añadirlo a la Guardería se mostrará como "castrado"
{% endhint %}

## 🎎 Incubación del Huevo

En la Aplicación de Crianza tendrás disponible las Guarderías donde criar a tus Pokémon. **Por defecto todos tienen 1 Guardería, para conseguir más necesitarás comprarlas hasta un máximo de 5 Guarderías.**

**Dentro de la Guardería tendrás que seleccionar al Pokémon macho y hembra que se usarán para criar**. En caso de usar Ditto, da igual donde lo pongas mientras que el padre/madre esté en el lugar correcto.

![Interfaz donde colocar los Pokémon para criar](../../images/cobblemon/crianza/crianza2.png)

{% hint style="info" %}
## Valores actuales de Crianza
- Tiempo entre cada intento de huevo: `10 minutos`
- Porcentaje de que aparezca un Huevo: `40%`
{% endhint %}

Usando los valores anteriores existe la posibilidad de que aparezca un Huevo en medio. Si tienes suerte, **te llegará una notificación y podrás recoger tu Huevo.**

![Así aparece la interfaz cuando el Huevo se ha generado](../../images/cobblemon/crianza/crianza3.png)

**También existe la Cesta de Huevos:** En la Guardería por defecto se pueden acumular hasta 2 Huevos, a medida que cries más esta cesta aumentará de tamaño hasta 5 Huevos.

## 🥚 Eclosionar el Huevo

Cuando reclamas un Huevo de la Guardería te aparecerá en tu equipo Pokémon. Aunque no puedes usarlo en combate.

![Huevos en tu equipo](../../images/cobblemon/crianza/crianza4.png)

**Al lado de "Huevo" aparece en gris el número de pasos que tienes que hacer para eclosionar el huevo.**

Puedes abrir las estadísticas del Huevo y ver con que IVs saldrá la cría, esto te puede ayudar a decidir si descartar o no el Huevo.

![Puedes ver las estadísticas del Huevo antes de eclosionar](../../images/cobblemon/crianza/crianza5.png)

{% hint style="success" %}
Puedes acelerar este proceso de eclosión si tienes en tu equipo un Pokémon con la habilidad **Cuerpo Llama**, **Escudo Magma** o **Combustible**.
{% endhint %}

## 💎 Comandos de pago
Los [Rangos Supremo, Astral y Titán de la Tienda Web](https://tienda.universopokenet.com/) tienen comandos útiles para la Crianza. No suponen una ventaja increíble debido al cooldown que estos comandos tienen, pero es una ayuda.

- `/hatch <slot>`:
  - Usa este comando para eclosionar de golpe un Huevo de tu equipo. En `<slot>` debes escribir el número del hueco del equipo donde está el Huevo.
- `/breed <slot padre> <slot madre>`:
  - Usa este comando para crear de golpe un Huevo. Deberás indicar en que huecos del equipo donde están el padre y la madre.

## 🎭 Herencia

Los padres pueden transmitir varios rasgos que poseen a su descendencia.

### 🧬 IV

En conjunto, los dos progenitores transmitirán tres de los seis IVs aleatorios a su descendencia. Estos IVs no se superpondrán entre sí (es decir, la madre y el padre no pueden transmitir ambos el mismo IV). Ciertos objetos equipados pueden influir en los IVs heredados.

**Los Objetos que Influyen en la Herencia de los IVs son:**

* **Lazo Destino** ![Lazo Destino](../../.gitbook/assets/DESTINYKNOT.png): si lo tiene equipado cualquiera de los padres, se pasarán cinco IVs entre ambos padres a la descendencia en lugar de tres.
* **Los Objetos Recios o Power Items**, que hacen heredar un IV específico:

| **Objeto Recio**                                                                 |        **Estadística/IV**        |
| -------------------------------------------------------------------------------- | :------------------------------: |
| Pesa Recia/Power Weight ![Pesa Recia](../../.gitbook/assets/POWERWEIGHT.png)     |              Vida/HP             |
| Brazal Recio/Power Bracer ![Brazal Recio](../../.gitbook/assets/POWERBRACER.png) |           Ataque/Attack          |
| Cinto Recio/Power Belt ![Cinto Recio](../../.gitbook/assets/POWERBELT.png)       |          Defensa/Defense         |
| Lente Recia/Power Lens ![Lente Recia](../../.gitbook/assets/POWERLENS.png)       |  Ataque Especial/Special Attack  |
| Banda Recia/Power Band ![Banda Recia](../../.gitbook/assets/POWERBAND.png)       | Defensa Especial/Special Defense |
| Franja Recia/Power Anklet ![Franja Recia](../../.gitbook/assets/POWERANKLET.png) |          Velocidad/Speed         |

> **Si ambos padres poseen un objeto recio se heredará solo 1 IV aleatoriamente**

### 💫 Habilidad

La crianza cruzada añade una pequeña probabilidad de obtener la **habilidad oculta** del Pokémon mediante la reproducción. **Si la madre ya posee su habilidad oculta, la probabilidad de transmitirla será del 60%**. Si la madre posee una habilidad normal, la probabilidad de que la descendencia obtenga la habilidad oculta será:

* 10% si el Pokémon tiene 3 habilidades posibles.
* 20% si el Pokémon tiene 2 habilidades posibles.

### ![](../../.gitbook/assets/egg1.png) Movimientos Huevo

Al criar, se revisarán todos los movimientos de ambos padres para transmitir los movimientos huevo que correspondan al Pokémon en el huevo. Esto incluye el conjunto de movimientos actual, así como los movimientos en banca/guardados.

{% hint style="warning" %}
Si, por alguna razón, un movimiento de los padres no se transmite correctamente, intenta incluirlo en los movimientos en banca del Pokémon.
{% endhint %}

### ![](../../.gitbook/assets/mirrorherb.png) **Hierba Copia**

Si un Pokémon en la Guardería lleva una **Hierba Copia**, aprenderá movimientos de huevo del Pokémon con el que está en la Guardería. El Pokémon que enseña y el que recibe el movimiento no necesitan pertenecer al mismo grupo de huevos para que se transfiera. La Hierba Copia se activará cada vez que la Guardería intente generar un huevo, incluso si no lo consigue.

{% hint style="warning" %}
Si, por alguna razón, un movimiento de los padres no se transmite correctamente, intenta incluirlo en los movimientos en banca del Pokémon.
{% endhint %}

### 🎨 Formas

La forma regional se hereda directamente de la madre sin necesidad de una Piedra Eterna. Esto también aplica a aspectos como las variantes de salto de Magikarp, el color de la flor de Flabébé, los Pokémon Valencianos, Mooshtank, etc.

### 🍀 Naturaleza

Si un progenitor posee la **Piedra Eterna** ![Piedra Eterna](../../.gitbook/assets/EVERSTONE.png), la **Naturaleza** de los descendientes siempre coincidirá con la naturaleza del progenitor que tiene equipada la Piedra Eterna. Si ambos progenitores poseen Piedras Eternas, los descendientes heredarán aleatoriamente una de las naturalezas de los progenitores.

### ✨ Caza de Shiny

El método de caza shiny es el **Masuda**. Este método aumentará las probabilidades en X4 si los padres tienen un Entrenador Original (OT) diferente.

## 💚 Crianza desde 0

### 🔹 Paso 1

El primer paso es conseguir los Pokémon con buenos IVs (los IVs son los valores individuales con los que nace el Pokémon y no pueden ser entrenados; van desde 0 a 31).

Una vez tengamos nuestros Pokémon un 31 IVs o más y de géneros diferentes, iremos a la Aplicación de Crianza.

{% hint style="info" %}
Los IVs **no** perfectos de uno de los Pokémon deben coincidir con los IVs perfectos del otro, para que entre ambos estén los 6 IVs perfectos.
{% endhint %}

### 🔹 Paso 2

Una vez tengamos a los dos Pokémon 1x31, 2x31 o 3x31, con los 6 IVs perfectos entre ambos, macho y hembra, procedemos a equipar los objetos necesarios.

1. Es necesario equipar a un Pokémon el **Lazo Destino** para que la cría herede 5 IVs. Al otro le equipamos un **Objeto Recio** de la estadística que él tenga perfecta y el otro no.
2. El objetivo es ir obteniendo crías con más IVs perfectos y cruzarlas con uno de los padres o entre ellas, dependiendo del caso, hasta obtener dos crías 5x31 que fallen en diferentes IVs.
3. Al tener los 2 Pokémon 5x31, procedemos a criarlos (como se explica en el punto 1) una y otra vez hasta obtener un Pokémon 6x31/**Perfecto** (_preferiblemente macho_).

Te preguntarás cómo se obtiene un Pokémon 6x31 IVs si el Lazo Destino permite heredar solo 5. Esto se logra con suerte, ya que el sexto IV es totalmente aleatorio y puede ser entre 0 y 31. Si se tiene la suficiente suerte, ese IV aleatorio puede ser un 31.

{% hint style="info" %}
Una cría puede salir 6x31 de cualquier combinación de cría (mientras tengan entre ambos padres los 6 IVs). Ya sea dos 3x31 o un 1x31 y un 5x31, todo es cuestión de suerte.
{% endhint %}

## 💙 Crianza a Partir de un Padre Perfecto (6X31 IVs)

Esto es un poco más fácil, basta con tener un macho ![macho](../../.gitbook/assets/male.png) 6x31 del mismo grupo huevo del Pokémon que quieres criar, pero tiene algunas restricciones:

* Solo aplica a Pokémon que tengan **género**, ![macho](../../.gitbook/assets/male.png) o ![hembra](../../.gitbook/assets/female.png).
* Solo aplica a Pokémon que puedan ser **hembra** ![Female](../../.gitbook/assets/female.png).
* Solo aplica a Pokémon que compartan un [**Grupo de Huevos**](https://bulbapedia.bulbagarden.net/wiki/Egg_Group).
* Los Grupos Huevo **Ditto** y **Undiscovered** no pueden criar por este método.

En este método no es necesario tener una hembra 3x31 o más *(es más rápido sí, pero no es estrictamente necesario)*. Basta con tener una hembra del Pokémon que quieras criar y un macho 6x31 con un grupo huevo en común.

* Equipar a la hembra el **Lazo Destino** para que la cría herede 5 IVs y al macho le equipamos un **Objeto Recio** de la estadística que te interese heredar a la cría o una **Piedra Eterna** si quieres pasar la naturaleza.
* El punto aquí es ir obteniendo crías hembras con más IVs perfectos y cruzarlas con el macho perfecto hasta obtener crías 5x31 o 6x31.

_El Lazo Destino debe llevarlo siempre el Pokémon con menos IVs._

### 💛 5x31 Asegurado

* 🟡 **Con un Pokémon 6x31 y un 5x31:** El **Lazo Destino** ![Lazo Destino](../../.gitbook/assets/DESTINYKNOT.png) va en el Pokémon 5x31 y el Pokémon 6x31 debe llevar el **Recio** del IV que le falta al 5x31.
* 🟡 **Con 2 Pokémon 6x31:** El **Lazo Destino** ![Lazo Destino](../../.gitbook/assets/DESTINYKNOT.png) va en un Pokémon y el otro Pokémon debe llevar un **Recio** del IV que quieras heredar o una **Piedra Eterna** ![Piedra Eterna](../../.gitbook/assets/EVERSTONE.png) para pasar naturaleza.

## 💜 Crianza con Ditto ![Ditto](../../.gitbook/assets/ditto.png)

La crianza con Ditto es el método más efectivo para criar, ya que Ditto puede criar con casi todos los Pokémon con cualquier género o sin género ![macho](../../.gitbook/assets/male.png) ![Female](../../.gitbook/assets/female.png).

#### Consideraciones:

1. Aplica para todos los Grupos Huevos menos **Grupo Ditto** y **Grupo Undiscovered**.
2. No puedes criar Ditto con Ditto.
3. Aplica a Pokémon que tengan género ![macho](../../.gitbook/assets/male.png) ![Female](../../.gitbook/assets/female.png) o no, _mientras cumpla el punto 1 y 2._

### 🟣 Con Dittos no 6x31

Es un poco engorroso porque Ditto no puede aumentar sus IVs base, ya que solo es obtenible por captura. Lo mejor será capturar Dittos lo más perfectos posible y cubrir entre todos ellos los 6 IVs.

Para criar con este método, suponiendo que son 6 Dittos 1x31 y uno de cada IV:

1. Equipar a cada Ditto con el **Recio** correspondiente a su IV 31 y el **Lazo Destino** ![Lazo Destino](../../.gitbook/assets/DESTINYKNOT.png) al Pokémon que queremos criar.
2. Una vez que las crías vayan heredando los IVs, ir rotando los Dittos y las crías. Por ejemplo, si en la primera cría heredó el IV de Velocidad, a esa le equipamos el Lazo Destino y la criamos con otro Ditto, por ejemplo, el Ditto de Ataque, hasta que una cría herede ambos IVs.
3. Seguir así sucesivamente hasta obtener una cría 5x31 o 6x31.

> _**Es el mismo procedimiento para Dittos 2x31, 3x31, 4x31 y 5x31.**_

### 🟣 Con Ditto 6x31

Este es por mucho el método más eficaz para criar Pokémon. Para conseguir un Ditto 6x31 debes comprarlo junto con el paquete de Crianza de la [Tienda Web de Universo PokéNet](https://tienda.universopokenet.com/).

Para criar con este método basta con cruzar el Ditto 6x31 con otro Pokémon y después cruzarlo con esa cría, teniendo en cuenta las consideraciones expuestas en el apartado anterior.

1. Si solo quieres subir IVs, es recomendable que el Ditto tenga equipado el **Recio** del IV que quieras heredar. Si no es así, equipar la **Piedra Eterna** ![Piedra Eterna](../../.gitbook/assets/EVERSTONE.png) si quieres pasar la naturaleza del Ditto o el **Lazo Destino** ![Lazo Destino](../../.gitbook/assets/DESTINYKNOT.png) si quieres pasar la naturaleza del otro Pokémon con una Piedra Eterna equipada.
2. Al ir engendrando crías con mejores IVs, cruzar esas crías con el Ditto e ir rotando los recios de Ditto hasta obtener una cría 5x31 o 6x31.
