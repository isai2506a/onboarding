# Merge Conflict Report

## What happened
Cree dos ramas a partir de main (rama1 y rama2)
Modifiqué en ambas ramas el mismo archivo y lineas (mergeconflict.txt)

## Conflict trigger
El conflictó occurió cuando quise correr: 

git merge rama1 (al estar en rama2)

Git detectó el problema

## Conflict resolution
Resolví el conflicto tomando solo los cambios de la rama2

## Conclusion
Estos conflicto pasan cuando se modifica sobre el mismo archivo en distintas ramas.
GitHub no puede detectar cuál es el correcto así que pide que se resuelva de manera
manual. 