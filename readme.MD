#Tutorial

## Historial de Commits

1. Commit A en rama principal
2. Commit C en rama 'exp' (clase diferente)
3. Commit D en rama 'exp' (clase diferente)
4. Commit B en rama principal
5. Commit E en rama principal

6. git merge exp //esto estando ya en "main"

Esto se hace de la siguiente manera:
´´´
touch A
git add A
git commit -m "A"
git push -u origin main
´´´
´´´
git checkout -b exp
touch C
git add C
git commit -m "C"
git push -u origin exp
´´´

## Comandos Utilizados

- `git init`: Iniciar un nuevo repositorio.
- `git add`: Agregar cambios al área de preparación.
- `git commit -m "Mensaje"`: Realizar un commit con un mensaje asociado.
- `git branch nombre_rama`: Crear una nueva rama.
- `git checkout nombre_rama`: Cambiar a la rama especificada. Con el parametro -b si no existe se crea la rama.
- `git merge nombre_rama`: Realizar el merge de una rama a la rama actual.
