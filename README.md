# Información

    Este es el resultado de mi esfuerzo aprendiendo GIT

# Pregunta 12

**¿Por qué el archivo historia.log no apareció?**

> el comando que utilice para restaurar fue `git reset .` y segun la documentacion del comando
> _Restore specified paths in the working tree with some contents from a restore source. If a path is tracked but does not exist in the restore source, it will be removed to match the source._
> _By default, if --staged is given, the contents are restored from HEAD, otherwise from the index._
> No aparece porque nunca agregamos el archivo historia.log al stage, ni lo comiteamos para porder hacer restore desde un indice.
