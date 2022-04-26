# Running text on 7-seg displays

### Team members

* Radim Macho (responsible for xxx)
* Richard Ladislav (responsible for xxx)
* Vilém Pecháček (responsible for xxx)
* ...

### Table of contents

* [Cíle projektu](#objectives)
* [Popis hardwaru](#hardware)
* [Popis VHDL modulů a simulace](#modules)
* [Popis TOPu a simulace](#top)
* [Video](#video)
* [Reference](#references)

<a name="objectives"></a>

## Cíle projektu

Cílem našeho projektu je naprogramovat ve VHDL jazyku běžící text na 8 segmentových displejích programovatelné desky Nexys A7-5OT. 
K vývoji kódu použijeme vývojové prostředí Vivado 2020. Naším cílem bude zobrazení slova "digital electronics 1" pomocí osmi 8 segmentových displejů. Slovo bude defaultně písmeno po písmenu přeblíkavat na displeji směrem zprava doleva. Docíli se tak efektu "běžícího" textu. Do programu také implementujeme možnost restartu textu, kdy po stisknutí prostředního tlačítka na desce dojde k navrácení slova do počátečního stavu.

<a name="hardware"></a>

## Popis hardwaru

K realizaci projektu využijeme programovatelnou desku Nexys A7-50T. Na desce využijeme osm 7 segmentových displejů (1) a pět tlačítek (5). Deska se napájí a programuje micro USB kabelem (3) připojeným k počítači. Vývojové prostředí Vivado 2020 nám umožňuje program zkompilovat a nahrát do desky.

![nexys](images/nexys-a7-50t.PNG)

<a name="modules"></a>

## VHDL modules description and simulations

Write your text here.

<a name="top"></a>

## TOP module description and simulations

Write your text here.

<a name="video"></a>

## Video

Write your text here

<a name="references"></a>

## References

1. Write your text here.
