---
{"dg-publish":true,"permalink":"/50-compendio/70-bestiario/caparazones-sepulcrales/"}
---

```statblock
layout: Basic Pathfinder 2e Layout
source: "Bestiario PF2e"
name: "CAPARAZÓN SEPULCRAL"
level: "Criatura 1"
rare_03: "Poco común"
alignment: "N"
size: "Grande"
trait_01: "Bestia"
modifier: 4
perception:
  - name: "Percepción"
    desc: "Percepción +4; __Sentir ondulaciones__ (impreciso) 30 pies (9 m), __visión en la oscuridad__;"
languages: "Común, infracomún"
skills:
  - name: "Habilidades"
    desc: "__Atletismo__: +6, __Sigilo__: +4"
abilityMods: [3, -1, 3, -3, 1, 0]

abilities_mid:
  - name: "Bloquear con el caparazón"
    desc: "⬲ __Desencadenante__ El caparazón sepulcral sufre daño por un ataque físico mientras se encuentra escondido dentro de su caparazón (ver Trile a continuación). __Efecto__ La bestia reduce el daño del ataque en una cantidad equivalente a la Dureza de su caparazón. El caparazón tiene una Dureza de 6, 10 Puntos de Golpe y un Umbral de Rotura de 5. Si se rompe, el caparazón sepulcral no puede atacar con las púas, ni usar Trile. Si el caparazón es destruido, la CA de la bestia se reduce a 16. Mientras está viva, su caparazón se repara naturalmente al cabo de una semana."
  - name: "Disfraz de cadáver"
    desc: "([[exploración\|exploración]]); El caparazón sepulcral oculta su verdadera naturaleza durante unos minutos al empalar un cadáver (normalmente humanoide) en su caparazón de púas y sumergirse parcialmente en el agua. Tiene un resultado automático de 22 en las pruebas de __Engaño__ y la CD para hacerse pasar por un cadáver que flota."
  - name: "Respirar profundamente"
    desc: "Un caparazón sepulcral puede contener la respiración durante 200 asaltos (20 minutos)."

abilities_bot:
  - name: "Trile"
    desc: "⬻ El caparazón sepulcral se esconde dentro de su caparazón, obtiene un bonificador +2 por circunstancia a la CA y puede usar Bloquear con el caparazón, hasta que se mueve o ataca con cualquier otro ataque que no sean sus púas de caparazón. El caparazón sepulcral no puede realizar esta acción, ni obtener ningún beneficio, si su caparazón se rompe."

speed: 20 pies (6 m), nadar 20 pies (6 m)

ac: "17"
armorclass:
  - name: CA
    desc: "17 (19 cuando se esconde dentro de su caparazón); __Fort__ +8, __Ref__ +2, __Vol__ +4"

hp: 20
health:
  - name: PG
    desc: "20"

attacks:
  - name: Cuerpo a cuerpo
    desc: "⬻ Mandíbulas +8; __Daño__ 1d6+3 perforante."
  - name: Cuerpo a cuerpo
    desc: "⬻ Garra +8 ([[ágil\|ágil]]); __Daño__ 1d4+3 cortante."
  - name: Cuerpo a cuerpo
    desc: "⬻ Púas de caparazón +8; __Daño__ 1d4+3 perforante."