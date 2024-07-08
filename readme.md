# DESHOJA LA MARGARITA

## Intro
Un clásico que queremos plasmar en una aplicación. Verás que los requerimientos de desarrollo tienen un formato un poco "extraño", se llama [Gherkin](https://cucumber.io/docs/gherkin/), y es un lenguaje habitual de descripción de requerimientos.

## Requerimientos

```Gherkin
FEATURE:
Saber si una persona me quiere o no al deshojar una margarita de número aleatorio de pétalos entre 0 y 15.

Acceptance criteria:
El primer pétalo debe corresponder a “me quiere”

Escenario: Margarita con número impar de pétalos
GIVEN:
Al recibir una margarita con un número de pétalos impar

WHEN:
Se arranquen los pétalos uno a uno

THEN:
Cuándo se arranque el último pétalo, el sistema devuelva: “Esa persona te quiere”

Escenario: Margarita con número par de pétalos
GIVEN:
Al recibir una margarita con un número de pétalos par

WHEN:
Se arranquen los pétalos uno a uno

THEN:
Cuándo se arranque el último pétalo, el sistema devuelva: “Esa persona no te quiere”

Escenario: Margarita con número o de pétalos
GIVEN:
Al recibir una margarita con un número de pétalos 0

WHEN:
Se arranquen los pétalos uno a uno

THEN:
Cuándo no se pueda arrancar pétalos, el sistema devuelve: “¿Estás segur@ que es la persona indicada? - deberías correr por tu estabilidad emocional”
```

## Requerimientos técnicos
Resuelve este reto en el lenguaje|framework que más te guste: JS, TS, Angular, C#, Blazor, Razor, Maui,...