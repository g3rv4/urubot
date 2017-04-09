---
layout: default
---
![@UruBot](/public/logo.png "@UruBot")

# Qué es? Qué hace?
Es un bot de twitter ([@UruBot](https://twitter.com/UruBot)) que sigue a @elpaisuy y @portalmvd, y hace lo posible por retwittear **sólo noticias**. Intenta filtrar:

* Deportes
* "Notas de color" (si, entre comillas)
* Carnaval
* Tweets repetidos
  * Los medios tienen la genial idea de twittear lo mismo varias veces (me imagino que para probar qué convierte mejor). Este bot sólo retwittea la primera vez.
  * Si dos cuentas twittean sobre lo mismo, el bot no lo cuenta como repetido

# Por qué? Cómo se usa?
Me pasó que seguía a estas dos cuentas pero me llenaban el timeline de cosas que no me interesaban. Entonces dejé de seguirlas y nunca más me enteré de qué pasaba en Uruguay. Para arreglar esto, hice el bot.

Cómo se usa? lo seguís al bot en vez de seguir a @elpaisuy y @portalmvd. En tu timeline van a aparecer sólo las cosas que retwittee :) si te interesa algo en particular que el bot filtra (ehem: fútbol) podés seguir cuentas especializadas.

# Tenés ejemplos?
Acá podés ver las cosas que retwitteó y que filtró
<div id="enpc">
<table>
  <tr>
    <th>Retwitteó</th>
    <th>&nbsp;</th>
    <th>Filtró</th>
  </tr>
  <tr>
    <td valign="top"><div id="timeline" style="width: 400px;"></div></td>
    <td>&nbsp;</td>
    <td valign="top"><div id="filtrado" style="width: 400px;"></div></td>
  </tr>
</table>
</div>
<div markdown="1" id="enmobile">
* [Retwitteó](https://twitter.com/UruBot)
* [Filtró](https://twitter.com/UruBot/timelines/849660649366056966)
</div>
