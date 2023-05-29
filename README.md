# NunnaTech.

## Pre-Requisitos

<br>

Necesitas tener [Visual Studio Code](https://code.visualstudio.com/) y [Docker](https://www.docker.com/) instalados, debido a que este repositorio hace uso de [devcontainers](https://containers.dev/), tiene muchos beneficios que puedes leer y aprender [aqu&iacute;](https://code.visualstudio.com/docs/devcontainers/containers). Despu&eacute;s, necesitas instalar la extensi&oacute;n [Dev Container](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) en Visual Studio Code.

<br>
<br>

## Ejecuta localmente el proyecto
<br>

Asumiendo que ya tienes clonado el repositorio, inicia el servicio de docker en tu computadora con el siguiente comando:

<br>

```bash 
sudo systemctl start docker
```

<br>

Abre la carpeta del repositorio con Visual Studio Code, despu&eacute;s presiona <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (o <kbd>Shift</kbd> + <kbd>Command</kbd> + <kbd>P</kbd> en Mac) y selecciona la opci&oacute;n `Dev Containers: Rebuild container`.

<br>

Y eso es todo, solo necesitas esperar a que el proyecto se construya, despu&eacute;s puedes acceder a la terminal dentro del contenedor con la opci&oacute;n `Nueva terminal` del men&uacute; `Terminal`.

<br>
<br>

## Extensiones dentro del DevContainer

<br>

| Nombre | Identificador &uacute;nico |
| ------ | ------ |
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | `dbaeumer.vscode-eslint` |
| [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) | `octref.vetur` |
| [Vue Language Features (Volar)](https://marketplace.visualstudio.com/items?itemName=vue.volar) | `vue.volar` |
| [VueDX](https://marketplace.visualstudio.com/items?itemName=znck.vue-language-features) | `znck.vue-language-features` |
| [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) | `christian-kohler.npm-intellisense` |
| [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) | `bradlc.vscode-tailwindcss` |
| [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | `eamodio.gitlens` |
| [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | `esbenp.prettier-vscode` |
