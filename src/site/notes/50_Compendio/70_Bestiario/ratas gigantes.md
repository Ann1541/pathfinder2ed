---
{"dg-publish":true,"permalink":"/50-compendio/70-bestiario/ratas-gigantes/"}
---

```statblock
layout: Basic Pathfinder 2e Layout
source: "Bestiario PF2e"
name: "RATA GIGANTE"
level: "Criatura –1"
rare_03: "Común"
alignment: "N"
size: "Pequeño"
trait_01: "Animal"
modifier: 5
perception:
  - name: "Percepción"
    desc: "Percepción +5; __Olfato__ (impreciso) 30 pies (9 m), __visión en la penumbra__;"
skills:
  - name: "Habilidades"
    desc: "__Acrobacias__: +5, __Atletismo__: +2 (+4 a nadar o trepar), __Sigilo__: +5"
abilityMods: [1, 3, 2, -4, 1, -3]

abilities_bot:
  - name: "Fiebre de la mugre"
    desc: "([[50_Compendio/20_Mecánicas/enfermedad\|enfermedad]]); Los estados [[50_Compendio/40_Estados/Indispuesto\|indispuesto]] e [[50_Compendio/40_Estados/inconsciente\|inconsciente]] debido a la fiebre de la mugre no mejoran solos hasta que la enfermedad se cura; __Salvación__ [[Fortaleza\|Fortaleza]] CD 14; __Etapa 1__ portador sin síntomas negativos (1d4 horas); __Etapa 2__ [[50_Compendio/40_Estados/Indispuesto\|indispuesto]] 1 (1 día); __Etapa 3__ [[50_Compendio/40_Estados/Indispuesto\|indispuesto]] 1 y [[50_Compendio/40_Estados/Lentificado\|lentificado]] 1 (1 día); __Etapa 4__ [[50_Compendio/40_Estados/inconsciente\|inconsciente]] (1 día); __Etapa 5__ [[muerto\|muerto]]."

speed: 30 pies (9 m), trepar 10 pies (3 m)

ac: "15"
armorclass:
  - name: CA
    desc: "15; __Fort__ +6, __Ref__ +7, __Vol__ +3"

hp: 8
health:
  - name: PG
    desc: "8"

attacks:
  - name: Cuerpo a cuerpo
    desc: "⬻ Fauces +7 ([[ágil\|ágil]], [[sutil\|sutil]]); __Daño__ 1d6+1 perforante más [[Fiebre de la mugre\|Fiebre de la mugre]]."