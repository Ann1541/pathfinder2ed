---
{"dg-publish":true,"permalink":"/50-compendio/70-bestiario/diablillos/"}
---

```statblock
layout: Basic Pathfinder 2e Layout
source: "Bestiario PF2e"
name: "DIABLILLO"
level: "Criatura 1"
rare_03: "Común"
alignment: "LM"
size: "Menudo"
trait_01: "Diablo"
trait_02: "Infernal"
modifier: 7
perception:
  - name: "Percepción"
    desc: "Percepción +7; __Visión en la oscuridad mayor__;"
languages: "Común, infernal; [[telepatía]] (toque)"
skills:
  - name: "Habilidades"
    desc: "__Acrobacias__: +7, __Arcanos__: +6, __Engaño__: +7, __Religión__: +5"
abilityMods: [-1, 4, 0, 1, 2, 2]

abilities_bot:
  - name: "Cambiar de forma"
    desc: "⬻ ([[concentrar]], [[divino]], [[polimorfismo]], [[transmutación]]); El diablillo adopta la apariencia de otra criatura. En estas formas, el diablillo usa su CA original y sus modificadores de ataque, pero obtiene el tamaño de la forma (si es mayor) y ataques, Sentidos y Velocidades listadas abajo: <ul class='inner-bullet-list'><li>__Araña gigante__ tamaño Mediano; Velocidad 25 pies (7,5 m), trepar 25 pies (7,5 m); __Cuerpo a cuerpo__ colmillos +9 ([[sutil]], [[veneno]]), __Daño__ 1d6-1 perforante más 1d4 [[veneno]]</li><li>__Cuervo__ olfato; Velocidad 10 pies (3 m), volar 40 pies (12 m); __Cuerpo a cuerpo__ pico +9 ([[sutil]]), __Daño__ 1 perforante</li><li>__Jabalí__ tamaño Mediano; olfato (impreciso) 30 pies (9 m); Velocidad 40 pies (12 m); __Cuerpo a cuerpo__ colmillos +9 ([[sutil]]), __Daño__ 1d10-1 perforante</li><li>__Rata__ olfato; Velocidad 20 pies (6 m); __Cuerpo a cuerpo__ fauces +9 ([[ágil]], [[sutil]]), __Daño__ 1 perforante</li></ul>"
  - name: "Curación diabólica"
    desc: "⬻ ([[concentrar]], [[curación]], [[divino]], [[nigromancia]]); __Frecuencia__ Una vez por asalto; __Efecto__ El diablillo recupera 1d6 PG."
  - name: "Tentación infernal"
    desc: "⬻ ([[concentrar]], [[divino]], [[encantamiento]], [[fortuna]], [[maligno]]); __Frecuencia__ Una vez al día; __Efecto__ El diablillo ofrece un trato a una criatura no infernal a 15 pies (4,5 m) o menos, lo que proporciona un don de buena suerte si la criatura lo acepta. El don dura 1 hora una vez aceptado. Si la criatura muere mientras el don está activo, su alma es enviada al Infierno, donde queda ligada por toda la eternidad y no puede ser revivida o resucitada excepto mediante [[deseo]] o una magia similar. Una sola vez durante esa hora, la criatura puede repetir una tirada de ataque o de salvación y usar el resultado más elevado."
  - name: "Veneno de diablillo"
    desc: "([[veneno]]); __Salvación__ [[Fortaleza]] CD 16; __Duración máxima__ 6 asaltos; __Etapa 1__ 1d6 daño por [[veneno]] y [[torpe]] 1 (1 asalto); __Etapa 2__ 1d6 daño por [[veneno]], [[torpe]] 1 y [[lentificado]] 1 (1 asalto)."

speed: 20 pies (6 m), volar 30 pies (9 m)

ac: "17"
armorclass:
  - name: CA
    desc: "17; __Fort__ +5, __Ref__ +9, __Vol__ +7; __Inmunidades__ [[fuego]]; __Debilidades__ [[bueno]] 3; __Resistencias__ físico 3 (excepto armas plateadas), [[veneno]] 5"

hp: 15
health:
  - name: PG
    desc: "15"

attacks:
  - name: Cuerpo a cuerpo
    desc: "⬻ Aguijón +9 ([[ágil]], [[mágico]], [[maligno]], [[sutil]]); __Daño__ 1d4-1 perforante más 1d4 [[maligno]] y [[Veneno de diablillo]]."

spellcasting:
  - name: "Conjuros divinos innatos CD 17"
    desc: "__4.º__ [[leer augurios]]; __2.º__ [[invisibilidad]] (a voluntad, sólo a sí mismo); __1.º__ [[detectar alineamiento]] (a voluntad, sólo bueno), [[hechizar]]; __Trucos (1.º)__ [[detectar magia]]"
```