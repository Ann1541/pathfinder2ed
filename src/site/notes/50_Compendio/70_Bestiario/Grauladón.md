---
{"dg-publish":true,"permalink":"/50-compendio/70-bestiario/grauladon/"}
---

```statblock
layout: Basic Pathfinder 2e Layout
source: "Bestiario PF2e"
name: "GRAULADÓN"
level: "Criatura 2"
rare_03: "Poco común"
alignment: "N"
size: "Grande"
trait_01: "Dragón"
modifier: 7
perception:
  - name: "Percepción"
    desc: "Percepción +7; __Olfato__ (impreciso) 30 pies (9 m), __visión en la oscuridad__;"
languages: "Dracónico (no puede articular palabras en ningún idioma)"
skills:
  - name: "Habilidades"
    desc: "__Atletismo__: +10, __Sigilo__: +6, __Supervivencia__: +5"
abilityMods: [4, 0, 4, -3, 1, -2]

abilities_mid:
  - name: "Aliento reactivo"
    desc: "⬲ __Desencadenante__ El grauladón sufre daño de una criatura adyacente. __Efecto__ El grauladón usa su Aliento ponzoñoso sobre un área que incluye a la criatura activadora en su interior."
  - name: "Respirar profundamente"
    desc: "Un grauladón puede contener la respiración durante 225 asaltos (22,5 minutos)."

abilities_bot:
  - name: "Aliento ponzoñoso"
    desc: "⬻ El grauladón sisea y emite una nube nauseabunda de halitosis en un cono de 15 pies (4,5 m). Cada criatura en el interior de dicha área debe superar una tirada de salvación de [[Fortaleza\|Fortaleza]] CD 18 o quedará [[50_Compendio/40_Estados/Indispuesto\|indispuesto]] 1 ([[50_Compendio/40_Estados/Indispuesto\|indispuesto]] 2 con un fallo crítico). El grauladón no puede volver a usar Aliento reactivo ni Aliento ponzoñoso durante 1d4 asaltos."
  - name: "Golpe en el cuerpo"
    desc: "⬻ __Requisitos__ Que haya más de un enemigo adyacente al grauladón. __Efecto__ El grauladón lanza su cola contra cada enemigo adyacente e intenta [[Derribar\|Derribar]] a cada criatura adyacente a éste. Tira una sola prueba de __Atletismo__ y compara el resultado con la CD de [[Fortaleza\|Fortaleza]] de cada objetivo."

speed: 20 pies (6 m), nadar 30 pies (9 m)

ac: "17"
armorclass:
  - name: CA
    desc: "17; __Fort__ +12, __Ref__ +6, __Vol__ +7; __Inmunidades__ [[paralizado\|paralizado]], [[sueño\|sueño]]"

hp: 35
health:
  - name: PG
    desc: "35"

attacks:
  - name: Cuerpo a cuerpo
    desc: "⬻ Mandíbulas +10; __Daño__ 1d12+4 perforante."
  - name: Cuerpo a cuerpo
    desc: "⬻ Cola +10 ([[ágil\|ágil]]); __Daño__ 1d8+4 contundente."