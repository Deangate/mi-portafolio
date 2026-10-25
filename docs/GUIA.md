# Guia de Trabajo Colaborativo en Git

Documentacion detallada para la gestion de ramas, integracion de codigo y resolucion de conflictos en proyectos de software.

## Requisitos previos

1. Tener instalado **Git** en el sistema.
2. Configurar el nombre de usuario y correo global.
3. Contar con un editor de codigo como *Visual Studio Code*.

### Herramientas principales

- Terminal `PowerShell` o `Git Bash`
- Editor de texto estructurado
- Plataforma remota `GitHub`

## Estado de la guia

- [x] Configuracion del repositorio local
- [x] Fusion de ramas con merge
- [ ] Resolucion de conflictos complejos

## Comandos mas utilizados

Para consultar el estado del proyecto en todo momento se utiliza el comando `git status`.

```bash
git checkout -b rama-funcional
git add .
git commit -m "Agrega nueva funcionalidad"
git switch main
```

| Comando | Funcion |
|---------|----------|
| git branch | Lista y gestiona las ramas locales |
| git checkout | Cambia de rama o restaura archivos |
| git merge | Fusiona una rama en la rama actual |

## Recurso externo e imagen

- Para revisar la documentacion oficial, visita [Guia Oficial de Git](https://git-scm.com/docs/)

![Imagen referencial](../img/git.png)

