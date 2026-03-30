git cherry-pick es un comando que permite seleccionar un commit específico de una rama y copiarlo directamente sobre tu rama actual

merge une todo el historial de dos ramas, combinando todos los commits.
rebase mueve una serie de commits de una rama a otra, reescribiendo la historia para que parezca lineal

## 3 CASOS
Hotfix de emergencia
Commit en la rama equivocada
En una rama experimental y quieres llevarla a tu rama principal, pero no quieres traer el resto de experimentos inestables


Se recomienda utilizar git cherry-pick con moderación porque, a diferencia de git merge o git rebase, no registra la relación histórica entre la rama de origen y la de destino
