---
{"dg-publish":true,"permalink":"/50-compendio/70-bestiario/huargo/"}
---

```statblock
layout: Basic Pathfinder 2e Layout
source: "Bestiario PF2e"
name: "HUARGO"
level: "Criatura 2"
rare_03: "Común"
alignment: "NM"
size: "Mediano"
trait_01: "Bestia"
modifier: 8
perception:
  - name: "Percepción"
    desc: "Percepción +8; __Olfato__ (impreciso) 30 pies (9 m), __visión en la oscuridad__;"
languages: "Común, goblin, orco"
skills:
  - name: "Habilidades"
    desc: "__Acrobacias__: +7, __Atletismo__: +8, __Engaño__: +6, __Intimidación__: +6, __Sigilo__: +7, __Supervivencia__: +8"
abilityMods: [4, 3, 3, -1, 2, 2]

abilities_mid:
  - name: "Ataque en manada"
    desc: "El huargo inflige 1d4 daño adicional a cualquier criatura que está dentro de alcance de por lo menos dos de sus aliados."
  - name: "Mordisco vengador"
    desc: "⬲ __Desencadenante__ Una criatura dentro del alcance de las fauces del huargo ataca a uno de los aliados del huargo; __Efecto__ El huargo da un Golpe de fauces contra la criatura desencadenante."

abilities_bot:
  - name: "Engullir"
    desc: "⬻ ([[ataque\|ataque]]); Pequeño, 1d6+2 contundente, __Liberarse__ 9."

speed: 40 pies (12 m)

ac: "17"
armorclass:
  - name: CA
    desc: "17; __Fort__ +11, __Ref__ +9, __Vol__ +6"

hp: 36
health:
  - name: PG
    desc: "36"

attacks:
  - name: Cuerpo a cuerpo
    desc: "⬻ Fauces +11; __Daño__ 1d8+4 perforante más [[agarrón\|agarrón]]."