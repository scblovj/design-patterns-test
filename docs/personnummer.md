---
layout: default
title: Personnummer
parent: Designmönster
status: utkast
nav_order: 10
---

**Fråga användare efter**

# Personnummer

## Använd mönstret när

Beskrivning.

## Använd inte mönstret när

Beskrivning.

## Så fungerar mönstret

Hjälp användare att ange ett personnummer genom att alltid använda ett förlåtande formulär där användaren kan mata in de vanligast förekommande varianterna:
- ååååmmdd-nnnn
- ååmmdd-nnnn
- ååååmmddnnnn
- ååmmddnnnn
- ååååmmdd nnnn
- ååmmdd nnnn
Oavsett vilken variant som användaren matar in så korrigeras det automatiskt till rätt format i koden.
Även med förlåtande inmatning kan en del användare behöva ett exempel för hur inmatningen kan se ut. Använd små bokstäver (gemener) i exemplet, så som åååå istället för ÅÅÅÅ.
