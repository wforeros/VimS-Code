# VimS Code

## Descripción

En este repositorio se busca mostrar una propuesta de configuración de Visual Studio Code pero con las ventajas y la experiencia de desarrollo que provee Neovim.

Para esto se van a aprovechar las funcionalidades que provee el plugin de Vim para VS Code pero adicionalmente se incluyen configuraciones de shortcuts para que usar las herramientas provistas por VS Code pero utilizando combinaciones de teclas que son más comunes en Neovim.

> [!IMPORTANT]
> Las configuraciones pueden ser modificadas, lo que se encuentra en este repositorio es basado en la configuración de [LazyVim](https://www.lazyvim.org/) junto a modificaciones personales.

## Video de YouTube

En este vídeo podrás ver como usar esta configuración junto a la demostración de los diferentes atajos que se encuentran en este repositorio.

[![Video para Configurar VS Code](https://img.youtube.com/vi/XHya6-pForE/0.jpg)](https://www.youtube.com/watch?v=XHya6-pForE)


## Requisitos

1. Tener instalado Visual Studio Code.
2. Querer aprender a usar Neovim o tener experiencia en este.
3. (No es un requisito) Vas a querer usar Neovim después de esto y lo mejor, se te facilitará muchísimo 🔥

## Set up

Dentro de Visual Studio code se pueden modificar las configuraciones de usuario o de espacio de trabajo. Para este caso se recomienda modificar las configuraciones de usuario para que estas sean aplicadas a todos los proyectos.

Adicionalmente tendremos que agregar la configuración de shortcuts para ejecutar comandos de VS Code, es decir que la mayoría de las acciones son configuradas dentro del archivo `keybindings.json`.

### Pasos

1. Instalar la extensión de [Vim para Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim).
2. Se recomienda tener una copia del settings.json de tu VS Code por si quieres volver a la tu configuración original.
3. Copia el contenido del archivo `settings.json` de este repositorio y pégalo en tu archivo de configuración de usuario o descarga directamente el archivo.

### Git con LazyGit (opcional)

Para el caso de git por un gusto personal no uso las herramientas provistar por GitHub por lo que lo dejé como un punto opcional para realmente tener una experiencia en la que el uso de mouse sea mínimo.

En este caso dentro de mi flujo de trabajo uso [LazyGit](https://github.com/jesseduffield/lazygit) desde mi terminal (puedes usar la terminal integrada de VSCode).

Adicionalmente para mejorar esta experiencia es necesario que hayas incluído los keybindings de terminal que se encuentran en el archivo `keybindings.json` para que tener una mejor experiencia; si lo copiaste completo entonces ya deberías tene dicha configuración.

> [!NOTE]
> Para abrirlo solo necesitas ejecutar `lazygit` en tu terminal y listo.

#### Overview de LazyGit

LazyGit es una herramienta que permite interactuar con git desde la terminal de una manera más visual y amigable. Permitiendo hacer todas esas tareas que conlleva trabajar con Git y en equipo incluyendo las tareas más basicas como:

- Crear commits
- Hacer push
- Hacer pull
- Ver el historial de commits
- Ver los cambios de un commit
- Mergear cambios
- Resolver conflictos
- Ver gráficos de ramas
- Y muchas más

Incluyendo otras un poco más avanzadas como:

- Hacer resets de distintos tipos
- Ejecutar rebases interactivos
- Stash de cambios
- Hacer copia de commits en otras ramas (cherry-pick)
- Y muchas más

